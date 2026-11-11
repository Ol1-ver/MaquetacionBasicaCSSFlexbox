# Lento — dirección de diseño

## Idea
Una guía editorial de escapadas rurales para quienes quieren viajar con calma. La página debe sentirse como una revista de viajes contemporánea: naturaleza cercana, hospitalidad y pocos elementos, elegidos con intención.

## Personalidad
- Sereno, cálido, honesto y optimista; nunca lujoso de forma ostentosa.
- Inspiración: editoriales de viajes independientes, alojamientos rurales de autor y la claridad de producto de Apple.
- La fotografía transmite silencio y amplitud. Evitar imágenes de stock con poses, saturación excesiva o tratamientos artificiales.

## Sistema visual
- **Fondo:** marfil cálido `#f6f5f0`; reservar el blanco roto `#fffefa` para superficies elevadas.
- **Texto:** carbón vegetal `#252c25`; texto secundario `#777a70`.
- **Acento:** verde bosque `#435b48` y verde profundo `#304337`; salvia `#e8ebe3` para bloques de descanso visual.
- **Tipografía:** Playfair Display para titulares con carácter editorial; DM Sans para navegación, cuerpo y datos.
- **Composición:** lienzo centrado, máximo 1440 px, márgenes generosos y jerarquía clara. Flexbox es el patrón de distribución; las tarjetas pasan de fila a columna en móvil.
- **Fotografía:** paisajes y refugios reales, tonos terrosos, luz natural, recortes amplios y esquinas discretamente redondeadas.
- **Iconografía:** Font Awesome usada con moderación y con texto accesible equivalente cuando el icono comunica una acción.

## Interacción y accesibilidad
- Navegación con enlaces a secciones; menú móvil nativo desplegable.
- Estados hover y foco visibles, enlace para saltar al contenido y estructura semántica.
- Todas las imágenes informativas tienen texto alternativo; las decorativas se marcan como tales.
- CTA de ayuda fijada en la esquina inferior derecha, con etiqueta accesible.
- Respetar `prefers-reduced-motion`; no depender del color o de hover para comunicar contenido.

## Tono de contenido
Español cercano y breve. Hablar de bajar el ritmo y conectar con el lugar, sin prometer servicios que la web todavía no ofrece ni utilizar urgencia comercial.
