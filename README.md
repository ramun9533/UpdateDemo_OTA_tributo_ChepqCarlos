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
