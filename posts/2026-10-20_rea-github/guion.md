# Reel: "¿El repo que copia cualquier app?" (REA)

- **Formato:** Reel / Short / TikTok 1080×1920
- **Duración estimada:** 30 s (~95 palabras de voz)
- **Gancho elegido:** "Dicen que este repo de GitHub copia cualquier app. No es tan así."
- **Ángulo:** desmentir el hype con datos verificados y dejar abierto un riesgo ("hay algo que casi nadie cuenta") que se revela al final, para que se queden hasta el cierre.
- **CTA único:** comentar "REA" para recibir el link oficial.

---

## Guion

| Tiempo | Visual | Texto en pantalla | Voz |
|---|---|---|---|
| 0–3 s | Cara a cámara, plano medio, ladrillo + camisa Grafa. Arranca hablando, sin intro. Al decir "No es tan así", corte seco a plano más cerrado. | **¿COPIA CUALQUIER APP?** | "Dicen que este repo de GitHub copia cualquier app. No es tan así." |
| 3–7 s | Pantalla de github.com/morluto/rea. Zoom rápido al contador de estrellas. | **REA · +300 MIL ESTRELLAS** | "Se llama REA y tiene más de 300 mil estrellas. Pero hay un riesgo que casi nadie cuenta." |
| 7–13 s | Animación low-poly: [CLAUDE CODE] → [REA] → [APP CERRADA]. La app se abre en triángulos y muestra piezas por dentro. | **LE DA RAYOS X A LA IA** | "Le da herramientas a una IA como Claude Code para mirar un programa por dentro, sin su código, y explicarte cómo funciona." |
| 13–18 s | Cara a cámara. Aparece "CLONA APPS" y lo cruza un tachado en diagonal. Abajo, chico: "Solo software propio o con permiso". | **NO CLONA APPS SOLO** | "Pero no clona apps de un botón: con programas grandes se pierde y a veces inventa." |
| 18–25 s | Pantalla partida en diagonal: arriba "morluto/rea ✔" en celeste, abajo una copia genérica "✖ COPIA" con etiqueta "EJEMPLO". Golpe de sonido al entrar. | **OJO: COPIAS CON VIRUS** | "Ahora, el riesgo: circulan copias truchas del repo, y se reportó una con virus. El único oficial es morluto barra rea." |
| 25–28 s | Cara a cámara, mirando directo. | **COMENTÁ "REA"** | "Comentá REA y te paso el link oficial." |
| 28–30 s | Fondo low-poly, firma animada. | **Bruno Jerke.** | — |

## Texto para teleprompter

> Dicen que este repo de GitHub copia cualquier app. No es tan así.
> Se llama REA y tiene más de 300 mil estrellas. Pero hay un riesgo que casi nadie cuenta.
> Le da herramientas a una IA como Claude Code para mirar un programa por dentro, sin su código, y explicarte cómo funciona.
> Pero no clona apps de un botón: con programas grandes se pierde y a veces inventa.
> Ahora, el riesgo: circulan copias truchas del repo, y se reportó una con virus. El único oficial es morluto barra rea.
> Comentá REA y te paso el link oficial.

## Notas de edición

- **Ritmo:** corte cada 2–3 s, sin aire entre frases. Jump cuts en las tomas a cámara. El primer cuadro ya tiene que tener texto y boca en movimiento.
- **Palabras en celeste `#2F8BBD`:** "COPIA", "REA", "300 MIL", "RAYOS X", "OFICIAL", "COMENTÁ".
- **Subtítulos:** General Sans Medium, palabra por palabra, resaltando en celeste las palabras clave de la voz.
- **Transiciones:** cortes en diagonal entre cara y pantalla. Tachado de "CLONA APPS" en diagonal, filoso.
- **Fondo:** low-poly azul en la animación del diagrama y en la firma.
- **Sonido:** beat tech con bajo marcado. Bajarlo en 13–18 s ("pero no clona…") y golpe seco al entrar "OJO: COPIAS CON VIRUS".
- **Audio:** filtros aprobados del CLAUDE.md (limpieza sobre la toma completa → cortar → `loudnorm`).

