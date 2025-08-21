# 🚛 Sistema Logístico - Plataforma Integral

El **Sistema Logístico** es un conjunto de microservicios diseñados para la gestión completa de flotas, viajes, facturación y rastreo en tiempo real.  
Cada módulo está desacoplado e integrado mediante un **API Gateway**, ofreciendo escalabilidad, seguridad y flexibilidad.

---

## 🏗️ Arquitectura General
![Arquitectura](docs/arquitectura.png)

### Módulos principales
- **Frontend** → [SistemaLogistico-frontend](https://github.com/Brian13b/SistemaLogistico-frontend)  
- **Backend (Gestión de flotas)** → [SistemaLogistico-backend](https://github.com/Brian13b/SistemaLogistico-backend)  
- **API Gateway** → [SistemaLogistico-gateway](https://github.com/Brian13b/SistemaLogistico-gateway)  
- **Facturación electrónica** → [SistemaLogistico-facturacion](https://github.com/Brian13b/SistemaLogistico-facturacion)  
- **Tracking GPS en tiempo real** → [SistemaLogistico-tracking](https://github.com/Brian13b/SistemaLogistico-tracking)  

---

## 🔧 Tecnologías principales
- **Backend / Microservicios** → FastAPI (Python), PostgreSQL, JWT  
- **Frontend** → React, Redux, Leaflet  
- **Facturación** → SOAP (AFIP / ARCA Argentina)  
- **Tracking** → TCP Socket Server + FastAPI  
- **Gateway** → FastAPI + JWT   

---

## 🚀 Cómo empezar
1. Clonar los repositorios individuales (o usar el repo `SistemaLogistico-infra`).  
2. Configurar los archivos `.env` en cada módulo.  
3. Levantar los servicios con Docker Compose desde el repo de infraestructura.  

---

## 👥 Contribución
¡Toda ayuda es bienvenida!
