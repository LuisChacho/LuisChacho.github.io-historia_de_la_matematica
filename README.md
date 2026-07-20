# 📊 Sistema de Retroalimentación Interactiva - Co-evaluación Didáctica

Este repositorio aloja la solución interactiva de recopilación, análisis y retroalimentación pedagógica para nuestro video educativo sobre **"Matemáticas Antiguas y su Aplicación Moderna"**.

## 🚀 Enlace de Despliegue Público
El proyecto se encuentra desplegado en vivo a través de **GitHub Pages**. Puedes acceder y realizar pruebas mediante el siguiente enlace:
👉 `https://<TU-USUARIO-DE-GITHUB>.github.io/<NOMBRE-REPOSITORIO>/`

---

## 🛠️ Arquitectura de Software
Para asegurar un despliegue sin errores de carga de archivos estáticos y una velocidad de respuesta óptima, el sistema fue estructurado bajo una **Arquitectura SPA (Single Page Application)** unificada:

* **Estructura semántica:** HTML5 con control de flujo dinámico por secciones.
* **Estilos & UI:** Tailwind CSS y FontAwesome integrados vía CDN, con un diseño intuitivo, limpio y adaptable (*Mobile-First*).
* **Motor analítico:** JavaScript Vanilla para el cálculo automático de promedios, renderización dinámica de testimonios e IA local para autogenerar conclusiones.
* **Biblioteca Gráfica:** Chart.js para el mapeo interactivo de fortalezas metodológicas mediante gráficos de tipo Radar.

---

## 🔒 Control de Roles y Privacidad (Acceso Restringido)
Para evitar sesgos durante la evaluación de los docentes externos, la aplicación restringe el acceso al panel analítico (Dashboard) a través de un control de seguridad integrado:

* **Modo Docente:** Visible para cualquier usuario para registrar su calificación cualitativa y cuantitativa.
* **Modo Analista (Equipo):** Requiere un código de acceso de administrador para desbloquear la visualización de gráficos, el consolidado de comentarios grupales y el descargador de datos.
  * 🔑 **Código de acceso configurado por defecto:** `admin2026`

---

## 📝 Dimensiones Evaluadas por el Instrumento
1. **Comprensión y claridad:** Escala numérica del 1 al 5.
2. **Conexión histórica-actual:** Escala numérica del 1 al 5.
3. **Atractivo técnico y audiovisual:** Escala numérica del 1 al 5.
4. **Respuestas de desarrollo cualitativo:** Tres campos textuales para sugerencias de mejora didáctica, impacto percibido y utilidad en el quehacer docente habitual.

---

## 📂 Funcionalidad de Exportación
El sistema cuenta con un botón para **exportar las valoraciones a formato CSV**, lo cual permite al equipo abrir los datos directamente en Microsoft Excel, Google Sheets o SPSS para su posterior integración en informes formales o tesis académicas.