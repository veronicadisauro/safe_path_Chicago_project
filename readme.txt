1. SafePath
 Descrizione: AI per generare percorsi sicuri per donne e minori in città ad alto rischio.
 Dataset: OpenStreetMap, UN Crime Data, SafeCity India
 Obiettivi ONU: 5, 11, 16
 Zone target: Sud America, India, Sudafrica
 Partner: ONU Donne, NGO locali
 Tecnologie: Python, Graph Neural Networks, Mapbox
 Fasi: raccolta dati, GNN, mappa interattiva
 Timeline: 4 mesi
 KPI: copertura 80%, feedback positivo >75%
 Impatto: sicurezza urbana in aree vulnerabili

Poiché i dataset urbani non contengono etichette di rischio per ogni segmento stradale, 
ho utilizzato una forma di etichettatura debole basata sulla densità di crimini localizzati, 
definendo proxy di rischio e permettendo al modello GNN di propagare queste informazioni sulla rete pedonale.

 Nella cartella code: 
 -codice per l'individuazione di un percorso sicuro da un indirizzo di origine a uno destinazione.

 Nella cartella data:
 -csv del dataset originale con i crimini
 -csv ripulito con i crimini, e dati normalizzati. 

 Nella cartella images:
 i risultati a video dell'implementazione