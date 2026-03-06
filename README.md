Fuel Price Dashboard

Interaktivní webová aplikace vytvořená v Pythonu pomocí Streamlit, která umožňuje přehledně analyzovat a porovnávat ceny pohonných hmot.

Aplikace pracuje s datasetem cen paliv, který načítá ze souboru CSV. Data jsou následně zpracována pomocí knihovny Pandas a vizualizována pomocí Altair. Výsledkem je jednoduchý dashboard, který umožňuje rychle získat přehled o cenách paliv a jejich vývoji.

🔗 Live aplikace:
https://fuel-app.streamlit.app/

---

Co aplikace umí

- načíst a zpracovat dataset cen pohonných hmot
- zobrazit základní statistiky (např. minimální cenu)
- vizualizovat data pomocí interaktivních grafů
- umožnit rychlé porovnání cen mezi typy paliv
- prezentovat výsledky v jednoduchém webovém dashboardu

---

Použité technologie

- Python
- Pandas – práce s daty
- Altair – datové vizualizace
- Streamlit – webová aplikace
- Git & GitHub – verzování projektu
- Streamlit Community Cloud – deployment aplikace

---

Struktura projektu

fuel-app
│
├── app.py            # hlavní Streamlit aplikace
├── data.csv          # dataset s cenami paliv
├── requirements.txt  # seznam Python knihoven
└── README.md

---

Spuštění projektu lokálně

1️⃣ Naklonujte repozitář

git clone <url-repozitare>
cd fuel-app

2️⃣ Nainstalujte závislosti

pip install -r requirements.txt

3️⃣ Spusťte aplikaci

streamlit run app.py

Po spuštění se aplikace otevře v prohlížeči na lokální adrese.

---

Kontext projektu

Projekt vznikl během workshopu zaměřeného na přechod od práce s daty k vytvoření jednoduché webové aplikace.
Cílem bylo projít celý proces:

- načtení a analýza dat
- vytvoření vizualizací
- zabalení do interaktivní aplikace
- nasazení na veřejnou URL

---

Možná budoucí rozšíření

- filtrování podle regionu nebo data
- porovnání cen mezi čerpacími stanicemi
- přidání dalších metrik (průměrná cena, trend)
- automatická aktualizace dat
