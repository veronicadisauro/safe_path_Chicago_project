SafePath
SafePath è un sistema basato su Intelligenza Artificiale progettato per generare percorsi pedonali sicuri per donne e minori in città ad alto rischio, con particolare attenzione a zone vulnerabili in Sud America, India e Sudafrica.

🌍 Obiettivi
ONU SDG Goals:

Goal 5: Parità di genere

Goal 11: Città e comunità sostenibili

Goal 16: Pace, giustizia e istituzioni solide

Impatto atteso: Miglioramento della sicurezza urbana in aree vulnerabili attraverso percorsi pedonali ottimizzati.

📊 Dataset utilizzati
OpenStreetMap

UN Crime Data

SafeCity India

🧠 Approccio Tecnico
Poiché i dataset urbani non contengono etichette esplicite di rischio per ciascun segmento stradale, è stata adottata una strategia di etichettatura debole basata sulla densità di crimini localizzati.
Sono stati definiti proxy di rischio che il modello GNN (Graph Neural Network) utilizza per propagare le informazioni attraverso la rete pedonale.

Tecnologie
Python

Graph Neural Networks (GNN)

Mapbox per la visualizzazione interattiva

🚀 Fasi del progetto
Raccolta e pulizia dei dati

Addestramento GNN su rete stradale e crimini

Generazione di mappa interattiva con percorsi sicuri



📦 Struttura del repository

├── code/         # Codice per il calcolo dei percorsi sicuri
├── data/
│   ├── crimes_raw.csv       # Dataset originale con i crimini
│   ├── crimes_cleaned.csv   # Dataset pulito e normalizzato
├── images/       # Risultati visivi e schermate dell’implementazione
└── README.md     # Descrizione del progetto



📈 KPI (Key Performance Indicators)
Copertura geografica percorsi: ≥ 80% delle aree urbane target

Feedback positivo da utenti e stakeholder locali: > 75%

🤝 Partner
ONU Donne

ONG locali nei paesi target


