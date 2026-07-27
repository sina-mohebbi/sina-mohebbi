<!-- Typing header -->
<div align="center">
  <a href="https://github.com/sina-mohebbi">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=0057FF&center=true&vCenter=true&width=680&lines=ML+%2B+Embedded+Systems+Engineer;Edge+AI+%C2%B7+TinyML+%C2%B7+IoT+%C2%B7+Sensor+Fusion;M.Sc.+Electronics+%40+University+of+Bologna;Making+neural+nets+small+enough+to+run+on+a+MCU" alt="Typing SVG" />
  </a>
</div>

<!-- Connect + profile views -->
<p align="center">
  <a href="https://www.linkedin.com/in/sina-mohebbi-31bb143b9/"><img src="https://img.shields.io/badge/LinkedIn-sina--mohebbi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mohebbixsina@gmail.com"><img src="https://img.shields.io/badge/Email-mohebbixsina%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=sina-mohebbi&label=Profile%20views&color=0057ff&style=flat-square" alt="Profile views" />
</p>

# 👋 Hi, I'm Sina, an Embedded AI Engineer based in Bologna 🇮🇹

I work where **machine learning meets real hardware**. I train models on a laptop, then quantize
them and run them on microcontrollers, where every kilobyte and millisecond matters. Before moving
into embedded AI I spent three years as a control and instrumentation engineer, so I enjoy problems
that span the whole stack, from a sensor on a pump to a dashboard in the browser.

## About me

- 🎓 M.Sc. **Electronic Engineering** at the University of Bologna, focused on Edge AI, IoT, and embedded systems
- 🎓 B.Sc. **Control Engineering** at the University of Tehran
- 🤖 I build **AI that runs on microcontrollers**: TinyML, int8 quantization, and multimodal sensor fusion
- 🏭 Previously spent **3 years** as a control and instrumentation engineer across 12 water pumping and treatment plants
- 🔬 Recent work: anomaly detection on an ESP32, pump cavitation detection from sound and vibration, and a full IoT desk monitor
- 🌱 Currently digging into **RISC-V**, **PULP**, and squeezing bigger models onto smaller hardware
- 🎯 Looking for a **curricular internship** in Embedded Systems / Edge AI / IoT / Firmware
- 📫 Reach me at **mohebbixsina@gmail.com**

## 🎓 Education

