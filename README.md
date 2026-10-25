<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Gautham Seetharaman — embedded systems, firmware, control, IoT" src="assets/header-dark.svg" width="100%">
</picture>

<br>

I'm an Electronics & Communication student who likes building the whole thing:
the firmware on the microcontroller, the circuit it drives, and the dashboard
on the other end of the serial cable. Most of my work is in embedded C on
STM32 and ESP32, closed-loop control, and small Linux boxes that tie sensors
together.

- Chair, **IEEE Signal Processing Society** Student Branch Chapter, RIT Bengaluru
- Embedded systems intern at **MicroLOGIX Embedded Controls** (Aug – Sep 2025)
- Looking for **embedded / embedded Linux internships**

## Tech

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C">
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white" alt="MicroPython">
      <img src="https://img.shields.io/badge/Verilog-6E4C13?style=flat-square" alt="Verilog">
    </td>
  </tr>
  <tr>
    <td><b>Hardware</b></td>
    <td>
      <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32">
      <img src="https://img.shields.io/badge/ESP32%20%2F%20ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32 / ESP8266">
      <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
      <img src="https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
    </td>
  </tr>
  <tr>
    <td><b>Interfaces</b></td>
    <td>
      <img src="https://img.shields.io/badge/UART%20%C2%B7%20SPI%20%C2%B7%20I%C2%B2C%20%C2%B7%201--Wire-30363D?style=flat-square" alt="UART, SPI, I2C, 1-Wire">
      <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
      <img src="https://img.shields.io/badge/Wi--Fi%20%C2%B7%20SMTP-30363D?style=flat-square" alt="Wi-Fi, SMTP">
    </td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32CubeIDE">
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
      <img src="https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PyQt5">
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma">
    </td>
  </tr>
</table>

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Gautham-Dev007/pid-testbench">PID Temperature Testbench</a></h3>
      Three controllers on one heated block, compared on the same hardware:
      fixed-gain PID, Ziegler–Nichols gains from a relay autotune, and
      gain-scheduled adaptive PID. PT100 over SPI, OLED, live PyQt5 dashboard.
      <br><br>
      <code>STM32G070RB</code> <code>HAL</code> <code>MAX31865</code> <code>PyQt5</code>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Gautham-Dev007/IoT_Pi32">IoT_Pi32</a></h3>
      ESP32-S3 and ESP8266 sensor nodes reporting to a Raspberry Pi hub over
      MQTT. Keeps every reading through Wi-Fi drops and power cuts, learns
      local rain and temperature trends, OTA updates, e-ink display and an
      installable web app.
      <br><br>
      <code>ESP32-S3</code> <code>Raspberry Pi 4</code> <code>MQTT</code> <code>Python</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Gautham-Dev007/PID-AutoTuning">PID-AutoTuning</a></h3>
      The Arduino version that started it: DS18B20 sensing, TRIAC heater drive
      through a zero-cross opto, self-tuning PI with Ziegler–Nichols, and a
      Python GUI with over-temperature alarms and data logging.
      <br><br>
      <code>Arduino</code> <code>DS18B20</code> <code>Matplotlib</code>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Gautham-Dev007/Internship">Internship work</a></h3>
      From MicroLOGIX: SMTP e-mail alerts from an STM32 over Wi-Fi, USB-camera
      face recognition with cloud upload, a camera-based visual pointer, and a
      Figma UI for an industrial control panel.
      <br><br>
      <code>STM32</code> <code>Embedded C</code> <code>OpenCV</code> <code>Figma</code>
    </td>
  </tr>
</table>

Also built: an ESP32 Wi-Fi mesh for environmental monitoring (shown at
Microsoft), and a helmet-detection system with an STM32 and YOLOv8n.

## Contact

<a href="mailto:gauthamseetharaman@outlook.com"><img src="https://img.shields.io/badge/Email-gauthamseetharaman%40outlook.com-0078D4?style=flat-square&logo=minutemailer&logoColor=white" alt="Email"></a>
