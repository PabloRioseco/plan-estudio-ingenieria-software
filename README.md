![Banner del plan de estudio](https://i.imgur.com/wKYTVLw.jpeg)

# Plan de formación autodidacta en Ingeniería de Software

## Introducción

Este documento constituye un plan de estudio formal y estructurado, diseñado para guiar a cualquier persona, con o sin conocimientos previos, a través de los fundamentos, prácticas y arquitecturas propias de la Ingeniería de Software. Su propósito es establecer una ruta de aprendizaje integral que permita al estudiante adquirir competencias de nivel profesional, capacitándolo para resolver problemas complejos, desarrollar aplicaciones escalables y competir exitosamente en la industria tecnológica actual.

El enfoque pedagógico se basa en un modelo de aprendizaje progresivo y en espiral, donde los conceptos se introducen desde sus bases fundamentales y se revisitan posteriormente con mayor profundidad técnica. Este plan ha sido construido tomando como referencia tanto las mallas curriculares de prestigiosas instituciones de educación superior, como las demandas reales del mercado laboral. Así, se asegura la relevancia en áreas clave como "Fundamentos de Programación", "Arquitectura de Software", "Bases de Datos Aplicadas", "Cloud Computing" y "Prácticas DevOps".

La estructura se divide en fases cronológicas, cada una con objetivos de aprendizaje y proyectos específicos. La Fase 1 se centra en los fundamentos conceptuales y el pensamiento lógico-matemático. La Fase 2 introduce la programación y el diseño de algoritmos. La Fase 3 aborda la persistencia de datos y la computación en la nube. Finalmente, la Fase 4 explora tópicos avanzados y el desarrollo de proyectos complejos, consolidando un portafolio sólido para la inserción profesional. Los anexos proveen una metodología de estudio y un cronograma detallado de hitos prácticos para asegurar la aplicación constante del conocimiento.

> **Nota sobre esta iteración:** Esta ruta en particular representa el **primer gran hito de inserción** y está optimizada para la transición laboral hacia el rol de **Service Delivery Manager (SDM)**. Como SDM, serás el puente entre el cliente y los equipos de ingeniería (como SREs y Desarrolladores). Por ello, este plan entrega bases técnicas sólidas (para hablar y entender su lenguaje) combinadas con habilidades críticas en gestión de servicios, proyectos, métricas y relación con clientes. Adicionalmente, se han incorporado fundamentos profundos orientados a facilitar un **salto natural a roles más técnicos en el futuro, como SRE (Site Reliability Engineer) o Cloud Engineer**.

---

**Tabla de Contenidos**
- [Plan de formación autodidacta en Ingeniería de Software](#plan-de-formación-autodidacta-en-ingeniería-de-software)
  - [Introducción](#introducción)
  - [Fase 1: Fundamentos de TI, Redes y Sistemas Operativos (Estimado: 50 horas)](#fase-1-fundamentos-de-ti-redes-y-sistemas-operativos-estimado-50-horas)
    - [Módulo 1.1: Arquitectura de sistemas computacionales](#módulo-11-arquitectura-de-sistemas-computacionales)
    - [Módulo 1.2: Sistemas Operativos y la Terminal de Comandos (Linux)](#módulo-12-sistemas-operativos-y-la-terminal-de-comandos-linux)
    - [Módulo 1.3: Ecosistema de Internet, Redes y Seguridad](#módulo-13-ecosistema-de-internet-redes-y-seguridad)
    - [Módulo 1.4: Virtualización y Contenedores](#módulo-14-virtualización-y-contenedores)
  - [Fase 2: Construcción de Software y Datos (Estimado: 40 horas)](#fase-2-construcción-de-software-y-datos-estimado-40-horas)
    - [Módulo 2.1: Ciclo de Vida del Software (SDLC) y Roles](#módulo-21-ciclo-de-vida-del-software-sdlc-y-roles)
    - [Módulo 2.2: Git, GitHub y Control de Versiones](#módulo-22-git-github-y-control-de-versiones)
    - [Módulo 2.3: Cloud Computing, Bases de Datos y SQL Práctico](#módulo-23-cloud-computing-bases-de-datos-y-sql-práctico)
  - [Fase 3: Gestión de Servicios de TI (ITSM) y Observabilidad (Estimado: 40 horas)](#fase-3-gestión-de-servicios-de-ti-itsm-y-observabilidad-estimado-40-horas)
    - [Módulo 3.1: Fundamentos de ITIL 4](#módulo-31-fundamentos-de-itil-4)
    - [Módulo 3.2: Acuerdos de Nivel de Servicio (SLA, SLO, SLI)](#módulo-32-acuerdos-de-nivel-de-servicio-sla-slo-sli)
    - [Módulo 3.3: Observabilidad y Monitoreo](#módulo-33-observabilidad-y-monitoreo)
  - [Fase 4: Agilidad, Herramientas y Rol SDM (Estimado: 30 horas)](#fase-4-agilidad-herramientas-y-rol-sdm-estimado-30-horas)
    - [Módulo 4.1: Metodologías Ágiles (Scrum y Kanban)](#módulo-41-metodologías-ágiles-scrum-y-kanban)
    - [Módulo 4.2: Herramientas de Gestión y Ticketing (Jira)](#módulo-42-herramientas-de-gestión-y-ticketing-jira)
    - [Módulo 4.3: KPIs y Quarterly Business Reviews (QBRs)](#módulo-43-kpis-y-quarterly-business-reviews-qbrs)
  - [Anexo A: Proyecto Final / Portafolio SDM](#anexo-a-proyecto-final--portafolio-sdm)
  - [Anexo B: Ruta de Certificaciones Clave](#anexo-b-ruta-de-certificaciones-clave)

---

## Fase 1: Fundamentos de TI, Redes y Sistemas Operativos (Estimado: 50 horas)

Esta fase establece el modelo mental necesario sobre el funcionamiento de los computadores, internet y la infraestructura moderna. Es la base dura técnica necesaria para interactuar con SREs y para preparar tu propio futuro en roles especialistas.

### Módulo 1.1: Arquitectura de sistemas computacionales

**Objetivos de aprendizaje:**
1. Diferenciar claramente entre los conceptos de hardware y software.
2. Identificar los componentes físicos principales de un computador.
3. Comprender el rol del sistema operativo como gestor de recursos.

**Recursos recomendados:**
* [Curso completo de informática básica desde cero para principiantes \[Videos 1 al 9\]](https://www.youtube.com/playlist?list=PL2Z95CSZ1N4HLqf215jj9ZJgmWIXm7gOo).
* [Conocimientos básicos de PC - Aprende.org](https://aprende.org/cursos/view/213).
* [¿Qué es hardware y software?](https://edu.gcfglobal.org/es/informatica-basica/que-es-hardware-y-software/1/)

### Módulo 1.2: Sistemas Operativos y la Terminal de Comandos (Linux)

**Objetivos de aprendizaje:**
1. Entender la diferencia entre un SO de escritorio (Windows/Mac) y un SO de servidor (Linux).
2. Aprender a navegar por el sistema y gestionar archivos usando únicamente comandos de texto (Bash). Un paso innegociable hacia roles Cloud o SRE.

**Recursos recomendados:**
* [Curso Básico de Linux desde Cero - EDteam](https://www.youtube.com/watch?v=N_8qW5c4wM8)
* [Los 50 Comandos de Linux más utilizados - Pelado Nerd](https://www.youtube.com/watch?v=D-w_N2q7Kzc)

### Módulo 1.3: Ecosistema de Internet, Redes y Seguridad

**Objetivos de aprendizaje:**
1. Explicar el funcionamiento de internet, DNS, IPs y CDNs.
2. Entender los principios básicos de criptografía y cómo se protege la información (HTTPS).

**Recursos recomendados:**
* [¿Cómo funciona Internet? - Video Explicativo](https://www.youtube.com/watch?v=G21kuUwsfeA&ab_channel=Byteando).
* [¿Qué es el DNS? | Cómo funciona el DNS - Cloudflare](https://www.cloudflare.com/learning/dns/what-is-dns/)
* [¿Qué es una CDN y por qué deberías activarla YA en tu web?](https://www.youtube.com/watch?v=16A6gDevptM)
* [¡La historia completa de la web en 40 minutos!](https://www.youtube.com/watch?v=NWUZCTTLQcg&ab_channel=EDteam)
* [¿Qué es y cómo funciona HTTPS?](https://www.youtube.com/watch?v=60606AHuq8c&ab_channel=EDteam)
* [Encriptación (Cifrado) Simétrica y Asimétrica](https://www.youtube.com/watch?v=wDpqrasDmxM)
* [Criptografía 🔐 ¿Qué es y por qué es importante para todos?](https://www.youtube.com/watch?v=M54vqFz1Z1Y)
* [¿Cómo funciona el cifrado de información?](https://www.youtube.com/watch?v=dChr0TyQ6yc)

### Módulo 1.4: Virtualización y Contenedores

**Objetivos de aprendizaje:**
1. Definir el concepto de virtualización y ejecutar un taller práctico de Máquinas Virtuales (VM).
2. Comprender qué es un contenedor (ej. Docker) y en qué se diferencia históricamente de una VM.

**Recursos recomendados (VMs):**
* [¿Qué es una máquina virtual? - Coursera](https://www.coursera.org/mx/articles/what-is-a-virtual-machine)
* [¿Qué es la virtualización?](https://www.ibm.com/es-es/topics/virtualization).
* [Taller práctico Máquinas virtuales - Opción 1](https://www.youtube.com/watch?v=uiFZUfmFAus)
* [Taller práctico Máquinas virtuales - Opción 2](https://www.youtube.com/watch?v=CLdHQPyHeN0)

**Recursos recomendados (Contenedores):**
* [¿Por qué todos usan contenedores hoy? Historia y comparativa con VMs)](https://www.youtube.com/watch?v=v8lpw8zrD_0)
* [Máquinas Virtuales y Contenedores - ¿Qué son? ¿A qué huelen? ¿Para qué sirven?](https://www.youtube.com/watch?v=mzo2OjcSxag)
* [La historia de los contenedores - Desde 1979 a 2021](https://www.youtube.com/watch?v=K0nHZlHNfQ4)

---

## Fase 2: Construcción de Software y Datos (Estimado: 40 horas)

### Módulo 2.1: Ciclo de Vida del Software (SDLC) y Roles

**Objetivos de aprendizaje:**
1. Entender cómo se crea y despliega el software (Desarrollo, Testing, Producción).
2. Distinguir las responsabilidades entre Frontend, Backend, QA y SRE/DevOps.

**Recursos recomendados:**
* [El ciclo de vida del software (SDLC) explicado](https://www.youtube.com/watch?v=qXvJ8w5oY-Q) *(Busca "Software Development Life Cycle español")*.
* [Frontend vs Backend vs DevOps - Diferencias](https://www.youtube.com/watch?v=BqBItx6Q0U4).

### Módulo 2.2: Git, GitHub y Control de Versiones

**Objetivos de aprendizaje:**
1. Entender el concepto de "Infraestructura como Código" (IaC) y por qué los ingenieros versionan su trabajo.
2. Comprender qué es un repositorio, un "commit", una "rama" (branch) y un "Pull Request".

**Recursos recomendados:**
* [Git y GitHub desde Cero - Fazt](https://www.youtube.com/watch?v=HiXLkL42CPQ) *(Ver la parte conceptual inicialmente).*
* [¿Qué es Git y GitHub? Explicación animada](https://www.youtube.com/watch?v=3fUBtghhl6k)

### Módulo 2.3: Cloud Computing, Bases de Datos y SQL Práctico

**Objetivos de aprendizaje:**
1. Entender de manera gerencial qué es Cloud Computing (IaaS, PaaS, SaaS).
2. Distinguir las diferencias entre bases de datos SQL y NoSQL.
3. Ejecutar consultas básicas en SQL (`SELECT`, `WHERE`, `JOIN`), lo cual es una habilidad real que un SDM usa para extraer reportes desde la base de datos de tickets.

**Recursos recomendados:**
* [¿Qué es el Cloud Computing? - Explicación sencilla](https://www.youtube.com/watch?v=2b3xG_YjgvI).
* [Bases de Datos Relacionales vs No Relacionales](https://www.youtube.com/watch?v=wveheI68t1g).
* **Taller SQL:** [Curso de SQL para Principiantes - Midudev](https://www.youtube.com/watch?v=itaEEsgqBkk) *(Enfoque en crear y consultar datos).*

---

## Fase 3: Gestión de Servicios de TI (ITSM) y Observabilidad (Estimado: 40 horas)

Aquí comienza el núcleo duro del rol del SDM, combinando las mejores prácticas de gestión con las herramientas que usan los ingenieros para mantener los servicios vivos.

### Módulo 3.1: Fundamentos de ITIL 4
ITIL es el estándar mundial para la gestión de servicios de TI.
* **Conceptos clave:** Gestión de Incidentes, Problemas, Cambios y Service Desk.
* **Recursos recomendados:**
  * [¿Qué es ITIL 4?](https://www.youtube.com/watch?v=20WlkQ5qwcU)
  * [¿Qué es ITSM?](https://www.youtube.com/watch?v=3NuL-I_pTL0)
  * [Curso ITIL 4 Foundation Español - Curso 1](https://www.youtube.com/playlist?list=PLp5yhJ4S9Euty2CyHK3g3vu3Zf0zsaWvj).
  * [Curso ITIL 4 Foundation Español - Curso 2](https://www.youtube.com/playlist?list=PLf8XMtbjh0dXYbPWjg-d5GifMXWuiKv5-).
  * [Conceptos Clave de ITIL 4 por Atlassian](https://www.atlassian.com/es/itsm/itil).

### Módulo 3.2: Acuerdos de Nivel de Servicio (SLA, SLO, SLI)
* **Conceptos clave:** SLA (Promesa comercial), SLO (Objetivo interno técnico), SLI (Métrica de la realidad).
* **Recursos recomendados:**
  * [SLA vs SLO vs SLI - Atlassian](https://www.atlassian.com/es/incident-management/kpis/sla-vs-slo-vs-sli).
  * [Google SRE Book - Capítulos sobre Service Level Objectives (Inglés)](https://sre.google/sre-book/service-level-objectives/).

### Módulo 3.3: Observabilidad y Monitoreo
* **Objetivos de aprendizaje:** Entender *cómo y dónde* se miden esos SLOs y SLAs. Aprender la diferencia técnica entre "Métricas", "Logs" y "Trazas", el pan de cada día de un SRE.
* **Recursos recomendados:**
  * [¿Qué es Observabilidad? Logs, Métricas y Trazas explicados](https://www.youtube.com/watch?v=5rT7e9e-5hI)
  * [Monitoreo vs Observabilidad](https://www.youtube.com/watch?v=b2oI_hC1qEM)

---

## Fase 4: Agilidad, Herramientas y Rol SDM (Estimado: 30 horas)

### Módulo 4.1: Metodologías Ágiles (Scrum y Kanban)
* **Scrum:** Roles (Scrum Master, PO, Devs), Artefactos y Eventos.
* **Kanban:** Tableros, WIP, Lead Time y Cycle Time.
* **Recursos recomendados:**
  * [La guía de Scrum (Oficial y Gratuita)](https://scrumguides.org/scrum-guide.html).
  * [Curso Scrum desde Cero](https://www.youtube.com/results?search_query=curso+scrum+completo+espa%C3%B1ol).
  * [Qué es Kanban - Atlassian](https://www.atlassian.com/es/agile/kanban).

### Módulo 4.2: Herramientas de Gestión y Ticketing (Jira)
* **Práctica requerida:** Crearte una cuenta gratuita en Jira Cloud, crear un proyecto de servicio (JSM) y configurar SLAs básicos.
* **Recursos recomendados:**
  * [Atlassian University (Cursos oficiales y gratuitos de Jira Fundamentals)](https://university.atlassian.com/).
  * [Tutorial de Jira para principiantes](https://www.youtube.com/results?search_query=jira+tutorial+espa%C3%B1ol).

### Módulo 4.3: KPIs y Quarterly Business Reviews (QBRs)
* **Métricas a dominar:** MTTR (Mean Time to Repair), CSAT, NPS, Disponibilidad.
* **QBRs:** La reunión trimestral donde el SDM le presenta al cliente el estado de su servicio y el manejo de incidentes graves (Outages).
* **Recursos recomendados:**
  * [Las métricas de incidentes que más importan](https://www.atlassian.com/es/incident-management/kpis/common-metrics).
  * [Cómo realizar un QBR (Quarterly Business Review)](https://www.youtube.com/results?search_query=quarterly+business+review+tutorial).

---

## Anexo A: Proyecto Final / Portafolio SDM

**Objetivo del Proyecto:**
1. **Configuración:** Crea una instancia gratuita de Jira Service Management.
2. **El Incidente:** Simula que "El portal de pagos principal se cayó un viernes al mediodía (Error 500)". Revisa un log falso o un dashboard que justifique el error (Observabilidad).
3. **El Flujo:** Crea los tickets correspondientes, muévelos por el tablero. Extrae un reporte usando SQL si lograste integrar una base de datos de pruebas.
4. **La Comunicación:** Escribe los correos que le enviarías al cliente: a) El reconocimiento del problema (T=0), b) La actualización en proceso (T=1 hora), c) La resolución.
5. **El Post-Mortem:** Redacta un documento en Word/Notion analizando por qué ocurrió (los "5 Por qués"), qué métrica de SLA se vio afectada, y qué harán para que no vuelva a pasar.
6. **La Presentación:** Arma 5 diapositivas (PowerPoint/Canva) como si estuvieras en un QBR presentando la salud trimestral del servicio y cómo se resolvió este incidente.

---

## Anexo B: Ruta de Certificaciones Clave

### 1. ITIL 4 Foundation
* **Por qué es importante:** Es el idioma universal de los SDMs. Todo reclutador buscará las palabras "ITIL" en tu CV. Te enseña cómo funciona un departamento de TI por dentro.
* **El Examen:** Es teórico, consta de 40 preguntas de opción múltiple.
* **Recursos gratuitos:** Simuladores gratuitos de examen en YouTube (Busca: *"ITIL 4 Foundation Exam Mock Test"*).

### 2. Professional Scrum Master (PSM I) - Scrum.org
* **Por qué es importante:** Valida que entiendes cómo trabajan hoy en día los equipos de desarrollo. Como SDM interactuarás con Scrum Masters y equipos técnicos todo el tiempo.
* **El Examen:** Altamente respetado, no expira. Cuesta alrededor de $200 USD.
* **Recursos gratuitos:** La [Scrum Guide](https://scrumguides.org/), simuladores gratuitos de Mikhail Lapshin, y foros de Scrum.org.