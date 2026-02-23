# RESPUESTAS — Reflexión y Resumen 

> **Actividad / ID:**  Reflexión y Resumen
> **Unidad / Tema:**  UD 2: Análisis de incidentes de ciberseguridad
> **Alumno/a:**  Jose Luis Godoy Khattaoui
> **Fecha:**  23/02/2026

---

## 1) Reflexión crítica (preguntas)
Responde con **lenguaje técnico** y **argumentos** (no solo opiniones). Si procede, usa ejemplos, riesgos y decisiones justificadas.

### 1.1) ¿Qué te han parecido los temas tratados en la unidad?
- Los temas tratados en la unidad me han parecido, en su mayoría, interesantes a nivel formativo, ya que son temas que conoces muy por encima y son importantes para entender mejor cómo puede funcionar una empresa en la que podríamos trabajar después de acabar la especialización.

### 1.2) ¿Qué ha sido más útil para tu futuro puesto de trabajo? ¿Por qué?
- Personalmente, el tema que me parece que podemos aprender y aplicar mejor es el último, el tema de cómo escribir un informe técnico, ya que creo que precisamente saber esto va a diferenciarnos de la competencia en nuestro puesto de trabajo. Está bien estructurado y la estructura que aconseja para plantear el *informe técnico* es **perfecta**.

### 1.3) ¿Qué partes ya conocías y cuáles han sido nuevas para ti?
- Conocía alguna parte del tema de redactar un informe, ya que buena parte de las buenas prácticas del tema son las que se usan para realizar cualquier buen informe, no solo relacionado con nuestra profesión. Personalmente aprendí cosas de ese estilo en el grado medio de administrativo que hice en su día.

### 1.4) ¿Qué concepto/idea te ha llamado más la atención y por qué?
- La taxonomía de los incidentes; lo que más me ha llamado la atención son las fases por las que pasa un incidente, porque me parece súper interesante la forma en que las empresas lo afrontan, sobre todo para saber cómo trabajan, que es al menos para mí la parte más interesante, ya que eso te puede ayudar a tener una pequeña guía sobre dónde dirigir tu futuro laboral.

### 1.5) ¿Qué parte recortarías o simplificarías si hubiera menos tiempo? Justifica.
- Sinceramente, es una pregunta difícil porque creo que todos los temas son importantes para entender cómo funciona parte del ámbito empresarial. Así que quizá simplificaría un poco la parte del SOC porque puede ser un poco extenso si hubiera menos tiempo; recortaría, por ejemplo, la parte de herramientas de los SIEM, porque al fin y al cabo es lo menos importante, ya que debemos tener más claro cómo funcionan que cuáles son las herramientas. En la taxonomía, recortaría la parte del contenido dañino, obtención de información y la intrusión, ya que es un poco redundante con lo que tratamos en otras asignaturas como, por ejemplo, Hacking Ético, donde tratamos eso mismo pero más a fondo.

### 1.6) ¿Qué tema has echado en falta o ampliarías? Justifica.
- Ampliaría un poco la parte del SOAR, ya que son una parte muy importante hoy en día de un SOC y verlo un poco más en profundidad podría darnos conocimientos y/o información de cara a un puesto de trabajo relacionado con el mismo.

### 1.7) ¿Qué aplicarías “mañana” en un entorno real con recursos limitados?
- En un entorno real con recursos limitados aplicaría una taxonomía y un SOC para revisar los logs diarios. Utilizaría un SIEM con pocos casos de uso (los más importantes como inicio de sesión, intentos de acceso al SSH y spam de solicitudes) y aprovecharía el uso de herramientas de OSINT gratuitas para así obligar a documentar cada incidente y a la creación de informes.

### 1.8) ¿Qué duda, riesgo o punto crítico te queda abierto tras la unidad?
- Cómo aplicar lo aprendido en una pequeña empresa de una manera óptima tanto en dinero a invertir como en personal, y cómo se llevaría la documentación en ese caso.

## 2) Resumen esquematizado (obligatorio)
[Aquí, incluye **todos los puntos** vistos en la unidad. Prioriza esquema/tabla/listas con **contenido claro sobre los puntos importantes**, sobre párrafos largos que no aporten. **No olvides el resumen**]

# 2.1 Taxonomía de incidentes
- Es una forma estandarizada de categorizar y describir incidentes, lo que permite una respuesta rápida y efectiva de las empresas.

# 2.2 SOC - Servicios y herramientas
- Un SOC es un centro de operaciones centralizado que se encarga de detectar, responder y prevenir amenazas de seguridad. Plantea beneficios para la empresa, sobre todo económicos.
- La herramienta principal de un SOC es el SIEM.

## 2.2.1 Qué es un SIEM
- Es una solución de seguridad que recopila e interpreta datos de la empresa y detecta potenciales amenazas, lo cual ayuda a monitorear dichas amenazas en tiempo real.

