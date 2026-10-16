# Parcial I: Diseño de interfaces con HTML5 y CSS3

Proyecto del primer parcial: tres ejercicios de diseño de interfaces usando únicamente **HTML5 y CSS3** (sin JavaScript), con **Flexbox** y **CSS Grid** para los layouts.

**Autores:** Paula Hernández y Julian Diaz
**Materia:** Computación Gráfica
**Profesor:** Andrés Felipe Ramirez Correa

## Contenido

### Punto 1: Reproducción de interfaces

- **1a. Composición geométrica:** rejilla de 3x3 con formas hechas solo con CSS (cuadrados, rombo, círculos, marcos y barras). Usa Grid para la rejilla, `aspect-ratio` para mantener las proporciones y `transform: rotate()` para el rombo.
- **1b. Layout con navbar y panel lateral:** barra de navegación con botones de distinto ancho (Flexbox), cuatro tarjetas en rejilla 2x2 y un panel oscuro con elementos decorativos (Grid).

### Punto 2: Portal de noticias "El Presente"

Página de noticias con HTML semántico: `header`, `nav`, `main` con varios `article`, `aside` y `footer`.

- **Encabezado:** logo, fecha y botones de suscripción e ingreso, con Flexbox.
- **Menú de secciones:** Inicio, Colombia, Mundo, Economía, Deportes, Tecnología, Salud, Cultura y Opinión.
- **Noticias:** rejilla de 3 columnas con Grid, con una noticia principal que ocupa 2 columnas.
- **Barra lateral:** "Lo más leído" y suscripción al boletín.
- **Pie de página:** derechos de autor y enlaces de contacto, privacidad y términos.
- **Estilo:** tipografía Georgia para el contenido y Arial para los elementos de interfaz; paleta de rojo (`#b00020`), negro y grises. Las imágenes son marcadores de posición.

### Punto 3: Dashboard financiero "FinControl"

Interfaz de una aplicación ficticia de control financiero, con cinco pantallas conectadas entre sí:

| Pantalla | Descripción |
|---|---|
| `login.html` | Usuario, contraseña y botón Ingresar (Flexbox). Lleva al dashboard |
| `dashboard.html` | Tarjetas de saldo total, ingresos y gastos del mes (Grid) y últimos movimientos |
| `ingresos.html` | Formulario para registrar ingresos y tabla de movimientos |
| `gastos.html` | Formulario para registrar gastos y tabla de movimientos |
| `reportes.html` | Comparativo mensual con barras hechas solo con CSS |

Todas comparten el mismo `style.css` y un menú lateral (`aside`) con las opciones Inicio, Ingresos, Gastos y Reportes. El diseño es responsive.

## Estructura del proyecto

```
parcial/
├── punto1/
│   ├── interfaz-a.html
│   ├── interfaz-a.css
│   ├── interfaz-b.html
│   └── interfaz-b.css
├── punto2/
│   ├── P2.html
│   ├── style.css
│   └── favicono.png
└── punto3/
    ├── login.html
    ├── dashboard.html
    ├── ingresos.html
    ├── gastos.html
    ├── reportes.html
    ├── style.css
    └── favicon.svg
```

## Cómo ejecutarlo

1. Clona el repositorio o descarga el ZIP.
2. Abre la carpeta en **VS Code**.
3. Abre cualquier archivo `.html` con la extensión **Live Server**, o con doble clic en el navegador.
4. Para el Punto 3, empieza siempre por `login.html`.

## Tecnologías

- HTML5 semántico
- CSS3: Flexbox, Grid, variables CSS y media queries

## Notas

- El proyecto es solo de interfaz: el login no valida credenciales y los formularios no guardan datos, porque el enunciado no incluye JavaScript.
- Los datos mostrados son ficticios.
