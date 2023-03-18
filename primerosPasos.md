> # Preguntas clave en la programacion de JS
#### 1. Como podemos conectar JS con nuestro codigo de html
```jsx
// Se usa la etiqueta script y se coloca en la parte inferior de nuestro codigo html
<script src="./script.js"></script>
```

> # Diferentes tipos de funciones y como podemos llegar a usarlas
```jsx
p.classList; // Nos retorna las clases que contiene nuestra etiqueta de p.
p.classList.add('red') // Nos agrega una clase con el nombre de "red".
p.classList.remove('red') // Nos elimina una clase con el nombre de "red".
p.classList.contains('red') // Nos analiza nuestra etiqueta para ver si contiene una etiqueta con el nombre de red.
p.trim // Nos elimina todods los espacios en blanco que los usuarios le incluyan a nuestro formulario.
```

> # Modificar el HTML desde nuestro codigo en JS
Se agrega html a nuestro codigo desde nuestra ventana de JS
```jsx
p.innerHTML = '<style>.parrafo-2 {color:blue}</style> <p>Hola mundo</p>'.
.
// En este caso se agrega simplemente texto a nuestro html
p.innerText = 'Hola mundo este es un texto de prueba'
```

> # Eventos
#### 1. Escuchador de eventos y su estructura
```jsx
1. Etiqueta que estara escuchando el evento
2. Escuchador de eventos
3. Tipo de evento que escuchara
4. Funcion que realizara cuando el evento sea escuchado.
 .
 .
button.addEventListener('click', function);
```
