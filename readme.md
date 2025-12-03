# SafePath

**SafePath** is an AI-powered project designed to generate safe walking routes for women and minors in high-risk urban areas, with a focus on South America, India, and South Africa.

---

## 🌍 Purpose

To provide an intelligent and accessible tool that enhances **urban safety** in vulnerable regions, leveraging geospatial data and machine learning.

---

## 🎯 Alignment with UN Sustainable Development Goals (SDGs)

- **Goal 5:** Gender Equality  
- **Goal 11:** Sustainable Cities and Communities  
- **Goal 16:** Peace, Justice and Strong Institutions

---

## 🧠 Technologies Used

- **Python**
- **Graph Neural Networks (GNN)**
- **Mapbox** (interactive visualization)

---

## 📊 Main Datasets

- **OpenStreetMap** (urban structure and street network)  
- **UN Crime Data** (global crime statistics)  
- **Chicago Crime Data** (crime reports)

---

## 🔎 Technical Approach

Since urban datasets do not include explicit risk labels for each street segment, we implemented a **weak labeling strategy** based on the **spatial density of localized crimes**, using this as a risk proxy.  
These signals are then propagated across the pedestrian network using a **Graph Neural Network (GNN)**, enabling the model to infer risk even in areas with sparse data.

---

## 🗺️ Output

- **Safe route suggestions** between user-defined points  
- **Interactive map visualization**  
- **Dynamic street-level safety scoring**

---

## 📁 Repository Structure



📦 Struttura del repository

├── code/         # Codice per il calcolo dei percorsi sicuri
├── data/
│   ├── crimes_raw.csv       # Dataset originale con i crimini
│   ├── crimes_cleaned.csv   # Dataset pulito e normalizzato
├── images/       # Risultati visivi e schermate dell’implementazione
└── README.md     # Descrizione del progetto



---

## 🕒 Project Timeline (4 months)

1. **Data collection and cleaning**  
2. **Urban network construction and weak labeling**  
3. **GNN model training**  
4. **Deployment of interactive map**

---

## 📌 Success Metrics (KPIs)

- **Coverage** of target zones ≥ **80%**  
- **Positive user feedback** ≥ **75%**

---

## 💡 Expected Impact

Reducing risk exposure for women and minors during urban travel, while promoting inclusive and safe access to public spaces.

---

For questions or collaboration proposals, feel free to contact us or open an issue in the repository.


