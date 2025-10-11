# 🌱 VerdeMente Bot  
## Prototipo Móvil de Agricultura Urbana Inteligente  

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-blue) ![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red) ![Arduino](https://img.shields.io/badge/Arduino_R4_WiFi-blue?logo=arduino&logoColor=white) ![IoT](https://img.shields.io/badge/IoT-Internet_of_Things-green) ![Render](https://img.shields.io/badge/Render-Cloud_Deploy-0099FF?logo=render&logoColor=white)

## 📋 Descripción del Sistema  
**VerdeMente Bot** es un robot educativo e inteligente que automatiza la recolección de variables ambientales (humedad, pH, temperatura, luz) en huertos urbanos.  
Está diseñado para promover la agricultura sostenible en comunidades, colegios y hogares, integrando hardware y software en una experiencia de aprendizaje real.  

Incluye:  
- Monitoreo autónomo de cultivos.  
- Recolección y envío de datos vía WiFi.  
- App web para visualizar recomendaciones.  
- Alertas automáticas cuando las condiciones no son óptimas.  

## 🛠 Stack Tecnológico  
**Hardware:**  
- Arduino Uno R4 WiFi  
- Sensores DHT11, humedad del suelo, pH y luz  
- Módulo motriz y batería recargable  

**Software:**  
- C++ (Arduino IDE)  
- Comunicación HTTP/MQTT  
- App web receptora (HTML + JS con Supabase REST API)  

## 🖥️ Infraestructura  
**Render (Producción):**  
- Hosting de app receptora (Frontend y API)  
- Contenedorizado con Docker  

**Supabase:**  
- PostgreSQL gestionado, políticas RLS  
- Auth y almacenamiento de datos ambientales  

**Monitoreo:**  
- Gráficas en tiempo real con dashboard Supabase  

## 🖥️ Estructura del Proyecto  
📁 VerdeMente_Bot  
├── 📂 firmware/ # Código Arduino  
│ ├── main.ino  
│ └── sensors.h  
├── 📂 web/ # Interfaz receptora  
│ ├── index.html  
│ ├── api.js  
│ └── charts.js  
└── 📂 docs/ # Documentación  

## 🔍 Características Clave  
- Prototipo autónomo de monitoreo ambiental  
- Integración WiFi y visualización en app web  
- Base de datos en la nube (Supabase)  
- Alertas y notificaciones automáticas  

## 🛡️ Seguridad Avanzada  
- Envío cifrado de datos (HTTPS + JWT temporal)  
- Políticas RLS por dispositivo  
- Claves API únicas por robot  

## 📊 Métricas de Rendimiento  
- Frecuencia de muestreo: cada 30 seg  
- Cobertura WiFi: hasta 20 m  
- Duración batería: 4 h promedio  
- Latencia: <1 s entre sensor y dashboard  

## 📝 Gestión de Versiones  
- GitFlow estructurado  
- CI/CD con Render  
- Repos separados para hardware y app  

💡 **Notas Técnicas:**  
✅ Proyecto educativo y sostenible  
✅ Integración IoT real con base de datos en la nube  
✅ Escalable a red de sensores urbanos  
✅ Visualización interactiva  

“Tecnología consciente para el futuro verde.”  

## 📬 Contacto Corporativo  
**Julián Alberto Ramírez**  
💻 Socio Fundador & Visionario Tecnológico  
<img width="222" height="29" alt="Logo" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />  
🏢 **WoMo Soluciónˢ**  

📅 **Control de Versiones**  
![Versión](https://img.shields.io/badge/Versión-3.2.0-blue) ![Última Actualización](https://img.shields.io/badge/Actualizado-Mar_2025-green)
