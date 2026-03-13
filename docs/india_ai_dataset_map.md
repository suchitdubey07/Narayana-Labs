# India AI Dataset Map

**Objective:** A strategic map of 100+ publicly accessible Indian datasets to build foundational AI models for Narayan Labs. These datasets focus on real-world applications across law, finance, agriculture, education, healthcare, policy, and language.

---

## Category 1 — Law and Judiciary Datasets
*Goal: Build Indian legal AI models.*

**Dataset 1: Supreme Court Judgements (e-SCR)**
- **Source Organization:** Supreme Court of India
- **Public Link:** https://main.sci.gov.in/
- **Data Type:** PDF, Text
- **AI Use Cases:** Legal reasoning, case law summarization, precedent matching
- **Suggested Scraping Method:** API (if available) / Web Scraping (Selenium)
- **Priority Level:** High

**Dataset 2: eCourts Case Database**
- **Source Organization:** Department of Justice, India
- **Public Link:** https://ecourts.gov.in/
- **Data Type:** Structured tabular data, Text
- **AI Use Cases:** Judicial delay prediction, case outcome modeling
- **Suggested Scraping Method:** Automated web scraping with CAPTCHA handling
- **Priority Level:** High

**Dataset 3: Indian Kanoon Case Archive**
- **Source Organization:** Indian Kanoon
- **Public Link:** https://indiankanoon.org/
- **Data Type:** HTML text
- **AI Use Cases:** Semantic search, citation graph building
- **Suggested Scraping Method:** HTML Parsing / Official API
- **Priority Level:** High

**Dataset 4: Law Commission Reports**
- **Source Organization:** Law Commission of India
- **Public Link:** https://lawcommissionofindia.nic.in/
- **Data Type:** PDF
- **AI Use Cases:** Legal theory extraction, policy analysis
- **Suggested Scraping Method:** PDF Extraction (OCR/PyPDF)
- **Priority Level:** Medium

**Dataset 5: IndiaCode (Central Acts)**
- **Source Organization:** Ministry of Law and Justice
- **Public Link:** https://www.indiacode.nic.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Regulatory compliance, statutory interpretation
- **Suggested Scraping Method:** Web scraping and PDF parsing
- **Priority Level:** High

**Dataset 6: NCLT Judgments**
- **Source Organization:** National Company Law Tribunal
- **Public Link:** https://nclt.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Corporate dispute resolution AI, bankruptcy prediction
- **Suggested Scraping Method:** PDF web scraping
- **Priority Level:** Medium

**Dataset 7: State High Court Judgments**
- **Source Organization:** Various High Courts (e.g., Delhi, Bombay)
- **Public Link:** Respective HC portals
- **Data Type:** PDF, Text
- **AI Use Cases:** Regional legal variations, localized precedent AI
- **Suggested Scraping Method:** Directed crawling scripts per state
- **Priority Level:** High

**Dataset 8: Bar Council Disciplinary Orders**
- **Source Organization:** Bar Council of India
- **Public Link:** http://www.barcouncilofindia.org/
- **Data Type:** PDF
- **AI Use Cases:** Legal ethics training, malpractice analysis
- **Suggested Scraping Method:** PDF extraction
- **Priority Level:** Low

**Dataset 9: Tribunals Orders (NGT, SAT)**
- **Source Organization:** National Green Tribunal / Securities Appellate Tribunal
- **Public Link:** https://greentribunal.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Environmental compliance, securities law reasoning
- **Suggested Scraping Method:** Automated URL listing and PDF download
- **Priority Level:** Medium

**Dataset 10: Ministry of Corporate Affairs (MCA) Regulations**
- **Source Organization:** MCA
- **Public Link:** https://www.mca.gov.in/
- **Data Type:** HTML, PDF
- **AI Use Cases:** Corporate compliance co-pilots
- **Suggested Scraping Method:** HTML parsing
- **Priority Level:** High

**Dataset 11: Parliamentary Standing Committee Reports (Law)**
- **Source Organization:** Parliament of India
- **Public Link:** https://loksabha.nic.in/
- **Data Type:** PDF
- **AI Use Cases:** Legislative intent understanding
- **Suggested Scraping Method:** PDF extraction
- **Priority Level:** Medium

**Dataset 12: Gazette of India**
- **Source Organization:** Department of Publication
- **Public Link:** https://egazette.gov.in/
- **Data Type:** PDF (Image-heavy)
- **AI Use Cases:** Tracking official legal notifications
- **Suggested Scraping Method:** Advanced OCR (Tesseract/Surya)
- **Priority Level:** High

---

## Category 2 — Finance and Economics Datasets
*Goal: Train financial and economic AI models.*

**Dataset 13: RBI Database of Indian Economy (DBIE)**
- **Source Organization:** Reserve Bank of India
- **Public Link:** https://dbie.rbi.org.in/
- **Data Type:** Structured tables (Excel/CSV)
- **AI Use Cases:** Macroeconomic forecasting, inflation modeling
- **Suggested Scraping Method:** Direct download / API reverse-engineering
- **Priority Level:** High

**Dataset 14: RBI Circular Archive**
- **Source Organization:** Reserve Bank of India
- **Public Link:** https://www.rbi.org.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Banking compliance bots, risk assessment
- **Suggested Scraping Method:** HTML/PDF extraction
- **Priority Level:** High

