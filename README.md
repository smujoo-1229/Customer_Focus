# Customer Focus – Success Experience Engine Console
A unified, offline, Excel‑driven insights engine for delivery excellence, renewal strategy, and executive reporting.

---

## ⭐ Overview
The **Customer Focus Engine Console** transforms six delivery‑critical Excel workbooks into structured insights and executive‑ready outputs.  
It is designed for Client Partners, Delivery Leaders, and Success Managers who need a **single pane of glass** for:

- Delivery assurance  
- Renewal forecasting  
- Stakeholder sentiment  
- Value realization  
- Weekly Status Reports (WSR)  
- Quarterly Business Reviews (QBR)

All processing runs **locally**, **offline**, and **securely**.

---

## ⭐ Features
- RAID insights  
- Ticket velocity & SLA performance  
- Delivery Health RAG scoring  
- Stakeholder sentiment analysis  
- Renewal probability scoring  
- Value realization tracking  
- Weekly Status Report generation  
- Quarterly Business Review content generation  

---

## ⭐ Architecture
The console uses a simple, modular pipeline:

1. **XLSX Parser Layer**  
   Validates required tabs and converts Excel → TSV.

2. **Engine Layer (6 engines)**  
   Each engine produces structured, deterministic outputs.

3. **Roll‑Up Layer**  
   Generates WSR and QBR summaries.

4. **Export Layer**  
   Outputs TXT, DOC, and clipboard‑ready content.

For full details, see the Wiki:  
- [Architecture](ca://s?q=Open_Architecture_Page)  
- [Engine Pipeline](ca://s?q=Open_Engine_Pipeline)  
- [Roll-Up Pipeline](ca://s?q=Open_Rollup_Pipeline)

---

## ⭐ Repository Structure

```
CustomerFocusEngineConsole/
│
├── RAID_Log.xlsx
├── Ticket_Velocity.xlsx
├── Delivery_Health.xlsx
├── Stakeholder_Map.xlsx
├── Renewal_Scoring.xlsx
├── Value_Realization.xlsx
│
└── README.md
```

Each workbook follows a strict template defined in the Wiki:  
- [Excel Template Requirements](ca://s?q=Open_File_Specifications)

---

## ⭐ Engines Included
- [RAID Engine](ca://s?q=Open_RAID_Engine)  
- [Ticket Velocity Engine](ca://s?q=Open_Ticket_Engine)  
- [Delivery Health Engine](ca://s?q=Open_Delivery_Engine)  
- [Stakeholder Engine](ca://s?q=Open_Stakeholder_Engine)  
- [Renewal Engine](ca://s?q=Open_Renewal_Engine)  
- [Value Realization Engine](ca://s?q=Open_Value_Engine)

---

## ⭐ How to Use

### 1. Prepare the six Excel templates  
Ensure all required tabs and columns are present.

### 2. Load the files into the console  
See: [Loading Files](ca://s?q=Open_User_Guide)

### 3. Run the engines  
Each engine processes its workbook and produces structured outputs.

### 4. Generate roll‑ups  
- Weekly Status Report  
- Quarterly Business Review  

### 5. Export results  
Copy to clipboard or save as TXT/DOC.

Full instructions:  
- [Running Engines](ca://s?q=Open_Running_Engines)  
- [Exporting Outputs](ca://s?q=Open_Exporting_Outputs)

---

## ⭐ Screenshots & Examples (Coming Soon)
Sample outputs for each engine will be added here.

---

## ⭐ Roadmap
- Add sample engine outputs  
- Add automated validation scripts  
- Add dark‑mode Wiki theme  
- Add QBR slide template  

See full roadmap:  
- [Roadmap](ca://s?q=Open_Roadmap_Page)

---

## ⭐ Contributing
Guidelines for contributors:  
- [Contributing Guide](ca://s?q=Create_a_Contributing_Guide)

---

## ⭐ License
This project is proprietary and intended for internal use.

s
