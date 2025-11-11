# 🧩 Proposta Progetto – Quiz Game Web App

## 📌 Titolo
**Quiz Game Web App**

## 👥 Team
- Nome Studente 1 – Matricola XXXX
- Nome Studente 2 – Matricola XXXX
- (eventuali altri membri)

---

## 🎯 Obiettivo
Realizzare una **web application interattiva** per giocare a quiz a risposta multipla.  
L’app permetterà di caricare quiz da file JSON, giocare in locale tramite interfaccia web, e visualizzare statistiche finali.  
Il progetto sarà sviluppato seguendo i principi di **qualità del software**, **testing automatizzato**, e **integrazione continua**.

---

## 🧠 Descrizione generale
L’applicazione consente di:
1. Caricare un set di domande da un file JSON.
2. Avviare il quiz e rispondere alle domande tramite interfaccia web.
3. Calcolare il punteggio finale e mostrare statistiche (risposte corrette/errate, percentuale).
4. (Opzionale) Aggiungere nuovi quiz o gestire quiz multipli.

Ogni quiz sarà composto da:
- un titolo
- un insieme di domande, ciascuna con:
  - testo della domanda
  - elenco di opzioni (3–5 risposte)
  - indice della risposta corretta

---

## ⚙️ Funzionalità principali
| Funzionalità | Descrizione |
|---------------|-------------|
| **Gestione quiz** | Caricamento e validazione di quiz da file JSON |
| **Esecuzione quiz** | Visualizzazione delle domande in ordine, selezione delle risposte |
| **Calcolo punteggio** | Conteggio automatico delle risposte corrette e punteggio finale |
| **Statistiche** | Percentuale di successo, tempo impiegato (se attivo il timer) |
| **Gestione errori** | Quiz vuoto, risposte fuori range, JSON malformato |
| **Timer (opzionale)** | Tempo limite per rispondere a ciascuna domanda |
| **Creazione quiz (opzionale)** | Interfaccia per inserire nuove domande e salvare su JSON |

---

## 🌐 Stack tecnologico
| Componente | Tecnologia |
|-------------|-------------|
| **Backend** | Python + Flask |
| **Frontend** | HTML, CSS, JavaScript (Bootstrap per lo stile) |
| **Storage** | File JSON (opzionale: database SQLite) |
| **Testing** | Pytest + Coverage |
| **CI/CD** | GitHub Actions |
| **Quality tools** | Flake8, Black, Conventional Commits |

---

## 🧪 Quality Features
- **Unit test** sulla logica del quiz (`quiz_logic.py`)
- **Test d’integrazione** sulle rotte Flask (`routes.py`)
- **CI automatica** (GitHub Actions) per esecuzione test e coverage
- **Code linting** e formattazione automatica (`flake8`, `black`)
- **Pull Request workflow** con review tra membri del gruppo
- **Documentazione** nel file `README.md` con istruzioni per setup ed esecuzione

---

## 🗂️ Struttura prevista del repository
