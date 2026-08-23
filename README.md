<h1 align="center" style="color: #0000FF; font-weight: bold;">
  Equipo 01 - Proyectos para Ingeniería 1
</h1>
<img width="1514" height="573" alt="image" src="https://github.com/user-attachments/assets/e3dce5fb-cd23-4aee-8a96-1f958714e830" />

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
- [🎯 Descripción del Equipo y Objetivo](#-descripción-del-equipo-y-objetivo)
- [🌍 Impacto y ODS](#-impacto-y-ods)
- [👥 Equipo Multidisciplinario](#-equipo-multidisciplinario)
- [🚀 Stack Tecnológico](#-stack-tecnológico)
- [📁 Estructura del Repositorio](#-estructura-del-repositorio)

---

## 🎯 Descripción del Equipo y Objetivo

**Sobre Nosotros (Equipo 01):**  
Somos un equipo multidisciplinario de estudiantes enfocados en la creación de soluciones tecnológicas que generen un impacto real y positivo en la sociedad. Combinamos conocimientos en investigación, diseño, desarrollo de software y gestión para construir herramientas accesibles y eficientes.

**Nuestro Objetivo:**  
Desarrollar e implementar **WILLAY** (del quechua *"Aviso/Alerta"*), un sistema DeepTech de inteligencia climática diseñado para predecir eventos meteorológicos extremos, como heladas y sequías, con alta precisión. Buscamos brindar alertas tempranas hiperlocales para salvaguardar los cultivos y mejorar la resiliencia de los pequeños agricultores andinos frente al cambio climático.

---

## 🌍 Impacto y ODS

Nuestro proyecto está alineado con 3 Objetivos de Desarrollo Sostenible (ODS) principales que abarcan la innovación, la tecnología y el cuidado ambiental:

| ODS | Enfoque | Contribución del Proyecto |
|:---:|:---:|---|
| <img src="imagenes/ODS9.jpg" width="80" style="border-radius:50%"> | **Innovación y Tecnología** | Desarrollo de infraestructura tecnológica (Redes neuronales BiLSTM y análisis satelital) adaptada para zonas rurales y de baja conectividad. |
| **🌍 ODS 13: Acción por el Clima** | **Cuidado Ambiental** | Creación de una herramienta directa de adaptación y mitigación ante los efectos del cambio climático en la agricultura de los Andes. |
| **🌱 ODS 15: Vida de Ecosistemas Terrestres** | **Cuidado Ambiental** | Promoción de prácticas agrícolas sostenibles al optimizar recursos y prevenir la degradación de las tierras de cultivo por fenómenos extremos. |

---

## 👥 Equipo Multidisciplinario

| Foto | Nombre | Rol Principal | Responsabilidades Clave |
|:---:|--------|--------------|-------------------------|
| <img src="./imagenes/jurgen.jpg" width="70" alt="Jurgen Carpio"> | **Carpio Huaranga, Jurgen Adriano** | 🎯 Líder del equipo | Gestión del proyecto, coordinación general, toma de decisiones y seguimiento de objetivos. |
| <img src="./imagenes/xio.jpg" width="70" alt="Xiomara Mendez"> | **Mendez Pecho, Xiomara Valentina** | 🔬 Responsable de investigación | Análisis de datos climáticos, validación científica, investigación bibliográfica y métricas de impacto. |
| <img src="./imagenes/xiomi.jpg" width="70" alt="Xiomi Cordova"> | **Cordova Asencio, Xiomi** | 🎨 Diseñador/a | Diseño UX/UI, creación de prototipos interactivos, experiencia de usuario y accesibilidad de la plataforma. |
| <img src="./imagenes/jherson.jpg" width="70" alt="Jherson Taipe"> | **Taipe Condori, Wilder Jherson** | 📝 Encargado/a de documentación | Redacción técnica, elaboración de manuales, actas de reuniones y estructuración del repositorio. |
| <img src="./imagenes/yen.jpg" width="70" alt="Yen Briceño"> | **Briceño More, Yen Yosue** | 💻 Programador/a - Modelador/a | Desarrollo del código (frontend/backend), implementación de modelos de IA y arquitectura de software. |

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