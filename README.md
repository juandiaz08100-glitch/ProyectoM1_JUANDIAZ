# 🎨 Generador de Paletas de Colores

Aplicación web interactiva que permite generar paletas de colores aleatorias en formato HEX o HSL.
El usuario puede elegir la cantidad de colores, copiar códigos al portapapeles y guardar paletas usando `localStorage`.

---

# 📌 Características

* Generación aleatoria de colores.
* Selección de cantidad de colores:

  * 6 colores
  * 8 colores
  * 9 colores
* Formatos disponibles:

  * HEX
  * HSL
* Copiar colores al hacer clic.
* Guardado de paletas en el navegador.
* Diseño responsive para desktop y dispositivos móviles.
* Animaciones y efectos visuales modernos.

---

# 🛠️ Tecnologías utilizadas

* HTML5
* CSS3
* JavaScript Vanilla

---

# 📂 Estructura del proyecto

```bash
📁 proyecto-paleta
│── index.html
│── style.css
│── script.js
│── README.md
```

---

# ▶️ Cómo ejecutar la aplicación

## Opción 1: Abrir directamente

1. Descargar o clonar el proyecto.
2. Abrir el archivo `index.html` en el navegador.

---

## Opción 2: Usar Live Server (recomendado)

1. Abrir el proyecto en Visual Studio Code.
2. Instalar la extensión **Live Server**.
3. Hacer clic derecho en `index.html`.
4. Seleccionar **Open with Live Server**.

La aplicación se abrirá automáticamente en el navegador.

---

# 🚀 Cómo usar la aplicación

1. Seleccionar la cantidad de colores.
2. Elegir el formato de color:

   * HEX
   * HSL
3. Presionar el botón **Generar paleta**.
4. Hacer clic sobre un color para copiar su código.
5. Presionar **Guardar paleta** para almacenarla localmente.

---

# 💾 Persistencia de datos

Las paletas guardadas se almacenan utilizando:

```javascript
localStorage
```

Esto permite conservar las paletas incluso después de cerrar o recargar el navegador.

---

# 🎨 Decisiones técnicas

## Uso de JavaScript Vanilla

Se decidió utilizar JavaScript puro para:

* Mantener el proyecto liviano.
* Evitar dependencias externas.
* Comprender mejor la manipulación del DOM.

---

## Uso de CSS Grid

La distribución de colores utiliza:

```css
display: grid;
```

Esto permite:

* Adaptabilidad responsive.
* Distribución automática de columnas.
* Mejor organización visual.

---

## Responsive Design

Se implementaron media queries para adaptar la interfaz a pantallas pequeñas:

```css
@media(max-width:768px)
```

---

## Efectos visuales

Se añadieron:

* Animaciones.
* Hover effects.
* Sombras.
* Fondo animado.
* Toast notifications.

Con el objetivo de mejorar la experiencia del usuario.

---

# 📱 Compatibilidad

Compatible con:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

---

# 🌐 Despliegue de la aplicación

La aplicación puede desplegarse fácilmente en:

* GitHub Pages
* Netlify
* Vercel

---

# 📤 Despliegue en GitHub Pages

1. Subir el proyecto a un repositorio de GitHub.
2. Ir a:

   * Settings
   * Pages
3. En "Branch", seleccionar:

   * `main`
   * `/root`
4. Guardar cambios.

GitHub generará un enlace público automáticamente.

---

# 📌 Posibles mejoras futuras

* Exportar paletas en formato JSON.
* Descargar paletas como imagen.
* Agregar modo oscuro/claro.
* Bloquear colores específicos.
* Generar colores armónicos automáticamente.

---

# 👩‍💻 Autor

Proyecto desarrollado como práctica de desarrollo web utilizando HTML, CSS y JavaScript.
