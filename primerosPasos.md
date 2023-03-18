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

### Acceder a una variable mediante una etiqueta que contenga

```jsx
 //Accede al elemento por medio de la etiqueta 'li'. 
console.log(document.getElementsByTagName('li'));
//Accede al elemento por medio de la clase 'card'.
console.log(document.getElementsByClassName('card')); 
//Accede a los elementos por medio del atributo "name" del documento, name se utiliza en los formularios.
console.log(document.getElementsByName('nombre'));
//Accede a los elementos por medio del identificador tipo id con el nombre "menu".
console.log(document.getElementById('menu'));
//Accede al elemento por medio de la etiqueta 'a'. Accede solo a el primer elemento de tipo 'a' del documento.
console.log(document.querySelector('a'));
//Accede al elemento por medio de la etiqueta a. Accede a todos los elemento de tipo 'a' del documento.
console.log(document.querySelectorAll('a'));
//Accede al elemento por medio de la clase '.card".
console.log(document.querySelector('.card'));
//Accede a los elementos por medio del identificador tipo id con el nombre #card'.
console.log(document.querySelector('#card'));
//Accede al elemento por medio de la clase card' y busca el elemento en la posicion indicada.
console.log(document.querySelectorAll('.card')[2]);
//Accede a todos los elementos 'li' que tengan la clase 'menu'.
console.log(document.querySelectorAll('.menu li'));
```







> # Modificar el HTML desde nuestro codigo en JS
- Agregar html a nuestro codigo desde la ventana de JS
```jsx
p.innerHTML = '<style>.parrafo-2 {color:blue}</style> <p>Hola mundo</p>'.
```
- Agregar simplemente texto
```jsx
p.innerText = 'Hola mundo este es un texto de prueba'
```
- Modificar un atributo










> # Eventos
### Escuchador de eventos y su estructura
1. Etiqueta que estara escuchando el evento
2. Escuchador de eventos
3. Tipo de evento que escuchara
4. Funcion que realizara cuando el evento sea escuchado.
```jsx
button.addEventListener('click', function);
```
### Diferentes tipos de eventos
- Click : El evento que escucha es cuando le das click a la etiqueta que lo contiene.
- blur : Este evento se presenta cuando sales de un campo por ejemplo de un formulario.
- input : Este evento se activa cada que estamos escribiendo un texto en pantalla.

















.
