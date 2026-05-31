# Usability Report



<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRF017nhV-TFmNER2OM8UbXtdN6xwAKBYrv0i6onNfKu6Yn0BV0RK6aiOroeXl73LSY-B0&usqp=CAU" alt="usability Download png" style="height:150px" />
# Evaluación de usabilidad del proyecto Remake Champions Burger
**Fecha:** Mayo 2026

![Proyecto](img/4a_ABTest.png)

**Enlace al repositorio:** https://github.com/DIU3-Duros/UX_CaseStudy

---

## Realizado por

Informe elaborado por el equipo **DIU1_SP** (Sergio Sánchez González y Paula Cobos González), del grupo de prácticas de Diseño de Interfaces de Usuario 2025/26 de la Universidad de Granada. Es nuestra primera experiencia realizando un informe de usabilidad formal sobre el trabajo de otro equipo. Durante el proceso hemos aplicado las metodologías aprendidas a lo largo del curso — A/B Testing, cuestionario SUS y Eye Tracking con GazeRecorder — lo que nos ha permitido contrastar nuestro propio diseño con el de los compañeros y obtener una visión más crítica y objetiva sobre ambos proyectos.

---

## 1. Resumen Ejecutivo

**Objetivo:** Evaluar la usabilidad del prototipo web *Remake Champions Burger*, desarrollado por el equipo DIU3.Clenchaos, con el fin de identificar los principales problemas de interacción y comparar su experiencia de usuario frente al Caso A (Osaka Bowl & Roll) mediante pruebas controladas.

**Metodología:** Se realizaron pruebas de A/B Testing con tareas guiadas y mis-click test sobre ambos prototipos, complementadas con el cuestionario SUS aplicado a 10 usuarios y un análisis de Eye Tracking con GazeRecorder sobre 3 pantallas del Caso B.

**Principales hallazgos:**
1. La información de contacto y ubicación del local es difícil de localizar: el 60% de los usuarios no la encontró sin ayuda.
2. Los indicadores de cola y foodtruck en la cabecera de la carta pasan completamente desapercibidos, según confirman los mapas de calor.
3. Los usuarios con baja experiencia digital tienen dificultades para identificar y usar los filtros de alérgenos, situados en una zona poco prominente de la interfaz.

**Resultado global:** La puntuación SUS media del Caso B es de **74 puntos** (*Good*), lo que lo sitúa en un nivel de usabilidad aceptable pero con margen de mejora notable, especialmente para perfiles con menor experiencia tecnológica.

---

## 2. Metodología y Reclutamiento

**Perfil de los participantes:** Se reclutaron 5 usuarios para evaluar el Caso B (Yaiza, Darío, Marcos, Tomás y Remedios), con edades comprendidas entre los 19 y los 58 años y una edad media de 30,8 años. El nivel de experiencia digital es variado: 1 usuario con Exp.TIC alta, 2 con media y 2 con baja, lo que permite detectar problemas tanto en perfiles expertos como en usuarios poco familiarizados con interfaces digitales.

**Escenario de las pruebas:** Cada usuario realizó las siguientes tareas sobre el prototipo del Caso B:
- **Tarea 1 (Mis-click Test):** Pulsar el CTA «Pedir ahora» a partir de la pantalla de inicio.
- **Tarea 2 (Tarea guiada):** Filtrar hamburguesas sin gluten y añadir una al carrito.
- **Tarea 3 (Tarea guiada):** Localizar la dirección y el contacto del local.
- **Tarea 4 (Tarea guiada):** Encontrar cómo realizar una reserva.
- **Tarea 5:** Completar el cuestionario SUS tras las pruebas anteriores.

**Herramientas utilizadas:**
- **GazeRecorder** para el análisis de Eye Tracking.
- **Hoja de cálculo SUS** (plantilla DIU19) para el cálculo de puntuaciones.
- Observación directa con toma de notas durante las pruebas de tareas.

---

## 3. Resultados del Cuestionario SUS

**Comparativa A vs. B:**

| Caso | Usuarios | Puntuación media SUS | Etiqueta |
|------|----------|----------------------|----------|
| A – Osaka Bowl & Roll | Alberto, Manu, Lucía, Sofía, Inés | **89** | Excellent |
| B – Remake Champions Burger | Yaiza, Darío, Marcos, Tomás, Remedios | **74** | Good |

**Desglose por ítems — Caso B:**

| # | Ítem | Puntuación media | Observación |
|---|------|-----------------|-------------|
| 2 | Encontré el website innecesariamente complejo | 2,4 | Peor valorado; los usuarios con baja Exp.TIC perciben mayor complejidad |
| 4 | Creo que necesitaría apoyo de un experto | 2,6 | Especialmente alto en Tomás y Remedios |
| 8 | Encontré el website muy grande al recorrerlo | 3,0 | Indica que el scroll y la extensión de la carta desorientan |
| 10 | Necesito aprender muchas cosas antes de manejarlo | 2,8 | Refleja la curva de aprendizaje percibida en los filtros |

