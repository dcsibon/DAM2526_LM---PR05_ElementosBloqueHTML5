
## 🧩 Práctica 5 – Web HTML5 *(Elementos de bloque en HTML5)*

### **Objetivo**

Crear una página web que utilice correctamente los principales **elementos semánticos de bloque** introducidos en **HTML5**.

---

### **Instrucciones**

1. **Estructura básica del documento**
   Crea un archivo HTML válido con la declaración `<!DOCTYPE html>` y configura la cabecera (`<head>`) del documento:

   * Incluye `<meta charset="UTF-8">`
   * Añade `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
   * Usa como título:

     ```html
     <title>Elementos de bloque HTML5</title>
     ```

2. **Cabecera principal del cuerpo**
   Dentro del `<body>`, crea un elemento `<header>` que contenga:

   * Una imagen del **logo del IES Saladillo** (`<img src="img/logo.png" alt="Logo del IES Saladillo">`).
   * Un encabezado de nivel 1 (`<h1>`) con el texto:

     ```
     DAM 1 – IES Saladillo
     ```

3. **Menú de navegación**
   Añade un elemento `<nav>` que contenga una **lista desordenada** (`<ul>`) con **cinco elementos** (`<li>`).
   Cada elemento debe incluir un **enlace** (`<a>`) que apunte al inicio de cada sección de contenido, con textos:

   ```
   Menú 1, Menú 2, Menú 3, Menú 4, Menú 5
   ```

   Ejemplo:

   ```html
   <nav>
     <ul>
       <li><a href="#sec1">Menú 1</a></li>
       <li><a href="#sec2">Menú 2</a></li>
       ...
     </ul>
   </nav>
   ```

4. **Contenido principal del sitio**
   Todo el contenido principal debe ir dentro de un elemento `<main>` con el atributo `id="contenido"`.
   Este contenedor agrupará todas las secciones del sitio.

5. **Estructura de las secciones**
   Crea **una sección (`<section>`) para cada Menú**.
   Cada sección representará un bloque temático y contendrá varios artículos relacionados con ese tema.
   Usa un identificador único para cada una:

   ```html
   <section id="sec1">...</section>
   <section id="sec2">...</section>
   ...
   ```

6. **Encabezado descriptivo dentro de cada sección**
   Dentro de cada sección, incluye un pequeño encabezado o bloque descriptivo:

   * Un `<h2>` con el título del contenido (por ejemplo: *“Título del contenido de Menú 1”*).
   * Un `<h3>` con una descripción breve o subtítulo (por ejemplo: *“Lorem Ipsum”*).
     Este bloque puede agruparse dentro de un `<header>` o un `<div>` según tu preferencia.

7. **Artículos de contenido**
   Dentro de cada sección, crea **dos o más artículos** (`<article>`), cada uno con:

   * Un atributo `id` único (por ejemplo: `art1`, `art2`, …).
   * Una agrupación (`<figure>`) que contenga una imagen (`<img>` con `alt`).
   * Un título del artículo con `<h3>`.
   * Una línea divisoria `<hr>`.
   * Dos o tres párrafos (`<p>`) con texto tipo *Lorem ipsum*, destacando alguna palabra con `<em>` y `<strong>`.

   Ejemplo:

   ```html
   <article id="art1">
     <figure>
       <img src="img/art1.jpg" alt="Imagen del artículo 1">
     </figure>
     <h3>Título del artículo 1</h3>
     <hr>
     <p>Este es un <strong>ejemplo</strong> de artículo con <em>HTML5</em> moderno.</p>
     <p>Segundo párrafo de contenido.</p>
   </article>
   ```

8. **Pie de página**
   Al final del documento, añade un `<footer>` con el siguiente contenido:

   * Un encabezado de nivel 5 (`<h5>`) con el texto:

     ```
     © 2025. DAM1 IES Saladillo.
     Avda. C. Duque de Rivas, s/n, 11207 Algeciras, Cádiz (España).
     ```

---

### **Pautas de validación HTML5**

* Usa **etiquetas semánticas**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`.
* No utilices etiquetas **obsoletas** como `<center>`, `<font>`, `<big>`, `<u>`, etc.
* Todos los elementos de imagen deben incluir el atributo `alt`.
* Asegúrate de que el documento pasa el **validador W3C HTML5**:
  [https://validator.w3.org/](https://validator.w3.org/)

---

### ✅ **Resultado esperado**

Una página web estructurada y semánticamente correcta, con una cabecera, un menú de navegación funcional, cinco secciones con artículos, y un pie de página informativo.

<img width="2327" height="1747" alt="image" src="https://github.com/user-attachments/assets/dce73a56-ac84-4540-a7cf-c4bcbe8d7f40" />

<img width="2330" height="1427" alt="image" src="https://github.com/user-attachments/assets/4b99a841-98d7-46f2-8c8b-41c17f9bd906" />

---

9. **Aplicar estilo**
  Por último, aplica el fichero de estilo que tienes en los recursos de la práctica 5 a la web que acabas de crear.

---
