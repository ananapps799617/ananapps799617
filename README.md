<!-- AnAnApps · Official Profile README · Propuesta A Aurora Violeta -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0A14,50:7C3AED,100:06B6D4&height=230&section=header&text=AnAnApps&fontSize=72&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=ENGINEERING%20DIGITAL%20EXPERIENCES&descAlignY=58&descSize=15" width="100%" alt="AnAnApps"/>

<a href="https://github.com/ananapps799617">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1100&color=06B6D4&center=true&vCenter=true&width=720&lines=%3E+Estudio+independiente+de+software+%E2%9A%A1;%3E+Android+%7C+Multiplataforma+%7C+Web+PWA+%7C+Windows;%3E+De+la+idea+a+producci%C3%B3n+en+fases+controladas;%3E+Construido+con+intenci%C3%B3n.+%F0%9F%9A%80" alt="Typing"/>
</a>

<p>
  <img src="https://img.shields.io/badge/SISTEMA-EN_L%C3%8DNEA-06B6D4?style=for-the-badge&labelColor=0A0A14" alt="En línea"/>
  <img src="https://img.shields.io/badge/PROYECTOS_ACTIVOS-5-7C3AED?style=for-the-badge&labelColor=0A0A14" alt="Proyectos"/>
  <img src="https://img.shields.io/badge/OPEN_SOURCE-1-F472B6?style=for-the-badge&labelColor=0A0A14" alt="Open Source"/>
  <img src="https://komarev.com/ghpvc/?username=ananapps799617&label=VISITAS&color=7C3AED&style=for-the-badge" alt="Visitas"/>
</p>

<p>
  <a href="#-quiénes-somos"><b>Quiénes somos</b></a> •
  <a href="#-mapa-de-fases"><b>Mapa de fases</b></a> •
  <a href="#-proyectos"><b>Proyectos</b></a> •
  <a href="#-herramientas"><b>Herramientas</b></a> •
  <a href="#-actividad"><b>Actividad</b></a> •
  <a href="#-contacto"><b>Contacto</b></a>
</p>

</div>

---

## 🛰️ Quiénes somos

**AnAnApps** es un estudio independiente de desarrollo de software con base en Zipaquirá, Colombia 🇨🇴. Creamos productos digitales para **Android nativo, multiplataforma (KMP), Web PWA y Windows**.

Cada producto avanza por un ciclo de fases controladas: **Incubación → Testing → Producción**, con revisión de calidad en cada paso.

<details>
<summary><b>⚙️ Nuestra forma de trabajar</b></summary>
<br/>

| Principio | En la práctica |
|---|---|
| 🎯 **Propósito** | Resolver problemas reales y concretos |
| 🧱 **Ingeniería** | Clean Architecture, fuente única de verdad (SSOT), tipado estricto |
| 🎨 **Experiencia** | Interfaces claras, consistentes y pensadas para móvil |
| ✅ **Calidad** | Cero datos simulados: cada pantalla conectada a funcionalidad real |
| 🔐 **Seguridad** | Cero secretos en el código, reglas Zero-Trust en la nube |

</details>

---

## 🗺️ Mapa de fases

```mermaid
flowchart LR
    I["🥚 INCUBACIÓN"] --> T["🧪 TESTING"] --> P["🚀 PRODUCCIÓN"]
    I -.- FF["💳 Finanzas Familiares"]
    I -.- AV["📦 Alacena Virtual"]
    T -.- KM["🚗 KiloMeta"]
    T -.- AS["🎓 AnAnStudy"]
    T -.- AM["🎵 AnAnMusic"]
    OS["🔓 OPEN SOURCE"] -.- CO["🏗️ Control de Obras"]
    style I fill:#FACC15,color:#000,stroke:#FACC15
    style T fill:#22D3EE,color:#000,stroke:#22D3EE
    style P fill:#4ADE80,color:#000,stroke:#4ADE80
    style OS fill:#F472B6,color:#000,stroke:#F472B6
```

