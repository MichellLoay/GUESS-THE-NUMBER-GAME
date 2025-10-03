Esercizio ripasso closure

Creare una funzione normale creaGioco(maxNumero, tentativiMax) che:

• genera un numero casuale intero tra 1 e maxNumero (incluso);

• mantiene uno stato interno che conta il numero di tentativi effettuati;

• restituisce una arrow function che rappresenta la closure del gioco.

La closure deve:

• accettare come parametro il numero scelto dall’utente;

• incrementare il numero di tentativi interni;

• restituire un messaggio che indichi se il numero inserito è troppo alto, troppo
basso o corretto;

• terminare quando il numero è indovinato o quando il numero di tentativi ha
raggiunto il limite tentativiMax, restituendo un messaggio appropriato.

Il programma principale deve:

• chiedere all’utente il numero massimo (maxNumero) e il numero massimo
di tentativi (tentativiMax) usando prompt;

• chiedere all’utente i tentativi con prompt e mostrare il risultato di ogni
tentativo con alert;

• continuare finché l’utente non indovina il numero o finisce il numero di
tentativi disponibili


Nella libreria Math sono presenti le funzioni
floor che arrotonda all’intero inferiore,
random che genera un numero casuale compresso fra 0 e 0.99999
