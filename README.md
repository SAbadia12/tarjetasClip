# Tarjetas con clip-path

Ejercicio de práctica: construir dos tarjetas de perfil responsive usando `clip-path`, la metodología BEM, media queries y Font Awesome por CDN.

## Estructura

```
tarjetasClip/
├── css/
│   └── styles.css
├── index.html
└── README.md
```

## Tecnologías

- HTML5
- CSS3 (`clip-path`, flexbox, media queries, variables CSS)
- [Font Awesome 7.3.1](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.3.1/css/all.min.css) por CDN
- Metodología BEM para nombrar las clases

## Metodología BEM

Las clases siguen el patrón `bloque__elemento--modificador`:

- Bloque: `card`
- Elementos: `card__header`, `card__avatar`, `card__body`, `card__name`, `card__text`, `card__actions`, `card__footer`, `card__social`
- Modificadores: `card--one`, `card--two`, `card__action--outline`

## clip-path

Cada tarjeta recorta su cabecera y su pie con un `polygon()` distinto. Los puntos se generaron y ajustaron con [Clippy](https://clippy.f8.edu.vn/).

## Responsive

- Escritorio: las dos tarjetas lado a lado.
- Móvil (`max-width: 680px`): las tarjetas se apilan una debajo de la otra.

## Ver el resultado

- Sitio publicado con GitHub Pages: https://sabadia12.github.io/tarjetasClip/
- Repositorio: https://github.com/SAbadia12/tarjetasClip