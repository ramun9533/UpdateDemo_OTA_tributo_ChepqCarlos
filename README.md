# 🚀 Sistema de Actualización OTA para ESP32/ESP8266

![ESP OTA](https://img.shields.io/badge/ESP-OTA-blue) 
![PlatformIO](https://img.shields.io/badge/PlatformIO-Compatible-brightgreen)
![License](https://img.shields.io/badge/License-MIT-orange)

Sistema completo para actualización inalámbrica (Over-The-Air) de firmware en dispositivos ESP32 y ESP8266 mediante interfaz web.

## 📌 Características Principales
- **Compatibilidad dual**: Funciona tanto en ESP32 como ESP8266
- **Interfaz web integrada**: Sube archivos `.bin` desde tu navegador
- **Mínima configuración**: Solo requiere credenciales WiFi
- **Sistema robusto**: Manejo de errores y reinicio automático
- **Soporte mDNS**: Acceso mediante `http://<nombre>.local`

## 🛠 Hardware Requerido
- Placa ESP32 **o** ESP8266
- Conexión WiFi estable
- Al menos 1MB de espacio en memoria flash

## ⚙ Configuración
1. Edita el archivo `data.h` con tus credenciales:
   ```cpp
   const char* ssid = "TU_SSID";
   const char* password = "TU_PASSWORD";
   const char* nombre = "esp32ota"; // Nombre para mDNS

## 📸 Capturas de Interfaz

| Vista en PC | Vista en Móvil |
|-------------|----------------|
| ![Interfaz PC]([https://github.com/ChepeCarlos/ESP32-OTA-Update/raw/main/docs/pc_screenshot.png](https://github.com/ramun9533/UpdateDemo_OTA_tributo_ChepqCarlos/blob/main/Captura%20de%20pantalla_20250811_162444-1.png)) | ![Interfaz Móvil]([https://github.com/ChepeCarlos/ESP32-OTA-Update/raw/main/docs/mobile_screenshot.png](https://github.com/ramun9533/UpdateDemo_OTA_tributo_ChepqCarlos/blob/main/Screenshot_2025-08-11-16-26-11-230_com.android.chrome.jpg)) |
