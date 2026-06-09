# Red Amiga — Formulación de Proyecto VIU 2026
### Navegando el Espacio Público: navegación urbana accesible e inclusiva

> **Nota de uso:** Este es un borrador para tu postulación-examen. Los campos marcados con 🔧 son supuestos que debes ajustar a tu realidad (memoria/tesis de origen, institución beneficiaria, nombres del equipo, TRL real y montos). Las cifras de población provienen del III Estudio Nacional de la Discapacidad (III ENDISC 2022, SENADIS/MDSF).

---

## Cierre del guion del video (pág. 10, ítems vi–vii)

> *Estos dos puntos cierran la pauta del video de presentación de 120 s. Se incluyen aquí porque están en la página 10 y porque su contenido respalda directamente la formulación escrita.*

**vi. Medios de verificación del nivel mínimo de madurez (TRL 2) al momento del video.** Se acredita el TRL de entrada mediante: 🔧 *[la memoria/proyecto de título de los integrantes]* que contiene el concepto tecnológico formulado (modelo de datos de accesibilidad y función de costo del grafo peatonal); el **prototipo navegable en Figma** que materializa el concepto y los flujos de la app; y la **investigación de usuarios** (entrevistas y protocolo de validación con perfiles de movilidad reducida) que sustenta los requisitos. Estos documentos se adjuntan como anexos de respaldo.

**vii. Justificación de los recursos solicitados a ANID.** Los recursos se destinan a transformar el resultado de investigación en un MVP funcional validado en terreno: gastos en personal para el desarrollo del motor de ruteo y la integración del grafo; operación para servicios cloud, cartografía, validación con usuarios y protección de PI; y equipamiento de desarrollo y prueba. El detalle y la pertinencia de cada ítem se desarrollan en el punto **viii (Plan de trabajo, presupuesto y fuentes de financiamiento)**.

---

## c. Nivel de desarrollo tecnológico del proyecto (Ver Anexo 2)

La propuesta es de base científico-tecnológica con un **nivel de entrada igual o superior a TRL 2** (requisito mínimo de admisibilidad). El concepto tecnológico está formulado: existe un modelo de datos de accesibilidad y una función de costo multicriterio para la red peatonal, derivados de 🔧 *[la memoria/proyecto de título]* y respaldados en literatura validada de *geocrowdsourcing* de accesibilidad y *wayfinding* de diseño universal (ver Referencias). La acreditación del nivel se respalda con documentación técnica adjunta en la postulación: memoria/proyecto de título, prototipo navegable en Figma, e investigación de usuarios.

> 🔧 **Importante:** si su memoria solo formuló el concepto (sin implementar ni probar el algoritmo), el TRL de entrada es **2** ("Concepto tecnológico formulado"). Si ya realizaron pruebas analíticas o a escala de laboratorio del algoritmo, pueden declarar **TRL 3** ("Prueba de concepto experimental"). Declaren únicamente el nivel que puedan defender con evidencia ante el panel.

---

## i. Resumen ejecutivo

**Red Amiga** es una aplicación de navegación urbana diseñada específicamente para personas con movilidad reducida, que calcula y entrega **rutas peatonales accesibles** considerando barreras arquitectónicas, pendientes, tipo de superficie, presencia de rampas/ascensores y otros atributos de accesibilidad que los navegadores tradicionales (Google Maps, Waze) ignoran por completo.

La propuesta parte de una premisa: *la discapacidad no es un atributo de la persona, sino una situación generada por un entorno mal diseñado*. Red Amiga ataca esa situación desde dos frentes: (1) un **motor de ruteo multicriterio** que optimiza la trayectoria según el perfil de cada usuario (silla de ruedas manual o eléctrica, bastón/andador, baja visión), y (2) una **plataforma de participación ciudadana** que permite reportar en tiempo real obstáculos e incumplimientos normativos (rampas con pendiente excesiva, veredas angostas, señalización ausente), generando una base de datos viva de accesibilidad urbana que también sirve como insumo de fiscalización ante las autoridades.