**Valoración numérica:** El Caso B obtiene 74 puntos, por encima del umbral de aceptabilidad (68), pero claramente por debajo del Caso A (89). La brecha es más pronunciada en los ítems relacionados con complejidad percibida y aprendizaje, lo que apunta directamente a los filtros y a la localización de información secundaria como los principales focos de mejora.

---

## 4. Análisis de Eye Tracking

**Pantallas evaluadas:** Carta con filtros, listado de hamburguesas y sección FAQ/Contacto.

**Mapas de calor — hallazgos por pantalla:**

**Pantalla 1 – Carta con filtros:**
Los usuarios concentran la mirada en el área del primer producto visible (La Clásica Brasa) y en los filtros de tipo (Clásica, Picante, Vegana, Sin gluten). Los indicadores de «Cola actual», «Foodtruck» y «Calidad» situados en la cabecera prácticamente no reciben fijaciones, siendo una zona de silencio total pese a ser una funcionalidad diferenciadora del proyecto.

**Pantalla 2 – Listado de hamburguesas:**
La atención se concentra en el nombre, la descripción y el precio del primer plato. El botón «+ Pídela» del primer ítem recibe buenas fijaciones, pero los platos inferiores son casi ignorados. No se observa un patrón de scroll natural, lo que indica que la interfaz no invita a explorar más allá del primer elemento visible.

**Pantalla 3 – FAQ y Contacto:**
Las fijaciones se dirigen a las preguntas del acordeón y a la sección de contacto del footer (dirección y email), lo que confirma que los usuarios buscaban activamente esa información. El hecho de que lleguen al footer después de explorar toda la pantalla indica que la ruta para encontrar el contacto no es inmediata.

**Zonas de silencio identificadas:**
- Badges de cola y foodtruck en la cabecera de la carta.
- Filtros de exclusión de alérgenos (lado derecho: Gluten, Lactosa, Huevo).
- Navegación superior (Carta, Sobre nosotros, Foodtruck, FAQ) durante la exploración de la carta.

**Hallazgo clave:** El 100% de los usuarios ignoró los indicadores de cola y foodtruck en la cabecera, a pesar de ser uno de los elementos más innovadores del diseño. Su posición y tamaño no son suficientes para competir visualmente con la imagen y el nombre del primer plato.

---

## 5. Auditoría de Accesibilidad

La auditoría se realizó de forma manual a partir de la inspección del prototipo y los resultados de las pruebas de usuario, sin acceso a herramientas automáticas como Lighthouse o WAVE al tratarse de un prototipo Figma sin despliegue web completo.

**Principales barreras detectadas:**

| Barrera | Impacto | Afecta a |
|---------|---------|----------|
| Bajo contraste entre texto y fondo oscuro en algunas zonas de la carta | Alto | Usuarios con baja visión |
| Filtros de alérgenos sin etiqueta accesible clara | Medio | Usuarios con lectores de pantalla |
| Ausencia de indicaciones de error o confirmación en el carrito | Medio | Usuarios con dificultades cognitivas |
| Información de contacto solo en footer, sin ruta alternativa | Alto | Usuarios mayores o con baja Exp.TIC |
| Badges informativos (cola, foodtruck) sin texto alternativo visible | Bajo | Usuarios con discapacidad visual |

---

## 6. Conclusiones y Recomendaciones

Remake Champions Burger es un proyecto con una propuesta de valor clara y una identidad visual coherente. No obstante, las pruebas revelan oportunidades de mejora concretas que, de abordarse, podrían elevar su puntuación SUS por encima de 85.

| Prioridad | Hallazgo | Recomendación de mejora |
|-----------|----------|-------------------------|
| Alta (Crítica) | Información de contacto y ubicación no localizable por el 60% de los usuarios | Añadir un acceso directo a «Contacto» en la barra de navegación principal, visible en todas las pantallas |
| Alta (Crítica) | Indicadores de cola y foodtruck ignorados por el 100% de los usuarios en el eye tracking | Reposicionarlos junto a cada tarjeta de hamburguesa o rediseñarlos con mayor contraste y tamaño |
| Media | Filtros de alérgenos poco identificables por usuarios con baja Exp.TIC | Unificar todos los filtros en una sola zona superior, con etiquetas más grandes y un botón de «Filtrar» explícito |
| Media | Scroll no intuitivo en el listado de carta | Mostrar parcialmente el segundo plato para indicar que hay más contenido; añadir indicador visual de desplazamiento |
| Baja | Ausencia de feedback al añadir un producto al carrito | Mostrar un contador animado en el icono del carrito al pulsar «+ Pídela» para confirmar la acción al usuario |
| Baja | Bajo contraste en texto sobre fondo oscuro en algunas zonas | Revisar la paleta de colores siguiendo los criterios de contraste WCAG 2.1 AA (ratio mínimo 4,5:1) |


