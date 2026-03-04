# Actorii 
Sistemul de gestionare a mersului trenurilor este conceput pentru a servi mai multi actori, fiecare cu roluri, responsabilitati si nevoi specifice. Aceasta sectiune descrie in detaliu cine are nevoie de sistem, cum il vor folosi si ce vor obtine din el.

## 1. Beneficiari

### 1.1 Compania de Transport Feroviar/Metrou

**Descriere**: Operatorul de transport care exploateaza tren sau metroul. Aceasta este organizatia care detine infrastructura, trenurile si personalul.

**Beneficii directe**:

- Reducerea drastica a costurilor operationale prin planificare mai inteligenta
- Optimizarea consumului de energie/combustibil
- Cresterea capacitatii de transport fara a cumpara trenuri suplimentare
- Minimizarea incidentelor si intarzierilor care duc la pierderi financiare
- Imbunatatirea reputatiei prin servicii mai punctuale

**Functionalitati importante**: Monitorizare trafic, Planificare optimizata, Raportare si Analytics, Gestiuni incidente

---

### 1.2 Pasageri - Oamenii care calatoresc

**Descriere**: Utilizatorii finali care isi cumpara biletele si se urca in trenuri. Sunt milioane de calatorii zilnici care depind de fiabilitatea sistemului.

**Beneficii directe**:

- Reducerea intarzierilor si a aglomeratiei
- Informatii actualizate in real-time despre orar si schimbari
- Incredere ca sistemul va face totul corect, automat

**Functionalitati importante**: Informatii in timp real, Predicitii de sosire, Notificari intarzieri, Rutare alternativa

---


## 2. Utilizatori de Sistem

### 2.1 Operatori de Control

**Descriere**: Oamenii care stau in centrul de control si privesc ecrane cu informatii. Cand se intampla ceva anormal, ei sunt primii care stiu.

**Responsabilitati principale**:

- Monitorizarea traficului in timp real pe toata reteaua
- Detectarea anomaliilor si situatiilor problematice
- Luarea deciziilor rapide in situatii de urgenta (accidente, defectiuni tehnice, etc.)
- Comunicarea cu conductorii de tren si cu personalul din teren
- Ajustarea planificarii in caz de intarzieri sau perturbatii

**Functionalitati pe care se bazeaza**: Monitorizare trafic real-time, Alerte inteligente, Panoul de control integrat, Istoricul deciziilor, Comunicare bidirectionala

---

### 2.2 Conducatori de Tren si Personal de Operare

**Descriere**: Acestia stau in cabina, control trenul si sunt direct responsabili pentru siguranta pasagerilor. Sistemul le spune cum sa opereze trenul, cu ce viteza sa mearga, cand sa se opreasca.

**Responsabilitati principale**:

- Ghidarea trenului pe rutele stabilite de sistem
- Respectarea comenzilor de viteza si oprire
- Monitorizarea starii mecanice a trenului
- Anuntarea intarzierilor si problemelor
- Asigurarea imbarcarilor/debarcarilor sigure

**Functionalitati pe care se bazeaza**: Transmitere comenzi viteza, Notificari ruta, Comunicare sistem-tren, Rapoarte probleme, Stocare date tren

---

### 2.3 Personal de Intretinere si Reparatii

**Descriere**: Sunt "medicii" sistemului. Cand ceva se strica, ei vin si il repara. Trebuie sa stie exact ce s-a intamplat, de ce s-a stricat si cum sa-l repare rapid.

**Responsabilitati principale**:

- Efectuarea unor inspectii periodice preventive
- Repararea echipamentelor defecte din teren
- Purtarea unor intretineri planificate ale infrastructurii
- Raportarea starii echipamentelor
- Colectarea datelor de senori pentru analiza
- Asigurarea ca echipamentele sunt in stare de functionare

**Functionalitati pe care se bazeaza**: Predictii defectiuni, Diagnostic tehnic, Rapoarte intretinere, Gestiune componente, Planificare reparatii

---

## 3. Utilizatori Finali - Cine are "avantajele"?

### 3.1 Calatori

**Descriere**: Sunt oamenii obisnuiti care iau metroul/trenul pentru a merge la munca, scoala, sau alte activitati. Nu stiu (si nu trebuie sa stie) ca exista un sistem complicat in spate.

**Cum interactioneaza cu sistemul**:

- Verifica orarul pe site-ul companiei sau aplicatia mobila
- Vede pe panouri electronice din statii informatii despre trenurile care sosesc
- Primeste notificari daca trenul lui intarzie
- Asculta anunturile din tren despre schimbari de ruta

**Functionalitati importante**: Informatii orar, Panouri electronice, Anunturi in tren, Notificari aplicatie, Predictii sosire

---

### 3.2 Personal de Vanzare Bilete si de Informare a Pasagerilor

**Descriere**: Sunt angajatii companiei de transport care lucreaza la ghisee, in statii sau prin call-center-uri. Raspund la intrebari ale pasagerilor despre orar, trasee, bilete.


**Functionalitati importante**: Informatii la ghiseu, Vedere real-time trafic, Explicatii intarzieri, Sugestii rute, Degree aglomeratie

---

### 3.3 Servicii Media si Comunicare (Reteaua, Social Media, Aplicatii)

**Descriere**: Sunt platformele care comunica cu publicul larev. Pot fi site-urile companiei, aplicatiile mobile, SMS, social media (Facebook, Twitter, etc).

**Cum interactioneaza cu sistemul**:

- Primesc date in timp real din sistemul principal (printr-o interfata API)
- Afiseaza aceste date utilizatorilor intr-o forma asa de inteleg
- Comunica intarzierile si schimbarile

**Functionalitati importante**: API pentru integrare, Real-time data feed, Notificari schimbari, Formatare date, Rapoarte HTML export

---