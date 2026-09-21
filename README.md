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

- **Caso 1:** [PENDIENTE: indicar las etiquetas utilizadas y justificar su elección según el significado de las zonas del centro de control].
- **Caso 2:** [PENDIENTE: indicar las etiquetas utilizadas y justificar su elección según el significado de la programación, los avisos y los servicios].

### 2. ¿Cómo organizó la jerarquía de encabezados?

- **Caso 1:** [PENDIENTE: explicar el uso de h1, h2 y h3 y la relación entre el título principal, las secciones y sus componentes].
- **Caso 2:** [PENDIENTE: explicar el uso de h1, h2 y h3 y la relación entre el festival, sus secciones y las actividades].

### 3. ¿Cómo incorporó la accesibilidad básica?

- **Caso 1:** [PENDIENTE: documentar idioma, navegación, legibilidad, contraste, estados comprensibles sin depender del color y textos alternativos si hay imágenes].
- **Caso 2:** [PENDIENTE: documentar idioma, navegación, legibilidad, contraste, avisos y estados comprensibles sin depender del color y textos alternativos si hay imágenes].

### 4. ¿Cómo funciona el modelo de caja en sus principales componentes?

- **Caso 1:** [PENDIENTE: explicar box-sizing, margin, padding, border y límites de tamaño con ejemplos reales de los paneles y tarjetas].
- **Caso 2:** [PENDIENTE: explicar cómo se calculan los tamaños y espaciados de las actividades, escenarios y servicios y cómo se evitan desbordamientos].

### 5. ¿Dónde utilizó posicionamiento, cuál valor de position empleó y por qué?

- **Caso 1:** [PENDIENTE: identificar el elemento y su selector, el valor de position, su propósito y el uso de z-index cuando corresponda].
- **Caso 2:** [PENDIENTE: identificar el elemento y su selector, el valor de position y cómo se evita que oculte contenido en teléfono].

### 6. ¿Por qué algunos estilos prevalecen sobre otros?

- **Caso 1:** [PENDIENTE: explicar un ejemplo real de cascada, especificidad, herencia u orden de las reglas y media queries].
- **Caso 2:** [PENDIENTE: explicar cómo se reutilizan las clases y cómo las reglas para pantallas mayores modifican los estilos base].

### 7. ¿Dónde utilizó Flexbox y por qué?

- **Caso 1:** [PENDIENTE: identificar componentes y propiedades de Flexbox y justificar la distribución unidimensional].
- **Caso 2:** [PENDIENTE: explicar el uso de Flexbox en la navegación y otros componentes, incluyendo alineación y ajuste de elementos cuando corresponda].

### 8. ¿Dónde utilizó CSS Grid y por qué?

- **Caso 1:** [PENDIENTE: explicar la cuadrícula principal, sus columnas o áreas y la distribución de las zonas del centro de control].
- **Caso 2:** [PENDIENTE: explicar la cuadrícula de programación por escenarios y otras zonas que utilicen Grid].

### 9. ¿Cómo cambia el layout entre teléfono, tableta y escritorio?

- **Caso 1:** [PENDIENTE: describir el orden, las columnas y la prioridad de las alertas en los tres tamaños].
- **Caso 2:** [PENDIENTE: describir la prioridad de las actividades actuales en teléfono y la comparación simultánea de escenarios en escritorio].

### 10. ¿Cuáles media queries utilizó y por qué seleccionó esos breakpoints?

- **Caso 1:** [PENDIENTE: enumerar las consultas min-width implementadas y justificar cada punto de cambio según las necesidades del contenido].
- **Caso 2:** [PENDIENTE: enumerar las consultas min-width implementadas y explicar cómo amplían y reorganizan el diseño base para teléfono].

### 11. ¿Cuáles unidades relativas utilizó?

- **Caso 1:** [PENDIENTE: indicar unidades como rem, em, %, fr o vw con ejemplos reales y justificar su uso].
- **Caso 2:** [PENDIENTE: indicar las unidades relativas utilizadas en tipografía, espaciados, contenedores y columnas].

### 12. ¿Para qué sirven las variables CSS que definió?

- **Caso 1:** [PENDIENTE: identificar las variables de :root para colores, fondo, texto, espaciados y bordes o radios, y explicar dónde se reutilizan].
- **Caso 2:** [PENDIENTE: identificar las variables de :root y explicar cómo mantienen la coherencia visual del festival].

## Resumen de commits

[PENDIENTE: completar con una fila por commit real del repositorio, en orden cronológico. Actualmente no hay commits registrados.]

| # | Fecha | Hash | Mensaje | Caso | Cambio |
| 1 | 20/9/2026 | 0ccd30ec877fc187d5b1c7522272f33d91926d32 | Estructura inicial de casos más readme | 1 y 2 | Readme, archivos html y css, carpetas |