- **M.Sc. Electronics for Big Data, IoT &amp; Intelligent Systems** &nbsp;![University of Bologna](https://img.shields.io/badge/University_of_Bologna-A6093D?style=flat-square&logoColor=white)
- **B.Sc. Control Engineering** &nbsp;![University of Tehran](https://img.shields.io/badge/University_of_Tehran-14367A?style=flat-square&logoColor=white)

## 🔧 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ [edgeAI-MachineSense](https://github.com/sina-mohebbi/edgeAI-MachineSense)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TFLite Micro](https://img.shields.io/badge/-TFLite%20Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/-ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

Detects when a machine starts to sound unhealthy, using a small **autoencoder** that is quantized to int8 and runs directly on an ESP32. It learns what a healthy machine sounds like and flags anything different, reaching 0.86 AUC at 49 ms per inference on the board.

</td>
<td width="50%" valign="top">

### 🔊 [edge-ai-sensor-fusion](https://github.com/sina-mohebbi/edge-ai-sensor-fusion)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Signal Processing](https://img.shields.io/badge/-Signal%20Processing-4B8BBE?style=flat-square)

Detects **cavitation in a centrifugal pump** using sensor fusion, combining a microphone and a vibration sensor in one small neural network. It is evaluated only on recordings it has never seen, so the accuracy reflects real generalization to a new pump.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ [library-desk-sense](https://github.com/sina-mohebbi/library-desk-sense)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/-ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/-FreeRTOS-4CAF50?style=flat-square&logo=freertos&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

A complete **IoT system for monitoring library desks**. An ESP32 senses occupancy, light, and noise and streams the data over HTTP/CoAP to a Python backend that stores it in InfluxDB, shows live Grafana dashboards, and pushes Telegram alerts.

</td>
<td width="50%" valign="top">

### 🧩 [jigsaw-puzzle-reconstruction-dl](https://github.com/sina-mohebbi/jigsaw-puzzle-reconstruction-dl)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)

A **visual-reasoning** model that rebuilds a 96×96 image after it is cut into 9 shuffled, partly erased tiles. It has to infer where each piece belongs and fill in the missing borders, with no position labels to guide it.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🦾 6-DOF Robotic Arm Communication &nbsp;·&nbsp; *B.Sc. Thesis*
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Modbus RTU](https://img.shields.io/badge/-Modbus%20RTU-1F4E79?style=flat-square)
![CAN](https://img.shields.io/badge/-CAN-333333?style=flat-square)
![SCADA](https://img.shields.io/badge/-SCADA-B7472A?style=flat-square)

Control and monitoring of a **6-DOF pick-and-place robotic arm** over Modbus and CAN. It ties together motor commands, sensor feedback, and remote operation through SCADA and a Bluetooth mobile app.

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

## 🔧 What I build: from sensor signal to on-device AI

<sub>Sensor signal → FFT → neural network → microcontroller → deployment</sub>
<!-- Profile banner -->
<p align="center">
  <img src="assets/banner.svg" alt="Sina Mohebbi — Edge AI · Embedded Systems · TinyML" width="100%">
</p>

## 🛠️ Tech I work with

**Languages**

![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/-MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![RISC-V](https://img.shields.io/badge/-RISC--V%20asm-283272?style=flat-square&logo=riscv&logoColor=white)

**Embedded &amp; Edge AI**

![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/-ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/-FreeRTOS-4CAF50?style=flat-square&logo=freertos&logoColor=white)
![TFLite Micro](https://img.shields.io/badge/-TFLite%20Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PULP](https://img.shields.io/badge/-PULP-283272?style=flat-square&logo=riscv&logoColor=white)

**ML / Signal**

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Protocols**

![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![CoAP](https://img.shields.io/badge/-CoAP-4B8BBE?style=flat-square&logo=coap&logoColor=white)
![HTTP](https://img.shields.io/badge/-HTTP-005571?style=flat-square&logo=curl&logoColor=white)
![Modbus](https://img.shields.io/badge/-Modbus%20RTU-1F4E79?style=flat-square)
![CAN](https://img.shields.io/badge/-CAN-333333?style=flat-square)
![I2C / SPI / UART](https://img.shields.io/badge/-I2C%20%2F%20SPI%20%2F%20UART-555555?style=flat-square)
![RS-485](https://img.shields.io/badge/-RS--485-555555?style=flat-square)
![Bluetooth](https://img.shields.io/badge/-Bluetooth-0082FC?style=flat-square&logo=bluetooth&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![InfluxDB](https://img.shields.io/badge/-InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Mosquitto](https://img.shields.io/badge/-Mosquitto-3C5280?style=flat-square&logo=eclipsemosquitto&logoColor=white)
![SCADA](https://img.shields.io/badge/-SCADA-B7472A?style=flat-square)
![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

## 📊 GitHub in numbers

<div align="center">
  <img height="165" alt="Sina's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=sina-mohebbi&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent" />
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sina-mohebbi&hide_border=true&layout=compact&langs_count=8&theme=transparent" />
</div>

<div align="center">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=sina-mohebbi&hide_border=true&theme=transparent" />
</div>

<div align="center">
  <img alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=sina-mohebbi&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6" />
</div>

<!-- Contribution activity graph -->
<div align="center">
  <img alt="Contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=sina-mohebbi&hide_border=true&area=true&bg_color=00000000&color=38bdf8&line=f472b6&point=fbbf24" width="98%" />
</div>

