![Banner del plan de estudio](https://i.imgur.com/wKYTVLw.jpeg)

# Plan de formación autodidacta en Ingeniería de Software

## Introducción

Este documento constituye un plan de estudio formal y estructurado, diseñado para guiar a cualquier persona, con o sin conocimientos previos, a través de los fundamentos, prácticas y arquitecturas propias de la Ingeniería de Software. Su propósito es establecer una ruta de aprendizaje integral que permita al estudiante adquirir competencias de nivel profesional, capacitándolo para resolver problemas complejos, desarrollar aplicaciones escalables y competir exitosamente en la industria tecnológica actual.

El enfoque pedagógico se basa en un modelo de aprendizaje progresivo y en espiral, donde los conceptos se introducen desde sus bases fundamentales y se revisitan posteriormente con mayor profundidad técnica. Este plan ha sido construido tomando como referencia tanto las mallas curriculares de prestigiosas instituciones de educación superior, como las demandas reales del mercado laboral. Así, se asegura la relevancia en áreas clave como "Fundamentos de Programación", "Arquitectura de Software", "Bases de Datos Aplicadas", "Cloud Computing" y "Prácticas DevOps".

La estructura se divide en fases cronológicas, cada una con objetivos de aprendizaje y proyectos específicos. La Fase 1 se centra en los fundamentos conceptuales y el pensamiento lógico-matemático. La Fase 2 introduce la programación y el diseño de algoritmos. La Fase 3 aborda la persistencia de datos y la computación en la nube. Finalmente, la Fase 4 explora tópicos avanzados y el desarrollo de proyectos complejos, consolidando un portafolio sólido para la inserción profesional. Los anexos proveen una metodología de estudio y un cronograma detallado de hitos prácticos para asegurar la aplicación constante del conocimiento.

> **Nota sobre esta iteración:** Esta ruta en particular representa el **primer gran hito de inserción** y está optimizada para la transición laboral hacia el rol de **Service Delivery Manager (SDM)**. Como SDM, serás el puente entre el cliente y los equipos de ingeniería (como SREs y Desarrolladores). Por ello, este plan entrega bases técnicas sólidas (para hablar y entender su lenguaje) combinadas con habilidades críticas en gestión de servicios, proyectos, métricas y relación con clientes.

---

**Tabla de Contenidos**
- [Plan de formación autodidacta en Ingeniería de Software](#plan-de-formación-autodidacta-en-ingeniería-de-software)
  - [Introducción](#introducción)
  - [Fase 1: Fundamentos de TI y Ecosistema de Software (Estimado: 40 horas)](#fase-1-fundamentos-de-ti-y-ecosistema-de-software-estimado-40-horas)
    - [Módulo 1.1: Arquitectura de sistemas computacionales: del hardware al software.](#módulo-11-arquitectura-de-sistemas-computacionales-del-hardware-al-software)
    - [Módulo 1.2: El ecosistema de internet y la virtualización](#módulo-12-el-ecosistema-de-internet-y-la-virtualización)
    - [Módulo 1.3: Ciclo de Vida del Software (SDLC) y Fundamentos Cloud/Bases de Datos](#módulo-13-ciclo-de-vida-del-software-sdlc-y-fundamentos-cloudbases-de-datos)
  - [Fase 2: Gestión de Servicios de TI (ITSM) (Estimado: 30 horas)](#fase-2-gestión-de-servicios-de-ti-itsm-estimado-30-horas)
    - [Módulo 2.1: Fundamentos de ITIL 4](#módulo-21-fundamentos-de-itil-4)
    - [Módulo 2.2: Acuerdos de Nivel de Servicio (SLA, SLO, SLI)](#módulo-22-acuerdos-de-nivel-de-servicio-sla-slo-sli)
  - [Fase 3: Gestión de Proyectos, Agilidad y Herramientas (Estimado: 30 horas)](#fase-3-gestión-de-proyectos-agilidad-y-herramientas-estimado-30-horas)
    - [Módulo 3.1: Metodologías Ágiles (Scrum y Kanban)](#módulo-31-metodologías-ágiles-scrum-y-kanban)
    - [Módulo 3.2: Herramientas de Gestión y Ticketing (Jira)](#módulo-32-herramientas-de-gestión-y-ticketing-jira)
  - [Fase 4: El Rol del SDM y Relación con el Cliente (Estimado: 20 horas)](#fase-4-el-rol-del-sdm-y-relación-con-el-cliente-estimado-20-horas)
    - [Módulo 4.1: KPIs y Métricas de Servicio](#módulo-41-kpis-y-métricas-de-servicio)
    - [Módulo 4.2: Reportes y Quarterly Business Reviews (QBRs)](#módulo-42-reportes-y-quarterly-business-reviews-qbrs)
  - [Anexo A: Proyecto Final / Portafolio SDM](#anexo-a-proyecto-final--portafolio-sdm)
  - [Anexo B: Ruta de Certificaciones Clave](#anexo-b-ruta-de-certificaciones-clave)

---

## Fase 1: Fundamentos de TI y Ecosistema de Software (Estimado: 40 horas)

Esta fase establece el modelo mental necesario sobre el funcionamiento de los computadores, internet y la infraestructura moderna. Un SDM no necesita programar, pero **debe** entender cómo funcionan estas piezas para tomar buenas decisiones, entender los incidentes reportados y comunicarse con equipos técnicos como DevOps o SRE.

### Módulo 1.1: Arquitectura de sistemas computacionales: del hardware al software.

**Objetivos de aprendizaje:**
1. Diferenciar claramente entre los conceptos de hardware y software.
2. Identificar los componentes físicos principales de un computador y describir su función.
3. Comprender el rol del sistema operativo como gestor de recursos y su interacción con el hardware y las aplicaciones.

**Plan de estudio:**

#### **Tema A: Componentes de un computador.**
* Se analizará en detalle la función de la CPU (el "cerebro"), la RAM (espacio de trabajo volátil) y las unidades de almacenamiento (HDD vs. SSD).
* **Recursos recomendados:**
    * [Curso completo de informática básica desde cero para principiantes \[Videos 1 al 9\]](https://www.youtube.com/playlist?list=PL2Z95CSZ1N4HLqf215jj9ZJgmWIXm7gOo).
    * [Conocimientos básicos de PC - Aprende.org](https://aprende.org/cursos/view/213).

#### **Tema B: El software y el sistema operativo.**
* Rol del sistema operativo (SO) como intermediario que gestiona los recursos. SO principales: Windows, macOS y Linux. Linux es especialmente clave en servidores.
* **Recursos recomendados:**
    * [¿Qué es hardware y software?](https://edu.gcfglobal.org/es/informatica-basica/que-es-hardware-y-software/1/)
    * [Curso completo de informática básica desde cero para principiantes \[Videos 9 al 16\]](https://www.youtube.com/playlist?list=PL2Z95CSZ1N4HLqf215jj9ZJgmWIXm7gOo).

### Módulo 1.2: El ecosistema de internet y la virtualización

**Objetivos de aprendizaje:**
1. Explicar el funcionamiento de internet y componentes como DNS e IPs.
2. Definir el concepto de virtualización y su impacto en servidores y escalabilidad.
3. Comprender qué es un contenedor (ej. Docker) y en qué se diferencia de una máquina virtual.

**Plan de estudio:**

#### **Tema A: Fundamentos de redes e internet.**
* Roles de cliente y servidor, direccionamiento IP, Sistema de Nombres de Dominio (DNS), y protocolos HTTP/HTTPS.
* **Recursos recomendados:**
  * [¿Cómo funciona Internet? - Video Explicativo](https://www.youtube.com/watch?v=G21kuUwsfeA&ab_channel=Byteando).
  * [¿Qué es el DNS? | Cómo funciona el DNS - Cloudflare](https://www.cloudflare.com/learning/dns/what-is-dns/)
  * [¿Qué es una CDN y por qué deberías activarla YA en tu web?](https://www.youtube.com/watch?v=16A6gDevptM)
  * [¡La historia completa de la web en 40 minutos!](https://www.youtube.com/watch?v=NWUZCTTLQcg&ab_channel=EDteam)
  * [¿Qué es y cómo funciona HTTPS?](https://www.youtube.com/watch?v=60606AHuq8c&ab_channel=EDteam)
  * [Encriptación (Cifrado) Simétrica y Asimétrica](https://www.youtube.com/watch?v=wDpqrasDmxM)
  * [Criptografía 🔐 ¿Qué es y por qué es importante para todos?](https://www.youtube.com/watch?v=M54vqFz1Z1Y)
  * [¿Cómo funciona el cifrado de información?](https://www.youtube.com/watch?v=dChr0TyQ6yc)

#### **Tema B: Introducción a la virtualización.**
* Crear una versión virtual de un recurso (servidores virtuales). Esto da paso a entender cómo los equipos despliegan código sin hardware físico.
* **Recursos recomendados:**
  * [¿Qué es una máquina virtual? - Coursera](https://www.coursera.org/mx/articles/what-is-a-virtual-machine)
  * [¿Qué es la virtualización?](https://www.ibm.com/es-es/topics/virtualization).
  * [Taller práctico Máquinas virtuales - Opción 1](https://www.youtube.com/watch?v=uiFZUfmFAus)
  * [Taller práctico Máquinas virtuales - Opción 2](https://www.youtube.com/watch?v=CLdHQPyHeN0)

#### **Tema C: Contenedores y su diferencia con Máquinas Virtuales.**
* Introducción a la tecnología de contenedores (como Docker). Explicar por qué la industria migró de usar solo máquinas virtuales (VMs) a empaquetar aplicaciones en contenedores ligeros y portables.
* **Recursos recomendados:**
  * [¿Por qué todos usan contenedores hoy? Historia y comparativa con VMs)](https://www.youtube.com/watch?v=v8lpw8zrD_0)
  * [Máquinas Virtuales y Contenedores - ¿Qué son? ¿A qué huelen? ¿Para qué sirven?](https://www.youtube.com/watch?v=mzo2OjcSxag)
  * [La historia de los contenedores - Desde 1979 a 2021](https://www.youtube.com/watch?v=K0nHZlHNfQ4)

### Módulo 1.3: Ciclo de Vida del Software (SDLC) y Fundamentos Cloud/Bases de Datos

**Objetivos de aprendizaje:**
1. Entender cómo se crea y despliega el software (Desarrollo, Testing, Producción).
2. Distinguir las responsabilidades entre Frontend, Backend, QA y SRE/DevOps.
3. Entender de manera gerencial qué es Cloud Computing y las diferencias entre bases de datos SQL y NoSQL.

**Plan de estudio:**
* **SDLC y Roles:** Conocer las fases (Requisitos, Diseño, Desarrollo, Pruebas, Despliegue, Mantenimiento).
* **Cloud Computing:** ¿Qué es AWS, Google Cloud o Azure? Modelos IaaS, PaaS, SaaS.
* **Bases de Datos:** Entender conceptualmente dónde vive la información.
* **Recursos recomendados:**
  * [El ciclo de vida del software (SDLC) explicado](https://www.youtube.com/watch?v=qXvJ8w5oY-Q) *(Busca "Software Development Life Cycle español")*.
  * [Frontend vs Backend vs DevOps - Diferencias](https://www.youtube.com/watch?v=BqBItx6Q0U4) *(EDteam o similares)*.
  * [¿Qué es el Cloud Computing? - Explicación sencilla](https://www.youtube.com/watch?v=2b3xG_YjgvI) *(Amazon Web Services)*.
  * [Bases de Datos Relacionales vs No Relacionales](https://www.youtube.com/watch?v=wveheI68t1g).

---

## Fase 2: Gestión de Servicios de TI (ITSM) (Estimado: 30 horas)

Aquí comienza el núcleo duro del rol del SDM. Debes entender que la TI no se trata solo de escribir código, sino de proveer "servicios" a los clientes que siempre deben estar disponibles, seguros y actualizados.

### Módulo 2.1: Fundamentos de ITIL 4
ITIL (Information Technology Infrastructure Library) es el estándar mundial para la gestión de servicios de TI.
* **Conceptos clave:** Gestión de Incidentes (cuando algo se rompe), Gestión de Problemas (la causa raíz de los incidentes recurrentes), Gestión de Cambios (despliegues de nuevo código) y Centro de Servicio al Usuario (Service Desk).
* **Recursos recomendados:**
  * [¿Qué es ITIL 4?](https://www.youtube.com/watch?v=20WlkQ5qwcU)
  * [¿Qué es ITSM?](https://www.youtube.com/watch?v=3NuL-I_pTL0)
  * [Curso ITIL 4 Foundation Español - Curso 1](https://www.youtube.com/playlist?list=PLp5yhJ4S9Euty2CyHK3g3vu3Zf0zsaWvj).
  * [Curso ITIL 4 Foundation Español - Curso 2](https://www.youtube.com/playlist?list=PLf8XMtbjh0dXYbPWjg-d5GifMXWuiKv5-).
  * [Conceptos Clave de ITIL 4 por Atlassian](https://www.atlassian.com/es/itsm/itil).

### Módulo 2.2: Acuerdos de Nivel de Servicio (SLA, SLO, SLI)
Un SDM se pasa gran parte de su día verificando que no se incumplan estos acuerdos. Hablarás de esto constantemente con los equipos de Site Reliability Engineering (SRE).
* **Conceptos clave:**
  * **SLA (Service Level Agreement):** El contrato legal o promesa con el cliente (Ej: 99.9% de tiempo en línea).
  * **SLO (Service Level Objective):** El objetivo interno de los equipos técnicos para cumplir el SLA (Ej: 99.95%).
  * **SLI (Service Level Indicator):** La métrica real actual (Ej: Hoy estuvimos 99.98% en línea).
* **Recursos recomendados:**
  * [SLA vs SLO vs SLI - Atlassian](https://www.atlassian.com/es/incident-management/kpis/sla-vs-slo-vs-sli).
  * [Google SRE Book - Capítulos sobre Service Level Objectives (Inglés)](https://sre.google/sre-book/service-level-objectives/).

---

## Fase 3: Gestión de Proyectos, Agilidad y Herramientas (Estimado: 30 horas)

### Módulo 3.1: Metodologías Ágiles (Scrum y Kanban)
El desarrollo moderno ya no funciona en modelos rígidos ("Cascada"), sino en iteraciones cortas llamadas Sprints (Scrum) o mediante flujos continuos visuales (Kanban).
* **Scrum:** Roles (Scrum Master, Product Owner, Developers), Artefactos (Backlog) y Eventos (Dailies, Planning, Retrospectivas).
* **Kanban:** Tableros, WIP (Work in Progress), Lead Time y Cycle Time.
* **Recursos recomendados:**
  * [La guía de Scrum (Oficial y Gratuita)](https://scrumguides.org/scrum-guide.html).
  * [Curso Scrum desde Cero](https://www.youtube.com/results?search_query=curso+scrum+completo+espa%C3%B1ol).
  * [Qué es Kanban - Atlassian](https://www.atlassian.com/es/agile/kanban).

### Módulo 3.2: Herramientas de Gestión y Ticketing (Jira)
Jira (de Atlassian) es la herramienta líder mundial en gestión de proyectos de software y ticketing (Jira Service Management). Un SDM vive en esta herramienta.
* **Práctica requerida:** Debes crearte una cuenta gratuita en Jira Cloud, crear un proyecto, configurar un flujo de trabajo (To Do, In Progress, Done) y gestionar incidentes.
* **Recursos recomendados:**
  * [Atlassian University (Cursos oficiales y gratuitos de Jira Fundamentals)](https://university.atlassian.com/).
  * [Tutorial de Jira para principiantes](https://www.youtube.com/results?search_query=jira+tutorial+espa%C3%B1ol).

---

## Fase 4: El Rol del SDM y Relación con el Cliente (Estimado: 20 horas)

### Módulo 4.1: KPIs y Métricas de Servicio
Medir para mejorar. Un SDM gestiona crisis basándose en datos, no en emociones.
* **Métricas a dominar:**
  * **MTTR** (Mean Time to Repair): Tiempo medio para resolver un incidente.
  * **CSAT** (Customer Satisfaction Score) y **NPS** (Net Promoter Score).
  * **Disponibilidad/Uptime** y **Downtime**.
* **Recursos recomendados:**
  * [Las métricas de incidentes que más importan](https://www.atlassian.com/es/incident-management/kpis/common-metrics).

### Módulo 4.2: Reportes y Quarterly Business Reviews (QBRs)
El QBR es la reunión trimestral donde el SDM le presenta al cliente el estado de su servicio, lo bueno, lo malo y el plan de acción a futuro.
* **Cómo crear un reporte ejecutivo:** De los datos operativos a la vista ejecutiva.
* **Manejo de crisis:** Cómo comunicar un incidente crítico (Outage) a un cliente enojado sin generar pánico.
* **Recursos recomendados:**
  * [Cómo realizar un QBR (Quarterly Business Review)](https://www.youtube.com/results?search_query=quarterly+business+review+tutorial).
  * *Investigación autodidacta:* Buscar artículos en LinkedIn o Medium sobre "Executive Reporting for SDMs" o "Incident Communication Strategies".

---

## Anexo A: Proyecto Final / Portafolio SDM

A diferencia de un desarrollador que muestra su código en GitHub, el "portafolio" de un SDM es la demostración de su gestión ante una crisis simulada.
**Objetivo del Proyecto:**
1. **Configuración:** Crea una instancia gratuita de Jira Service Management.
2. **El Incidente:** Simula que "El portal de pagos principal se cayó un viernes al mediodía (Error 500)".
3. **El Flujo:** Crea los tickets correspondientes, muévelos por el tablero.
4. **La Comunicación:** Escribe los borradores de los correos que le enviarías al cliente: a) El reconocimiento del problema (T=0), b) La actualización en proceso (T=1 hora), c) La resolución.
5. **El Post-Mortem:** Redacta un documento en Word/Notion (Post-Incident Review) analizando por qué ocurrió (los "5 Por qués"), qué métrica de SLA se vio afectada, y qué harán para que no vuelva a pasar.
6. **La Presentación:** Arma 5 diapositivas (PowerPoint/Canva) como si estuvieras en un QBR presentando la salud trimestral del servicio y cómo se resolvió este gran incidente.

Este proyecto lo puedes presentar en entrevistas de trabajo para demostrar que, aunque no tengas experiencia previa, tienes dominio procedimental del rol.

---

## Anexo B: Ruta de Certificaciones Clave

La transición laboral es más sencilla si cuentas con certificaciones avaladas internacionalmente. Dado que no posees grado universitario en el área, estas credenciales funcionarán como tu validación profesional frente a Recursos Humanos.

### 1. ITIL 4 Foundation
* **Por qué es importante:** Es el idioma universal de los SDMs. Todo reclutador buscará las palabras "ITIL" en tu CV. Te enseña cómo funciona un departamento de TI por dentro.
* **El Examen:** Es teórico, consta de 40 preguntas de opción múltiple.
* **Recursos gratuitos:** Puedes prepararte 100% de manera autodidacta leyendo material en internet, usando simuladores gratuitos de examen en YouTube (Busca: *"ITIL 4 Foundation Exam Mock Test"*).

### 2. Professional Scrum Master (PSM I) - Scrum.org
* **Por qué es importante:** Valida que entiendes cómo trabajan hoy en día los equipos de desarrollo. Como SDM interactuarás con Scrum Masters y equipos técnicos todo el tiempo.
* **El Examen:** Es altamente respetado porque es difícil y no expira (a diferencia de otros certificados). Cuesta alrededor de $200 USD, pero el aprendizaje es gratis.
* **Recursos gratuitos:** La [Scrum Guide](https://scrumguides.org/) (lectura obligatoria unas 5 veces), simuladores gratuitos como Mikhail Lapshin, y foros de Scrum.org.