**Dataset 15: SEBI Filings and Guidelines**
- **Source Organization:** SEBI
- **Public Link:** https://www.sebi.gov.in/
- **Data Type:** PDF, Text
- **AI Use Cases:** Fraud detection, mutual fund advisory AI
- **Suggested Scraping Method:** Automated scraping with delay (rate-limited)
- **Priority Level:** High

**Dataset 16: NSE Market Data Archives**
- **Source Organization:** National Stock Exchange
- **Public Link:** https://www.nseindia.com/
- **Data Type:** CSV, JSON
- **AI Use Cases:** Algorithmic trading, sentiment impact analysis
- **Suggested Scraping Method:** API (requires header spoofing/session handling)
- **Priority Level:** High

**Dataset 17: BSE Corporate Filings (Announcements)**
- **Source Organization:** Bombay Stock Exchange
- **Public Link:** https://www.bseindia.com/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Corporate event extraction, financial summarization
- **Suggested Scraping Method:** Selenium / API interception
- **Priority Level:** High

**Dataset 18: Ministry of Statistics (MoSPI) Indicators**
- **Source Organization:** MoSPI
- **Public Link:** https://mospi.gov.in/
- **Data Type:** Excel, PDF
- **AI Use Cases:** Poverty estimation, demographic AI models
- **Suggested Scraping Method:** Direct file download
- **Priority Level:** Medium

**Dataset 19: GST Portal Statistics**
- **Source Organization:** GSTN
- **Public Link:** https://www.gst.gov.in/
- **Data Type:** Structured tables
- **AI Use Cases:** Tax revenue forecasting, MSME health tracking
- **Suggested Scraping Method:** Web scraping (tabular extraction)
- **Priority Level:** High

**Dataset 20: UIDAI / Aadhaar Dashboard stats**
- **Source Organization:** UIDAI
- **Public Link:** https://uidai.gov.in/
- **Data Type:** JSON/HTML
- **AI Use Cases:** Population metadata analytics, identity verification stats
- **Suggested Scraping Method:** API / HTML extraction
- **Priority Level:** Low

**Dataset 21: EPFO Payroll Data**
- **Source Organization:** Employees' Provident Fund Organisation
- **Public Link:** https://www.epfindia.gov.in/
- **Data Type:** PDF/Excel
- **AI Use Cases:** Formal sector employment modeling
- **Suggested Scraping Method:** File parsing
- **Priority Level:** Medium

**Dataset 22: IBBI Bankruptcy Records**
- **Source Organization:** Insolvency and Bankruptcy Board
- **Public Link:** https://ibbi.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Corporate failure prediction
- **Suggested Scraping Method:** PDF Extraction
- **Priority Level:** Medium

**Dataset 23: NABARD Rural Economy Reports**
- **Source Organization:** NABARD
- **Public Link:** https://www.nabard.org/
- **Data Type:** PDF
- **AI Use Cases:** Rural credit risk scoring
- **Suggested Scraping Method:** PDF Extraction
- **Priority Level:** High

**Dataset 24: India Budget Documents**
- **Source Organization:** Ministry of Finance
- **Public Link:** https://www.indiabudget.gov.in/
- **Data Type:** PDF, Excel
- **AI Use Cases:** Fiscal policy assistants
- **Suggested Scraping Method:** Direct download
- **Priority Level:** High

---

## Category 3 — Agriculture Datasets
*Goal: Train agricultural advisory AI.*

**Dataset 25: Agmarknet Market Prices**
- **Source Organization:** Directorate of Marketing & Inspection
- **Public Link:** https://agmarknet.gov.in/
- **Data Type:** Structured tables
- **AI Use Cases:** Real-time crop price prediction, arbitrage AI
- **Suggested Scraping Method:** Web scraping (ASP.NET form handling)
- **Priority Level:** High

**Dataset 26: ICAR Research Publications**
- **Source Organization:** Indian Council of Agricultural Research
- **Public Link:** https://icar.org.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** General agronomy Q&A, disease identification text
- **Suggested Scraping Method:** HTML/PDF crawling
- **Priority Level:** High

**Dataset 27: Soil Health Card Database**
- **Source Organization:** Dept. of Agriculture
- **Public Link:** https://soilhealth.dac.gov.in/
- **Data Type:** Structured tabular data
- **AI Use Cases:** Fertilizer optimization models
- **Suggested Scraping Method:** Web scraping / API
- **Priority Level:** High

**Dataset 28: Crop Production Statistics**
- **Source Organization:** Ministry of Agriculture (DAC)
- **Public Link:** https://agricoop.nic.in/
- **Data Type:** Excel, CSV
- **AI Use Cases:** Yield forecasting models
- **Suggested Scraping Method:** Direct file download
- **Priority Level:** High

**Dataset 29: IMD Weather Data Archive**
- **Source Organization:** India Meteorological Department
- **Public Link:** https://mausam.imd.gov.in/
- **Data Type:** CSV, API, PDF
- **AI Use Cases:** Climate adaptation, weather-integrated crop advisory
- **Suggested Scraping Method:** IMD API / automated CSV downloads
- **Priority Level:** High

**Dataset 30: Kisan Call Center Transcripts/Summaries**
- **Source Organization:** KCC (via data.gov.in)
- **Public Link:** https://data.gov.in/
- **Data Type:** CSV
- **AI Use Cases:** Intent classification for farmer queries
- **Suggested Scraping Method:** Open Government Data API
- **Priority Level:** High

