# 🏛️ Planeaciones Didácticas CONALEP — Plantel Chilpancingo

Este repositorio centraliza las **planeaciones didácticas semestrales, interactivas y estandarizadas** del Catedrático **Cruz Enrique García** para las carreras de:
- **Profesional Técnico-Bachiller en Informática**
- **Profesional Técnico-Bachiller en Pilotaje de Drones**
- **Formación Sociocognitiva Interdisciplinar (Cultura Digital)**

---

## 📚 Catálogo Oficial de Módulos Formativos

| Módulo | Siglema | Semestre | Horas / Semana | Horas Semestre | Créditos | Evidencias SAE | Enlace |
|---|---|---|---|---|---|---|---|
| **Aplicación de la Seguridad Informática** | **ASIN-03** | 3° Semestre | 4 hrs/sem | 72 Horas | 7 Créditos | 5 Evaluaciones (100%) | [Abrir Módulo](./aplicacion-de-la-seguridad-informatica/index.html) |
| **Programación Básica en Python** | **PBAS-03** | 2° y 3° Semestre | 7 hrs/sem | 126 Horas | 13 Créditos | 4 Evaluaciones (100%) | [Abrir Módulo](./programacion-basica/index.html) |
| **Aplicación de Tecnologías Digitales (Cultura Digital)** | **ATDI-00** | 1° Semestre | 5 hrs/sem | 90 Horas | — | 7 Evaluaciones (100%) | [Abrir Módulo](./aplicacion-de-tecnologias-digitales/index.html) |
| **Manejo de Redes (Cisco Packet Tracer)** | **MRDE-03** | 6° Semestre | 8 hrs/sem | 144 Horas | 14 Créditos | 7 Evaluaciones (100%) | [Abrir Módulo](./manejo-de-redes/index.html) |

---

## ⚖️ Criterios Institucionales de Evaluación y Acreditación

Todas las asignaturas operan bajo el esquema oficial de evaluación formativa y sumativa:
- **40% Firmas:** Actividades continuas de aula, ejercicios resueltos del problemario (10 ejercicios por tema), diagramas de flujo/topologías y reportes de prácticas en simulador.
- **10% Asistencias:** Asistencia y puntualidad reglamentaria (mínimo 80%) y programa de preceptorías académicas.
- **50% Proyecto Integrador / Evidencias SAE:** Proyectos funcionales ejecutables (archivos `.pkt`, scripts de Cisco IOS) y Actividades de Evaluación Oficiales capturadas en el Sistema de Administración Escolar (SAE).

---

## 🎯 Estructura Pedagógica Obligatoria de 5 Fases por Subtema / RA

Cada subtema y Resultado de Aprendizaje (RA) se imparte bajo una secuencia estructurada:
1. **Fase 1: Apertura (Activación y Contextualización):** Casos de estudio de la industria real (ciberseguridad, drones, tormentas de broadcast, colapsos de red, agotamiento de IPv4) y preguntas diagnósticas detonadoras.
2. **Fase 2: Desarrollo Conceptual:** Fundamentación teórica rigurosa, estándares internacionales (ISO/IEC 27000, IEEE 802.11, IEEE 802.1Q, IEEE 802.1D, RFC 1918, PEP 8, MCCEMS) y glosarios técnicos.
3. **Fase 3: Demostración y Modelado Paso a Paso:** Procedimientos guiados con código fuente y comandos documentados (Cisco IOS CLI, Python 3, PowerShell, Linux, HTML5), pruebas de escritorio y diagramas vectoriales SVG interactivos.
4. **Fase 4: Aplicación Práctica:**
   - **Simuladores Interactivos en JavaScript Nativo:**
     - *ASIN-03:* Calculadora CIA de Riesgos ISO 27005, Validador de Políticas ISO 27001, Terminal de Firewall, Monitor SIEM de Logs y Matriz de Gap Analysis.
     - *PBAS-03:* Intérprete REPL de Python, Trazador de Flujo y Ciclos, Visualizador de Call Stack y Simulador de Pilas (LIFO) y Colas (FIFO).
     - *ATDI-00:* Calculadora de Huella Digital, Medidor de Passwords, Trazador Algorítmico, Evaluador Condicional, Generador de Color, Calculadora Estadística y Topologías de Red.
     - *MRDE-03:* Configurador Web AP Linksys, Auditor de Seguridad WPA2 y Filtro MAC, Emulador de Terminal Cisco IOS CLI, Simulador de NAT/PAT y DHCP, Diseñador de VLANs 802.1Q, Gestor de Dominio VTP / STP y Enrutador Inter-VLAN (Router-on-a-Stick).
   - **Problemario / Taller:** 10 ejercicios prácticos por tema para el portafolio de firmas (40%).
5. **Fase 5: Cierre, Evaluación y Metacognición:** Matrices de valoración oficiales del CONALEP (Excelente / Suficiente / Insuficiente) con ponderación exacta para el SAE y preguntas de metacognición.

---

## 💻 Arquitectura Web y Diseño

- **White UI (Inspirado en Luis Llamas):** Interfaz limpia, responsiva, fondo `#ffffff` y tipografías *Outfit* y *JetBrains Mono*.
- **3 Columnas de Navegación:** Menú lateral izquierdo con badges de dificultad, columna central didáctica con diapositivas/código, y panel lateral derecho con tabla de contenidos dinámica y resumen SAE.
- **Tecnologías:** Tailwind CSS CDN, FontAwesome 6, MathJax 3 y JavaScript nativo (sin dependencias inseguras como polyfill.io).
