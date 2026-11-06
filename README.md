# 🛡️ bridg-E — Continuous DevSecOps Platform

> **Proiect universitar la disciplina Antreprenoriat și Inovare (ANI)**  
> **Denumire afacere:** bridg-E S.R.L.  
> **Domeniu:** Securitate Cibernetică Aplicată / DevSecOps Continuu pentru IMM-uri și Startup-uri Tehnologice

---

## 👥 Echipa de Proiect & Fondatori

| Nume & Prenume | Rol în Proiect / Companie | Responsabilități Principale | Calificare & Focus |
| :--- | :--- | :--- | :--- |
| **Robert Bacula** | **Coordonator Proiect & Lead Cloud Architect** *(Administrator Unic)* | Viziune tehnică, arhitectură cloud (AWS/Kubernetes), pipeline-uri CI/CD, reprezentare juridică și administrativă | Inginerie software, cloud-native, infrastructură scalabilă |
| **Răzvan Iliescu** | **Chief Technology Officer (CTO) & Security Researcher** | Motoare de scanare SAST/SCA, analiză CVE, algoritmi de filtrare a vulnerabilităților (*Reachability Analysis*) | Securitate cibernetică ofensivă/defensivă, cercetare vulnerabilități |
| **Horia Rusu** | **Lead Backend & DevSecOps Engineer** | Dezvoltare API-uri de scanare de mare viteză, microservicii în Go/Python, conectori GitHub / GitLab | Arhitecturi distribuite, baze de date analitice (ClickHouse, Postgres) |
| **Mihai Dobrescu** | **Product Manager & Business Development Lead** | Strategie B2B, segmentare piață (TAM/SAM/SOM), conformitate legislativă (NIS 2, GDPR, DORA), pricing | Management de produs tehnologic, vânzări B2B SaaS |
| **Grasu George Sebastian** | **Lead Frontend & Fullstack Developer** | Dashboard interactiv de securitate, vizualizare indicatori de risc și conformitate, integrare UX/UI, QA automat | Dezvoltare web modernă (React, TypeScript), Application Security |

---

## 📌 Despre Proiect

**bridg-E** este o soluție software de tip **SaaS (Security as a Service)** concepută pentru a rezolva decalajul critic dintre ritmul accelerat de livrare a codului sursă și cerințele stricte de securitate și conformitate cibernetică impuse companiilor mici și mijlocii (Directiva Europeană **NIS 2**, **GDPR**, **DORA**).

Platforma se conectează nativ prin **1-Click Integration** la repozitoriile Git (GitHub, GitLab, Bitbucket) și scanează automat fiecare *Pull Request* în mai puțin de 90 de secunde, reducând alertele false cu peste **80%** prin analiză contextuală de apelabilitate (*reachability graph*).

---

## 🎯 Problema și Soluția

### 🔴 Problema
- **Costuri inaccesibile:** Uneltele consacrate de securitate enterprise (*Snyk*, *Checkmarx*, *Veracode*) pornesc de la 15.000 € – 30.000 € / an, având modele opace de tarifare.
- **Deficit masiv de personal:** Peste 340.000 de posturi neacoperite în securitate cibernetică în Europa (studiu ISC2 2024); IMM-urile nu își permit salarii de specialiști in-house (4.000 €+/lună).
- **Zgomot și burnout:** Scanerele open-source generează sute de avertismente neexploatabile (alerte false), blocând release-urile de producție.
- **Risc financiar critic:** Costul mediu al unei breșe de date este de **4,88 milioane USD** (raport oficial IBM 2024).

### 🟢 Soluția bridg-E
1. **Filtrare inteligentă a alertelor false:** Verifică dacă funcția vulnerabilă dintr-o bibliotecă externă este într-adevăr apelată de codul aplicației.
2. **Remediere automată (Auto-PRs):** Deschide automat Pull Requests cu actualizarea versiunilor de dependențe sigure, fără a rupe compatibilitatea.
3. **Audit continuu & Raportare de conformitate printr-un singur clic:** Generează rapoarte auditate pentru clienți enterprise și autorități de reglementare (NIS 2).
4. **Preț accesibil și transparent:** Planuri lunare începând de la **79 € / lună**, concepute special pentru echipe de 5–40 de programatori.

---

## 📊 Dimensionarea Pieței (TAM / SAM / SOM)

Calculul pieței a fost realizat utilizând metodologia **Top-Down** combinată cu **Bottom-Up**, ancorat în datele oficiale **Eurostat**, **INS** și raportul **ANIS România**:

```
┌─────────────────────────────────────────────────────────────┐
│  TAM (Total Addressable Market) - Piața Globală/UE          │
│  7.680.000.000 € (Piața DevSecOps & AppSec Europa)          │
├─────────────────────────────────────────────────────────────┤
│  SAM (Serviceable Addressable Market) - IMM-uri Software CEE │
│  42.500.000 € (România, Polonia, Cehia, Bulgaria, Ungaria)  │
├─────────────────────────────────────────────────────────────┤
│  SOM (Serviceable Obtainable Market) - Obiectiv Anul 2      │
│  214.560 € / an (120 clienți plătitori activi)              │
└─────────────────────────────────────────────────────────────┘
```

- **Punct de rentabilitate (Break-Even):** Atingerea a doar **28 de clienți activi** pe abonamentul Pro (149 €/lună).

---

## 💼 Modelul de Monetizare (Pricing Tiers)

| Pachet | Preț Lunar | Preț Anual | Cui i se adresează | Funcționalități Cheie |
| :--- | :---: | :---: | :--- | :--- |
| **Starter** | **79 € / lună** | 790 € / an | Echipe mici (până la 5 dev) | Scanare SAST, Secret Shield, SCA nelimitat, integrare GitHub/GitLab |
| **Pro** | **149 € / lună** | 1.490 € / an | IMM-uri în scalare (6–20 dev) | Tot din Starter + Motor de prioritizare inteligentă, PR-uri automate de patch, Rapoarte NIS 2 |
| **Enterprise** | **349 € / lună** | 3.490 € / an | Software houses & FinTech (>20 dev) | Tot din Pro + Scanare privată izolată (on-premise runner), SLA dedicat, consultanță trimestrială |

---

## 🏛️ Forma Juridică și Structura Firmei

- **Formă juridică:** Societate cu Răspundere Limitată (**S.R.L.**)
- **Cod CAEN principal:** **6201** – *Activități de realizare a software-ului la comandă (software orientat client)*
- **Coduri CAEN secundare:** **6202** (*Consultanță în tehnologia informației*), **6209** (*Alte activități de servicii privind tehnologia informației*)
- **Capital social:** **2.000 lei** (200 părți sociale a 10 lei fiecare, deținute egal: **20% per asociat fondator**)
- **Regim fiscal:** Plătitoare de impozit pe veniturile microîntreprinderilor (1% conform Legii 227/2015 și OUG 115/2023) și **plătitoare de TVA** (deducere 100% a cheltuielilor de infrastructură cloud).

---

## 📁 Structura Repozitoriului

```text
├── README.md                  # Prezentarea generală a proiectului și a echipei
├── Proiect_bridg-E_ANI.md     # Documentul complet al proiectului (S1 + S2 + S3)
│   ├── Secțiunea 0: Cercetarea Preliminară & Arborele Problemei
│   ├── Secțiunea 1: Identificarea și Înființarea Afacerii
│   ├── Secțiunea 2: Segmentarea și Dimensionarea Pieței (TAM/SAM/SOM)
│   ├── Secțiunea 3: Modelul de Afaceri (Business Model Canvas)
│   ├── Secțiunea 4: Analiza SWOT & Corelarea Elementelor
├── ANI_S1.pdf                 # Ghid metodologic Seminar 1 (Cercetare preliminară & Înființare)
├── ANI_S2.pdf                 # Ghid metodologic Seminar 2 (Segmentare & Dimensionare piață)
└── ANI_S3.pdf                 # Ghid metodologic Seminar 3 (Business Model Canvas & Analiză SWOT)
```

---

## 🚀 Tehnologii Avute în Vedere

- **Scanare & Parsing de Cod:** Algoritmi AST (Abstract Syntax Tree), Tree-sitter, motoare Semgrep personalizate
- **Backend & Microservicii:** Go (Golang) pentru execuție ultrarapidă, Python pentru analiză inteligentă de date
- **Baze de Date & Stocare:** PostgreSQL (date relaționale), ClickHouse (telemetrie și jurnale de scanare), Redis (cozi de sarcini)
- **Frontend & Dashboard:** React 18, TypeScript, TailwindCSS, Chart.js / Recharts
- **Infrastructură Cloud:** AWS (Fargate serverless, S3, RDS), Hetzner Cloud (noduri izolate conforme GDPR în UE)

---

## 📚 Bibliografie & Surse Statistice

1. **IBM Security (2024)** – *Cost of a Data Breach Report 2024*
2. **Sonatype (2024)** – *State of the Software Supply Chain, 10th Annual Edition*
3. **Veracode (2024)** – *State of Software Security Report 2024*
4. **ISC2 (2024)** – *Cybersecurity Workforce Study 2024*
5. **Parlamentul European & Consiliul UE** – *Directiva (UE) 2022/2555 privind măsuri pentru un nivel comun ridicat de securitate cibernetică în Uniune (Directiva NIS 2)*
6. **ANIS România (2024)** – *Studiul privind impactul industriei de software și servicii IT în economia României*
7. **Legislație Națională** – Legea societăților nr. 31/1990 republicată, Legea nr. 227/2015 privind Codul Fiscal, Legea nr. 239/2025.