**Dataset 31: Enam (National Agriculture Market) Data**
- **Source Organization:** e-NAM
- **Public Link:** https://www.enam.gov.in/
- **Data Type:** Structured tables
- **AI Use Cases:** Supply chain friction analysis
- **Suggested Scraping Method:** Web scraping
- **Priority Level:** Medium

**Dataset 32: Bhuvan Agriculture Geo-Data**
- **Source Organization:** ISRO
- **Public Link:** https://bhuvan-app1.nrsc.gov.in/
- **Data Type:** GeoTiff, Spatial Data
- **AI Use Cases:** Multispectral crop health assessment
- **Suggested Scraping Method:** Bhuvan API
- **Priority Level:** Medium

**Dataset 33: Directorate of Pulses Research Docs**
- **Source Organization:** ICAR-IIPR
- **Public Link:** https://iipr.icar.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Specialized crop advisory
- **Suggested Scraping Method:** URL crawling
- **Priority Level:** Low

**Dataset 34: Spice Board Export Data**
- **Source Organization:** Spices Board India
- **Public Link:** http://www.indianspices.com/
- **Data Type:** Excel
- **AI Use Cases:** Export viability modeling
- **Suggested Scraping Method:** Direct download
- **Priority Level:** Low

**Dataset 35: PM Fasal Bima Yojana Data**
- **Source Organization:** Ministry of Agriculture
- **Public Link:** https://pmfby.gov.in/
- **Data Type:** PDF reports
- **AI Use Cases:** Crop insurance risk modeling
- **Suggested Scraping Method:** Web scraping
- **Priority Level:** Medium

**Dataset 36: Central Water Commission Reservoir Levels**
- **Source Organization:** CWC
- **Public Link:** http://cwc.gov.in/
- **Data Type:** Excel, PDF
- **AI Use Cases:** Irrigation planning AI
- **Suggested Scraping Method:** File extraction
- **Priority Level:** High

---

## Category 4 — Education Datasets
*Goal: Build AI tutors and learning models.*

**Dataset 37: NCERT Textbooks**
- **Source Organization:** NCERT
- **Public Link:** https://ncert.nic.in/
- **Data Type:** PDF, epub
- **AI Use Cases:** K-12 curriculum-aligned AI tutors
- **Suggested Scraping Method:** PDF downloading and text extraction
- **Priority Level:** High

**Dataset 38: SWAYAM Course Materials**
- **Source Organization:** Ministry of Education
- **Public Link:** https://swayam.gov.in/
- **Data Type:** Video transcripts, PDFs
- **AI Use Cases:** Higher education AI teaching assistants
- **Suggested Scraping Method:** Headless browser for auth-gated content (if permitted)
- **Priority Level:** High

**Dataset 39: DIKSHA Education Platform Content**
- **Source Organization:** Sunbird / MoE
- **Public Link:** https://diksha.gov.in/
- **Data Type:** Multilingual text, JSON metadata
- **AI Use Cases:** Multilingual teaching models mapped to micro-capabilities
- **Suggested Scraping Method:** Sunbird telemetry/content APIs
- **Priority Level:** High

**Dataset 40: NPTEL Video Transcripts**
- **Source Organization:** IITs
- **Public Link:** https://nptel.ac.in/
- **Data Type:** Text
- **AI Use Cases:** Engineering conceptual reasoning
- **Suggested Scraping Method:** YouTube transcript extraction
- **Priority Level:** Medium

**Dataset 41: UDISE+ School Data**
- **Source Organization:** Ministry of Education
- **Public Link:** https://udiseplus.gov.in/
- **Data Type:** Structured tabular data
- **AI Use Cases:** Education infrastructure assessment models
- **Suggested Scraping Method:** Report downloading
- **Priority Level:** Medium

**Dataset 42: CBSE Past Year Question Papers**
- **Source Organization:** CBSE
- **Public Link:** https://cbse.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Exam preparation AI, automatic grading validation
- **Suggested Scraping Method:** Web crawling & PDF extraction
- **Priority Level:** High

**Dataset 43: AICTE Approved Institutions Data**
- **Source Organization:** AICTE
- **Public Link:** https://www.aicte-india.org/
- **Data Type:** Excel
- **AI Use Cases:** Higher ed capacity modeling
- **Suggested Scraping Method:** File download
- **Priority Level:** Low

**Dataset 44: Skill India Frameworks**
- **Source Organization:** NSDC
- **Public Link:** https://www.nsdcindia.org/
- **Data Type:** PDF qualification packs
- **AI Use Cases:** Vocational training chatbots
- **Suggested Scraping Method:** PDF extraction
- **Priority Level:** Medium

**Dataset 45: IGNOU Study Materials (eGyanKosh)**
- **Source Organization:** IGNOU
- **Public Link:** https://egyankosh.ac.in/
- **Data Type:** PDF
- **AI Use Cases:** Distance learning AI integration
- **Suggested Scraping Method:** DSpace repository scraping OAI-PMH
- **Priority Level:** High

**Dataset 46: CUET Syllabus and Guidelines**
- **Source Organization:** NTA
- **Public Link:** https://cuet.samarth.ac.in/
- **Data Type:** PDF
- **AI Use Cases:** Entrance exam advisory bots
- **Suggested Scraping Method:** File extraction
- **Priority Level:** Low