## Qué grabar

- **A cámara:**
  - Gancho (0–3 s): 3 versiones con distinta energía; elegimos la más natural.
  - "Pero no clona apps…" (13–18 s).
  - Cierre "Comentá REA…" (25–28 s).
  - Opcional: todo el texto de corrido en una sola toma, para tener cobertura.
- **Pantalla:** github.com/morluto/rea, scroll del README + contador de estrellas (grabar en 1080×1920 o recortar después).
- **Para `editor-marca`:**
  1. Diagrama Claude Code → REA → app que se abre en triángulos.
  2. Tachado en diagonal sobre "CLONA APPS".
  3. Split diagonal oficial vs. copia (la copia genérica, sin nombre real, con etiqueta "EJEMPLO").
  4. Tarjeta final con firma.
- **No mostrar** una instalación ni decir "lo probé" salvo que lo pruebes de verdad antes.

---

## Investigación (verificado al 20/10/2026)

- **Qué es:** REA = *Reverse Engineer Anything*. Open source (MIT), funciona como servidor MCP: le da a agentes como Claude Code, Codex, Cursor o Gemini CLI herramientas de ingeniería inversa para analizar programas sin su código fuente, y devuelve hallazgos con evidencia.
- **Qué analiza:** apps de escritorio y Electron, APK de Android, sitios web, binarios nativos, firmware, capturas de red, entre otros. Corre local.
- **Instalación:** `npx rea-agents setup` (Node.js 22.19+). Para binarios nativos necesita Ghidra, Hopper o IDA.
- **Popularidad:** el README dice que pasó las 300.000 estrellas; GitHub muestra ~344 mil estrellas y ~87 mil forks. Existe desde abril de 2026 y explotó a principios de octubre.
- **Lo que no es:** no clona apps de un botón ni recupera el código original. Con binarios de más de ~2 MB se pierde por límite de contexto y con datos ambiguos puede inventar.
- **Uso permitido:** investigación, seguridad, educación, interoperabilidad y software propio o autorizado.
- **Seguridad:** solo son oficiales `github.com/morluto/rea`, `rea.tools` y el paquete npm `rea-agents`. Se reportó una copia con instalador de Windows que Defender marcó como troyano.

## Videos que ya se publicaron

| Video | Ángulo |
|---|---|
| "Reverse Engineer Anything (REA) Explained: The Software Industry Will Never Be the Same" | Hype / "cambia todo" |
| "I Tested the Viral Reverse Engineer Anything Skill" (y variantes paso a paso) | Lo prueba y muestra tutorial |
| "REA: Reverse Engineer Anything Tutorial with Hands-on Demo" | Tutorial técnico |
| "Reverse Engineer Anything : la VÉRITÉ sur le repo qui copie tout" (francés) | "La verdad" / desmentir |
| "Reverse-engineer any feature with Claude Code (the right way)" #Shorts | Short: cómo usarlo bien |
| "Probé el Repo Viral que Copia CUALQUIER App: REA" (Benjamín Cordero, español) | Prueba + "copia cualquier app" |

En inglés está saturado de tutoriales y hype; en español casi no hay formato corto y casi nadie habla de las copias con virus.

## Fuentes

- Repo oficial: https://github.com/morluto/rea
- https://laprensaia.com/ingenieria-inversa-con-ia-rea-reverse-engineer-anything/
- https://regestio.com.ar/novedades/rea-ingenieria-inversa-con-agentes-de-ia
- https://nachoconesa.com/blog/rea-reverse-engineer-anything-ia
- https://pasqualepillitteri.it/en/news/23845/rea-reverse-engineer-anything-github-true-false
- https://apidog.com/blog/what-is-rea-reverse-engineer-anything/