La base científico-tecnológica proviene de 🔧 *[la memoria/proyecto de título de los integrantes]*, donde se desarrolló el modelo de datos de accesibilidad y el algoritmo de costo asociado a la red peatonal, alimentándose de literatura validada en *geocrowdsourcing* de accesibilidad y *wayfinding* de diseño universal. El proyecto VIU busca llevar este resultado de investigación desde un prototipo funcional de concepto (TRL 3 🔧) hasta un piloto validado en condiciones reales en una comuna de Santiago (TRL 5–6), con un modelo de negocio probado con usuarios y municipios.

El financiamiento solicitado a ANID es de hasta **$36.000.000**, con un aporte de la institución beneficiaria de al menos el 20% del costo total, en un plazo de ejecución de 12 meses.

---

## ii. Problema, necesidad u oportunidad (impacto, magnitud y vigencia)

**El problema.** En Chile, las personas con movilidad reducida no cuentan con ninguna herramienta de navegación que les indique si una ruta es efectivamente transitable para ellas. Planificar un trayecto cotidiano —ir al trabajo, a un centro de salud, a un parque— implica incertidumbre, dependencia de terceros y, con frecuencia, la imposibilidad de completar el recorrido por una rampa inexistente, una vereda rota o un ascensor fuera de servicio. El resultado es la exclusión de la vida urbana.

**Magnitud (datos III ENDISC 2022).**
- El **17% de la población chilena de 2 años y más** vive con alguna discapacidad: **3.291.602 personas**.
- Entre la población adulta (18+), el **17,6% presenta discapacidad: 2.703.893 personas** (5,9% leve a moderada y 11,1% severa).
- En la **Región Metropolitana**, donde se ejecutará el piloto, la prevalencia adulta llega al **18,3%, cerca de 1.400.000 personas**.
- El **57,7%** de las personas adultas con discapacidad se encuentra en situación de dependencia, y solo el **51%** participa del mercado laboral (vs. 71,1% de las personas sin discapacidad) —brecha que la falta de movilidad autónoma agrava directamente.

A esta población hay que sumar el universo más amplio de **movilidad reducida transitoria o circunstancial**: personas mayores (la prevalencia de discapacidad sube a 32,6% en mayores de 60), personas con lesiones temporales, embarazadas, y cuidadores con coches de bebé. El mercado direccionable es, por tanto, sustancialmente mayor que la cifra de discapacidad permanente.

**Vigencia.** El problema está plenamente vigente y con marco normativo que lo respalda: la **Ley 20.422** (igualdad de oportunidades e inclusión), la **OGUC y el DS 50** (accesibilidad universal obligatoria en el espacio público) fijan estándares técnicos exigibles —ancho libre mínimo de rampa 0,90 m, pendiente máxima 8–12%, pendiente transversal ≤ 2%, superficies antideslizantes, áreas de giro 0,90 × 1,20 m— que en la práctica se incumplen masivamente sin un mecanismo ciudadano de detección y fiscalización. Existe, además, una brecha de mercado: las soluciones globales (Wheelmap, AccessNow) mapean accesibilidad de *lugares* pero no resuelven el **ruteo punto a punto**, y los navegadores masivos no contemplan accesibilidad.

**La oportunidad de negocio** es doble: (a) un producto de alto valor social para una población desatendida y en crecimiento por envejecimiento poblacional, y (b) una base de datos de accesibilidad urbana georreferenciada y actualizada con valor para municipios, MINVU, inmobiliarias y operadores de transporte que deben acreditar cumplimiento normativo.

---

## iii. Descripción de la solución, mérito y justificación científico-tecnológica

**La solución.** Red Amiga es una app móvil con cuatro componentes integrados:

1. **Motor de rutas accesibles personalizadas:** algoritmo de ruteo sobre una red peatonal (grafo) enriquecida con atributos de accesibilidad, que asigna un *costo* a cada segmento en función de pendiente, ancho, tipo de superficie, presencia de rampa/ascensor, obstáculos y contaminación sonora, y optimiza la trayectoria según el perfil del usuario. No busca la ruta más corta, sino la de **menor barrera arquitectónica** transitable para ese perfil.
2. **Mapa de accesibilidad:** capa visual que muestra rampas, ascensores, superficies aptas y puntos críticos.
3. **Alertas ciudadanas en tiempo real:** los usuarios reportan obstáculos, reparaciones o peligros que actualizan inmediatamente el grafo (vía en mal estado, ausencia de elemento básico, estructura en mantenimiento, etc.).
4. **Plataforma de fiscalización:** los reportes que detectan incumplimiento normativo (p. ej. una rampa que excede el 12% de pendiente que fija el DS 50) se sistematizan como insumo de seguimiento ante autoridades.

**Mérito y justificación científico-tecnológica.** El núcleo de innovación no es la interfaz, sino **cómo se construye y mantiene actualizado el grafo de accesibilidad**. La literatura demuestra que el dato de accesibilidad urbana es altamente dinámico y costoso de levantar centralizadamente, y que el *geocrowdsourcing* —combinar capas oficiales con reportes ciudadanos validados— es la estrategia más viable para entornos cambiantes (Qin et al., 2015; Qin, Curtin & Rice, 2017; Riganova, Balata & Mikovec, 2017; Witzel et al., 2023). El aporte de Red Amiga es integrar ese modelo de datos con un **algoritmo de ruteo multicriterio basado en principios de diseño universal de *wayfinding*** (Fogli, Arenghi & Gentilin, 2019) y con una arquitectura móvil de reporte validada para usuarios con discapacidad (Sweidan, Darabkh & Afaneh, 2025).

El mérito frente a la competencia: a diferencia de Wheelmap y AccessNow (mapeo de puntos) y de Google Maps/Waze (ruteo sin variable de accesibilidad), Red Amiga es el único que combina **ruteo punto a punto + criterio de accesibilidad + actualización ciudadana + fiscalización normativa** anclada al marco chileno (OGUC/DS 50).

🔧 *Ajusta este apartado para que el "resultado de investigación" descrito coincida exactamente con lo que efectivamente desarrollaron en su memoria/tesis: si solo formularon el concepto y validaron requisitos con usuarios, la base es la metodología de levantamiento y el modelo de datos; si ya implementaron y probaron el algoritmo, eso eleva el TRL.*

---

## iv. Tamaño del segmento de mercado, clientes y/o usuarios

**Usuarios (lado de la demanda B2C):**
- **Segmento núcleo:** personas con discapacidad física/movilidad reducida. Tomando los 2,7 millones de adultos con discapacidad en Chile y aplicando una estimación conservadora de prevalencia de discapacidad física/motora, el segmento directo se cuenta en **cientos de miles de personas a nivel nacional**.
- **Mercado inicial (piloto):** Región Metropolitana, ~1,4 millones de personas adultas con discapacidad; foco en 🔧 *[1–2 comunas piloto]*.
- **Segmento ampliado:** personas mayores (32,6% de prevalencia sobre 60 años), movilidad reducida transitoria y cuidadores con coches.

**Clientes (lado del ingreso, B2B/B2G):** el modelo no monetiza al usuario final vulnerable, sino el **valor del dato y de la herramienta de cumplimiento**:
- **Municipios** (auditoría y priorización de inversión en accesibilidad).
- **MINVU / SERVIU y SENADIS** (cumplimiento OGUC/DS 50, política pública).
- **Operadores de transporte, inmobiliarias, retail y mall** que deben acreditar accesibilidad.
- **Universidades y hospitales** (campus/recintos accesibles).

**Dimensionamiento (formato TAM/SAM/SOM — completar con tu investigación):**
- **TAM:** mercado nacional de accesibilidad urbana + datos de movilidad 🔧.
- **SAM:** municipios urbanos + población con discapacidad de regiones metropolitanas 🔧.
- **SOM (3 años):** 🔧 *[N comunas + N usuarios activos]*.

🔧 *Reemplaza las cifras de TAM/SAM/SOM por estimaciones propias; el panel valora que estén calculadas, no solo declaradas.*

---