**Dataset 47: State Board Bilingual Textbooks**
- **Source Organization:** Various State SCERTs (e.g., Balbharati)
- **Public Link:** State-specific portals
- **Data Type:** PDF
- **AI Use Cases:** Dialect-specific learning assistants
- **Suggested Scraping Method:** Web crawling
- **Priority Level:** High

**Dataset 48: National Education Policy (NEP 2020) Docs**
- **Source Organization:** Ministry of Education
- **Public Link:** https://www.education.gov.in/nep-new
- **Data Type:** HTML, PDF
- **AI Use Cases:** Policy compliance checking in EdTech
- **Suggested Scraping Method:** Standard web scraping
- **Priority Level:** Medium

---

## Category 5 — Healthcare Datasets
*Goal: Build medical knowledge models.*

**Dataset 49: National Health Portal Knowledge Base**
- **Source Organization:** Ministry of Health
- **Public Link:** https://www.nhp.gov.in/
- **Data Type:** HTML, Multilingual Text
- **AI Use Cases:** Primary health triage bots (informational)
- **Suggested Scraping Method:** Web scraping using Scrapy
- **Priority Level:** High

**Dataset 50: Ayush Research Datasets**
- **Source Organization:** Ministry of Ayush / TKDL
- **Public Link:** https://ayush.gov.in/
- **Data Type:** Text
- **AI Use Cases:** Traditional medicine knowledge extraction
- **Suggested Scraping Method:** Web scraping (Respecting TKDL permissions)
- **Priority Level:** Medium

**Dataset 51: National Family Health Survey (NFHS)**
- **Source Organization:** IIPS Mumbai
- **Public Link:** https://rchiips.org/nfhs/
- **Data Type:** Excel, PDF fact sheets
- **AI Use Cases:** Public health trend analysis, malnutrition modeling
- **Suggested Scraping Method:** Document parsing
- **Priority Level:** High

**Dataset 52: Indian Pharmacopoeia Guidelines**
- **Source Organization:** IPC
- **Public Link:** https://ipc.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Drug interaction and standard formulation checking
- **Suggested Scraping Method:** Secure document scraping
- **Priority Level:** High

**Dataset 53: ICMR Treatment Guidelines**
- **Source Organization:** Indian Council of Medical Research
- **Public Link:** https://www.icmr.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Clinical decision support SLMs
- **Suggested Scraping Method:** PDF Extraction
- **Priority Level:** High

**Dataset 54: CDSCO Drug Approvals**
- **Source Organization:** Central Drugs Standard Control Organisation
- **Public Link:** https://cdsco.gov.in/
- **Data Type:** HTML tables, PDF
- **AI Use Cases:** Pharma regulatory AI
- **Suggested Scraping Method:** Web scraping tabular data
- **Priority Level:** Medium

**Dataset 55: Health Management Information System (HMIS)**
- **Source Organization:** MoHFW
- **Public Link:** https://hmis.nhp.gov.in/
- **Data Type:** Aggregated tabular data
- **AI Use Cases:** Resource allocation prediction
- **Suggested Scraping Method:** Portal report extraction
- **Priority Level:** Medium

**Dataset 56: eSanjeevani Telemedicine Stats**
- **Source Organization:** MoHFW
- **Public Link:** https://esanjeevani.mohfw.gov.in/
- **Data Type:** JSON dashboard data
- **AI Use Cases:** Rural healthcare demand forecasting
- **Suggested Scraping Method:** API polling
- **Priority Level:** Low

**Dataset 57: FSSAI Food Safety Standards**
- **Source Organization:** FSSAI
- **Public Link:** https://fssai.gov.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Nutritional compliance and public safety bots
- **Suggested Scraping Method:** Web crawling
- **Priority Level:** Medium

**Dataset 58: NCOV/COVID-19 Open Data Portals**
- **Source Organization:** covid19india.org (Archive)
- **Public Link:** https://data.covid19india.org/
- **Data Type:** JSON, CSV
- **AI Use Cases:** Epidemiological modeling benchmarks
- **Suggested Scraping Method:** Direct download/API
- **Priority Level:** Low

**Dataset 59: Medical Council of India (NMC) Regulations**
- **Source Organization:** National Medical Commission
- **Public Link:** https://www.nmc.org.in/
- **Data Type:** PDF
- **AI Use Cases:** Medical ethics AI
- **Suggested Scraping Method:** PDF parsing
- **Priority Level:** Low

**Dataset 60: Poshan Abhiyaan Data Metadata**
- **Source Organization:** MWCD
- **Public Link:** https://poshanabhiyaan.gov.in/
- **Data Type:** HTML, CSV
- **AI Use Cases:** Maternal health and nutrition policy models
- **Suggested Scraping Method:** Web scraping
- **Priority Level:** Medium

---

## Category 6 — Government and Policy Datasets
*Goal: Train policy interpretation models.*

**Dataset 61: Open Government Data (OGD) Portal**
- **Source Organization:** NIC / MeitY
- **Public Link:** https://data.gov.in/
- **Data Type:** CSV, JSON, APIs
- **AI Use Cases:** Public administration intelligence, regional demographic AI
- **Suggested Scraping Method:** Official OGD APIs
- **Priority Level:** High

**Dataset 62: Lok Sabha Debates (Hansard)**
- **Source Organization:** Parliament of India (Lok Sabha)
- **Public Link:** https://loksabha.nic.in/
- **Data Type:** PDF/HTML transcripts
- **AI Use Cases:** Political discourse modeling, policy intent analysis
- **Suggested Scraping Method:** Web scraping debate archives
- **Priority Level:** High

