# Pick your project

## Overview

Nella fase iniziale del corso, i progetti che svilupperemo saranno basati sulla solita formula:

* Recuperare dati da una sorgente: internet e/o database
* Mostrarli in una lista che l'utente puo' scrollare
* Mostrare un schermata di dettaglio per l'elemento della lista clickato

## UI

Dal punto di vista della UI partiremo con qualcosa del genere:

<img src="https://user-images.githubusercontent.com/19003/106162928-e88e0480-6188-11eb-9671-eab6b6377e00.png" width="400"/>

Nella prima iterazione, i componenti principali su cui ci concentreremo sono:

* [La lista](https://material.io/components/lists)
* [Le card](https://material.io/components/cards)

Le card conterranno solo una immagine e un testo, non avremo un "[hamburger menu](https://material.io/components/navigation-drawer#usage)" e non aggiungeremo azioni alla [top bar](https://material.io/components/app-bars-top#usage).

Nelle iterazioni successive potremo aggiungere altri dettagli a nostro piacere: il menu per navigare verso altre schermate, le azioni nella top bar, animazioni, piu' dettagli alle card. Potremo anche pensare a un business model, come gli ads nell'immagine di esempio. Ci faremo trascinare dalla fantasia e dalla curiosità.

## Topics and APIs

L'immagine di esempio mostra una lista di libri

<p align="center">
  <img src="https://user-images.githubusercontent.com/19003/106165809-c34ec580-618b-11eb-947a-b0253ca0aca3.gif"/>
</p>

ma per i nostri progetti sceglieremo tra queste possibili API:

### Football
* API overview https://www.thesportsdb.com/api.php
* Endpoint per Task1
https://www.thesportsdb.com/api/v1/json/1/search_all_teams.php?l=Italian%20Serie%20A

### Recipes
* API overview https://www.themealdb.com/api.php
* Endpoint per Task1 https://www.themealdb.com/api/json/v1/1/filter.php?c=Beef

### Cocktails
* API overview https://www.thecocktaildb.com/api.php
* Endpoint per Task1 https://www.thecocktaildb.com/api/json/v1/1/filter.php?c=Cocktail

### Albums
* API overview https://www.theaudiodb.com/api_guide.php
* Endpoint per Task1 https://www.theaudiodb.com/api/v1/json/1/searchalbum.php?s=queen

### Dogs (+)
* API overview https://thedogapi.com/
* Endpoint per Task1 https://docs.thedogapi.com/api-reference/breeds/breeds-list