## v. Ventajas o atributos de la tecnología/producto para el segmento

1. **Ruteo con criterio de accesibilidad real**, no solo mapeo de lugares (diferencia clave frente a Wheelmap/AccessNow).
2. **Personalización por perfil** (silla manual/eléctrica, andador/bastón, baja visión): la misma calle puede ser ruta válida para un perfil y barrera para otro.
3. **Dato siempre vigente** gracias al modelo de geocrowdsourcing: el grafo se actualiza con reportes ciudadanos, capturando el carácter dinámico del espacio público (un ascensor que se descompone hoy cambia la ruta hoy).
4. **Anclaje normativo chileno:** las alertas se evalúan contra los estándares del DS 50/OGUC, convirtiendo cada reporte en evidencia de (in)cumplimiento.
5. **Doble valor:** producto de navegación para el usuario + base de datos de fiscalización para clientes institucionales.
6. **Accesibilidad de la propia interfaz** (modo oscuro de alto contraste validado con usuarios de baja visión), un atributo de diseño que la competencia masiva no prioriza.
7. **Efecto de red:** cada usuario que reporta mejora la utilidad para todos los demás (barrera de entrada para competidores).

---

## vi. Impactos económicos, sociales y/o medioambientales esperados

**Sociales (impacto principal):**
- Mayor **autonomía y movilidad**: más salidas semanales al espacio público sin dependencia de terceros.
- **Reducción del tiempo y la carga cognitiva/estrés** asociados a planificar trayectos inciertos.
- **Mayor participación** en la vida laboral, educativa y social — incidiendo en la brecha de empleo (51% vs 71,1%).
- **Datos para política pública:** evidencia georreferenciada para priorizar inversión municipal en accesibilidad.

**Económicos:**
- Generación de una **EBCT** con ingresos por servicios de datos y cumplimiento a clientes B2B/B2G.
- Ahorro para municipios al priorizar inversión donde el impacto en transitabilidad es mayor.
- Potencial de empleo inclusivo (validadores/reportadores).

**Medioambientales:**
- Fomento de la **movilidad peatonal y activa** frente al uso de vehículo particular, al hacer transitables a pie trayectos hoy evitados.

---

## vii. Resultados según niveles de madurez (Anexo 2), estrategia de desarrollo y plan de validación

> **Posición de partida (autodiagnóstico IRL):** 🔧 *ajustar a la realidad del equipo.*
> - **TRL (tecnología):** entrada **3** (prueba de concepto / prototipo funcional clickeable), meta **5–6** (validado en entorno relevante / piloto).
> - **CRL (cliente):** entrada **3–4** (problema confirmado con usuarios, segmentación inicial), meta **6**.
> - **BRL (negocio):** entrada **2–3** (concepto y Canvas inicial), meta **5**.
> - **IPRL (PI):** entrada **2** (formas de PI identificadas, marca), meta **4–5**.
> - **TMRL (equipo):** entrada **4–5** (equipo fundador con roles), meta **6**.
> - **FRL (financiamiento):** entrada **3** (soft funding VIU asegurado), meta **5–6**.

### a. Tecnologías de producto, proceso o servicio
- **Resultado:** MVP funcional de la app con motor de ruteo accesible operativo sobre el grafo de la comuna piloto, mapa de accesibilidad y módulo de alertas.
- **Estrategia de desarrollo:** del prototipo Figma → MVP funcional → piloto en terreno.
- **Plan de validación:** pruebas de transitabilidad real de rutas calculadas vs. recorrido efectivo de usuarios (silla de ruedas, andador, baja visión); medición de tasa de éxito de trayecto y desvíos.
- *Medio de verificación:* MVP desplegado + informe de pruebas en entorno relevante (eleva a TRL 5–6).

### b. Estrategia de propiedad intelectual
- **Resultado:** registro de **marca comercial "Red Amiga"**; estudio de *freedom to operate*; protección del modelo de datos/algoritmo vía **secreto industrial y derecho de autor de software**.
- *Medio de verificación:* solicitud de registro de marca presentada ante INAPI; informe de estrategia de PI elaborado con la OTL.