**Dataset 63: Rajya Sabha Debates**
- **Source Organization:** Parliament of India (Rajya Sabha)
- **Public Link:** https://rajyasabha.nic.in/
- **Data Type:** PDF transcripts
- **AI Use Cases:** Legislative monitoring, sentiment analysis
- **Suggested Scraping Method:** PDF downloading and parsing
- **Priority Level:** High

**Dataset 64: Election Commission Past Results**
- **Source Organization:** Election Commission of India
- **Public Link:** https://eci.gov.in/
- **Data Type:** Excel, PDF, HTML
- **AI Use Cases:** Electoral trend prediction, constituency analysis
- **Suggested Scraping Method:** Tabular scraping
- **Priority Level:** Medium

**Dataset 65: NITI Aayog SDG India Index**
- **Source Organization:** NITI Aayog
- **Public Link:** https://sdgindiaindex.niti.gov.in/
- **Data Type:** JSON dashboards, PDF
- **AI Use Cases:** State-level policy modeling, development index forecasting
- **Suggested Scraping Method:** API polling
- **Priority Level:** High

**Dataset 66: Census of India Metadata & Reports**
- **Source Organization:** Office of the Registrar General & Census Commissioner
- **Public Link:** https://censusindia.gov.in/
- **Data Type:** Excel, PDF
- **AI Use Cases:** Core demographic baselines for sociolinguistic models
- **Suggested Scraping Method:** Direct download
- **Priority Level:** High

**Dataset 67: PM Gati Shakti National Master Plan Data**
- **Source Organization:** DPIIT / BISAG-N
- **Public Link:** https://pmgatishakti.gov.in/
- **Data Type:** Geo-spatial documents
- **AI Use Cases:** Infrastructure planning AI
- **Suggested Scraping Method:** Web scraping public reports
- **Priority Level:** Medium

**Dataset 68: Ministry of Rural Development Reports**
- **Source Organization:** MoRD
- **Public Link:** https://rural.nic.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Rural scheme (MGNREGA) evaluation bots
- **Suggested Scraping Method:** HTML/PDF crawling
- **Priority Level:** High

**Dataset 69: MGNREGA Public Data Portal**
- **Source Organization:** MoRD
- **Public Link:** https://nrega.nic.in/
- **Data Type:** Structured tabular
- **AI Use Cases:** Employment trend prediction
- **Suggested Scraping Method:** Automated web scraping
- **Priority Level:** Medium

**Dataset 70: National Crime Records Bureau (NCRB) Reports**
- **Source Organization:** NCRB, MHA
- **Public Link:** https://ncrb.gov.in/
- **Data Type:** PDF, Excel
- **AI Use Cases:** Criminology and socio-legal modeling
- **Suggested Scraping Method:** File extraction
- **Priority Level:** High

**Dataset 71: Comptroller and Auditor General (CAG) Audit Reports**
- **Source Organization:** CAG
- **Public Link:** https://cag.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Government expenditure anomaly detection
- **Suggested Scraping Method:** PDF parsing
- **Priority Level:** High

**Dataset 72: MyGov Consultations and Discussions**
- **Source Organization:** MyGov India
- **Public Link:** https://www.mygov.in/
- **Data Type:** Text, HTML
- **AI Use Cases:** Public sentiment mapping towards policies
- **Suggested Scraping Method:** Web scraping (Requires careful rate limiting)
- **Priority Level:** Medium

---

## Category 7 — Language and Multilingual Datasets
*Goal: Train multilingual Indian language models.*

**Dataset 73: Bhashini (NLTM) Parallels & Corpora**
- **Source Organization:** Ministry of Electronics and IT (MeitY)
- **Public Link:** https://bhashini.gov.in/
- **Data Type:** Text, Audio
- **AI Use Cases:** Machine translation, ASR (Automatic Speech Recognition)
- **Suggested Scraping Method:** Official Bhashini API/Downloads
- **Priority Level:** High

**Dataset 74: AI4Bharat Datasets (Samanantar, IndicCorp)**
- **Source Organization:** IIT Madras / AI4Bharat
- **Public Link:** https://ai4bharat.org/
- **Data Type:** Massive text corpora, HuggingFace datasets
- **AI Use Cases:** Base SLM pre-training, Tokenizer expansion
- **Suggested Scraping Method:** HuggingFace `datasets` library
- **Priority Level:** High

**Dataset 75: TDIL (Technology Development for Indian Languages)**
- **Source Organization:** MeitY
- **Public Link:** https://tdil.mit.gov.in/
- **Data Type:** Parallel corpora, Lexicons
- **AI Use Cases:** Traditional NLP, morphological analyzers
- **Suggested Scraping Method:** Direct download (requires free registration)
- **Priority Level:** High

**Dataset 76: Central Institute of Indian Languages (CIIL) Corpora**
- **Source Organization:** CIIL, Mysuru
- **Public Link:** https://www.ciil.org/
- **Data Type:** Text, Linguistic rules
- **AI Use Cases:** Deep linguistic fine-tuning
- **Suggested Scraping Method:** Web scraping/Direct request
- **Priority Level:** Medium

