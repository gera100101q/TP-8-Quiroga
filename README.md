# TP-8-Quiroga# Sistema de Gestión de Fixtures

Proyecto de la materia Laboratorio de Programación - 6° G (IPET N° 249). Entorno multi-página para cargar y visualizar el fixture de un torneo, con estética minimalista inspirada en una galería de arte: fondos neutros, tipografía fina y espacios amplios.

## Trabajo Práctico N° 8 - Estructuración Semántica Avanzada y Entornos Multi-página

El sistema está compuesto por tres pantallas independientes conectadas entre sí mediante una barra de navegación común:

- index.html: panel de control con novedades del torneo y próximos encuentros destacados.
- alta-fixture.html: formulario para cargar nuevos encuentros (equipos, fecha, hora, sede e instancia del torneo).
- ver-fixture.html: visualizador con la tabla general de partidos y una sección lateral con reglamento, posiciones y avisos.

## Estructura del proyecto

```
├── index.html            Panel de control (dashboard)
├── alta-fixture.html      Formulario de administración
├── ver-fixture.html       Visualizador del fixture
├── css/
│   └── estilos.css        Hoja de estilos compartida por las tres páginas
└── assets/
    └── ...                 Imágenes y recursos
```

## Requisitos técnicos cumplidos (TP8)

- Etiquetas semánticas en las tres páginas: header, nav, main, section, article, aside y footer
- Barra de navegación y pie de página idénticos en estructura y estilos en las tres pantallas
- Formulario de alta con select para equipo local y visitante, campos type="date" y type="time", sede en texto libre e instancia del torneo mediante radio
- Todos los campos críticos del formulario son required, con label asociado mediante for e id
- Botones de acción: submit con el texto "Registrar encuentro" y reset con el texto "Restablecer formulario"
- Tabla HTML (table) con fecha, rivales, horario, sede e instancia de cada encuentro
- Aside independiente con reglamento, tabla de posiciones y avisos
- Misma hoja de estilos externa en las tres páginas
- cursor: pointer en todos los elementos interactivos y text-transform: uppercase en botones y etiquetas de navegación
- Enlaces internos con rutas relativas entre las tres páginas

## Tecnologías utilizadas

- HTML5
- CSS3
- Google Fonts (Cormorant Garamond y Work Sans)

## Cómo verlo

Opción 1 - Online: activar GitHub Pages en el repositorio (Settings > Pages > Branch: main) y acceder a:
```
https://gera100101q.github.io/TU-REPOSITORIO/index.html
```

Opción 2 - Local: descargar el proyecto completo y abrir index.html con el navegador, manteniendo la carpeta css en el mismo nivel que los archivos HTML.

## Datos de la entrega

- Trabajo Práctico: N° 8 - Estructuración Semántica Avanzada y Entornos Multi-página
- Materia: Laboratorio de Programación
- Curso: 6° G - IPET N° 249
- Fecha de entrega: Jueves 11 de junio

## Autor

Gerardo Quiroga
