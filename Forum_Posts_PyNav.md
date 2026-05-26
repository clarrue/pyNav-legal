# PyNav - Posts d'annonce multi-plateformes

---

# 🌐 POST 1 : forum.pypilot.org (EN)

**Title:** PyNav - Android app for pypilot remote control + full NMEA instruments display

---

Hi pypilot community!

I'm excited to share **PyNav**, an Android app I developed as a pypilot user myself.

## 🎯 Two use cases

**For pypilot users (free + PRO):**
Full autopilot control from smartphone or tablet, plus complete NMEA instrument display on a 10" tablet.

**For any navigator with a NMEA/WiFi module (PRO only):**
Turn your Android tablet into a professional navigation center — no pypilot required.

---

## ⚓ FREE — Autopilot tab

Direct WiFi connection to your Raspberry Pi hotspot (no router needed):

- Engage / disengage autopilot
- Mode switching (compass, wind, GPS, true wind, nav)
- Current heading display + target heading input
- Rudder angle indicator
- IMU data: pitch, roll, heel, rate of turn
- Full PID gain tuning (P, I, D, DD, PR, FF, WG, Deadzone)
- Compass & rudder calibration
- Tack parameters, pilot profiles
- Servo stats (amp-hours, voltage, temperatures, runtime)

⚠️ Free version: pypilot data only, no external NMEA instruments.

---

## 💎 PRO — Full navigation center (€8.99 launch / €12.99 regular)

**Works with or without pypilot** — just need a NMEA/WiFi module + Android tablet.

### ⊞ Dashboard
6 drag-and-drop panels: Wind, Navigation, Autopilot, Depth, Pressure (with 3h trend), Engine RPM.

### 🌬 Wind
Wind rose + 5-min history graph. AWA, AWS, TWA, TWS.

### 🔧 Engine instruments
RPM, coolant temp, oil pressure/temp, battery/alternator voltage, engine hours, fuel flow, exhaust temp, gear ratio, transmission oil, trim tabs.

**Tank levels:** port/starboard fuel, fresh water, grey water, black water.

Custom graphs: any engine parameter vs RPM or time.

### ◎ Navigation
Heading rose, SOG, COG, STW, lat/lon, waypoint navigation (BTW, DTW, XTE).

### 🔔 Alarms
Configurable on ALL NMEA data:
- Navigation: depth, speed, heading, pressure, wind (AWS/AWA/TWS/TWA)
- Engine: RPM, temps, pressures, voltages, fuel levels
- Autopilot: rudder angle, servo voltage, controller temp

Audio alarm + vibration + on-screen banner.

---

## 📡 Network setup

**Without pypilot:**
```
NMEA Module (WiFi hotspot) ──── Tablet
```

**With pypilot (Config A - recommended):**
```
Pypilot RPi ──WiFi──┐
                     ├── Mini router ──── Tablet
NMEA Module ──WiFi──┘
```

**With pypilot (Config B - NMEA module as AP):**
```
Pypilot RPi ──WiFi──┐
                     ├── NMEA Module (AP) ──── Tablet
Instruments ────────┘
```

Compatible: Yacht Devices YDWG-02/YDWN-02, Quark-elec QK-A034, Digital Yacht WLN10, Hat Labs SH-wg, Actisense W2K-1, any NMEA TCP/UDP WiFi module.

**Protocols:** NMEA 0183 TCP, NMEA 2000 Raw TCP, Pypilot TCP (port 23322).

---

🔒 100% local — no data sent to external servers. No ads, no tracking.

📥 Google Play Store: [LINK]
iOS: Coming soon

Happy to answer questions!
Colin — colin.larrue.pro@gmail.com

---
---

# 🌐 POST 2 : Cruisers Forum / YBW / Sailing Anarchy (EN)

**Title:** PyNav - Professional NMEA instrument center on Android tablet (+ pypilot remote)

---

Hi fellow sailors!

I've just released **PyNav**, an Android app that turns your tablet into a complete NMEA navigation center.

## Why I built it

MFDs cost €500-2000+. A good Android tablet costs €200-400 and a NMEA/WiFi module costs €150-300. Why not use what you already have — with a proper instrument display app?

## What PyNav PRO does (€8.99 launch / €12.99 regular)

Connect any NMEA/WiFi module to your tablet and get:

**Dashboard:** 6 customizable drag-and-drop panels — wind, navigation, depth (color-coded), pressure with 3h trend, engine RPM, autopilot.

