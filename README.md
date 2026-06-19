# Tu Catálogo Aquí

## Descripción

"Tu Catálogo Aquí" es un sitio web personal que simula una plataforma de catálogo digital para emprendedores, pensada para mostrar productos de tecnología, belleza, ropa y accesorios a través de un solo enlace. El proyecto incluye una página principal, un catálogo de productos, un panel de administración, formularios de inicio de sesión y registro, y una página de contacto.

## Objetivo

Integrar estilos CSS externos, componentes de Bootstrap, diseño mobile-first y representaciones de datos en formatos JSON y XML dentro de un proyecto web personal, aplicando los conocimientos adquiridos sobre HTML, CSS y diseño adaptable.

## Tecnologías utilizadas

- HTML5
- CSS3 (archivos externos, sin estilos en línea)
- Bootstrap 5.3.8
- Font Awesome 6.5.0
- JSON
- XML

## Estructura de carpetas

```
PROYECTO_FUNDAMENTOS/
│
├── index.html
├── README.md
│
├── css/
│   ├── general.css
│   ├── index.css
│   ├── admin.css
│   ├── auth.css
│   ├── catalogo.css
│   └── contacto.css
│
├── data/
│   ├── datos.json
│   └── datos.xml
│
├── img/
│   ├── carrusel/
│   ├── fondo/
│   ├── logos/
│   └── productos/
│
├── pages/
│   ├── admin.html
│   ├── catalogo.html
│   ├── contacto.html
│   ├── login.html
│   └── registrarse.html
│
└── videos/
```

## Páginas disponibles

| Página | Archivo | Descripción |
|---|---|---|
| Inicio | `index.html` | Presentación del proyecto, beneficios y carrusel destacado |
| Catálogo | `pages/catalogo.html` | Listado de productos con detalle en modal y carrusel de promociones |
| Iniciar sesión | `pages/login.html` | Formulario de acceso al panel de administración |
| Registrarse | `pages/registrarse.html` | Formulario de creación de cuenta |
| Administrador | `pages/admin.html` | Panel con estadísticas, tabla de productos y métricas de ventas |
| Contacto | `pages/contacto.html` | Formulario de contacto, preguntas frecuentes e información de la tienda |

## Componentes Bootstrap utilizados

- Navbar
- Offcanvas
- Dropdown
- Cards
- Carousel
- Modal
- Accordion
- Alert
- Badge
- List Group
- Progress
- Spinners
- Placeholders
- Scrollspy
- Buttons
- Container / Container-fluid

## Instrucciones para ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto en un editor de código (por ejemplo, Visual Studio Code).
3. Abrir el archivo `index.html` directamente en el navegador, o usar una extensión como "Live Server" para visualizarlo con recarga automática.
4. Navegar entre las páginas usando el menú principal; las páginas internas se encuentran dentro de la carpeta `pages/`.

No se requiere instalar dependencias ni levantar un servidor, ya que el proyecto no se conecta a una base de datos: los datos se encuentran simulados directamente en el HTML.

## Archivos JSON y XML

Dentro de la carpeta `data/` se incluyen los archivos `datos.json` y `datos.xml`, los cuales representan la estructura que tendría la información de los productos del catálogo si en el futuro se obtuviera desde un servidor o una API, en lugar de estar escrita directamente en el HTML como ocurre actualmente. Ambos archivos contienen los mismos 8 productos (nombre, descripción, precio, stock, calidad e imagen), expresados en dos formatos distintos de intercambio de datos.

## Autor

Estefany Briones
