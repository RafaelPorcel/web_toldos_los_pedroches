# Toldos y Lonas Los Pedroches — Sitio web corporativo

Sitio web estático de **Toldos y Lonas Los Pedroches**, empresa con más de 10 años de experiencia en **Pozoblanco** y la comarca de **Los Pedroches (Córdoba)**. Especialistas en instalación de toldos, lonas, pérgolas, cerramientos, cortinas de cristal y ventanas de PVC y aluminio.

---

## Descripción del proyecto

Web corporativa de presentación y contacto, orientada a posicionamiento local (SEO) con términos como *toldos Pozoblanco*, *lonas Los Pedroches*, *cerramientos* y *ventanas*. Incluye:

- **Inicio**: servicios, ventajas y llamadas a la acción.
- **Nosotros**: historia, misión y valores.
- **Trabajos**: galería de proyectos realizados.
- **Contacto**: WhatsApp, teléfono y correo con enlaces directos (llamar y escribir).

Diseño responsive (móvil, tablet y escritorio), con identidad visual en azul corporativo y enlaces a redes sociales (Instagram, Facebook) y WhatsApp.

---

## Tecnologías

- **HTML5** — Estructura y semántica.
- **CSS3** — Estilos, variables CSS, grid, flexbox y media queries.
- **JavaScript** — Menú móvil y pequeña interactividad.
- Sin frameworks ni backend; preparado para alojamiento estático.

---

## Estructura del proyecto

```
toldos_los_pedroches/
├── index.html          # Página de inicio
├── nosotros.html       # Sobre la empresa
├── trabajos.html       # Galería de trabajos
├── contacto.html       # Datos de contacto (WhatsApp, teléfono, correo)
├── css/
│   └── style.css      # Estilos globales y responsive
├── js/
│   └── main.js        # Menú hamburguesa y utilidades
├── img/
│   ├── logo/          # Logo principal y favicon (jpg)
│   ├── icono/         # Iconos: toldos, pérgolas, cortinas, teléfono, email, redes
│   ├── trabajos/      # Imágenes de la galería de trabajos
│   └── fondo/         # Imagen de fondo (p. ej. portada)
└── README.md
```

---

## Cómo usar el sitio

1. Clona o descarga el repositorio.
2. Abre `index.html` en un navegador (doble clic o arrastrar al navegador).
3. Para desarrollo local con recarga opcional: sirve la carpeta con cualquier servidor estático (por ejemplo Live Server en VS Code, o `npx serve`).

No requiere instalación de dependencias ni base de datos.

---

## Características principales

| Aspecto | Detalle |
|--------|---------|
| **Diseño** | Responsive, tarjetas de servicios y bloques de contacto claros |
| **Identidad** | Color azul corporativo (#1e3a8a), logo en header y favicon |
| **Navegación** | Inicio, Nosotros, Trabajos, Contacto; menú adaptable en móvil |
| **Contacto** | Enlaces directos: WhatsApp (wa.me), teléfono (tel:) y correo (mailto:) |
| **SEO** | Título y meta description únicos por página, palabras clave locales |
| **Redes** | Enlaces a Instagram y Facebook en header y footer |

---

## Personalización

- **Colores**: Variables en `css/style.css` (sección `:root`): `--primary-blue`, `--secondary-blue`, etc.
- **Textos y SEO**: Editar títulos, meta description y contenidos en cada `.html`.
- **Imágenes**: Sustituir archivos en `img/logo/`, `img/trabajos/` e `img/fondo/` manteniendo nombres o actualizando rutas en HTML/CSS.
- **Contacto**: Teléfonos, correo y enlaces de redes en las cuatro páginas (header, contacto y footer).

---

## Licencia y autor

Proyecto desarrollado para **Toldos y Lonas Los Pedroches**.  
Uso interno o según acuerdo con el propietario del negocio.