**Dataset 77: Wikipedia Dumps (Indic Languages)**
- **Source Organization:** Wikimedia Foundation
- **Public Link:** https://dumps.wikimedia.org/
- **Data Type:** XML, Text
- **AI Use Cases:** Foundational knowledge graph, Continual Pre-Training
- **Suggested Scraping Method:** Direct torrent/HTTP download
- **Priority Level:** High

**Dataset 78: Sahitya Akademi Journals and Texts (Open Access)**
- **Source Organization:** Sahitya Akademi
- **Public Link:** http://sahitya-akademi.gov.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Cultural nuance capture, literary stylistics
- **Suggested Scraping Method:** Web crawling
- **Priority Level:** Low

**Dataset 79: Indian Wikisource (Public Domain Books)**
- **Source Organization:** Wikimedia
- **Public Link:** https://wikisource.org/
- **Data Type:** Text, HTML
- **AI Use Cases:** High-quality OCR validation, historical text modeling
- **Suggested Scraping Method:** API
- **Priority Level:** Medium

**Dataset 80: Project Gutenberg (Indic subset)**
- **Source Organization:** Project Gutenberg
- **Public Link:** https://www.gutenberg.org/
- **Data Type:** plain text
- **AI Use Cases:** Pre-training corpora
- **Suggested Scraping Method:** Mirror downloading
- **Priority Level:** Low

**Dataset 81: Anuvaad Project Code & Data (Supreme Court AI)**
- **Source Organization:** EkStep / Supreme Court
- **Public Link:** https://anuvaad.sunbird.org/
- **Data Type:** Legal parallel text
- **AI Use Cases:** Domain-specific translation
- **Suggested Scraping Method:** GitHub / Sunbird APIs
- **Priority Level:** High

**Dataset 82: NPTEL Translated Transcripts**
- **Source Organization:** IITs via AICTE
- **Public Link:** https://nptel.ac.in/translation
- **Data Type:** VTT, Text
- **AI Use Cases:** Scientific concept translation
- **Suggested Scraping Method:** API/Scraping
- **Priority Level:** High

**Dataset 83: Prasar Bharati Audio/Text Transcripts**
- **Source Organization:** Doordarshan/AIR
- **Public Link:** https://prasarbharati.gov.in/
- **Data Type:** Audio, some text
- **AI Use Cases:** Indic TTS/ASR
- **Suggested Scraping Method:** RSS / Web scraping
- **Priority Level:** Medium

**Dataset 84: IndicGLUE Benchmark Data**
- **Source Organization:** AI4Bharat
- **Public Link:** https://indicnlp.ai4bharat.org/indicglue/
- **Data Type:** JSON
- **AI Use Cases:** Benchmarking SLMs for Indic tasks
- **Suggested Scraping Method:** Direct Download
- **Priority Level:** High

---

## Category 8 — News and Media Datasets
*Goal: Train information retrieval and summarization models.*

**Dataset 85: Press Information Bureau (PIB) Releases**
- **Source Organization:** Ministry of I&B
- **Public Link:** https://pib.gov.in/
- **Data Type:** Multilingual HTML, PDF
- **AI Use Cases:** News summarization, fact-checking benchmarks
- **Suggested Scraping Method:** Selenium / Scrapy
- **Priority Level:** High

**Dataset 86: PRS Legislative Research Archives**
- **Source Organization:** PRS
- **Public Link:** https://prsindia.org/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Legislative monitoring, bill summarization AI
- **Suggested Scraping Method:** Web Crawling
- **Priority Level:** High

**Dataset 87: DD News Multilingual Feeds**
- **Source Organization:** Doordarshan
- **Public Link:** https://ddnews.gov.in/
- **Data Type:** RSS, HTML, Video
- **AI Use Cases:** Cross-lingual event extraction
- **Suggested Scraping Method:** RSS feed parsing
- **Priority Level:** Medium

**Dataset 88: Rajya Sabha TV / Sansad TV Debates (Metadata)**
- **Source Organization:** Sansad TV
- **Public Link:** https://sansadtv.nic.in/
- **Data Type:** HTML, YouTube Metadata
- **AI Use Cases:** Political debate summarization
- **Suggested Scraping Method:** YouTube API
- **Priority Level:** Medium

**Dataset 89: INFLIBNET Shodhganga (Open Access Theses)**
- **Source Organization:** UGC
- **Public Link:** https://shodhganga.inflibnet.ac.in/
- **Data Type:** PDF
- **AI Use Cases:** Academic RAG, scholarly summarization
- **Suggested Scraping Method:** OAI-PMH Harvesting
- **Priority Level:** High

**Dataset 90: National Archives of India (Digital)**
- **Source Organization:** Ministry of Culture
- **Public Link:** https://www.nationalarchives.nic.in/
- **Data Type:** Scanned images, Metadata
- **AI Use Cases:** Indic handwriting recognition, historical modeling
- **Suggested Scraping Method:** Portal scraping
- **Priority Level:** Low

**Dataset 91: Indira Gandhi National Centre for the Arts (IGNCA) Library**
- **Source Organization:** IGNCA
- **Public Link:** http://ignca.gov.in/
- **Data Type:** PDF manuscripts
- **AI Use Cases:** Cultural heritage AI, ancient language NLP
- **Suggested Scraping Method:** Web crawling
- **Priority Level:** Low

