C8080
Il seguente framework è formato da un insieme di package che collaborano tra loro
per estrarre i dati relativi al GPS , agli Accounts associati allo smartphone , ai
dati statistici di rete , delle app installate sul dispositivo e del display.

Package:
business_object: contiene le classi rappresentati i dati.
Ognuna delle classi presenti in questo package verrà mappata all'interno del DB. Ogni dato verrà inviato  al server sotto formato Json , per questo ogni classe
in questo package estende AbstractData la quale implementa 3 metodi per la gestione e trasformazione degli oggetti in Json.
