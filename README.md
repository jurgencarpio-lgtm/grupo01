# 🌩️ Proyecto WILLAY - Equipo 04
### Proyectos de Ingeniería 2026-1 | Universidad Peruana Cayetano Heredia

<p align="center">
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-yellow?style=for-the-badge" alt="Estado">
  <img src="https://img.shields.io/badge/Tecnología-DeepTech-blue?style=for-the-badge" alt="Tecnología">
  <img src="https://img.shields.io/badge/Enfoque-AgTech%20%7C%20Clima-green?style=for-the-badge" alt="Enfoque">
  <img src="https://img.shields.io/badge/Licencia-MIT-orange?style=for-the-badge" alt="Licencia">
</p>

<p align="center">
  <strong>Plataforma de Inteligencia Climática para la Resiliencia Agrícola en los Andes</strong>
</p>

---

## 📋 Tabla de Contenidos
- [🎯 Resumen Ejecutivo](#-resumen-ejecutivo)
- [🌍 Impacto y ODS](#-impacto-y-ods)
- [👥 Nuestro Equipo](#-nuestro-equipo)
- [🚀 Stack Tecnológico](#-stack-tecnológico)
- [📁 Estructura del Repositorio](#-estructura-del-repositorio)
- [⚙️ Guía de Instalación](#️-guía-de-instalación)
- [🤝 Cómo Contribuir](#-cómo-contribuir)
- [📬 Contacto](#-contacto)

---

## 🎯 Resumen Ejecutivo

**WILLAY** (del quechua *"Aviso/Alerta"*) es un sistema DeepTech enfocado en la inteligencia climática. Su objetivo principal es predecir eventos extremos como heladas y sequías con alta precisión y anticipación, salvaguardando los cultivos de pequeños agricultores andinos.

### 💡 Pilares de la Solución
- **Modelos de IA:** Redes neuronales BiLSTM para el análisis temporal del clima.
- **Imágenes Satelitales:** Combinación de datos de Sentinel-1 y Sentinel-2.
- **Alertas Hiperlocales:** Notificaciones precisas a nivel de parcela.
- **Soporte Offline:** Funcionalidad asegurada en zonas con conectividad limitada.

---

## 🌍 Impacto y ODS

Nuestro proyecto está directamente alineado con los Objetivos de Desarrollo Sostenible de la ONU:

| ODS PRINCIPAL | Contribución del Proyecto |
|-----|----------------------|
| **🌍 ODS 13: Acción Climática** | Herramienta de adaptación al cambio climático con base científica y tecnológica. |

| ODS SECUNDARIOS | Contribución del Proyecto |
|-----|----------------------|
| **🌾 ODS 2: Hambre Cero** | Prevención de pérdidas en cultivos fundamentales (papa, quinua, maíz). |
| **💧 ODS 6: Agua Limpia** | Gestión y optimización eficiente del riego ante posibles casos de estrés hídrico. |
| **⚙️ ODS 9: Innovación** | Desarrollo de infraestructura tecnológica inclusiva para zonas rurales. |

---

## 👥 Nuestro Equipo

| Nombre | Rol Principal | Responsabilidades Clave |
|--------|--------------|-------------------------|
| **Carpio Huaranga, Jurgen Adriano** | 🎯 Líder del equipo | Gestión del proyecto, coordinación general, toma de decisiones y seguimiento de objetivos. |
| **Mendez Pecho, Xiomara Valentina** | 🔬 Responsable de investigación | Análisis de datos climáticos, validación científica, investigación bibliográfica y métricas de impacto. |
| **Cordova Asencio, Xiomi** | 🎨 Diseñador/a | Diseño UX/UI, creación de prototipos interactivos, experiencia de usuario y accesibilidad de la plataforma. |
| **Taipe Condori, Wilder Jherson** | 📝 Encargado/a de documentación | Redacción técnica, elaboración de manuales, actas de reuniones y estructuración del repositorio. |
| **Briceño More, Yen Yosue** | 💻 Programador/a - Modelador/a | Desarrollo del código (frontend/backend), implementación de modelos de IA y arquitectura de software. |

---

## 🚀 Stack Tecnológico

### 🖥️ Entorno Web y Móvil
- **Frontend:** React + TypeScript (Vite)
- **Estilos:** Tailwind CSS + shadcn/ui
- **Offline:** Progressive Web App (PWA) para modo sin conexión

### ⚙️ Lógica y Modelado (IA)
- **Backend:** Python + FastAPI
- **Modelos:** TensorFlow / PyTorch (Redes BiLSTM)
- **Base de datos:** Firebase / Supabase

### 🛰️ Orígenes de Datos
- **Procesamiento Satelital:** Google Earth Engine API
- **Datos:** Sentinel-1, Sentinel-2 y datos meteorológicos de SENAMHI

---

## 📁 Estructura del Repositorio

```text
willay-project/
├── frontend/       # Interfaz de usuario (Web/App)
├── backend/        # APIs y modelos predictivos (FastAPI, PyTorch)
├── iot/            # Código para microcontroladores en campo (Sensores ESP32)
├── docs/           # Manuales, arquitectura y documentación del sistema
└── README.md       # Presentación general del proyecto