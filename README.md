# 📊 T1 Esports Data Analysis

### 1. Introduction
This project focuses on collecting, processing, and analyzing match data of **T1** in various tournaments.  
The workflow includes:  
1. **Data crawling** from [T1 Match History on LoL Fandom](https://lol.fandom.com/wiki/T1/Match_History) for the period **01/2022 – 08/2025** (columns: `Date`, `Tournament`, `P`, `W/L`, `Side`, `Vs`, `Bans`, `Bans Vs`, `Picks`, `Picks Vs`, `Players`, `SB`, `VOD`).  
2. **Data preprocessing** using Python and Power BI: merging files, removing duplicates, standardizing column names (`Tournament`, `Vs`), and creating measures.  
3. **Data visualization** in Power BI: building dashboards to analyze results, performance, and comparisons.

---

### 2. Tools Used
- **Python**: BeautifulSoup (bs4), requests, pandas  
- **Power BI**: interactive report creation  
- **Data Source**: public data from [T1 Match History on LoL Fandom](https://lol.fandom.com/wiki/T1/Match_History)  
**Author:** Tai Pham
