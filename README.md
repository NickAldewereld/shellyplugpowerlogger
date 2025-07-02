# shellyplugpowerlogger
Inspired by the post of Bert Hubert on LinkedIn: https://www.linkedin.com/posts/bert-hubert-b05452_last-week-i-presented-over-at-joy-of-coding-activity-7345926351108947968-KERN
# Shelly Plug Power Logger

## ⚡ Wat is dit?
Deze repository bevat een simpele, meetbare en uitbreidbare oplossing om het stroomverbruik van een apparaat via een **Shelly Plug S Gen3** te loggen, visualiseren en (optioneel) door te sturen naar externe diensten zoals InfluxDB, een API of MQTT-broker.

Het combineert:
- Een eenvoudige **bash-logger**
- Een **Python visualisatie-script** (matplotlib)
- Optionele integratie met externe systemen

---

## 📚 Waarom ik dit maak
Software- en hardware-efficiëntie zijn van maatschappelijk belang. Zoals Bert Hubert treffend zei:
> _"Save the world, write more efficient code."_

De meeste mensen hebben geen idee hoeveel energie software, apps en services verbruiken. Deze tool is een uitnodiging om dat **zelf te meten**. Bewustzijn begint bij zichtbaarheid. Wie zijn eigen energieverbruik kan meten, kan het verbeteren.

---

## 🌍 Waarom ik dit open source beschikbaar stel
- Om het makkelijker te maken voor anderen om écht energiebewuste software en infrastructuur te bouwen
- Om open kennisdeling te stimuleren over iets wat vaak verborgen blijft: **de energievoetafdruk van code**
- Omdat kleine meetbare acties zich kunnen opstapelen tot grote impact

Je mag deze repo vrij gebruiken, aanpassen en verbeteren. Ik waardeer bijdragen in de vorm van PR's, meldingen van verbeteringen of documentatie.

---

## ⚙️ Functionaliteit
- Bash-script dat elke seconde het actuele verbruik logt via Shelly's HTTP-API
- CSV-logbestand met `timestamp;power`
- Python-script voor eenvoudige visualisatie en gemiddelde berekening
- Voorbeeldcode om data door te sturen naar externe API's of tijdreeksdatabases

---

## 🚀 Toekomstige uitbreidingen (PRs welkom)
- Docker-compose met Mosquitto (MQTT) + InfluxDB + Grafana
- Integratie met Home Assistant
- Real-time notificaties bij piekverbruik
- Grafiek-export naar PNG/PDF
- Energieverbruik per sessie of applicatie

---

## 💪 Doe mee
Gebruik deze repo als startpunt. Meet je laptop, server, NAS, monitor of router. Deel wat je ontdekt. En help de wereld efficiënter te coderen.

---

**Auteur:** Nick (Aldewereld)  
**Contact:** [LinkedIn](https://www.linkedin.com/in/nickaldewereld) / [aldewereldconsultancy.nl](https://aldewereldconsultancy.nl)

---

> _"To measure is to know. If you cannot measure it, you cannot improve it."_  
> — Lord Kelvin