**Wind:** Wind rose + 5-min history graph. AWA, AWS, TWA, TWS.

**Engine instruments:**
- RPM with configurable thresholds
- Coolant temp, oil pressure/temp, alternator/battery voltage
- Engine hours, fuel flow, exhaust temp
- Gear ratio (F/N/R), transmission oil
- **Tank gauges:** port/starboard fuel, fresh water, grey & black water
- Custom graphs (any parameter vs RPM or time)

**Navigation:** Heading rose, SOG, COG, STW, lat/lon, full waypoint navigation (BTW, DTW, XTE).

**Alarms on all NMEA data:** depth, speed, heading, wind, pressure, engine parameters, fuel levels — audio + vibration + banner.

## Compatible NMEA/WiFi modules
Yacht Devices YDWG-02/YDWN-02, Quark-elec QK-A034, Digital Yacht WLN10, Hat Labs SH-wg, Actisense W2K-1, or any NMEA 0183/2000 TCP/UDP WiFi module.

## Bonus
If you also run pypilot, the **free version** gives full autopilot remote control (modes, gains, calibration, profiles, servo stats) from the same device.

## Setup
```
NMEA Module (WiFi hotspot) ──── Android Tablet (PyNav)
```
Or via central router if you also have pypilot.

📥 Google Play Store: [LINK]
iOS: Coming soon

Happy to answer questions!
Colin

---
---

# 🌐 POST 3 : Reddit r/sailing / r/liveaboard (EN)

**Title:** [App] PyNav - Full NMEA instruments on Android tablet + pypilot remote

---

Hey r/sailing!

Just launched **PyNav** — an Android app for NMEA instrument display on tablet and/or pypilot autopilot control.

**TL;DR:**
- FREE: Full pypilot autopilot remote (if you have pypilot)
- PRO €8.99 launch / €12.99: Complete NMEA navigation center on any Android tablet

**What you need for PRO:**
Any NMEA/WiFi module (Yacht Devices, Quark-elec, Digital Yacht, etc.) + Android tablet.

**What you get:**
- Dashboard with customizable panels (wind, depth, pressure trend, engine RPM...)
- Wind rose + history graph (AWA, AWS, TWA, TWS)
- Full engine instruments: RPM, coolant, oil pressure/temp, battery, alternator, fuel flow, exhaust temp, gear ratio, **tank levels** (fuel port/stbd, fresh water, grey/black water)
- GPS navigation + waypoint (BTW, DTW, XTE)
- Configurable alarms on ALL NMEA data: depth, speed, wind, pressure, engine, fuel levels...
- Audio alarm + vibration + banner

No pypilot needed for PRO — just a NMEA/WiFi gateway and a tablet.
Works 100% offline on your boat's local network.

📥 [Play Store link]

Questions about setup or compatibility, happy to help!

---
---

# 🇫🇷 POST 4 : voile-hauturier.fr / hisse-et-oh.com / voileux.com

**Titre :** PyNav - Centrale de navigation NMEA complète sur tablette Android + télécommande pypilot

---

Bonjour à tous !

Je viens de publier **PyNav**, une application Android pour afficher tous vos instruments NMEA sur tablette et/ou contrôler un pilote automatique pypilot.

## Pourquoi cette appli ?

Les MFD dédiés coûtent 500 à 2000€. Une tablette Android 10" vaut 200-400€ et un module NMEA/WiFi 150-300€. Autant exploiter ce qu'on a déjà à bord avec une vraie appli d'instruments !

## Version GRATUITE — Télécommande pypilot complète

Si vous avez un pilote pypilot (Raspberry Pi) :
- Engager/désengager, modes (compas, vent, GPS, vent réel, nav)
- Cap courant + cap cible, angle de barre
- Données IMU : tangage, roulis, gîte, taux de rotation
- Réglage gains PID complet, calibration compas et barre
- Paramètres virement de bord, profils pilote
- Stats servomoteur : ampères-heures, tension, températures, durée
- Connexion directe hotspot Raspberry Pi — aucun routeur nécessaire

⚠️ Version gratuite : données pypilot uniquement, pas d'instruments NMEA externes.

## Version PRO — Centrale de navigation (8,99€ lancement / 12,99€ régulier)

**Fonctionne AVEC ou SANS pypilot.**
Il vous suffit d'un module NMEA/WiFi et d'une tablette Android.

