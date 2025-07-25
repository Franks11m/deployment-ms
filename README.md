# Microservices Deployment - Proyecto de Titulación

Este repositorio contiene la configuración de despliegue basada en contenedores **Docker** para el sistema desarrollado bajo una **arquitectura de microservicios**. El proyecto está compuesto por varios microservicios independientes y componentes de infraestructura, orquestados mediante `docker-compose`.

---

## Arquitectura del Sistema

La solución implementa los siguientes componentes principales:

- **Eureka Server:** Servicio de descubrimiento de microservicios.
- **API Gateway:** Punto de entrada único para el acceso a los servicios.
- **Customer-MS:** Microservicio para la gestión de clientes.
- **Sales-MS:** Microservicio para la gestión de ventas.


Los microservicios comunican entre sí a través de HTTP y utilizan Eureka para descubrirse dinámicamente. El API Gateway enruta las solicitudes externas a los servicios internos.

### 🔷 Diagrama de Arquitectura

>  
 <img src="Images/Diagrama-Arquitectura-ms.png" alt="drawing" width="800"/>


---



