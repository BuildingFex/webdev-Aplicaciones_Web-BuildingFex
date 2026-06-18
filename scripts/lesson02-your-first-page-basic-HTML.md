# GUION COMPLETO – VIDEO 2: TU PRIMERA PÁGINA: HTML BÁSICO

**Duración aproximada: 10 minutos**

---

## Diapositiva 1. Portada

**Tiempo aproximado: 40 segundos**

### Texto en pantalla

**Tu primera página: HTML básico**

Aprende a crear tu primera página web paso a paso.

### Narración

"¡Hola! Bienvenidos a este nuevo video del curso de desarrollo web.

En el video anterior aprendimos qué es una página web y cómo forma parte de nuestra vida diaria. Ahora ha llegado el momento más emocionante: vamos a crear nuestra primera página utilizando HTML.

No te preocupes si nunca has programado antes. Este video está pensado para personas que están comenzando desde cero. Vamos a avanzar paso a paso, explicando cada concepto con ejemplos sencillos.

Al finalizar este video habrás creado tu primera página web básica y entenderás cómo están organizadas muchas de las páginas que visitas todos los días.

Así que prepárate, porque hoy escribirás tus primeras líneas de código."

---

## Diapositiva 2. ¿Qué es HTML?

**Tiempo aproximado: 1 minuto**

### Texto en pantalla

HTML = HyperText Markup Language

El lenguaje que estructura una página web.

### Narración

"Primero debemos responder una pregunta importante: ¿qué es HTML?

HTML significa HyperText Markup Language, que en español se puede traducir como Lenguaje de Marcado de Hipertexto.

Aunque el nombre parece complicado, la idea es bastante sencilla.

Imagina que quieres construir una casa. Necesitas paredes, puertas, ventanas y habitaciones. HTML cumple una función parecida: proporciona la estructura básica de una página web.

Gracias a HTML podemos indicar qué partes del contenido son títulos, cuáles son párrafos, dónde aparecerán imágenes y qué elementos servirán como enlaces.

Sin HTML, una página web sería simplemente un conjunto de textos sin organización.

Por eso se dice que HTML es el esqueleto o la estructura de un sitio web."

---

## Diapositiva 3. ¿Dónde escribiremos nuestro código?

**Tiempo aproximado: 45 segundos**

### Texto en pantalla

Usaremos CodePen.

• Gratuito
• En línea
• No requiere instalación

### Narración

"Para practicar no necesitaremos instalar programas en nuestra computadora.

Utilizaremos una herramienta gratuita llamada CodePen.

CodePen funciona directamente desde el navegador. Solo debemos abrir la página y podremos escribir código inmediatamente.

Esto es muy útil para quienes están aprendiendo, porque evita configuraciones complicadas y nos permite concentrarnos en entender cómo funciona HTML.

En la descripción del video encontrarás un enlace para acceder al editor y practicar por tu cuenta."

---

## Clip: Mostrar CodePen

**Tiempo aproximado: 20 segundos**

Narración:

"Cuando abras CodePen verás varias secciones. Nosotros trabajaremos principalmente en la sección llamada HTML, donde escribiremos nuestro código."

---

## Diapositiva 4. La estructura básica de una página

**Tiempo aproximado: 2 minutos**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi primera página</title>
</head>

<body>

</body>
</html>
```

### Narración

"Puede parecer mucho texto al principio, pero vamos a analizarlo parte por parte.

La primera línea, llamada DOCTYPE, le indica al navegador que estamos utilizando una versión moderna de HTML.

Después encontramos la etiqueta HTML. Esta etiqueta funciona como el contenedor principal de toda nuestra página.

Dentro de ella aparece la sección HEAD.

El HEAD almacena información importante sobre la página, aunque normalmente esa información no es visible directamente para los visitantes.

Dentro del HEAD tenemos la etiqueta TITLE.

El contenido del TITLE aparecerá como el nombre de la pestaña del navegador.

Finalmente encontramos la etiqueta BODY.

Esta es probablemente la parte más importante para nosotros, porque dentro del BODY colocaremos todo el contenido que verá el usuario: títulos, textos, imágenes, listas y mucho más.

Podemos pensar que el BODY es el espacio donde realmente construimos nuestra página."

---

## Diapositiva 5. ¿Qué son las etiquetas?

```html
<h1>Mi primer título</h1>
```

### Narración

"HTML funciona mediante etiquetas.

Las etiquetas son instrucciones que le dicen al navegador qué debe mostrar y cómo organizar la información.

La mayoría de etiquetas tienen una apertura y un cierre.

Por ejemplo, si queremos escribir un título utilizamos una etiqueta de apertura, escribimos el contenido y luego colocamos la etiqueta de cierre.

Todo lo que está entre ambas etiquetas forma un elemento HTML.

Esta idea es fundamental porque la utilizarás constantemente cuando sigas aprendiendo desarrollo web."

---

## Diapositiva 6. Agregando nuestro primer título

```html
<body>
    <h1>Hola, soy Ana</h1>
</body>
```

### Narración

"Vamos a añadir nuestro primer contenido.

La etiqueta H1 se utiliza para crear títulos principales.

La letra H proviene de la palabra heading, que significa encabezado o título.

Existen varios niveles de encabezados, pero H1 representa el más importante.

Al guardar o ejecutar el código, veremos que el texto aparece grande y destacado.

Esto indica al navegador que se trata del título principal de nuestra página."

---

## Diapositiva 7. Agregando un párrafo

```html
<p>
Bienvenido a mi primera página web.
Estoy aprendiendo HTML.
</p>
```

### Narración

"Ahora agregaremos un párrafo utilizando la etiqueta P.

La letra P proviene de la palabra paragraph, que significa párrafo.

Los párrafos sirven para escribir descripciones, explicaciones o cualquier bloque de texto que queramos mostrar."

---

## Diapositiva 8. ¿Qué son los atributos?

```html
<p title="Este mensaje aparece al pasar el mouse">
Estoy practicando HTML.
</p>
```

### Narración

"Además de las etiquetas, HTML también utiliza atributos.

Los atributos añaden información extra a un elemento.

Piensa en ellos como características especiales."

---

## Diapositiva 9. ¡Tu turno!

- Cambia el título por tu nombre.
- Escribe un párrafo sobre tu pasatiempo favorito.
- Modifica el título de la pestaña.

---

## Diapositiva 10. Resultado final

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi primera página</title>
</head>

<body>
    <h1>Hola, soy Ana</h1>

    <p>
        Bienvenido a mi primera página web.
        Estoy aprendiendo HTML.
    </p>

    <p title="Este mensaje aparece al pasar el mouse">
        Estoy practicando HTML.
    </p>
</body>
</html>
```

---

## Diapositiva 11. Despedida

¡Felicitaciones por llegar hasta aquí!

En el siguiente video aprenderás a enriquecer tu página utilizando listas, imágenes y enlaces para hacerla más útil e interesante.