## 2.2.2 Casos de uso
- Es el contexto en el que un SOC debe actuar; es decir, un escenario en el que se describe cuándo y cómo debe hacerlo.

## 2.2.3 Implantación de un SIEM
- Fase de descubrimiento y planificación, donde se revisan las políticas de seguridad.  
- Fase piloto.  
- Fase de implementación.  
- Fase de mejora continua.

## 2.2.4 Evolución de SIEM
- Desde el SIEM que se utilizaba para cloud fundamentalmente hasta el que se usa hoy día, han pasado de ser amenazas estáticas a amenazas polimórficas, que cambian constantemente para evadir la detección. Hoy en día, los sistemas SIEM se esfuerzan en reconocer también patrones, no solo procesan datos.

# 2.3 Fuentes Abiertas
- Al detectar un incidente, se debe llevar a cabo un análisis más detallado para comprender la causa, el alcance y el impacto, con el objetivo de identificar la vulnerabilidad, evaluar las amenazas y detectar brechas de seguridad.  
- Hay 2 tipos de OSINT:  
  - Activo: interactúa con el sistema operativo, cortafuegos, dirección IP, etc.  
  - Pasivo: no se interactúa, solo se consulta en motores de búsqueda, redes sociales u otras fuentes.

## 2.3.1 OSINT
- Se refiere a la recopilación y análisis de la información proveniente de fuentes públicas con el objetivo de extraer información útil.

# 2.4 Documentación de incidentes
- Trata sobre la importancia de qué y cómo documentar un incidente de seguridad.

## 2.4.1 Documentación de Incidentes

## 2.4.2 Cómo escribir informes técnicos
- Consejos sobre cómo realizar un informe técnico de manera profesional y cómo estructurarlo para que sea comprensible para personas técnicas y no técnicas.

### 2.1) Mapa/índice de la unidad (visión global)
- Taxonomía de incidentes de ciberseguridad
- Ecosistema de un SOC: servicios, personas, procesos y tecnologías
- SIEM: definición, recopilación, análisis y alertas
- Casos de uso en un SOC
- Mejores prácticas para implementación de SIEM
- Evolución de SIEM y herramientas SOAR
- OSINT: fuentes abiertas, técnicas, herramientas y procesos
- Gestión y documentación de incidentes
- Cómo escribir informes técnicos e informes de incidentes

### 2.2) Conceptos clave (lista breve)
- SOC: Centro de Operaciones de Seguridad
- SIEM: Gestión de eventos de seguridad
- SOAR: Automatización y respuesta de seguridad
- OSINT: Inteligencia de fuentes abiertas
- Incidente de seguridad: evento que compromete la seguridad
- Playbook: guía para respuesta a incidentes
- EPS: Eventos por segundo (SIEM)

### 2.3) Procesos / procedimientos (pasos o checklist)
- Clasificación de incidentes según taxonomía
- Monitorización de alertas en SOC
- Escalado y respuesta a incidentes
- Recopilación y análisis de logs en SIEM
- Enriquecimiento de registros (geolocalización, DNS, etc.)
- Gestión de alertas y casos de uso
- Planificación y ejecución de procesos OSINT
- Documentación y seguimiento post-incidente

### 2.4) Herramientas / técnicas (si aplica)
- SIEM, SOAR, IDS/IPS, sistemas de ticketing
- Herramientas de Threat Intelligence y forense digital
- Shodan, Wayback Machine, Maltego, SpiderFoot
- Técnicas: Footprinting, Google Dorking, análisis de metadatos, monitorización Dark Web

### 2.5) Buenas prácticas y errores típicos
- Definir objetivos claros y priorizar activos críticos
- Estandarizar procesos y roles dentro del SOC
- Evitar alertas excesivas o mal configuradas en SIEM
- Documentar incidentes de manera completa y precisa
- No confundir hechos con hipótesis en informes
- Realizar revisiones post-mortem para mejora continua

### 2.6) Glosario mínimo (términos y definiciones cortas)
- SOC: Centro especializado en monitorizar y responder a incidentes
- SIEM: Plataforma que centraliza, correlaciona y analiza logs
- SOAR: Automatización de respuesta y orquestación de seguridad
- OSINT: Inteligencia obtenida de fuentes públicas y abiertas
- Incidente: Evento que amenaza la confidencialidad, integridad o disponibilidad
- Playbook: Procedimiento estandarizado para gestión de incidentes
- EPS: Métrica de eventos procesados por segundo en SIEM

## 4) Conclusión (cierre)

- En la unidad he aprendido como se gestionan los incidentes de seguridad en una empresa, la forma en como ésta debe actuar y las herramientas y los procesos que pueden facilitar esa actuación, lo cual es bastante interesante de cara a un futuro laboral