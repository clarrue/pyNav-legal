# PyNav - Google Play Store Description (ENGLISH)

---

## TITLE (50 characters max)
PyNav - Marine NMEA Display & Pypilot Remote

---

## SHORT DESCRIPTION (80 characters max)
NMEA WiFi instruments on tablet + free pypilot remote control

---

## FULL DESCRIPTION

🧭 **NMEA NAVIGATION CENTER + PYPILOT REMOTE CONTROL**

PyNav is designed for two types of navigators:

🔹 **Have a pypilot autopilot?** Control it from your smartphone AND display all your NMEA instruments on your tablet.
🔹 **No pypilot?** Use PyNav as a standalone professional NMEA navigation center on your tablet.

---

⚓ **FREE VERSION — Autopilot tab + Settings**

Full access to pypilot autopilot control:

• Engage / disengage autopilot
• Mode selection: compass, wind, GPS, true wind, nav
• Current heading display, target heading input
• Rudder angle indicator
• IMU data: pitch, roll, heel, rate of turn
• Full PID gain adjustment (P, I, D, DD, PR, FF, WG, Deadzone)
• IMU compass calibration and rudder calibration
• Tack parameters configuration
• Pilot profile selection (basic, wind, gps, simple, rate, absolute)
• Servo stats: amp-hours, voltage, temperatures, runtime
• Direct WiFi connection to Raspberry Pi pypilot hotspot (no router needed)

⚠️ The free version gives access to pypilot data only. It does not include external NMEA instrument display.

**Device:** Android 6.0+ smartphone or tablet
**Network:** Direct WiFi connection to Raspberry Pi pypilot hotspot

---

💎 **PRO VERSION — Complete navigation center**

🎉 **Launch price: €8.99** (first 3 months) → Regular price: **€12.99**
✅ One-time lifetime purchase — No subscription

**Works WITH or WITHOUT pypilot.**
All you need is a NMEA/WiFi module and an Android tablet.

💡 Optimized for 10"+ tablets — also works on smaller tablets with adapted display.

---

### ⊞ Dashboard — Unified customizable view

6 configurable panels, drag-and-drop reordering (long press 400ms):

**Wind panel:** dynamic wind rose or raw data grid
**Navigation panel:** SOG, COG and GPS data
**Autopilot panel:** engage/disengage, target heading, rudder indicator, IMU
**Depth panel:** value with color coding (green → yellow < 10m → red < 3m)
**Pressure panel:** hPa value, 3h trend, history graph
**Engine panel:** RPM with color coding (nominal / warning / danger)

Resizable panels via separators, 1 or 2-column layout.

---

### 🌬 Wind — Apparent and true wind

• Dynamic wind rose with color fill
• 5-minute sliding history graph
• AWA, AWS, TWA, TWS real-time values

---

### 🔧 Instrum. — Complete engine dashboard

**Engine data displayed:**
• RPM with progress bar and configurable thresholds
• Coolant temperature
• Oil pressure and temperature
• Battery voltage and current / alternator voltage
• Engine hours, fuel flow, engine load
• Exhaust and sea water temperature
• Gear ratio (Forward / Neutral / Reverse)
• Transmission oil pressure and temperature

**Level gauges:**
• Port and starboard fuel tanks
• Fresh water
• Grey water and black water

**Custom graphs:** Y-axis = any engine parameter, X-axis = RPM or time

---

### ◎ Nav — GPS and waypoint navigation

• Large-format heading rose with true heading
• Magnetic heading, SOG, COG, STW
• Latitude / Longitude (DD°MM'SS format)
• Waypoint navigation: bearing (BTW), distance (DTW), cross-track error (XTE port/starboard)
• Waypoint arrival indicator

---

### 🔔 Configurable alarms on all NMEA data

**Navigation:** depth, speed (STW/SOG), heading, pressure, apparent and true wind (AWS, AWA, TWS, TWA)
**Engine:** RPM, temperatures, oil pressures, battery/alternator voltage, fuel levels
**Autopilot:** rudder angle, servo voltage, controller temperature

Each alarm: custom name, condition (above / below), threshold, individual on/off.
Trigger: audio alarm + vibration + on-screen banner.

---

🔧 **TECHNICAL REQUIREMENTS**

### FREE Version
• Android 6.0+
• Functional pypilot installation (Raspberry Pi + motor + sensors)
• Direct WiFi connection to pypilot hotspot — no router needed

### PRO Version
**REQUIRED hardware:**
• NMEA/WiFi module (e.g.: Yacht Devices YDWG-02, Quark-elec QK-A034, Digital Yacht WLN10, Hat Labs SH-wg, Actisense W2K-1, or any TCP/UDP WiFi module)
• Android 6.0+

**OPTIONAL hardware:**
• Pypilot (Raspberry Pi) — only for autopilot control

**Network without pypilot:**
```
NMEA Module (WiFi hotspot) ──── PyNav Tablet
```

**Network with pypilot:**
```
Pypilot RPi ──WiFi──┐
                     ├── Central WiFi Router ── Tablet
NMEA Module ──WiFi──┘
```
Or: NMEA module in Access Point mode + Pypilot RPi in client mode.

**Supported protocols:**
• NMEA 0183 over WiFi/TCP
• NMEA 2000 Raw over WiFi/TCP
• Pypilot via TCP (port 23322)

---

🔗 **COMPATIBLE NMEA/WIFI MODULES**

• Yacht Devices YDWG-02 (NMEA 2000)
• Yacht Devices YDWN-02 (NMEA 0183)
• Quark-elec QK-A034
• Digital Yacht WLN10
• Hat Labs SH-wg
• Actisense W2K-1
• Any module broadcasting NMEA 0183 or NMEA 2000 Raw via TCP/UDP over WiFi

---

⚙️ **SETTINGS**

• Display theme: Light / Dark / Night
• Units: depth (m / ft / fathoms), speed (knots / km/h / mph), pressure (bar / psi), temperatures (°C)
• Configurable data expiry (warning and hide delays)
• Dashboard panel visibility customization
• Configurable engine thresholds (max, warning, danger)
• Unlimited custom engine graphs

---

⚠️ **SAFETY WARNING**

PyNav is a navigation interface. It does not replace regulatory equipment.
• The skipper remains SOLELY RESPONSIBLE for navigation
• Permanent watch at sea is MANDATORY
• Pypilot is a DIY open-source project provided "as-is"
• Use at your own risk

---

🔒 **PRIVACY**

• No navigation data transmitted to external servers
• Works 100% locally on your onboard network
• No ads, no tracking

---

📜 **LEGAL**

• Publisher: CL Consulting SASU — SIRET: 94261399300016
• 24 rue Jean Paul Pandolfi, 20110 Propriano, France
• GDPR compliant

**Pypilot** is an independent open-source project (Sean D'Epagnier, GPLv3). PyNav is not affiliated with the pypilot project.

---

🚀 **DOWNLOAD PYNAV**

🎉 **LAUNCH PRICE: €8.99** (first 3 months)
💎 **REGULAR PRICE: €12.99** — One-time purchase, lifetime, free updates

---

**Keywords:** NMEA display, marine instruments, navigation center, boat instruments dashboard, NMEA WiFi, marine electronics, pypilot, autopilot, sailing, boat, marine navigation, WiFi gateway, Yacht Devices, speed, heading, depth, wind, pressure, engine RPM, fuel gauge, compass, speedometer, anemometer, depth sounder, marine dashboard, instrument panel, engine monitor, tank level

**Category:** Maps & Navigation
**Rating:** Everyone — No ads — In-app purchases (PRO €8.99)
