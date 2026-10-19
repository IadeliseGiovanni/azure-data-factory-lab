# Azure Data Factory - ETL Pipeline Lab

Primi passi nel mondo del **Cloud Data Engineering** tramite Microsoft Azure. Questo repository raccoglie esercizi pratici e configurazioni relativi all'orchestrazione dei flussi di dati e alla gestione delle pipeline ETL.

---

## 🛠️ Architettura e Tecnologie Utilizzate
* **Cloud Provider:** Microsoft Azure
* **Storage:** Azure Blob Storage (Architettura a strati: `telco-raw` per i dati grezzi, `telco-processed` per i dati elaborati)
* **Orchestrazione:** Azure Data Factory (ADF)
* **Componenti chiave:** Linked Services, Datasets, Pipeline (Copy Data Activity)

---

## 📂 Struttura del Progetto
```text
├── dataset/            # Definizione della struttura dei dati (JSON)
├── pipeline/           # Configurazione delle pipeline di orchestrazione (JSON)
└── README.md           # Documentazione del progetto
