# Desafío 2: CSS Grid & Flexbox

Este proyecto corresponde al segundo desafío del **Módulo 2** del bootcamp de **Desarrollo Front-End**. El objetivo fundamental de este ejercicio práctico fue dominar el uso de **CSS Grid Layout** para la estructura principal del sitio, complementándolo con **Flexbox** para la distribución de componentes internos menores.

## 🔗 Revisalo aquí
https://ciga25.github.io/m2d2_grid/

## 🎯 Objetivos del Desafío
* **Maquetación con CSS Grid:** Implementar un sistema de rejilla bidimensional configurando áreas explícitas (`grid-template-areas`), columnas y filas adaptables.
* **Alineación con Flexbox:** Resolver la distribución espacial, centrado vertical y separación de los elementos internos en componentes moleculares de la interfaz.

## 🛠️ Tecnologías y Herramientas
* **HTML5 Semántico:** Estructuración del sitio mediante el uso correcto de etiquetas como `nav`, `aside`, `main`, `figure` y `footer`.
* **CSS3 Avanzado:** Uso combinado de arquitecturas CSS Grid y Flexbox.
* **Google Fonts:** Integración de la tipografía *Space Grotesk* para reforzar la identidad visual del proyecto.

## 🌟 Características Técnicas Destacadas

### 1. Estructura Global con CSS Grid
El layout base de la aplicación se construyó utilizando el modelo de áreas para asegurar un posicionamiento rígido y ordenado de los bloques estructurales.

### 2. Catálogo de Productos Dinámico (main)
La sección contenedora de las tarjetas de productos utiliza una rejilla automática de tres columnas paralelas que organiza los elementos fluidamente.

### 3. Flexbox en Componentes Internos
Se aplicó `display: flex` para resolver de forma limpia la alineación interna de los siguientes módulos:
* **Navbar & Footer:** Alineación de títulos, logos y listas de enlaces de contacto.
* **Barra Lateral:** Distribución vertical de los bloques de categorías e indicadores numéricos alineados a los extremos (`justify-content: space-between`).
* **Tarjetas de Producto:** Estructura en columna con espaciados homogéneos y botones de compra perfectamente alineados con el precio.

### 4. Microinteracciones (UI/UX)
* Las tarjetas de los productos y las filas de categorías reaccionan al posicionamiento del cursor (`:hover`) mediante sutiles sombras internas, cambios de color de fondo y efectos de elevación visual (`box-shadow`).
* Los botones y elementos clickeables cambian de estado cromático al presionarse (`:active`), mejorando el feedback visual para el usuario.

## 📂 Estructura del Proyecto

```
.
├── index.html          # Estructura e-commerce principal (Singularity Shop).
├── assets/
│   ├── css/
│   │   └── styles.css  # Reglas de estilo (Grid + Flexbox + Efectos).
│   └── img/            # Recursos visuales (imágenes)
```

---
*Este proyecto es parte del proceso de aprendizaje en el bootcamp de Desarrollo Front-End - 2026.*
