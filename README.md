# 🌱 VerdeMente Bot  
## Prototipo de Monitoreo Ambiental Autónomo  

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-blue) ![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red) ![Arduino](https://img.shields.io/badge/Arduino_R4_WiFi-blue?logo=arduino&logoColor=white) ![IoT](https://img.shields.io/badge/IoT-Internet_of_Things-green) ![Render](https://img.shields.io/badge/Render-Cloud_Deploy-0099FF?logo=render&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-Auth_%26_DB-3ECF8E?logo=supabase&logoColor=white)

## 📋 Descripción del Sistema  
Robot móvil diseñado para medir parámetros de calidad del agua, humedad y temperatura en zonas de reforestación o reservas naturales.  

Incluye:
- Lectura de sensores (pH, turbidez, humedad, temperatura)  
- Envío de datos vía WiFi a base Supabase  
- Visualización de métricas en Render (web dashboard)  

## 🛠 Stack Tecnológico  
**Hardware:** Arduino UNO R4 WiFi  
**Software:** C++ (Arduino IDE) + API Flask  
**Base de Datos:** Supabase (Auth + RLS + Storage)  
**Frontend:** HTML5, CSS3, JS  

## 🖥️ Infraestructura  
**Render:**  
- Dashboard y API REST  
- Docker + HTTPS  

**Supabase:**  
- PostgreSQL gestionado, RLS, métricas  

**Monitoreo:**  
- Logs y alertas  

## 🖥️ Estructura del Proyecto  
📁 VerdeMente_Bot  
├── hardware/ (sensors.ino, motor.ino)  
├── api/ (app.py, routes/)  
├── web/ (index.html, js/)  
└── docs/  

## 🔍 Características Clave  
- Lectura IoT remota  
- Visualización de datos ambientales  
- Envío automático de registros  
- Panel responsive  

## 🛡️ Seguridad Avanzada  
- API Key cifrada  
- Auth Supabase  
- HTTPS activo  

## 📊 Métricas de Rendimiento  
- Latencia <300ms  
- 99.9% uptime  

## 📝 Gestión de Versiones  
- GitFlow + SemVer  

💡 **Notas Técnicas:**  
✅ Integración IoT  
✅ Arduino + Supabase  
✅ Render web en tiempo real  
✅ Datos ambientales históricos  

“La tecnología al servicio del planeta.”  

## 📬 Contacto Corporativo  
**Julián Alberto Ramírez**  
💻 Socio Fundador & Visionario Tecnológico  
<img width="222" height="29" alt="Logo WSˢ" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />  
🏢 **WoMo Soluciónˢ – Soluciones Tecnológicas Avanzadas**  

📅 **Control de Versiones**  
![Versión](https://img.shields.io/badge/Versión-1.0.0-blue) ![Actualizado](https://img.shields.io/badge/Actualizado-Oct_2025-green)
