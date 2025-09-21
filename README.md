# 🚀 Building Cloud Business Applications for SKODA  

## 📌 Descripción General del Proyecto  
Este proyecto implementa una **solución de negocio automatizada** para **SKODA** que permite **registrar, modificar y dar seguimiento a las órdenes de trabajo generadas en talleres**, integrando los distintos canales de venta y asesores en una sola plataforma digital.  

La arquitectura está basada en la **nube** y diseñada para:  
- Centralizar datos operativos.  
- Optimizar su procesamiento mediante **flujos ETL**.  
- Ofrecer acceso flexible y seguro a través de **aplicaciones low-code** y herramientas de **autoservicio analítico**.  

La solución integra tecnologías como **Azure SQL, Microsoft Fabric (Data Factory & Warehouse), Power Apps, Power Automate y Power BI**, brindando a SKODA una plataforma integral, escalable y en tiempo real que impulsa la eficiencia en la operación y la toma de decisiones basada en datos.  

---

## 🎯 Objetivos Principales  
- 🧱 Implementar una base de datos en **Azure SQL** para el registro estructurado de órdenes de trabajo.  
- ⚡ Integrar **Microsoft Power Apps** como capa de ingreso, edición y consulta de datos.  
- 🔄 Desarrollar procesos **ETL** con Fabric Data Factory y notebooks en Python.  
- 📦 Construir un **Data Warehouse en Microsoft Fabric** para consolidación y análisis.  
- 🤖 Automatizar flujos e integraciones mediante **Power Automate**.  
- 📊 Facilitar el análisis con **reportes interactivos y storytelling en Power BI**.  

---

## ✨ Resultados Clave  
- ⚙️ **Automatización de procesos**: Reducción de tiempos operativos mediante pipelines ETL y automatizaciones con Power Automate.  
- ⏱️ **Velocidad en la obtención de insights**: Reportes y tableros en Power BI que entregan información accionable más rápido.  
- 🔄 **Flexibilidad y actualización en tiempo real**: Ingreso y edición de registros desde Power Apps con persistencia en Azure SQL.  
- 🔔 **Alertas proactivas**: Notificaciones automáticas a clientes y gerentes de operaciones según indicadores definidos.  
- 🔐 **Seguridad y gobernanza**: Acceso controlado por roles en Azure, protegiendo la integridad de la información.  

---

## ☁️ Arquitectura Cloud del Proyecto  
El proyecto SKODA se estructura en capas para ofrecer una solución **completa, escalable y orientada a la gestión de órdenes de trabajo**:  

🔹 **Data Sources**: Órdenes de trabajo registradas en talleres, integradas de forma semi-automatizada.  
🔹 **Data Layer**: Información centralizada en **Azure SQL**, con almacenamiento seguro y estructurado en la nube.  
🔹 **Application Layer**: **Power Apps** como interfaz gráfica conectada con Azure SQL.  
🔹 **ETL Layer**: Pipelines y Dataflows de **Microsoft Fabric**, más Notebooks en Python para validación y notificaciones.  
🔹 **Data Warehouse Layer**: Consolidación en **Fabric Data Warehouse** para análisis avanzado.  
🔹 **Presentation Layer**: Reportes interactivos en **Power BI Service** y acceso en Excel.  
🔹 **User Access**: Roles gestionados en Azure, Power Apps y Power BI, con notificaciones automáticas para trazabilidad.  

📌 Puedes revisar el código SQL para la creación de tablas y estructuras en el siguiente enlace:  
👉 [Ver código en GitHub](https://github.com/Grupo3Pucp/ProyectoGP3)  

---

## ✅ Conclusión  
El proyecto **SKODA – Gestión de Órdenes de Servicio** evidencia cómo la integración del ecosistema Microsoft —**Power Apps, Azure SQL, Microsoft Fabric, Power Automate y Power BI**— puede convertirse en el motor de una solución empresarial robusta, escalable y centrada en el usuario.  

La arquitectura diseñada asegura que cada orden de servicio registrada en los talleres se procese de forma **estructurada, trazable y automatizada**, fortaleciendo la eficiencia operativa y la toma de decisiones estratégicas.  

Puntos destacados:  
- 📌 **Centralización**: Consolidación de órdenes de servicio, vehículos, clientes, talleres y servicios en una única fuente confiable.  
- 📌 **Automatización**: Flujos ETL con Microsoft Fabric que reducen la intervención manual y garantizan datos precisos.  
- 📌 **Comunicación**: Notificaciones automáticas que refuerzan la trazabilidad y el control operativo.  
- 📌 **Usabilidad**: Power Apps como interfaz intuitiva para registrar y actualizar órdenes en los talleres.  
- 📌 **Análisis**: Dashboards interactivos en Power BI que permiten entender indicadores clave como volumen de órdenes, servicios más frecuentes o ticket promedio.  
- 📌 **Seguridad**: Acceso gobernado con roles en Azure que protegen la integridad de la información.  

En conjunto, esta solución representa un modelo de **transformación digital** para la gestión de órdenes de servicio, alineado con los objetivos de eficiencia, crecimiento y excelencia en la experiencia de cliente que demanda la industria automotriz.  

🚗 Con este proyecto, **SKODA da un paso firme hacia un futuro más ágil, inteligente y conectado en sus talleres**.  

---

👨‍💻 **Autores:** Equipo Grupo 3 – PUCP | Diplomado en Business Analytics  