**Dataset 92: NITI Aayog Blogs and Op-Eds**
- **Source Organization:** NITI Aayog
- **Public Link:** https://niti.gov.in/
- **Data Type:** HTML
- **AI Use Cases:** Policy opinion mining
- **Suggested Scraping Method:** HTML parsing
- **Priority Level:** Medium

**Dataset 93: Reserve Bank of India Speeches**
- **Source Organization:** RBI
- **Public Link:** https://rbi.org.in/Scripts/BS_SpeechesView.aspx
- **Data Type:** HTML
- **AI Use Cases:** Economic sentiment analysis
- **Suggested Scraping Method:** Web scraping
- **Priority Level:** High

**Dataset 94: Ministry of External Affairs Statements**
- **Source Organization:** MEA
- **Public Link:** https://mea.gov.in/
- **Data Type:** HTML, PDF
- **AI Use Cases:** Geopolitical context modeling
- **Suggested Scraping Method:** Web crawling
- **Priority Level:** Medium

**Dataset 95: Open Government Data (News APIs)**
- **Source Organization:** OGD India
- **Public Link:** https://data.gov.in/
- **Data Type:** JSON/XML
- **AI Use Cases:** General event extraction
- **Suggested Scraping Method:** APIs
- **Priority Level:** Low

**Dataset 96: Supreme Court Observer Reports**
- **Source Organization:** SCO / Law organizations
- **Public Link:** https://www.scobserver.in/
- **Data Type:** HTML
- **AI Use Cases:** Layman legal summarization
- **Suggested Scraping Method:** Crawling
- **Priority Level:** High

---

## Category 9 — Transport and Infrastructure Datasets
*Goal: Train mobility, logistics, and spatial AI models.*

**Dataset 97: IRCTC / Indian Railways Statistics**
- **Source Organization:** Ministry of Railways
- **Public Link:** https://indianrailways.gov.in/
- **Data Type:** Excel, PDF
- **AI Use Cases:** Network optimization, demand forecasting
- **Suggested Scraping Method:** File extraction
- **Priority Level:** Medium

**Dataset 98: MoRTH Road Accident Data**
- **Source Organization:** Ministry of Road Transport and Highways
- **Public Link:** https://morth.nic.in/
- **Data Type:** PDF Annual Reports
- **AI Use Cases:** Road safety prediction models
- **Suggested Scraping Method:** PDF Tabular extraction (Camelot)
- **Priority Level:** Medium

**Dataset 99: Vahan/Sarathi Dashboard Public Stats**
- **Source Organization:** MoRTH
- **Public Link:** https://vahan.parivahan.gov.in/
- **Data Type:** HTML, JSON Dashboards
- **AI Use Cases:** EV adoption tracking, logistics modeling
- **Suggested Scraping Method:** API Polling
- **Priority Level:** High

**Dataset 100: AAI (Airports Authority of India) Traffic News**
- **Source Organization:** AAI
- **Public Link:** https://www.aai.aero/
- **Data Type:** PDF
- **AI Use Cases:** Aviation demand modeling
- **Suggested Scraping Method:** PDF downloading
- **Priority Level:** Low

**Dataset 101: FASTag Toll Collection Data**
- **Source Organization:** NETC / NPCI (via reports)
- **Public Link:** https://www.npci.org.in/
- **Data Type:** Excel, PDF
- **AI Use Cases:** Economic activity tracking via mobility
- **Suggested Scraping Method:** File extraction
- **Priority Level:** Medium

**Dataset 102: Smart Cities Mission Project Data**
- **Source Organization:** Ministry of Housing and Urban Affairs
- **Public Link:** https://smartcities.gov.in/
- **Data Type:** HTML, PDF
- **AI Use Cases:** Urban planning AI
- **Suggested Scraping Method:** Web scraping
- **Priority Level:** Medium

**Dataset 103: RERA (Real Estate Regulatory Authority) Project Filings**
- **Source Organization:** State RERAs (e.g., MahaRERA)
- **Public Link:** https://maharera.mahaonline.gov.in/
- **Data Type:** PDF, HTML
- **AI Use Cases:** Real estate risk assessment models
- **Suggested Scraping Method:** Web scraping (complex forms)
- **Priority Level:** High

**Dataset 104: OpenStreetMap (OSM) India Dumps**
- **Source Organization:** OSM Community / Geofabrik
- **Public Link:** https://download.geofabrik.de/asia/india.html
- **Data Type:** PBF, XML
- **AI Use Cases:** Logistics routing algorithms, spatial SLMs
- **Suggested Scraping Method:** Direct download
- **Priority Level:** High

**Dataset 105: Sagarmala Project Reports**
- **Source Organization:** Ministry of Ports, Shipping
- **Public Link:** https://sagarmala.gov.in/
- **Data Type:** PDF
- **AI Use Cases:** Maritime trade analysis
- **Suggested Scraping Method:** Document parsing
- **Priority Level:** Low

**Dataset 106: National Power Portal (NPP)**
- **Source Organization:** CEA / Ministry of Power
- **Public Link:** https://npp.gov.in/
- **Data Type:** Structured Tables, Dashboard Arrays
- **AI Use Cases:** Grid load forecasting AI
- **Suggested Scraping Method:** Tableau/Dashboard scraping
- **Priority Level:** High

**Dataset 107: MNRE Renewable Energy Statistics**
- **Source Organization:** Ministry of New and Renewable Energy
- **Public Link:** https://mnre.gov.in/
- **Data Type:** Excel
- **AI Use Cases:** Clean energy adoption mapping
- **Suggested Scraping Method:** File extraction
- **Priority Level:** Medium

