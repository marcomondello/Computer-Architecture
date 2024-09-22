## Cosa c'è dietro ad un programma?

La maggior parte dei programmi che utilizziamo ogni giorno, 
dal broswer per vedere video Youtube, all'editor di foto o al software
di guida autonoma delle Tesla, tutti contengono milioni
di linee di complesso codice di alto livello come Python, Java o C.

Ma il colcolatore riesce ad eseguire solo semplici istruzioni di basso livello.
Per trasformare un codice da alto a basso livello occorrono numerosi strati di software che traducono ogni singola 
istruzione in altre più semplici.

Questi strati di software sono organizzati in maniera gerarchica come nella seguente figura.

![StratiDelSoftware](../images/stratiDelSoftware.png)

Nel cerchio estrerno torviamo il **software applicativo**, ovvero tutte le applicazioni e programmi. Se hai mai utilizzato un browser per navigare su Internet o un’app per modificare una foto, hai già interagito con il software applicativo. Questi programmi funzionano grazie al software di sistema che lavora dietro le quinte. 

Mentre i componenti del **software di sistema** sono raffigurati nel cerchio intermedio tra l'hardware e le app software.
Il software di sistema ha diversi componenti ma due sono quelli essenziali per tutti i calcolatori moderni: il sistema operativo e il compilatore.

Il **sistema operativo** è responsabile della gestione della memoria, dei processi e delle periferiche come tastiere, schermi e dischi rigidi, consentendo ai programmi di comunicare con l'hardware senza dover conoscere i dettagli del funzionamento fisico. Linux, IOS e Windows sono i sistemi operativi più utilizzati.

I **compilatori** eseguono una funzione importantissima, quella di permettere all'hardware ai programmi di essere eseguiti. In sostanza un compilatore è un programma che traduce il codice sorgente scritto in un linguaggio come Python o Java in linguaggio macchina, una serie di istruzioni che il processore del computer può comprendere direttamente. Senza questa traduzione, il codice non potrebbe essere eseguito.

