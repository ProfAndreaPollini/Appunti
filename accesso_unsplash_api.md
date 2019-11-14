# setup

* registrarsi a https://unsplash.com/developers
* creare una applicazione
* recuperare l'access key

A questo punto le richieste andranno fatte specificando l'access key in questo modo

https://api.unsplash.com/photos/?client_id=<acces_key>

# Steps

## 1 - contattare l'api

creare un bottone che alla pressione contatti l'api di unsplash e stamapare a video il contenuto dell'url

https://api.unsplash.com/photos/?client_id=<access_key>

## 2 - Parsing JSON, ricerca ed estrazione immagini

Fare il parsing del JSON ricevuto ed estrarre le url delle immagini ritornate. Utilizzare il parametro query per selezionare solo le immagini di un certo tipo.

## 3 - Ricerca interattiva

Consentire all'utente di inserire il parametro di ricerca. Mostrare a video le immagini suddivise su tre colonne
