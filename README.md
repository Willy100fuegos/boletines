# Pixmedia Communications Hub 📢

> **Centro de Inteligencia y Comunicaciones Corporativas.**
> *Repositorio centralizado para la distribución de boletines de seguridad, alertas viales y dashboards operativos.*

---

## 🎯 Propósito del Sistema

Este repositorio actúa como la **Sala de Prensa Digital** para la Dirección de Tecnologías y Seguridad. Su objetivo es alojar informes HTML "ricos" (con gráficos, mapas y formatos complejos) que no pueden enviarse fácilmente por correo electrónico plano, permitiendo compartir un enlace seguro y profesional con clientes y directivos.

### 📋 Contenido Actual
* **🚨 Alertas de Bloqueo:** Informes de inteligencia vial sobre manifestaciones y cierres carreteros (Ej. *Alerta Nacional 05 Dic*).
* **📊 Dashboards Operativos:** Resúmenes ejecutivos mensuales sobre incidencia delictiva y KPIs de seguridad en Veracruz.

---

## 🛠️ Estructura Técnica

El sistema está construido sobre una arquitectura **Static Web (Jamstack)** para máxima velocidad y seguridad.

| Archivo | Función |
| :--- | :--- |
| `index.html` | **Hub Principal:** Tablero que lista todos los boletines disponibles con filtros por categoría. |
| `boletin.html` | **Dashboard Veracruz:** Informe mensual de KPIs de seguridad y riesgo social. |
| `bloqueos-*.html` | **Alertas Viales:** Informes específicos sobre contingencias carreteras. |
