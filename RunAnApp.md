# Come eseguire un'APP
Per eseguire l'app che verrà sviluppata durante il corso è possibile scegliere se
* usare un device fisico collegato al pc
* usare un device emulato da Android Studio

## Device Fisico
Nel caso in cui si voglia usare un device fisico bisognerà attivare la modalità sviluppatore sul proprio device.In questo caso è fortemente consigliato scaricare e installare il software gratuito vysor (reperibile al sito https://www.vysor.io/download/?return=https%3A%2F%2Fwww.vysor.io%2F).
Questo software consente di fare il mirroring dello schermo del proprio device fisico, in modo tale che  anche gli altri partecipanti possano vedere l'app in esecuzione.

***N.B. Usando vysor viene mostrato a video lo schermo del vostro smartphone e, di conseguenza, gli altri vedranno tutto quello che accade sul vostro smartphone (notifiche di messaggi, notifiche di email, chiamate in arrivo, etc.). Per tutelare la vostra privacy si consiglia di mettere lo smartphone in modalità Aereo in modo tale da non
ricevere messaggi o chiamate private.***

## Device Emulato da Android Studio
Se vogliamo utilizzare un device simulato dobbiamo:
1. Aprire l'IDE Android Studio.
2. Aprire un progetto già esistente o crearne uno nuovo
3. Cliccare sul menù "No Devices" e cliccare sulla voce "AVD Manager"

![1](https://user-images.githubusercontent.com/53529795/104844510-ef875e00-58d0-11eb-9432-e633fa938304.PNG)

4. Cliccare su "Create Virtual Device"

![2](https://user-images.githubusercontent.com/53529795/104844511-f2824e80-58d0-11eb-81f5-c1b7a3537701.PNG)

5. Selezionare il tipo di device che si vuole simulare. Nel nostro caso scegliamo "Phone" e, una volta selezionato il modello,
   clicchiamo su Next

![3](https://user-images.githubusercontent.com/53529795/104844513-f4e4a880-58d0-11eb-8714-3ca431f7d8d0.PNG)

6. Scegliamo una "System Image" e scarichiamola cliccando sul pulsante "Download".

![4](https://user-images.githubusercontent.com/53529795/104844514-f615d580-58d0-11eb-81c8-05cddab6343d.PNG)

![5](https://user-images.githubusercontent.com/53529795/104844516-f7470280-58d0-11eb-940f-83481b01c111.PNG)

7. Dopo aver terminato con il download clicchiamo su "Next" e, se non dobbiamo selezionare delle impostazioni avanzate, possiamo cliccare su "Finish"

![6](https://user-images.githubusercontent.com/53529795/104844517-f7df9900-58d0-11eb-9fd9-76d2f88ea550.PNG)

A questo punto il device che abbiamo creato comparirà nella lista "Your Virtual Devices".

![7](https://user-images.githubusercontent.com/53529795/104844518-f8782f80-58d0-11eb-8e2d-d7639df8202c.PNG)

Se abbiamo un solo device questo verrà selezionato in automatico da Android Studio se, invece, abbiamo più device emulati dobbiamo cliccare sul menù mostrato in figura e scegliere quale device simulato vogliamo usare.

![8](https://user-images.githubusercontent.com/53529795/104844519-f9a95c80-58d0-11eb-883a-b66d5d074804.PNG)

Una volta che abbiamo cliccato sul tasto run Android Studio farà la build dell'applicazione, manderà in esecuzione il virtual device, e installerà ed eseguirà la nostra app

![9](https://user-images.githubusercontent.com/53529795/104844508-ec8c6d80-58d0-11eb-8b3f-329fd277db31.PNG)