**Dataset 108: Jal Jeevan Mission Dashboards**
- **Source Organization:** Ministry of Jal Shakti
- **Public Link:** https://ejalshakti.gov.in/
- **Data Type:** JSON
- **AI Use Cases:** Water resource tracking and planning
- **Suggested Scraping Method:** API Polling
- **Priority Level:** Medium

---

## Category 10 — Science, Space, and Environment Datasets
*Goal: Train scientific research, space, and climate AI models.*

**Dataset 109: ISRO Space Science Data Archives (ISSDC)**
- **Source Organization:** Indian Space Research Organisation
- **Public Link:** https://www.issdc.gov.in/
- **Data Type:** Specialized scientific data arrays (HDF5), images
- **AI Use Cases:** Astrophysics modeling, satellite image segmentation
- **Suggested Scraping Method:** Direct authenticated downloads
- **Priority Level:** High

**Dataset 110: MOSDAC (Meteorological and Oceanographic Satellite Data)**
- **Source Organization:** Space Applications Centre (SAC), ISRO
- **Public Link:** https://www.mosdac.gov.in/
- **Data Type:** NetCDF, Spatial
- **AI Use Cases:** Cyclone prediction models, oceanstate forecasting
- **Suggested Scraping Method:** Portal API
- **Priority Level:** High

**Dataset 111: Central Pollution Control Board (CPCB) AQI Data**
- **Source Organization:** CPCB
- **Public Link:** https://app.cpcbccr.com/
- **Data Type:** Live JSON / Historical CSV
- **AI Use Cases:** Air pollution prediction, civic alert bots
- **Suggested Scraping Method:** REST API / Dash scraping
- **Priority Level:** High

**Dataset 112: Wildlife Institute of India (WII) Reports**
- **Source Organization:** WII / MoEFCC
- **Public Link:** https://wii.gov.in/
- **Data Type:** PDF, GPS logs (if public)
- **AI Use Cases:** Bio-diversity tracking, poaching risk models
- **Suggested Scraping Method:** PDF Extraction
- **Priority Level:** Low

**Dataset 113: Geological Survey of India (GSI) Portal**
- **Source Organization:** Ministry of Mines
- **Public Link:** https://www.gsi.gov.in/
- **Data Type:** Geo-spatial maps, PDF reports
- **AI Use Cases:** Mineral exploration AI, landslide prediction
- **Suggested Scraping Method:** Web portal scraping
- **Priority Level:** Medium

**Dataset 114: INCOIS (Indian National Centre for Ocean Information)**
- **Source Organization:** MoES
- **Public Link:** https://incois.gov.in/
- **Data Type:** GeoTiff, Text advisories
- **AI Use Cases:** Tsunami early warning, potential fishing zone (PFZ) AI
- **Suggested Scraping Method:** Portal APIs and RSS
- **Priority Level:** High

**Dataset 115: CSIR Open Access Repositories**
- **Source Organization:** Council of Scientific & Industrial Research
- **Public Link:** Various lab portals (e.g., NAL, NCL)
- **Data Type:** Patent filings, Research papers
- **AI Use Cases:** R&D co-pilots, material science discovery
- **Suggested Scraping Method:** OAI-PMH Harvesting
- **Priority Level:** Medium

**Dataset 116: National Biodiversity Authority Database**
- **Source Organization:** NBA
- **Public Link:** http://nbaindia.org/
- **Data Type:** HTML, PDF
- **AI Use Cases:** Bio-piracy checking, taxonomy models
- **Suggested Scraping Method:** Web scraping
- **Priority Level:** Low

**Dataset 117: India WRIS (Water Resources Information System)**
- **Source Organization:** Ministry of Jal Shakti
- **Public Link:** https://indiawris.gov.in/
- **Data Type:** Hydrological data (Dashboards)
- **AI Use Cases:** Groundwater depletion predictive models
- **Suggested Scraping Method:** API Polling
- **Priority Level:** High

**Dataset 118: DST (Department of Science and Technology) Funding Data**
- **Source Organization:** DST
- **Public Link:** https://dst.gov.in/
- **Data Type:** PDF/Excel
- **AI Use Cases:** R&D trend analysis
- **Suggested Scraping Method:** Direct download
- **Priority Level:** Low

**Dataset 119: FSI (Forest Survey of India) State of Forest Reports**
- **Source Organization:** MoEFCC
- **Public Link:** https://fsi.nic.in/
- **Data Type:** PDF, GIS data
- **AI Use Cases:** Deforestation mapping via remote sensing baseline
- **Suggested Scraping Method:** PDF/Spatial download
- **Priority Level:** Medium

**Dataset 120: NCBS / TIFR Bio-Databases**
- **Source Organization:** Tata Institute of Fundamental Research
- **Public Link:** https://www.ncbs.res.in/
- **Data Type:** Protein sequences, biological texts
- **AI Use Cases:** Bioinformatics SLMs
- **Suggested Scraping Method:** specific bio-informatics APIs
- **Priority Level:** High

---

**Summary:** This map details 120 critical datasets tailored for the rapid development of Small Language Models and specialized AI systems relevant to India's unique socio-economic landscape. The prioritization ensures that Narayan Labs focuses initial scraping resources on building the highest-impact legal, financial, agricultural, and linguistic models first.
