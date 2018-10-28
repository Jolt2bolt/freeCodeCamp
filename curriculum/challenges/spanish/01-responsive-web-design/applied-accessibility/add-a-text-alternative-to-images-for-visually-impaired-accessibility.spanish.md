---
id: 587d774c367417b2b2512a9c
title: Add a Text Alternative to Images for Visually Impaired Accessibility
challengeType: 0
videoUrl: ''
guideUrl: 'https://spanish.freecodecamp.org/guide/certificates/add-alt-text-to-an-image-for-accessibility'
localeTitle: Agregar una alternativa de texto a las imágenes para la accesibilidad de personas con discapacidad visual
---

## Descripción 
<section id="description"> Es probable que hayas visto un atributo <code>alt</code> en una etiqueta <code>img</code> en otros desafíos. En este contexto, el atributo <code>alt</code> se utiliza para describir el contenido de la imagen o proporcionar un texto alternativo que se mostraría en caso de que la imagen no cargue correctamente o no pueda ser vista por un usuario. También es utilizado por los motores de búsqueda para comprender qué contiene una imagen para incluirla en los resultados de búsqueda. Aquí hay un ejemplo: <code>&lt;img src=&quot;importantLogo.jpeg&quot; alt=&quot;Company logo&quot;&gt;</code> personas con discapacidades visuales dependen de los lectores de pantalla para convertir el contenido web a una interfaz de audio ya que no obtendrán información si solo se presenta visualmente. Para las imágenes, los lectores de pantalla pueden acceder al atributo <code>alt</code> y leer su contenido para entregar información clave. Una buena descripción en el atributo <code>alt</code> debe ser breve pero descriptiva y debe está pensada para transmitir brevemente el significado de la imagen. Por eso, siempre debes incluir un atributo <code>alt</code> en tu imagen. Por medio de la implementación de la especificación HTML5, esto ahora se considera obligatorio. </section>

## Instrucciones 
<section id="instructions"> Resulta que el gato campero es tanto un ninja codificador como un ninja real, y está construyendo un sitio web para compartir sus conocimientos. La imagen de perfil que desea usar muestra sus habilidades, así que debe ser apreciada por todos los visitantes del sitio. Por eso, vamos a agregar un atributo <code>alt</code> en la etiqueta <code>img</code> que explique que el gato campero está haciendo karate. (Porque la dirección de la imagen en el atributo <code>src</code> no se vincula a un archivo real, verás en su lugar la descripción que escribiste en el atributo <code>alt</code> en vez de la imagen en la pantalla). </section>

## Pruebas
<section id='tests'>

```yml
tests:
  - text: 'Su etiqueta <code>img</code> debe tener un atributo <code>alt</code> , y su descripción no debe estar vacia.'
    testString: 'assert($("img").attr("alt"), "Your <code>img</code> tag should have an <code>alt</code> attribute, and it should not be empty.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<img src="doingKarateWow.jpeg">

```

</div>



</section>

## Solución
<section id='solution'>

```js
// solution required
```
</section>