| Proyecto | Fase | Plataforma | Repositorio |
|---|---|---|---|
| 🚗 **KiloMeta** | ![](https://img.shields.io/badge/TESTING-22D3EE?style=flat-square) | Android nativo | 🔒 Privado |
| 🎓 **AnAnStudy** | ![](https://img.shields.io/badge/TESTING-22D3EE?style=flat-square) | Web PWA | 🔒 Privado |
| 🎵 **AnAnMusic** | ![](https://img.shields.io/badge/TESTING-22D3EE?style=flat-square) | Android nativo | 🔒 Privado |
| 💳 **Finanzas Familiares** | ![](https://img.shields.io/badge/INCUBACI%C3%93N-FACC15?style=flat-square) | Android + Windows | ⏳ Próximamente |
| 📦 **Alacena Virtual** | ![](https://img.shields.io/badge/INCUBACI%C3%93N-FACC15?style=flat-square) | Android nativo | 🌐 [Público](https://github.com/ananapps799617/alacena-virtual-android) |
| 🏗️ **Control de Obras** | ![](https://img.shields.io/badge/OPEN_SOURCE-F472B6?style=flat-square) | Web PWA | 🌐 [Público · MIT](https://github.com/ananapps799617/control-de-obras) |

---

## 🧭 Proyectos

> 👇 Haz clic en cada proyecto para ver su ficha técnica.

<details>
<summary><b>🚗 KiloMeta</b> · Gestión operativa y financiera para conductores</summary>
<br/>

![](https://img.shields.io/badge/FASE-TESTING-22D3EE?style=flat-square&labelColor=0A0A14) ![](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![](https://img.shields.io/badge/Kotlin_2.x-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

Aplicación nativa para socios conductores: turnos, recorridos y finanzas en un solo lugar.

- **Stack:** Jetpack Compose · Clean Architecture · Hilt · Room (SSOT) · OSMDroid · Firestore · OTA In-App
- **Doble bolsillo:** balance separado por plataforma (Uber, DiDi, inDrive) en pesos colombianos
- **Telemetría:** odómetro inteligente, turnos y control real de combustible
- **Resiliencia:** sincronización bidireccional con protección anti-registros fantasma

</details>

<details>
<summary><b>🎓 AnAnStudy</b> · Aprendizaje acelerado con IA</summary>
<br/>

![](https://img.shields.io/badge/FASE-TESTING-22D3EE?style=flat-square&labelColor=0A0A14) ![](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white) ![](https://img.shields.io/badge/React_+_TS-3178C6?style=flat-square&logo=typescript&logoColor=white)

Aplicación web instalable para estudiar mejor y recordar más.

- **Stack:** React 18 · TypeScript · Vite · Groq AI · Firestore · Discord Webhooks
- **Repetición espaciada:** algoritmo SM-2 para memoria a largo plazo
- **Tutor IA:** generación de flashcards y explicaciones contextuales
- **Offline:** funciona sin conexión e instalable en cualquier dispositivo

</details>

<details>
<summary><b>🎵 AnAnMusic</b> · Música en Android</summary>
<br/>

![](https://img.shields.io/badge/FASE-TESTING-22D3EE?style=flat-square&labelColor=0A0A14) ![](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

Aplicación musical nativa para Android, actualmente en fase de pruebas.

- **Plataforma:** Android nativo
- **Estado:** en pruebas internas · más detalles próximamente

</details>

<details>
<summary><b>💳 Finanzas Familiares</b> · Presupuesto del hogar en Android y Windows</summary>
<br/>

![](https://img.shields.io/badge/FASE-INCUBACI%C3%93N-FACC15?style=flat-square&labelColor=0A0A14) ![](https://img.shields.io/badge/KMP-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)

Un solo núcleo de código ejecutándose como `.apk` en Android y `.exe` en Windows.

- **Stack:** Kotlin Multiplatform · Compose Multiplatform · Room KMP · Material 3
- **Funciones:** ingresos, gastos, categorías y metas de ahorro

</details>

<details>
<summary><b>📦 Alacena Virtual</b> · Inventario doméstico inteligente</summary>
<br/>

![](https://img.shields.io/badge/FASE-INCUBACI%C3%93N-FACC15?style=flat-square&labelColor=0A0A14) ![](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![](https://img.shields.io/badge/Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

Organiza la despensa del hogar y evita desperdicios.

- **Stack:** Kotlin · Jetpack Compose · Room · Firebase
- **Funciones:** inventario, alertas de vencimiento y consumo

👉 [**Ver repositorio**](https://github.com/ananapps799617/alacena-virtual-android)

</details>

<details>
<summary><b>🏗️ Control de Obras</b> · Open Source · Gestión de obras y diseño 3D</summary>
<br/>

![](https://img.shields.io/badge/PAUSADO_%C2%B7_OPEN_SOURCE-F472B6?style=flat-square&labelColor=0A0A14) ![](https://img.shields.io/badge/Licencia-MIT-green?style=flat-square) ![](https://img.shields.io/badge/Three.js-black?style=flat-square&logo=three.js&logoColor=white)

Madurado en 92 órdenes de desarrollo y liberado para que cualquiera lo use, lo bifurque o lo continúe.

- **Stack:** React 18 · TypeScript 5 · Vite · Three.js · Tailwind · Firestore
- **Funciones:** presupuestos, compras, abonos, balance y diseñador 3D paramétrico con optimización de corte

👉 [**Ver repositorio**](https://github.com/ananapps799617/control-de-obras)

</details>

---

## 🧰 Herramientas

| Herramienta | Función |
|---|---|
| 📸 **Capturador de Evidencia Visual** | Capturas duales (móvil + escritorio) para auditoría de interfaz |
| ☁️ **Sync Drive API** | Publicación OTA de APKs y respaldo documental en Google Drive |
| 🛡️ **Git & GitHub Manager** | Control de versiones, ramas y despliegues |

---

## 🛠️ Arsenal tecnológico

<p align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,react,ts,vite,firebase,sqlite,tailwind,threejs,discord,git,github&theme=dark" alt="Tecnologías"/>
</p>

---

## 📈 Actividad

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ananapps799617&show_icons=true&hide_border=true&bg_color=0A0A14&title_color=7C3AED&icon_color=06B6D4&text_color=E2E8F0" width="49%" alt="Estadísticas"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ananapps799617&hide_border=true&background=0A0A14&ring=7C3AED&fire=F472B6&currStreakLabel=06B6D4&sideLabels=E2E8F0&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=94A3B8" width="49%" alt="Racha"/>
  <br/>
  <img src="https://github-profile-trophy.vercel.app/?username=ananapps799617&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=6" width="100%" alt="Trofeos"/>
  <br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ananapps799617&bg_color=0A0A14&color=06B6D4&line=7C3AED&point=F472B6&area=true&hide_border=true" width="100%" alt="Gráfico de actividad"/>
</div>

---

## 📡 Contacto

<div align="center">

**¿Tienes una idea o propuesta de colaboración?**

<a href="mailto:ananapps.soporte@gmail.com"><img src="https://img.shields.io/badge/ESCR%C3%8DBENOS-ananapps.soporte@gmail.com-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Correo"/></a>

📍 Zipaquirá, Colombia · 🧬 **Ecosistema AnAnApps v2.0**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:7C3AED,100:0A0A14&height=110&section=footer" width="100%" alt="Footer"/>

<sub><em>Construido con intención. Diseñado para evolucionar.</em></sub>

</div>
