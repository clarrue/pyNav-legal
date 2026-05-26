# PyNav - Description Google Play Store (FRANÇAIS)

---

## TITRE (50 caractères max)
PyNav - Marine NMEA Display & Pypilot Remote

---

## DESCRIPTION COURTE (80 caractères max)
Instruments NMEA WiFi sur tablette + télécommande pypilot gratuite

---

## DESCRIPTION COMPLÈTE

🧭 **CENTRALE DE NAVIGATION NMEA + TÉLÉCOMMANDE PYPILOT**

PyNav s'adresse à deux types de navigateurs :

🔹 **Vous avez un pilote pypilot ?** Contrôlez-le depuis votre smartphone ET affichez tous vos instruments NMEA sur tablette.
🔹 **Pas de pypilot ?** Utilisez PyNav comme centrale de navigation NMEA professionnelle sur votre tablette.

---

⚓ **VERSION GRATUITE — Onglet Autopilot + Paramètres**

Accès complet au contrôle du pilote automatique pypilot :

• Engager / désengager le pilote automatique
• Sélection du mode : compas, vent, GPS, vent réel, nav
• Affichage du cap courant, saisie du cap cible
• Indicateur d'angle de barre (rudder)
• Données IMU : tangage, roulis, gîte, taux de rotation
• Réglage complet des gains PID (P, I, D, DD, PR, FF, WG, Deadzone)
• Calibration compas IMU et calibration de barre
• Paramètres de virement de bord
• Sélection de profils pilote (basic, wind, gps, simple, rate, absolute)
• Statistiques servomoteur : ampères-heures, tension, températures, durée
• Connexion WiFi directe au hotspot du Raspberry Pi pypilot (sans routeur)

⚠️ La version gratuite donne accès uniquement aux données pypilot. Elle ne comprend pas l'affichage des instruments NMEA externes.

**Appareil :** Smartphone ou tablette Android 6.0+
**Réseau :** Connexion directe au hotspot WiFi du Raspberry Pi pypilot

---

💎 **VERSION PRO — Centrale de navigation complète**

🎉 **Prix de lancement : 8,99€** (3 premiers mois) → Prix régulier : **12,99€**
✅ Achat unique à vie — Pas d'abonnement

**Fonctionne AVEC ou SANS pypilot.**
Il vous suffit d'un module NMEA/WiFi et d'une tablette Android.

💡 Optimisée pour tablette 10" ou plus — fonctionne aussi sur tablettes plus petites avec affichage adapté.

---

### ⊞ Dashboard — Vue unifiée personnalisable

6 panneaux configurables et réorganisables par glisser-déposer :

**Panneau Vent :** rosé de vent dynamique ou grille de données brutes
**Panneau Navigation :** SOG, COG et données GPS
**Panneau Autopilot :** engage/désengage, cap cible, indicateur barre, IMU
**Panneau Profondeur :** valeur avec code couleur (vert → jaune < 10 m → rouge < 3 m)
**Panneau Pression :** valeur hPa, tendance sur 3 h, graphique historique
**Panneau Moteur :** RPM avec code couleur (nominal / avertissement / danger)

Redimensionnement des panneaux par séparateurs, mise en page 1 ou 2 colonnes.

---

### 🌬 Wind — Vent apparent et réel

• Rosé de vent dynamique avec remplissage coloré
• Graphique historique glissant sur 5 minutes
• AWA, AWS, TWA, TWS en temps réel

---

### 🔧 Instrum. — Tableau de bord moteur complet

**Données moteur affichées :**
• RPM avec barre de progression et seuils configurables
• Température liquide de refroidissement
• Pression et température d'huile
• Tension et courant batterie / alternateur
• Heures moteur, débit carburant, charge moteur
• Température échappement et eau de mer
• Rapport de transmission (Avant / Neutre / Arrière)
• Pression et température huile transmission

**Jauges de niveaux :**
• Carburant bâbord et tribord
• Eau douce
• Eaux grises et eaux noires

**Graphiques personnalisés :** axe Y = tout paramètre moteur, axe X = RPM ou temps

---

### ◎ Nav — Navigation GPS et waypoint

