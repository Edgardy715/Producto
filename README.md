# Proyecto de Implementación Empresarial - Redes 🚀

**Instituto Tecnológico de Las Américas (ITLA)** **Materia:** Conmutación y Enrutamiento (TI-203)  
**Profesor:** Onel Luis Pelegrino  

---

## 📌 Descripción del Proyecto
Este repositorio contiene la documentación, configuraciones y scripts del **Proyecto de implementación de Empresarial**. El objetivo principal es crear una red confiable, segura y escalable para una mediana empresa. 

La infraestructura está diseñada para soportar segmentación por departamentos (VLANs), alta disponibilidad en el gateway (HSRP), redundancia de enlaces (EtherChannel, STP), enrutamiento interior con OSPFv2 (soportando crecimiento multiarea) y políticas de seguridad estrictas basadas en ACLs.

## 🏗️ Entorno de Trabajo
* **Simulador:** Implementación en PNETLab.
* **Automatización y Testing:** Scripts en Python / Bash (Ver directorio `scripts/`).

## 📁 Estructura del Repositorio
Para mantener el proyecto modular y organizado, utilizamos la siguiente estructura:

* 📂 **`docs/`**: Documentación oficial, tablas de direccionamiento (VLSM/IPv6) y diagramas de topología.
* 📂 **`topologia/`**: Archivos `.unl` exportados de PNETLab para facilitar la colaboración.
* 📂 **`configs/`**: 
  * `base/`: Plantillas de configuración inicial (seguridad, accesos, contraseñas).
  * `routers/` & `switches/`: Configuraciones específicas por nodo.
* 📂 **`scripts/`**: Herramientas para validación de red y pruebas automatizadas.

## ✅ Criterios de Aceptación Generales
El proyecto se considerará exitoso cuando cumpla con los siguientes puntos:
1. Conectividad entre VLANs según política definida.
2. Redundancia de gateway funcional (HSRP) con failover probado.
3. Convergencia de OSPF y propagación de rutas estáticas predeterminada.
4. Accesos restringidos por ACLs según políticas de seguridad diseñada por el equipo.

## 🗓️ Fases de Desarrollo (Sprints)
El despliegue está dividido en tres fases principales:

* **Sprint 1 (Semana 1) — Diseño y plan básico:** Topología lógica/física, direccionamiento IPv4/IPv6 y diseño de VLANs.
* **Sprint 2 (Semana 2) — Implementación L2/L3 y alta disponibilidad:** Configuración de VTP, STP, EtherChannel y HSRP.
* **Sprint 3 (Semana 3) — Enrutamiento, seguridad, pruebas y documentación final:** Despliegue de OSPFv2, ACLs y ejecución de casos de prueba.

## 👥 Equipo de Trabajo
* **Edgardy** - *[Por definir...]*
* **Michael Robles** - *[Por definir...]*
* **Josue Santana** - *[Por definir...]*
* **Sael Regalado Gregorio** - *[Por definir...]*

---
*Documentación mantenida por el equipo de TI-203. Prohibida la copia para otros periodos académicos.*