### c. Validación del modelo de negocio
- **Resultado:** modelo de negocio (Canvas) validado con al menos 🔧 *[1–2 municipios]* y entrevistas a clientes B2B/B2G; primera versión de modelo de ingresos.
- **Plan de validación:** cartas de interés / pilotos pagados o no pagados con municipios; *customer discovery* con usuarios y clientes institucionales.
- *Medio de verificación:* cartas de intención, actas de reuniones, modelo de ingresos documentado (eleva BRL a 5).

### d. Estrategia de financiamiento
- **Resultado:** plan de financiamiento post-VIU con fuentes identificadas (Corfo SSAF/Startup, capital semilla, fondos de innovación pública/municipal).
- *Medio de verificación:* plan de financiamiento y *pitch* de inversión ensayado; postulación a fuente complementaria iniciada.

### e. Equipo de trabajo y desarrollo de capacidades
- **Resultado:** equipo fundador con roles definidos (dirección, desarrollo, negocios/UX accesibilidad), reforzado con un desarrollador y mentoría de negocios.
- *Medio de verificación:* acuerdo de socios/roles firmado; incorporación de capacidades técnicas críticas.

### f. Demostración de valor frente a usuarios/clientes
- **Resultado:** sesiones de demostración del MVP con usuarios reales y presentación a clientes institucionales; *workshop* de difusión.
- **Plan de validación:** protocolo cualitativo moderado 1:1 con técnica *Think-Aloud* (30–45 min) sobre el prototipo enlazado en Figma desde celular, con tres perfiles (silla de ruedas; andador/bastón; baja visión moderada para validar contrastes del modo oscuro). Métricas: usabilidad (tiempo por tarea, tasa de error, satisfacción), carga cognitiva/estrés percibido y observación etnográfica en entorno natural.
- *Medio de verificación:* informe de resultados de validación con usuarios + registro de la actividad de difusión.

---

## viii. Plan de trabajo, presupuesto y fuentes de financiamiento

### Plan de trabajo (Carta Gantt resumida, 12 meses) 🔧

| Hito | Meses | Resultado clave |
|---|---|---|
| H1. Modelo de datos y grafo de accesibilidad de la comuna piloto | 1–3 | Grafo enriquecido + integración de capas oficiales |
| H2. Desarrollo del MVP funcional (ruteo + mapa + alertas) | 2–6 | App funcional desplegada (TRL 4→5) |
| H3. Estrategia y registro de PI (marca + software) | 3–5 | Marca solicitada en INAPI; estrategia PI |
| H4. Validación con usuarios (Think-Aloud, 3 perfiles) | 5–8 | Informe de usabilidad y ajustes |
| H5. Piloto en terreno y validación de transitabilidad | 7–10 | Piloto validado en entorno real (TRL 5–6) |
| H6. Validación del modelo de negocio con municipios | 6–11 | Cartas de interés + modelo de ingresos |
| H7. Plan de financiamiento y difusión / cierre | 10–12 | Plan post-VIU + workshop + informe final |

### Presupuesto (referencial — máximo ANID $36.000.000) 🔧

| Ítem | Aporte ANID | Detalle |
|---|---|---|
| Gastos en personal | ~$20.000.000 | Director(a)/estudiante (hasta $500.000/mes); desarrollador(a); profesor(a) guía (hasta $200.000/mes) |
| Equipamiento | ~$3.000.000 | Equipos de desarrollo, dispositivos de prueba, créditos cloud |
| Operación | ~$10.000.000 | Hosting/servicios cloud, cartografía/datos, gastos de validación con usuarios, PI/marca, asesoría UX-accesibilidad y legal, difusión |
| Administración superior | ~$3.000.000 | ≤ 15% del subsidio ANID |
| **Total ANID** | **~$36.000.000** | |

**Aporte de la institución beneficiaria (≥ 20% del costo total):** 🔧 valorizado en horas de mentor de negocios, uso de laboratorios e infraestructura, gestión de la OTL, difusión institucional y horas del profesor guía. Si el costo total es ~$45M, el aporte de la beneficiaria debe ser ≥ ~$9M.

