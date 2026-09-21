# Tarea 1: Interfaces web adaptables con HTML y CSS

Proyecto académico con dos casos independientes: un centro de control para una expedición científica y un panel público de información para un festival cultural.

## Identificación

| Dato | Información |
| --- | --- |
| Estudiante | Daniel Campos Sánchez |
| Universidad | Universidad CENFOTEC |
| Escuela | Escuela de Software |
| Curso | SOFT-12 — Programación web avanzada |
| Sección | SCV2 |
| Periodo | III cuatrimestre 2026 |
| Docente | Álvaro Cordero Peña |
| Fecha de entrega | 2026-09-20 |
| Modalidad | Individual |

## Descripción de los casos

### Caso 1: Centro de control de una expedición científica

Una expedición científica en una zona protegida de Costa Rica necesita coordinar actividades simultáneas. El centro de control tiene como objetivo facilitar la consulta del estado general de la expedición, los indicadores de operaciones, las misiones, los equipos científicos, las alertas y las próximas actividades. El problema consiste en organizar información de distinta importancia para reconocer rápidamente qué está ocurriendo y qué requiere atención. 

### Caso 2: Panel público de información de un festival

Un festival cultural desarrolla actividades simultáneas en distintos escenarios. El panel tiene como objetivo ayudar a los asistentes a consultar qué ocurre ahora, qué comenzará próximamente, dónde se realiza cada actividad, cuáles eventos han cambiado y qué servicios están disponibles. El problema consiste en facilitar una consulta rápida desde teléfonos y permitir comparar la programación de varios escenarios en pantallas grandes.

## Estructura de carpetas

```text
Tarea1/
├── README.md
├── caso1/
    ├── index.html
    └── css/
        └── estilos.css
    └── img/
└── caso2/
    ├── index.html
    └── css/
        └── estilos.css
    └── img/
```

- `README.md`: identificación, descripción, instrucciones de apertura, decisiones de diseño e historial de trabajo.
- `caso1/index.html` y `caso2/index.html`: documentos HTML de cada caso.
- `caso1/css/estilos.css` y `caso2/css/estilos.css`: hojas de estilo independientes.

## Instrucciones para abrir cada caso

1. Descargar el repositorio y descomprimirlo, o clonarlo desde GitHub.
2. Conservar la estructura de carpetas para que las rutas relativas de las hojas de estilo y los recursos funcionen.
3. Abrir el archivo correspondiente en un navegador web:
   - **Caso 1:** abrir [caso1/index.html](caso1/index.html).
   - **Caso 2:** abrir [caso2/index.html](caso2/index.html).
4. Cambiar el ancho de la ventana o utilizar las herramientas de desarrollo del navegador para revisar la distribución en teléfono, tableta y escritorio.

La entrega está prevista para funcionar directamente desde cada `index.html`, con HTML5 y CSS3, sin JavaScript ni frameworks de CSS.

## Decisiones de diseño

Las siguientes preguntas corresponden al apartado «Aspectos que el estudiante deberá poder explicar» de la consigna. Las respuestas pendientes deben describir el código final y señalar componentes o clases concretas.

### 1. ¿Por qué seleccionó determinadas etiquetas semánticas?

Para brindar una mejor legibilidad al programa de accesibilidad que se utilice.

### 2. ¿Cómo organizó la jerarquía de encabezados?

Dentro del header, coloque un h1 seguidos del p.

### 3. ¿Cómo incorporó la accesibilidad básica?

Inclui aria-label, aria-labelby, ademas de pseudo-clases como :focus-visible

### 4. ¿Cómo funciona el modelo de caja en sus principales componentes?

Inicialmente es un solo grid de 1 columna porque primero es mobile first. Posteriormente se definen mas columnas segun el ancho de la pantalla

### 5. ¿Dónde utilizó posicionamiento, cuál valor de position empleó y por qué?

Use sticky para el nav, asi la barra de navegacion siempre esta presente

### 6. ¿Por qué algunos estilos prevalecen sobre otros?

Si colocamos media querys al inicio del archivo, estos van a ser sobreescritos por los otros que se coloquen debajo. Especialmente por la caracterisica de cascada que tiene CSS

### 7. ¿Dónde utilizó Flexbox y por qué?

En el nav para que los enlaces se acomoden em varias filas cuando falte espacio.

### 8. ¿Dónde utilizó CSS Grid y por qué?

En el encabezado (y en su media query) porque es mas facil organizarlo de esa forma y en el main

### 9. ¿Cómo cambia el layout entre teléfono, tableta y escritorio?

Para el encabezado, incialmente es una columna y despues de 48rem son 2

### 10. ¿Cuáles media queries utilizó y por qué seleccionó esos breakpoints?

Para header use min-width y los seleccione porque hay mejor armonizacion visual segun lo investigado en internet

### 11. ¿Cuáles unidades relativas utilizó?

min-width: 48rem, minmax(0, 1fr), max-width: 100%.

### 12. ¿Para qué sirven las variables CSS que definió?

Para estandarizar estilos y dar escalabilidad.

## Resumen de commits

| # | Fecha | Hash | Mensaje | Caso | Cambio |
| --- | --- | --- | --- | --- | --- |
| 1 | 2026-09-20 | 0ccd30e | Estructura inicial de casos más readme | Ambos | Agrega el README, la estructura HTML inicial del caso 1 y los archivos vacíos de CSS y del caso 2. |
| 2 | 2026-09-20 | 2db29ba | Commit 0ccd30ec877fc187d5b1c7522272f33d91926d32 agregado | Ambos | Añade al README el registro del primer commit. |
| 3 | 2026-09-20 | 56b3a13 | Estilo para header, van y resumen de operaciones | 1 | Agregar clases en html y css. Agregar mediaquerys en css.|
| 4 | 2026-09-20 | 9a1066a | Finalizacion de estilos para equipos, agenda, y footer | 1 | Agregar clases en html y css para equipos, agenda y footer|
| 5 | 2026-09-20 | 27db2bf | Modificacion de readme, agrega html para todo el contendio y estilos para header y nav | 2 | html y css para caso 2 |
| 6 | 2026-09-20 | 900e956 | Agrega clases para secciones de Ahora y Cambios. Ademas de su css respectivo | 2 | html y css para caso 2 |
| 7 | 2026-09-20 | 900e956 | Finaliza estilos para escenarios, informacion y footer | 2 | html y css para caso 2 |

