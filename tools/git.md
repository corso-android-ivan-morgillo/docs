# Git & Co.

## Overview

A questo punto avrete già un account Github e vi starete chiedendo:

> "Che me ne faccio!?"

Github è un servizio web che vi consente di "storare" e condividere il codice sorgente dei vostri progetti usando [git](https://git-scm.com/).

## Concetti fondamentali

Git è uno strumento immenso, ma a noi servirà solo un sottoinsieme di tutte le sue funzionalità. Formalmente parlando, git è un sistema di versionamento del codice sorgente, e ci consente di avere una history dei cambiamenti che apportiamo ai nostri file. Vedremo l'utilizzo pratico a lezione, ma quello di cui abbiamo bisogno da subito è un vocabolario comune, per parlare la stessa lingua. 

### Repository

Un repository, o repo se siete pigri come dei bradipi come me, è quello che state usando in questo momento. La documentazione del corso si trova all'indirizzo

> https://github.com/corso-android-ivan-morgillo/docs

Se analizziamo l'url, vediamo che ci sono 

* `https://github.com/` - il sito di Github (duh!?)
* `corso-android-ivan-morgillo` - l'organizzazione a cui facciamo parte noi studenti e docenti
* `docs` - questo è il repo che contiene la documentazione del corso.

Potete immaginare un repo come una cartella un po' particolare.

### Clonare un repo

Quando vogliamo portare una copia del repo da Github al nostro computer possiamo effettuare una _clone_ del repo.

Per effettuare la _clone_ useremo Android Studio:

![image](https://user-images.githubusercontent.com/19003/105202541-637c6d00-5b42-11eb-9e02-3c5b145f391d.png)

Ci basterà inserire l'url come nell'immagine successiva e scegliere la cartella di destinazione:

![image](https://user-images.githubusercontent.com/19003/105202802-a50d1800-5b42-11eb-877d-cd0c95c3909d.png)

A questo punto il repo è sul nostro computer e Android Studio lo tratterà come un progetto su cui lavorare.

### Pullare un repo

Git è un sistema di versionamento distribuito e consente a tanti programmatori di lavorare contemporaneamente sullo stesso progetto.

Quando vogliamo iniziare a lavorare su un nuovo task vogliamo essere sicuri di avere tutti i cambiamenti che i nostri colleghi hanno apportato mentre noi dormivamo.

Per fare ciò useremo il comando `pull` di git. Anche questo comando è prensente in Android Studio:

![image](https://user-images.githubusercontent.com/19003/105203748-c28eb180-5b43-11eb-8e91-2f30f02f546c.png)

### Committare il nostro lavoro

Una volta che il nostro lavoro è concluso vogliamo raggruppare tutte le modifiche che abbiamo effettuato, allegare un messaggio descrittivo ed imprimerle nella history del repo.

Per fare ciò useremo i comandi `add` e `commit` di git. Anche in questo caso Android Studio vi aiuta. Vi basterà usare la combinazione di tasti `Cmd+K` se siete su Mac o `Ctrl+K` se siete su PC e vi apparirà una schermata simile a questa:

![image](https://user-images.githubusercontent.com/19003/105204528-8f98ed80-5b44-11eb-93f8-2c750257b872.png)

Qui potrete selezionare i file da aggiungere alla commit e specificare un "commit message". Vedremo esempi pratici al corso e questa operazione diventerà una consuetudine molto rapidamente.

### Pushare sul repo

Una volta registrate le nostre commit in locale dovremo _pushare_ per rendere le commit disponibili anche ai nostri colleghi. Usere il commando `push` di git e ancora una volta Android Studio di aiuterà:

![image](https://user-images.githubusercontent.com/19003/105340369-1352e880-5bde-11eb-8606-3ce9f935fc14.png)

