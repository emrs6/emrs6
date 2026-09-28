<div align="center">

# Hi, I'm Emre 👋

**Building AI-powered industrial systems**<br>
Automation · Embedded · Computer Vision

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3500&pause=1200&color=36BCF7&center=true&vCenter=true&width=560&lines=Raspberry+Pis+on+the+plant+floor;Modbus+RTU+%E2%86%92+live+dashboards+%E2%86%92+Android;Closed-loop+control%2C+shadow+mode+first;YOLOv8+%2B+OCR+on+the+edge" alt="Raspberry Pis on the plant floor · Modbus RTU → live dashboards → Android · Closed-loop control, shadow mode first · YOLOv8 + OCR on the edge" />

📍 Bursa, Türkiye &nbsp;·&nbsp; 🏭 [Etna Maden](https://www.etnamaden.com)

</div>

---

## 👋 About me

I build the software that monitors and controls our plant at **Etna Maden**, a calcite (calcium carbonate) producer in Bursa. It covers the whole chain: Raspberry Pis wired to motors and sensors on the plant floor, a real-time server in the middle, and the Android app operators carry in their pockets.

I like problems where software meets the physical world: motors, sensors, cameras, and the people who work with them.

- 🔭 **Currently:** digitising our plant end to end (edge, backend, mobile and documentation)
- 🌱 **Exploring:** 🕊️ *Güvercin*, a delay-tolerant emergency communication and coordination network for disaster areas
- 💬 **Ask me about:** Modbus RTU on a Raspberry Pi, keeping Pis running 24/7 in a factory, Jetpack Compose, YOLO + OCR

## 🏭 Featured work

<sub>🔒 = private, company-internal code. I can't share the source, but I'm happy to talk about it.</sub>

### 🍓 Plant-floor edge platform 🔒

Python services on a fleet of Raspberry Pis that read and control VFDs and soft starters over **Modbus RTU / RS-485**, track silo levels (4–20 mA) and detect conveyor jams. A central Node.js server ties them together with REST + WebSocket, SQLite history, JWT auth, push alerts, work orders and maintenance records.

Its closed-loop mode keeps the mills' motor current inside the target band by adjusting the feed conveyor's speed. It ran in log-only *shadow mode* before it was allowed to move a motor.

<sub>**Stack:** Python · asyncio · pymodbus · FastAPI · Node.js · Express · WebSocket · SQLite · systemd · pytest</sub>

### 📱 EtnaApp: plant monitoring & control for Android 🔒

A native Kotlin + Jetpack Compose rewrite of an earlier .NET MAUI app. It shows live silo levels, motor currents and drive frequencies with charts, and adds remote speed control with locking and role-based access, alarms and push notifications, work orders with photo evidence, daily and monthly reports, and quality-lab screens with a guided camera test. Backed by 1,300+ unit tests.

<sub>**Stack:** Kotlin · Jetpack Compose · Material 3 · Retrofit · OkHttp · CameraX · Firebase Cloud Messaging</sub>

### 🗺️ Plant digital twin (documentation) 🔒

A living map of the plant's IT/OT systems: devices, services, data flows, control logic, failure impact, backup and recovery. It is written from the code, verified on site and drawn with Mermaid. It also ships an AI-assistant skill that makes coding agents read the docs before they propose any change to the plant.

<sub>**Stack:** Markdown · Mermaid · HTML</sub>

### 🌐 [etnamaden.com](https://www.etnamaden.com)

The company website, designed and built by me: bilingual (TR/EN), ~60 pages, hreflang + JSON-LD SEO, a PWA manifest, a 115-frame scroll animation with a WebP image pipeline, and a hardened quote form (CSP, honeypot, rate limiting, KVKK consent).

<sub>**Stack:** HTML · CSS · JavaScript · PHP · Node.js (Sharp)</sub>

### 🚗 [TurkPlakaOkuyucu](https://github.com/emrs6/TurkPlakaOkuyucu): Turkish licence-plate reader

A custom-trained YOLOv8n detector plus Tesseract / EasyOCR, with Turkish plate-format validation. It runs on a Raspberry Pi (Picamera2, I²C LCD) or on Windows with CUDA; an early prototype opened a gate through an Arduino for whitelisted plates.

<sub>**Stack:** Python · OpenCV · Ultralytics YOLOv8 · EasyOCR · Tesseract · Raspberry Pi · Arduino</sub>

### 🚚 Delivery cost calculator 🔒

A WinUI 3 desktop app that works out the delivered cost per ton for every destination and exports Excel price lists. Small Python helpers ([EtnaFilesUpdates](https://github.com/emrs6/EtnaFilesUpdates)) fetch the current diesel price and build the spreadsheets.

<sub>**Stack:** C# · .NET · WinUI 3 · Python · pandas · BeautifulSoup</sub>

## 🧰 Tech stack

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Industrial & embedded**<br>
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![Modbus RTU](https://img.shields.io/badge/Modbus_RTU-2F4858?style=for-the-badge)
![RS-485](https://img.shields.io/badge/RS--485-2F4858?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![systemd](https://img.shields.io/badge/systemd-2F4858?style=for-the-badge)

**Apps & backend**<br>
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![WinUI 3](https://img.shields.io/badge/WinUI_3-0078D4?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-2F4858?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

**Computer vision & data**<br>
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Tools**<br>
![Git](https://img.shields.io/badge/Git-F03C2E?style=for-the-badge&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Mermaid](https://img.shields.io/badge/Mermaid-FF3670?style=for-the-badge&logo=mermaid&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

## 🛠️ How I work

- **Safety first on the plant floor.** New control logic runs in log-only shadow mode before it can move a motor. Watchdogs, UPS monitoring and backups are part of the design, not an afterthought.
- **Tested.** pytest and JS test suites on the edge platform, 1,300+ unit tests in the Android app.
- **Documented.** Devices, services and data flows are written down and verified on site.
- **AI-assisted, with guardrails.** I build with Claude Code, and the plant documentation doubles as a guardrail: the assistant has to read it before touching anything.

## 🗺️ Journey

- **2020:** joined GitHub; first hobby project, a Discord music bot
- **2023:** got into computer vision with a Turkish licence-plate reader (YOLOv8 + OCR); built the first internal tools for Etna Maden (C# / WinUI 3, Python)
- **2026:** digitising the plant end to end: Raspberry Pi edge platform, native Android app, digital-twin documentation and a new company website
- **Next:** 🕊️ *Güvercin*, delay-tolerant emergency communication for disaster areas

<details>
<summary><b>🇹🇷 Türkçe</b></summary>

<br>

Merhaba, ben Emre 👋

Bursa'da kalsit (kalsiyum karbonat) üreticisi **Etna Maden**'de tesisi izleyen ve yöneten yazılımları uçtan uca geliştiriyorum: sahadaki motor ve sensörlere bağlı Raspberry Pi'lardan gerçek zamanlı sunucuya, oradan da operatörlerin cebindeki Android uygulamasına kadar.

- 🍓 **Saha (edge):** Sürücüleri ve soft starter'ları Modbus RTU / RS-485 üzerinden okuyup kontrol eden, silo seviyelerini ve bant sıkışmalarını izleyen Python servisleri
- 🧠 **Kontrol:** Değirmen akımını hedef amper bandında tutan kapalı çevrim besleme kontrolü; motora dokunmadan önce yalnızca log tutan "gölge modda" test edildi
- 🖥️ **Sunucu:** REST + WebSocket ile canlı veri, alarmlar, raporlar, iş emirleri ve bakım kayıtları (Node.js, SQLite)
- 📱 **Mobil:** İzleme, uzaktan kontrol ve bakım için native Android uygulaması (Kotlin, Jetpack Compose)
- 🗺️ **Dijital ikiz:** Tesisin BT/OT sistemlerinin koddan çıkarılıp sahada doğrulanmış dokümantasyonu
- 🌐 **Web:** [etnamaden.com](https://www.etnamaden.com), tasarımı ve geliştirmesi bana ait
- 👁️ **Görüntü işleme:** [TurkPlakaOkuyucu](https://github.com/emrs6/TurkPlakaOkuyucu), YOLOv8 + OCR ile Türk plakalarını okuma
- 🕊️ **Sırada:** *Güvercin*, afet bölgeleri için gecikmeye dayanıklı acil durum iletişim ve koordinasyon ağı

</details>

<!--
  İletişim rozetleri: profilde göstermek için bu yorum bloğunu kaldırıp kendi bilgilerinle doldur.

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/KULLANICI-ADIN/)
  [![E-posta](https://img.shields.io/badge/E--posta-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:E-POSTA-ADRESIN)
-->
