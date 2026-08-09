# 📊 Dashboard Interactivo de Análisis Organizacional: Liderazgo en Entornos VUCA

> **Herramienta de Diagnóstico Relacional, Simulador de Decisiones Directivas y Arquitectura de Influencia (`Potestas` vs `Auctoritas`)**  
> *Desarrollado para entornos de Educación Ejecutiva y formación universitaria en Administración de Empresas / Gestión de Relaciones Organizacionales.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-NONE-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 📌 Descripción General

Este proyecto es una aplicación web interactiva en un **único archivo ejecutable (*Single-File Component*)** diseñada para procesar, visualizar y simular dilemas complejos de comportamiento organizacional y liderazgo en entornos **VUCA** (Volatilidad, Incertidumbre, Complejidad y Ambigüedad).

A diferencia de un informe estático en PDF, esta herramienta actúa como un **centro de decisiones y aprendizaje interactivo** que permite a estudiantes y ejecutivos evaluar la credibilidad directiva, calibrar el uso del poder formal frente a la autoridad moral, y analizar fallos relacionales reales dentro de las organizaciones.

---

## ✨ Características Principales

### 🎓 1. Alternancia de Roles en Aula (Vista Estudiante vs. Vista Docente)
- **Modo Estudiante:** Enfocado en el análisis de casos, autoevaluación y resolución de dilemas sin sesgos.
- **Modo Docente / Facilitador:** Activa un conmutador (*toggle*) en el encabezado que despliega **notas metodológicas y de facilitación** (vinculadas a autores como Amy Edmondson, French & Raven, David Rock y Herbert Simon) para guiar el debate en clase.

### 🎮 2. Simulador de Decisiones Dilemáticas (*Branching Scenario*)
- Presentación de dilemas ético-operativos redactados en **segunda persona del singular** (*"Estás liderando una célula de trabajo y..."*).
- Retroalimentación pedagógica inmediata basada en las consecuencias de elegir entre **Potestas** (mando jerárquico coercitivo) y **Auctoritas** (autoridad moral sustentada en el ejemplo y la competencia).

### 🔍 3. Buscador y Filtro Combinado Multi-Criterio
- Motor de búsqueda JS en tiempo real que evalúa de forma simultánea el texto ingresado en la caja de búsqueda **Y** la categoría seleccionada (*Fallos de Liderazgo* vs. *Dilemas Éticos*), evitando sobreescrituras de estado.

### 📊 4. Visualización de Métricas e Integridad Data-Driven
- **KPI Cards:** Destacado visual de métricas críticas (como el impacto financiero de $500M por fallos de gobernanza operacional en IA).
- **Gráficos SVG Nativos:** Representación de barras para la distribución de desafíos VUCA sin requerir librerías externas (como Chart.js o D3.js).

### ✅ 5. Plan de Acción y Ecuación de Credibilidad ($\text{Pensar} = \text{Decir} = \text{Hacer}$)
- Checklist interactivo de 10 comportamientos directivos coherentes.
- **Barra de progreso dinámica** con cálculo porcentual en tiempo real.
- **Persistencia Local (`localStorage`):** Guarda el avance en el navegador sin backend.
- **Exportación JSON:** Permite al alumno descargar un reporte ligero (`plan_coherencia_liderazgo.json`) para entregas académicas.

### 💬 6. Asistente de Consultas Híbrido (Local + IA External)
- **Modo Base Local (Gratuito):** Búsqueda por palabras clave sobre conceptos del informe (Sun Tzu, French & Raven, VUCA, Potestas/Auctoritas).
- **Modo API Externa (Opcional):** Conexión efímera mediante API Key de Anthropic Claude que vive únicamente en la memoria de la sesión (sin almacenamiento en disco ni fugas de seguridad).

---

## 🛠️ Especificaciones Técnicas y Arquitectura

- **Arquitectura:** Single-File Component (HTML5 + CSS3 + Vanilla JavaScript ES6+).
- **Cero Dependencias Externa:** Carga instantánea, ejecutable *offline* o alojable en GitHub Pages / servidores estáticos.
- **Diseño Responsive:** Breakpoint adaptativo a 640px. Las tablas comparativas se transforman automáticamente en tarjetas verticales para smartphones.
- **Accesibilidad (WCAG AA):** Tipografía base ampliada a `1.05rem` (~17px) con interlineado `1.7`, bordes de contraste de `1.5px` y estados `:focus-visible` para navegación completa por teclado.
- **Paleta Funcional de Estado:**
  - 🟢 **Verde (`#15803d`):** Fortalezas / Cumplimiento / Prioridad Baja
  - 🟡 **Ámbar (`#b45309`):** Advertencias / En Progreso / Prioridad Media
  - 🔴 **Rojo (`#b91c1c`):** Riesgos Críticos / Fallos / Prioridad Alta
  - 🟣 **Púrpura (`#6b21a8`):** Insights / Dilemas Éticos / Oportunidades

---

## 🚀 Instalación y Uso Rápido

No requiere instalación de entornos Node.js, compilar paquetes ni configurar bases de datos.

1. **Clonar o descargar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/dashboard-liderazgo-vuca.git](https://github.com/tu-usuario/dashboard-liderazgo-vuca.git)
