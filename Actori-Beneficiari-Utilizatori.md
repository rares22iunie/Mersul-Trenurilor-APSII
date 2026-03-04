# Actorii Beneficiari, Utilizatori de Sistem și Utilizatori Finali

## 1. Actorii Beneficiari

Beneficiarii sunt entități care au avantaje directe din implementarea și funcționarea sistemului de gestionare a mersului trenurilor/metroului.

### 1.1 Compania de Transport Feroviar/Metrou

- **Beneficii**: Reducerea costurilor operaționale, optimizarea consumului de combustibil, creșterea capacității de transport prin planificare mai eficientă
- **Interes**: Eficiență operațională și profitabilitate

### 1.2 Pasageri

- **Beneficii**: Călătorii mai sigure, reducerea întârzierilor, informații în timp real, orar mai predictibil
- **Interes**: Confort și fiabilitate

### 1.3 Autorități Locale și Naționale

- **Beneficii**: Îmbunătățirea transportului public, reducerea congestiei, date pentru planicare urbană
- **Interes**: Mobilitate urbană și calitatea vieții

### 1.4 Mediul

- **Beneficii**: Reducerea emisiilor prin optimizare, încurajarea utilizării transportului public
- **Interes**: Sustenabilitate

---

## 2. Utilizatori de Sistem

Utilizatorii de sistem sunt profesioniști care interacționează direct cu sistemul pentru a gestiona și monitoriza operațiile.

### 2.1 Operatori de Control

- **Responsabilități**: Monitorizarea traficului în timp real, gestionarea situațiilor de urgență, ajustarea planificării
- **Permisiuni**: Acces complet la panoul de control, autoritate de decizie

### 2.2 Mecanici și Personal de Exploatare

- **Responsabilități**: Conducerea trenurilor, raportarea problemelor tehnice, respectarea instrucțiunilor sistemului
- **Permisiuni**: Acces la informații privind ruta, viteza și semnale

### 2.3 Personal de Întreținență

- **Responsabilități**: Mentenanța infrastructurii, repararea echipamentelor defecte, verificări de siguranță
- **Permisiuni**: Acces la date de diagnozare și raportare defectelor

### 2.4 Administratori de Sistem

- **Responsabilități**: Configurare și întreținere a software-ului, gestiunea utilizatorilor, backup și securitate
- **Permisiuni**: Acces complet la toate funcționalitățile tehnice și administrative

---

## 3. Utilizatori Finali

Utilizatorii finali sunt persoane care beneficiază indirect de serviciile sistemului fără a-l utiliza direct.

### 3.1 Pasageri

- **Interacțiune**: Aplicații mobile, panouri de informații la stații, anunțuri în trenuri
- **Necesități**: Informații despre orar, întârzieri, alternative de rute

### 3.2 Personal de Vânzare și Informare

- **Interacțiune**: Sisteme de informare integrate, vizualizare orar și disponibilitate
- **Necesități**: Informații actualizate pentru răspunsuri rapide pasagerilor

### 3.3 Servicii de Informare (Web, SMS, Social Media)

- **Interacțiune**: API-uri de integrare cu sisteme externe
- **Necesități**: Date în timp real despre stare trafic și anomalii

---

## 4. Relații între Actori

```
Sistem de Gestionare a Mersului Trenurilor
│
├── Beneficiari
│   ├── Compania de Transport
│   ├── Pasageri
│   ├── Autorități
│   └── Mediu
│
├── Utilizatori de Sistem
│   ├── Operatori de Control
│   ├── Mecanici
│   ├── Personal de Întreținență
│   └── Administratori
│
└── Utilizatori Finali
    ├── Pasageri
    ├── Personal de Vânzare
    └── Servicii de Informare
```

---

## 5. Prioritate și Considerații de Securitate

- **Acces Rol-Bazat (RBAC)**: Fiecare utilizator are acces doar la informațiile și funcționalitățile necesare rolului
- **Audit și Logging**: Toate acțiunile în sistem trebuie înregistrate pentru siguranță și conformitate
- **Autentificare Sigură**: Identificare obligatorie prin credențiale sau biometrie
- **Redundanță și Disaster Recovery**: Sistemul trebui să continue funcționarea chiar și la defeciuni parțiale