### ⊞ Dashboard
6 panneaux configurables par glisser-déposer : vent, navigation, autopilot, profondeur (code couleur), pression avec tendance 3h, moteur RPM.

### 🌬 Wind
Rosé de vent dynamique + graphique historique 5 minutes. AWA, AWS, TWA, TWS.

### 🔧 Instruments moteur
- RPM avec seuils configurables
- Température refroidissement, pression/temp huile
- Tension/courant batterie, tension alternateur
- Heures moteur, débit carburant, température échappement
- Rapport boîte (AV/N/AR), huile transmission
- **Jauges de niveaux :** carburant bâbord/tribord, eau douce, eaux grises, eaux noires
- Graphiques personnalisés (tout paramètre vs RPM ou temps)

### ◎ Navigation
Rose des caps, SOG, COG, STW, lat/lon, navigation waypoint (BTW, DTW, XTE bâbord/tribord).

### 🔔 Alarmes sur toutes les données NMEA
Navigation : profondeur, vitesse, cap, pression, vent apparent et réel
Moteur : RPM, températures, pressions, tensions, niveaux carburant
Autopilot : angle de barre, tension servomoteur, température contrôleur

Déclenchement : alarme sonore + vibration + bannière écran.

## Configuration réseau

**Sans pypilot :**
```
Module NMEA (hotspot WiFi) ──── Tablette Android (PyNav)
```

**Avec pypilot :**
```
Raspberry Pi ──WiFi──┐
                      ├── Mini routeur ──── Tablette
Module NMEA ──WiFi──┘
```
Ou module NMEA en mode Access Point avec Raspberry Pi en client.

**Modules compatibles :** Yacht Devices YDWG-02/YDWN-02, Quark-elec QK-A034, Digital Yacht WLN10, Hat Labs SH-wg, Actisense W2K-1, tout module NMEA 0183/2000 TCP/UDP WiFi.

🔒 100% local — aucune donnée transmise à des serveurs. Pas de pub, pas de tracking.
💡 Fonctionne aussi sur tablettes plus petites que 10" (affichage adapté).

📥 Google Play Store : [LIEN]
iOS App Store : Bientôt

N'hésitez pas pour les questions de config ou compatibilité !
Colin — colin.larrue.pro@gmail.com

---
---

# 📱 POST 5 : Facebook / LinkedIn (FR + EN)

**🇫🇷 Français :**

🚢 **PyNav est disponible sur Android !**

Transformez votre tablette en centrale de navigation NMEA professionnelle, ou contrôlez votre pilote pypilot depuis votre smartphone.

✅ **Gratuit** : Télécommande pypilot complète (modes, gains, calibration, stats servo)
💎 **PRO 8,99€** (lancement) : Instruments NMEA complets sur tablette

**Onglets PRO :**
⊞ Dashboard personnalisable (vent, profondeur, pression, moteur, nav)
🌬 Wind — rosé + historique 5 min
🔧 Moteur — RPM, températures, pressions, niveaux carburant, eaux noires...
◎ Nav — cap, SOG/COG/STW, waypoint (BTW/DTW/XTE)
🔔 Alarmes sur toutes les données NMEA

**Il vous faut juste :** module NMEA/WiFi + tablette Android
**Fonctionne sans pypilot !**

🔒 100% local — aucune donnée transmise
⚡ Achat unique — mises à jour à vie

👉 [Lien Play Store]

#sailing #navigation #NMEA #pypilot #marine #voile #bateau #instruments

---

**🇬🇧 English:**

🚢 **PyNav is now on Android!**

Turn your tablet into a professional NMEA navigation center — or control your pypilot autopilot.

✅ **Free**: Full pypilot remote (modes, gains, calibration, servo stats)
💎 **PRO €8.99** (launch): Complete NMEA instruments on tablet

**PRO tabs:**
⊞ Customizable dashboard (wind, depth, pressure, engine, nav)
🌬 Wind — rose + 5-min history graph
🔧 Engine — RPM, temps, pressures, fuel/water/black water tank levels...
◎ Nav — heading, SOG/COG/STW, waypoint (BTW/DTW/XTE)
🔔 Alarms on all NMEA data

**All you need:** NMEA/WiFi module + Android tablet
**Works without pypilot!**

🔒 100% local — no data sent to external servers
⚡ One-time purchase — lifetime updates

👉 [Play Store link]

#sailing #navigation #NMEA #pypilot #marine #boating #marineelectronics
