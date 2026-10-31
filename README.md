# Vasúti szintbeni átjáró felüljáróval történő kiváltásának CBA és Érzékenységvizsgálati Modellezése

Ez a repozitórium a Széchenyi István Egyetemen készült TDK-dolgozat automatizált költség-haszon elemzési (CBA) és kétváltozós érzékenységvizsgálati Python-modelljét tartalmazza.

## 🚀 Főbb funkciók
- **17-féle társadalmi-gazdasági haszon automatizált számítása** (időmegtakarítás, baleseti kockázat, légszennyezés, éghajlatváltozás, zajterhelés, rendkívüli események).
- **Közgazdasági teljesítménymutatók meghatározása:** ENPV (Közgazdasági Nettó Jelenérték), ERR (Közgazdasági Belső Megtérülési Ráta), BCR (Haszon-Költség Arány).
- **Kétváltozós Érzékenységvizsgálati Mátrix:** A beruházási költség (CAPEX) és a társadalmi hasznok szimultán elmozdulásának hatásvizsgálata.
- **Interaktív Streamlit Dashboard:** Döntéstámogató webes felület a paraméterek valós idejű finomhangolásához.

## 🛠️ Használat és futtatás

1. A függőségek telepítése:
```bash
pip install -r requirements.txt
```

2. Modell futtatása:
```bash
python modell.py