**Fuentes de financiamiento:** subsidio ANID-VIU (principal) + aporte valorizado de la beneficiaria + financiamiento complementario futuro (Corfo, capital semilla) identificado en la estrategia FRL.

---

## ix. Equipos técnicos y financieros de la institución beneficiaria que darán soporte

🔧 *Completar con los nombres y unidades reales de tu institución.*

- **Dirección del proyecto:** 🔧 *[estudiante/egresado/a director(a)]* — gestión técnica y financiera ante ANID.
- **Investigador(a) asociado(a)/profesor(a) guía:** 🔧 *[docente]* — soporte científico-tecnológico (mín. 20 h/mes), con trayectoria en proyectos de I+D en los últimos 5 años.
- **Mentor(a) de negocios:** 🔧 *[mentor de la incubadora / OTL / sector productivo]* — aporte valorizado, no se contrata con recursos ANID.
- **Oficina de Transferencia y Licenciamiento (OTL) / Incubadora:** 🔧 *[nombre]* — gestión de PI, modelo de negocio y vinculación con el ecosistema.
- **Soporte financiero-contable:** 🔧 *[profesional del área de finanzas/dirección de investigación]* — rendición de cuentas (SISREC), gestión presupuestaria y seguimiento del convenio ante ANID.
- **Capacidades e infraestructura puestas a disposición:** laboratorios/espacios de trabajo, equipamiento existente, licencias de software, y apoyo de difusión institucional.

---

## e. Convenio de Propiedad Intelectual entre estudiante(s), institución beneficiaria e investigador asociado (pág. 11)

Las bases exigen suscribir un convenio de PI —entregable hasta 30 días corridos tras la comunicación de la adjudicación— firmado por el/los estudiante(s), el/la profesor(a) guía, el/la investigador(a) asociado(a) y la institución beneficiaria. Debe establecer:

- **Titularidad de la PI:** la propiedad intelectual de los resultados se comparte en **al menos un tercio (1/3) con el/la director(a) del proyecto** (estudiante); si hubo más de un estudiante en la memoria/tesis, ese tercio puede repartirse entre ellos.
- **Condiciones de uso y explotación:** derecho de uso preferente de los estudiantes participantes por al menos 5 años una vez que la tecnología alcance TRL 7 o superior, y derecho preferente indefinido vencido ese plazo.
- **Confidencialidad:** cláusula de resguardo de la información generada durante la ejecución; acuerdo de confidencialidad adicional firmado por el/la mentor(a) y la beneficiaria.
- **Regalías y beneficios comerciales:** mecanismo de distribución entre ejecutores, institución beneficiaria y demás partes.
- **Continuidad:** hitos críticos, responsabilidades y hoja de ruta para dar continuidad al emprendimiento una vez cerrado el proyecto (requisito de cierre, incorporado al informe final).

> 🔧 Para el examen basta describir estos compromisos; el convenio firmado se entrega recién en caso de adjudicación. La gestión de la PI ante INAPI es responsabilidad de la OTL de la institución beneficiaria, no de ANID.

---

### Referencias (base científico-tecnológica)
- Fogli, Arenghi & Gentilin (2019). *A universal design approach to wayfinding and navigation.*
- Qin, Curtin & Rice (2017). *Pedestrian network repair with spatial optimization models and geocrowdsourced data.*
- Qin et al. (2015). *Geocrowdsourcing and accessibility for dynamic environments.*
- Riganova, Balata & Mikovec (2017). *Crowdsourcing of accessibility attributes on sidewalk-based geodatabase.*
- Sweidan, Darabkh & Afaneh (2025). *A novel mobile Android application for facilitating wheelchair users' access to public buildings in urban environments.*
- Witzel et al. (2023). *On-site and remote crowdsourcing of accessibility data for people with mobility impairments: Zurich's District 1.*

*Cifras de población: III Estudio Nacional de la Discapacidad (III ENDISC 2022), SENADIS / Ministerio de Desarrollo Social y Familia.*