• Rose des caps avec cap vrai grand format
• Cap magnétique, SOG, COG, STW
• Latitude / Longitude (format DD°MM'SS)
• Navigation waypoint : relèvement (BTW), distance (DTW), écart de route (XTE bâbord/tribord)
• Indicateur d'arrivée au waypoint

---

### 🔔 Alarmes configurables sur toutes les données NMEA

**Navigation :** profondeur, vitesse (STW/SOG), cap, pression, vent apparent et réel (AWS, AWA, TWS, TWA)
**Moteur :** RPM, températures, pressions d'huile, tensions batterie/alternateur, niveaux carburant
**Autopilot :** angle de barre, tension servomoteur, température contrôleur

Chaque alarme : nom personnalisé, condition (au-dessus / en-dessous), seuil, activation individuelle.
Déclenchement : alarme sonore + vibration + bannière écran.

---

🔧 **PRÉREQUIS TECHNIQUES**

### Version GRATUITE
• Android 6.0+
• Installation pypilot fonctionnelle (Raspberry Pi + moteur + capteurs)
• Connexion WiFi directe au hotspot pypilot — aucun routeur nécessaire

### Version PRO
**Matériel OBLIGATOIRE :**
• Module NMEA/WiFi (ex : Yacht Devices YDWG-02, Quark-elec QK-A034, Digital Yacht WLN10, Hat Labs SH-wg, Actisense W2K-1, ou tout module TCP/UDP WiFi)
• Android 6.0+

**Matériel OPTIONNEL :**
• Pypilot (Raspberry Pi) — uniquement pour le contrôle autopilot

**Réseau sans pypilot :**
```
Module NMEA (hotspot WiFi) ──── Tablette PyNav
```

**Réseau avec pypilot :**
```
Pypilot RPi ──WiFi──┐
                     ├── Routeur WiFi central ── Tablette
Module NMEA ──WiFi──┘
```
Ou : Module NMEA en mode Access Point + Pypilot RPi en mode client.

**Protocoles supportés :**
• NMEA 0183 sur WiFi/TCP
• NMEA 2000 Raw sur WiFi/TCP
• Pypilot via TCP (port 23322)

---

🔗 **MODULES NMEA/WIFI COMPATIBLES**

• Yacht Devices YDWG-02 (NMEA 2000)
• Yacht Devices YDWN-02 (NMEA 0183)
• Quark-elec QK-A034
• Digital Yacht WLN10
• Hat Labs SH-wg
• Actisense W2K-1
• Tout module diffusant NMEA 0183 ou NMEA 2000 Raw via TCP/UDP sur WiFi

---

⚙️ **PARAMÈTRES**

• Thème d'affichage : Clair / Sombre / Nuit
• Unités : profondeur (m / ft / brasses), vitesse (nœuds / km/h / mph), pression (bar / psi), températures (°C)
• Péremption des données configurable (avertissement et masquage)
• Visibilité des panneaux Dashboard personnalisable
• Seuils moteur configurables (max, avertissement, danger)
• Graphiques moteur personnalisés (nombre illimité)

---

⚠️ **AVERTISSEMENT DE SÉCURITÉ**

PyNav est une interface de navigation. Elle ne remplace pas les équipements réglementaires.
• Le skipper reste SEUL RESPONSABLE de la navigation
• La veille permanente en mer est OBLIGATOIRE
• Pypilot est un projet open-source DIY fourni "en l'état"
• Utilisation à vos risques et périls

---

🔒 **CONFIDENTIALITÉ**

• Aucune donnée de navigation transmise à des serveurs externes
• Fonctionne 100% en local sur votre réseau de bord
• Pas de publicité, pas de tracking

---

📜 **MENTIONS LÉGALES**

• Éditeur : CL Consulting SASU — SIRET : 94261399300016
• 24 rue Jean Paul Pandolfi, 20110 Propriano, France
• Conforme RGPD

**Pypilot** est un projet open-source indépendant (Sean D'Epagnier, GPLv3). PyNav n'est pas affilié au projet pypilot.

---

🚀 **TÉLÉCHARGEZ PYNAV**

🎉 **PRIX DE LANCEMENT : 8,99€** (3 premiers mois)
💎 **PRIX RÉGULIER : 12,99€** — Achat unique, à vie, mises à jour gratuites

---

**Mots-clés :** NMEA display, instruments de navigation, centrale de navigation, tableau de bord bord, affichage NMEA, instruments bord, pypilot, pilote automatique, autopilot, voile, bateau, marine, navigation maritime, WiFi NMEA, gateway NMEA, Yacht Devices, vitesse, cap, profondeur, vent, pression, RPM moteur, jauge carburant, compas, speedomètre, anémomètre, profondimètre, dashboard marin, instrument panel

**Catégorie :** Cartes et navigation
**Classification :** Tout public — Pas de publicité — Achats intégrés (PRO 8,99€)
