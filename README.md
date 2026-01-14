# Gioco delle Otto Regine

Una semplice applicazione web che permette di giocare con il classico problema delle **8 regine**.
Link: [Gioco delle otto regine](https://salvatorecapolupo.github.io/ottoregine)
Mirror: [Gioco delle otto regine (con auto-risolutore)](https://lipercubo.it/gioco-delle-8-regine.html)

Come risolvere il gioco: 
Pensa a come puoi avanzare regina per regina, riga per riga
Verifica se è possibile posizionarla senza conflitti con quelle già piazzate. 
Se trovi un vicolo cieco, torna indietro.

## Descrizione

Il “Gioco delle Otto Regine” è una rappresentazione interattiva del noto problema combinatorio:  
> *posizionare otto regine su una scacchiera 8×8 in modo che nessuna possa attaccarne un’altra*.  
Le regine si attaccano lungo righe, colonne e diagonali, e lo scopo è trovare una configurazione valida.

L’interfaccia permette:
- di **cliccare su una cella** per piazzare o rimuovere una regina;
- di visualizzare quante regine sono state posizionate;
- di **risolvere automaticamente** l’enigma tramite backtracking;
- di **ricominciare** da capo.

## Competenze coinvolte
- Informatica
- Matematica
- Logica
- Capacità di problem Solving

## Funzionalità

### 🧠 Risolutore automatico
Il pulsante **“Aiutami!”** attiva un algoritmo di backtracking che calcola una soluzione valida e la mostra sulla scacchiera.

### ♟️ Interazione manuale
L’utente può comunque posizionare o rimuovere manualmente le regine per sperimentare o provare combinazioni diverse.

### 🔁 Reset
Un pulsante “Ricomincia” permette di azzerare la scacchiera.

## Come funziona il backtracking

L’algoritmo usa un approccio ricorsivo:
1. Prova a piazzare una regina in ogni colonna della riga corrente.
2. Controlla se la posizione è sicura (nessuna conflitto in riga, colonna, diagonali).
3. Se sì, passa alla riga successiva.
4. Altrimenti, torna indietro e prova la successiva.

Questo metodo garantisce di trovare almeno una soluzione valida.

## Tecnologie utilizzate

- HTML
- CSS
- JavaScript (ES6+)
