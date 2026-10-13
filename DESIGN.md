---
version: alpha
name: jonmircha
description: Moderna, enérgica y docente — naranjas vibrantes sobre carbones profundos, minimalista y de alto contraste.
colors:
  primary: "#E7562E"
  primary-hover: "#D94D1F"
  primary-active: "#C63C0A"
  secondary: "#E7762E"
  tertiary: "#0088CC"
  tertiary-light: "#73CFFA"
  surface: "#FCFCFC"
  surface-alt: "#F7F7F7"
  on-surface: "#202225"
  neutral: "#808080"
  coal-dark: "#2B3A42"
  coal-medium: "#20252C"
  coal-deep: "#202B38"
  muted-bg: "#EEEEEE"
  disabled: "#CCCCCC"
  white: "#FFFFFF"
  # [REVIEW] no definido en DESIGN.docx — valor razonable de Material para estados de error:
  error: "#B00020"
typography:
  display:
    fontFamily: Raleway Black
    fontSize: 40px
    fontWeight: 900
    lineHeight: 48px
  h1:
    fontFamily: PT Sans
    fontSize: 40px
    fontWeight: 700
    # [REVIEW] line-height no especificado para h1 — asumido igual que display:
    lineHeight: 48px
  h2:
    fontFamily: Raleway Black
    fontSize: 40px
    fontWeight: 900
    # [REVIEW] line-height no especificado para h2 — asumido:
    lineHeight: 48px
  h3:
    fontFamily: PT Sans
    fontSize: 16px
    fontWeight: 700
    # [REVIEW] line-height no especificado para h3 — asumido:
    lineHeight: 24px
  body-lg:
    fontFamily: PT Sans
    fontSize: 20px
    fontWeight: 400
    lineHeight: 30px
  body-list:
    fontFamily: Raleway
    fontSize: 20px
    fontWeight: 400
    # [REVIEW] line-height no especificado — asumido:
    lineHeight: 30px
  body-sm:
    fontFamily: Raleway
    fontSize: 16px
    fontWeight: 400
    # [REVIEW] line-height no especificado — asumido:
    lineHeight: 24px
  button-label:
    fontFamily: Raleway
    fontSize: 19.216px
    fontWeight: 700
    # [REVIEW] line-height y weight exactos no especificados — asumidos:
    lineHeight: 24px
  link:
    fontFamily: PT Sans
    fontSize: 20px
    fontWeight: 400
    lineHeight: 30px
  code:
    fontFamily: Roboto Mono
    fontSize: 16px
    fontWeight: 400
    # [REVIEW] tamaño/line-height de código no especificados — asumidos:
    lineHeight: 24px
  label:
    fontFamily: PT Sans
    fontSize: 16px
    fontWeight: 700
    lineHeight: 24px
  chip:
    fontFamily: Raleway
    fontSize: 13px
    fontWeight: 400
    # [REVIEW] line-height no especificado — asumido:
    lineHeight: 16px
rounded:
  none: 0px
  sm: 8px
  md: 16px
  pill: 50px
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  2xl: 32px
  3xl: 40px
  4xl: 48px
  5xl: 92px
  6xl: 136px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.button-label}"
    rounded: "{rounded.pill}"
    padding: 12px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.white}"
    typography: "{typography.button-label}"
    rounded: "{rounded.pill}"
    padding: 12px
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.white}"
    typography: "{typography.button-label}"
    rounded: "{rounded.pill}"
    padding: 12px
  button-primary-disabled:
    backgroundColor: "{colors.disabled}"
    textColor: "{colors.neutral}"
    typography: "{typography.button-label}"
    rounded: "{rounded.pill}"
    padding: 12px
  button-icon:
    backgroundColor: "{colors.muted-bg}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 32px
  button-icon-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 32px
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.tertiary}"
    typography: "{typography.link}"
    rounded: "{rounded.none}"
    padding: 12px
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 12px
  hero:
    backgroundColor: "{colors.white}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 48px
  navbar:
    backgroundColor: "transparent"
    textColor: "{colors.on-surface}"
    typography: "{typography.link}"
    rounded: "{rounded.none}"
    height: 64px
  input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 12px
  nav-link:
    backgroundColor: "transparent"
    textColor: "{colors.on-surface}"
    typography: "{typography.link}"
    rounded: "{rounded.none}"
    padding: 8px
  social-icon:
    backgroundColor: "{colors.muted-bg}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.full}"
    size: 32px
  social-icon-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 32px
  chip:
    backgroundColor: "{colors.muted-bg}"
    textColor: "{colors.on-surface}"
    typography: "{typography.chip}"
    rounded: "{rounded.full}"
    padding: 8px
  avatar:
    backgroundColor: "{colors.muted-bg}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.full}"
    size: 200px
  contact-button:
    backgroundColor: "{colors.white}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 12px
  course-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 16px
  card-alt:
    backgroundColor: "{colors.surface-alt}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 16px
  card-dark:
    backgroundColor: "{colors.coal-medium}"
    textColor: "{colors.surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 12px
  hero-dark:
    backgroundColor: "{colors.coal-deep}"
    textColor: "{colors.surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 48px
  input-dark:
    backgroundColor: "{colors.coal-dark}"
    textColor: "{colors.surface}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.none}"
    padding: 12px
  link-dark:
    backgroundColor: "{colors.coal-deep}"
    textColor: "{colors.tertiary-light}"
    typography: "{typography.link}"
    rounded: "{rounded.none}"
    padding: 8px
