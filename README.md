# tp-01-final

Alumna: Im Yoo Ri
Profesor: Martínez Luciano
Materia: Contenidos y creatividad.
El proyecto se trata de una casa de música que vende instrumentos como el piano, guitarra y batería. Se basó en el Chat Gpt para la codificación y después se le añadió una imagen extraída de google. 
Para visualizar el sitio en el git hub pages hay que ir al enlace proporcionado. Una vez codificado en el visual studio code se hace un repositorio y se carga la página para obtener un enlace en settings-page para visualizar la página web.

El javascript utilizado cambia de color de fondo 

function changeBackgroundColor() {
    document.body.style.backgroundColor = document.body.style.backgroundColor === 'lightblue' ? '#f4f4f4' : 'lightblue';

y muestra e oculta la imagen principal de la página.

function toggleElement() {
    const imgElement = document.querySelector('img');
    if (imgElement.style.display === 'none') {
        imgElement.style.display = 'block';
    } else {
        imgElement.style.display = 'none';
    }

