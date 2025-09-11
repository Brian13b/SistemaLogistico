# 🚛 Sistema Logístico - Plataforma Integral

El **Sistema Logístico** es un conjunto de microservicios diseñados para la gestión completa de flotas, viajes, facturación y rastreo en tiempo real.  
Está diseñado bajo una arquitectura de **microservicios**, integrados a través de un **API Gateway**, garantizando **escalabilidad, seguridad y flexibilidad**.

---

## 🏗️ Arquitectura General
![Arquitectura](imagenes/arquitectura.png)

### Módulos principales
- **Frontend** → [SistemaLogistico-frontend](https://github.com/Brian13b/SistemaLogistico-frontend)  
- **Backend (Gestión de flotas)** → [SistemaLogistico-backend](https://github.com/Brian13b/SistemaLogistico-backend)  
- **API Gateway** → [SistemaLogistico-gateway](https://github.com/Brian13b/SistemaLogistico-gateway)  
- **Facturación electrónica** → [SistemaLogistico-facturacion](https://github.com/Brian13b/SistemaLogistico-facturacion)  
- **Tracking GPS en tiempo real** → [SistemaLogistico-tracking](https://github.com/Brian13b/SistemaLogistico-tracking)  

---

## 🔧 Tecnologías principales
- **Backend** → FastAPI (Python), PostgreSQL, JWT  
- **Frontend** → React, Redux, Leaflet, TailwindCSS 
- **Facturación** → SOAP (AFIP / ARCA Argentina)  
- **Tracking** → TCP Socket Server + FastAPI  
- **Gateway** → FastAPI + JWT   

---

## 🚀 Cómo empezar
1. Clonar los repositorios individuales (o usar el repo `SistemaLogistico-devops`).  
2. Configurar los archivos `.env` en cada módulo.  
3. Levantar los servicios con Docker Compose desde el repo de infraestructura.  

---

## 🖥️ Capturas de la Plataforma

### Inicio Sesion 
![Inicio Sesion](imagenes/IniciarSesion.jpg)

### Dashboard
![Dashboard](imagenes/dashboard.jpg)

### Gestión de Vehículos
![Gestión de Vehículos](imagenes/Conductores.jpg)

### Gestión de Conductores
![Gestión de Conductores](imagenes/vehiculos.jpg)

### Gestión de Viajes
![Gestión de Viajes](imagenes/Viajes.jpg)

### Modales de Gestión
![Modales](imagenes/ConductoresModal.jpg)
![Modales](imagenes/vehiculosModal.jpg)
![Modales](imagenes/vehiculosCargaModal.jpg)
![Modales](imagenes/vehiculosCargaDocumentosModal.jpg)

### Reportes y Análisis
![Reportes y Análisis](imagenes/Reportes.jpg)
![Reportes y Análisis](imagenes/reportes2.jpg)

### Seguimiento en Tiempo Real
![Seguimiento en Tiempo Real](imagenes/Seguimiento.jpg)

---

## 👥 Contribución
¡Toda ayuda es bienvenida!
