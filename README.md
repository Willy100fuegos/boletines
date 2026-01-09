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

---

## 🚀 Cómo Publicar un Nuevo Boletín

1.  **Subir Archivo:** Sube tu nuevo archivo HTML (ej. `reporte-enero.html`) a la raíz del repositorio.
2.  **Registrar en el Hub:** Abre `index.html` y busca la sección `const boletines`.
3.  **Agregar Entrada:** Copia y pega el siguiente bloque con los datos nuevos:

```javascript
{
    titulo: "Título de tu Nuevo Reporte",
    fecha: "01 Ene 2026",
    categoria: "seguridad", // Opciones: seguridad, vial, dashboard
    descripcion: "Breve resumen de 2 líneas sobre el contenido.",
    url: "reporte-enero.html",
    icon: "fa-shield-halved", // Ícono de FontAwesome
    color: "text-emerald-500",
    badgeColor: "bg-emerald-900/30 text-emerald-400 border-emerald-800"
},