---

# jonmircha Design System

## Overview

Marca moderna, enérgica y centrada en la docencia: puente entre experiencia técnica y calidez cercana. Naranjas vibrantes ({colors.primary}, {colors.secondary}) sobre carbones profundos ({colors.coal-dark}, {colors.coal-medium}, {colors.coal-deep}) transmiten confianza, creatividad y pasión por la enseñanza digital.

Filosofía minimalista: layouts limpios, mucho espacio en blanco, tipografía con propósito. Pensada para creadores y desarrolladores; respeta tiempo y carga cognitiva. En una frase: acento audaz sin abrumar, alto contraste, componentes sin ornamentación innecesaria.

Público: creadores y desarrolladores. Tono: cercano pero experto. Motivo de marca: logo del búho con degradado naranja de {colors.primary} a {colors.secondary}.

## Colors

Paleta sobre dos naranjas de marca y neutros de alto contraste.

- **Primary ({colors.primary} #E7562E):** Naranja de acción. CTA primarios, acentos, títulos y marca.
- **Secondary ({colors.secondary} #E7762E):** Naranja alterno. Énfasis puntual.
- **Primary Hover ({colors.primary-hover} #D94D1F):** Hover del botón primario.
- **Primary Active ({colors.primary-active} #C63C0A):** Pressed del botón primario.
- **Tertiary ({colors.tertiary} #0088CC):** Azul cielo. Enlaces y elementos interactivos secundarios.
- **Tertiary Light ({colors.tertiary-light} #73CFFA):** Fondos azules claros y estados hover secundarios.
- **Muted BG ({colors.muted-bg} #EEEEEE):** Fondo de botones secundarios, fantasma, chips e iconos sociales.
- **On-Surface ({colors.on-surface} #202225):** Negro casi puro. Texto principal, máximo contraste.
- **Neutral ({colors.neutral} #808080):** Texto terciario, placeholders y deshabilitados. Mínimo gris permitido para texto.
- **Coal Dark ({colors.coal-dark} #2B3A42):** Fondos profundos / texto secundario oscuro.
- **Coal Medium ({colors.coal-medium} #20252C):** Neutro oscuro para capas.
- **Coal Deep ({colors.coal-deep} #202B38):** Overlays de alto contraste.
- **Surface ({colors.surface} #FCFCFC):** Fondo base casi blanco.
- **Surface Alt ({colors.surface-alt} #F7F7F7):** Fondo alternativo suave.
- **White ({colors.white} #FFFFFF):** Máximo contraste, fondos de campos y tarjetas.
- **Disabled ({colors.disabled} #CCCCCC):** Fondo de primario deshabilitado.
- **[REVIEW] Error ({colors.error} #B00020):** No definido en el .docx. Valor Material añadido para validación de formularios. Revisar si se desea otro rojo de marca.

Combinación por defecto: {colors.primary} sobre {colors.white} / {colors.surface} para máximo contraste. Nunca naranja y azul en el mismo interactivo.

Tema claro / oscuro: el tema claro usa {colors.surface} y {colors.surface-alt} como fondos con texto {colors.on-surface}; el tema oscuro usa {colors.coal-deep}, {colors.coal-medium} y {colors.coal-dark} como fondos con texto {colors.surface}, y enlaces en {colors.tertiary-light} sobre {colors.coal-deep}.

## Typography

Tres familias con roles claros. Archivos disponibles en `assets/fonts/`: PT Sans, Raleway + Raleway Black, Roboto Mono.

- **Display ({typography.display}):** Raleway Black 40px / 48px. Titulares más importantes, uso moderado.
- **H1 ({typography.h1}):** PT Sans 700, 40px / 48px [REVIEW: line-height asumido].
- **H2 ({typography.h2}):** Raleway Black 40px [REVIEW: line-height 48px asumido].
- **H3 ({typography.h3}):** PT Sans 700, 16px / 24px [REVIEW: line-height asumido]. Subsecciones y `label` de formularios.
- **Body LG ({typography.body-lg}):** PT Sans 20px / 30px. Cuerpo base en escritorio.
- **Body List ({typography.body-list}):** Raleway 20px. Ítems de lista.
- **Body SM ({typography.body-sm}):** Raleway 16px. Texto pequeño. Mínimo permitido: 16px (18–20px en móvil para cuerpo).
- **Button Label ({typography.button-label}):** Raleway 19.216px, 700 [REVIEW: redondear a 19px en CSS].
- **Link ({typography.link}):** PT Sans 20px / 30px. Enlaces y navegación.
- **Code ({typography.code}):** Roboto Mono 16px [REVIEW: tamaño asumido, no especificado].
- **Label ({typography.label}):** PT Sans 700, 16px. Etiquetas de campo.
- **Chip ({typography.chip}):** Raleway 13px. Etiquetas píldora.

Jerarquía solo con tamaño, peso y color, nunca con opacidad (excepto título-enlace en hover a 0.8). Sin serif en jerarquía principal.

> [REVIEW] `assets/fonts/Chalet.ttf` existe en el repo pero no se menciona en el .docx. Confirmar si se conserva solo como asset o si tiene un rol tipográfico.

## Layout

Modelo: rejilla fija con ancho máximo 1440px centrado, mobile-first.

- **Escala:** unidad base {spacing.base} (8px). {spacing.xs} 4px micro, {spacing.sm} 8px, {spacing.md} 12px, {spacing.lg} 16px, {spacing.xl} 24px, {spacing.2xl} 32px, {spacing.3xl} 40px, {spacing.4xl} 48px, {spacing.5xl} 92px, {spacing.6xl} 136px.
- **Padding:** botones y campos 12–16px; tarjetas 12–24px; hero 48px horizontal / 92px vertical; secciones grandes 48–92px vertical, mínimo 92px entre zonas visuales.
- **Grid:** desktop 12 columnas; tableta 8 columnas con márgenes 48px; móvil 1 columna con márgenes 12–16px.
- **Breakpoints (del .docx §9):** móvil 320–599px (1 col, margen 12px, secciones 24px); tableta 600–1023px (2–3 cols, margen 48px, secciones 48px); escritorio 1024–1439px (3+ cols, márgenes 48–92px, secciones 92px); amplio 1440px+ (max 1440px centrado, secciones 92–136px).
- **Táctil:** interactivos mínimo 44×44px; campos mínimo 40px alto. En móvil navegación apilada/hamburguesa, tarjetas a 1 columna, titulares nunca bajo 24px.

Espacio en blanco generoso e intencional; contenido nunca apretado.

## Elevation & Depth

Diseño mayormente plano. Sombras suaves y difusas solo con interacción o apilamiento.

- **Flat (none):** tarjetas en reposo, campos, navegación. Sin sombra, jerarquía por borde ({colors.muted-bg}) y contraste.
- **Subtle:** `0 2px 4px rgba(0,0,0,0.08)` — hover de tarjetas. [REVIEW: color de sombra asumido negro; no especificado].
- **Medium:** `0 4px 12px rgba(0,0,0,0.12)` — tarjetas elevadas, modales, popovers.
- **High:** `0 8px 24px rgba(0,0,0,0.16)` — botones flotantes. Máximo permitido.
- **Scrim:** negro al 0.5 para fondo de modal.

Nunca más profundo que High. Enfasis de input por borde {colors.primary} + halo suave [REVIEW: radio/intensidad del halo no especificados — sugerido `0 0 0 4px rgba(231,86,46,0.15)`].

## Shapes

Lenguaje nítido y moderno.

- **None ({rounded.none} 0px):** defecto. Tarjetas, campos, botones de contacto, course-cards, contenedores.
- **SM ({rounded.sm} 8px):** opcional en elementos flotantes.
- **MD ({rounded.md} 16px):** reservado para componentes especiales.
- **Pill ({rounded.pill} 50px):** botón primario tipo píldora.
- **Full ({rounded.full}):** círculos perfectos — botones de icono 32×32px, avatar 200px (160px móvil) con borde 4px {colors.muted-bg}, badges, chips, iconos sociales.

No mezclar radios rectos y redondos en la misma vista.

## Components

Tokens en front-matter usan referencias (`{colors.primary}`, `{typography.button-label}`, `{rounded.pill}`). Detalle de bordes y estados en prosa.

**Botones**

- **Primary (`components.button-primary`):** fondo {colors.primary}, texto {colors.white}, {typography.button-label}, pill {rounded.pill}, padding 12px 24px. Hover → {colors.primary-hover}; active → {colors.primary-active} + encoge ligero; disabled → fondo {colors.disabled} + texto {colors.neutral}.
- **Icono circular (`components.button-icon`):** 32×32px, fondo {colors.muted-bg}, icono {colors.primary}, {rounded.full}. Hover invierte a fondo {colors.primary} + icono blanco.
- **Ghost (`components.button-ghost`):** sin fondo, texto {colors.tertiary} en {typography.link}. Hover: texto {colors.primary} + subrayado.
- Alturas mínimas: circular 32px, rectangular 40px, táctil 44×44px.

**Tarjetas y contenedores**

- **Card (`components.card`):** fondo transparente o {colors.surface}, texto {colors.on-surface} 20px PT Sans, {rounded.none}, padding horizontal 12px. Hover: sombra subtle.
- **Hero (`components.hero`):** full-width, fondo {colors.white} o {colors.surface}, padding 48px H / 92px V, max 1440px.
- **Navbar (`components.navbar`):** transparente, texto {colors.on-surface}, 64px alto, borde inferior opcional 1px {colors.muted-bg}.
- **Skill item:** icono acento {colors.primary} + texto, en tarjeta blanca con borde gris.
- **Edu/Experiencia:** borde izquierdo 4px {colors.primary}, fondo blanco, borde gris, {rounded.none}. Fila superior título/rol + fecha a la derecha en mono gris, luego descripción.
- **Course card:** columna, icono arriba, título Raleway 700 19px, enlace "Ver →" en {colors.tertiary}. Fondo blanco, borde gris, recto. Hover: borde {colors.primary} + sombra subtle.
- **Contact button:** fondo blanco, texto oscuro, icono {colors.primary}, borde 1px gris, recto. Hover: borde y texto {colors.primary}.

**Campos**

- **Input (`components.input`):** fondo {colors.white}, texto {colors.on-surface} 20px PT Sans, padding 12px 16px, borde 2px {colors.muted-bg}, {rounded.none}. Focus: borde {colors.primary} + halo. Placeholder {colors.neutral}. Label en {typography.label}.

**Navegación y enlaces**

- **Nav-link:** PT Sans 20px, {colors.on-surface}. Hover: {colors.primary} + subrayado 2px. Activo: subrayado 3px.
- **Enlace en texto:** {colors.tertiary} sin subrayado; hover: {colors.primary} + subrayado.
- **Título-enlace (Raleway Black):** {colors.primary}; hover opacidad 0.8.

**Social / Avatar / Chips**

- **Social (`components.social-icon`):** circular 32×32px, fondo {colors.muted-bg}, icono {colors.on-surface}. Hover: fondo {colors.primary}, icono blanco.
- **Avatar (`components.avatar`):** círculo {rounded.full}, 200px (160px móvil), borde 4px {colors.muted-bg}.
- **Chip (`components.chip`):** píldora {rounded.full}, fondo {colors.muted-bg}, texto oscuro 13px.

**Tema oscuro / superficies alternas**

- **Card Alt (`components.card-alt`):** fondo {colors.surface-alt}, texto {colors.on-surface}. Alternativa suave en tema claro.
- **Card Dark (`components.card-dark`):** fondo {colors.coal-medium}, texto {colors.surface}.
- **Hero Dark (`components.hero-dark`):** fondo {colors.coal-deep}, texto {colors.surface}.
- **Input Dark (`components.input-dark`):** fondo {colors.coal-dark}, texto {colors.surface}.
- **Link Dark (`components.link-dark`):** fondo {colors.coal-deep}, texto {colors.tertiary-light}.

## Do's and Don'ts

Do:

- Usa {colors.primary} para todos los CTA primarios y énfasis de marca.
- Mantén 20px como cuerpo base en escritorio; nunca bajo 16px (18–20px en móvil).
- Aplica 48–92px vertical entre secciones mayores (mínimo 92px entre zonas).
- Usa PT Sans para cuerpo/navegación y Raleway Black solo para titulares top.
- Combina naranja con blancos y gris claro para máximo contraste.
- Usa botones icono circulares ({rounded.full}) para sociales y acciones secundarias.
- Mantén tarjetas a {rounded.none} para apariencia nítida.
- Hover con color o subrayado, nunca solo opacidad (salvo título-enlace a 0.75).

Don't:

- No combines naranja y azul en el mismo interactivo; elige uno.
- No uses sombras más profundas que `0 8px 24px`.
- No uses grises más claros que #808080 ({colors.neutral}) para texto.
- No uses serif en jerarquía principal.
- No hagas botones <32px (circulares) o <40px alto (rectangulares); táctil mínimo 44×44px.
- No escondas navegación crítica tras desplegables en móvil sin necesidad.
- No uses fondos/texturas que compitan con legibilidad.
