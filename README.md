La declaración <!DOCTYPE html> especifica que el documento es un documento HTML5.
Se establece el idioma de la página en español con <html lang="es">.
En el <head>, se especifican metadatos como el juego de caracteres (UTF-8) y la configuración de la vista del dispositivo.
Se asigna un título a la página: "Personajes de Rick and Morty".
Se importa el archivo CSS de Bootstrap desde un CDN (https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css), lo que proporciona estilos predefinidos para el diseño.
También se carga un archivo CSS local (../css/bootstrap.min.css), posiblemente para personalizaciones adicionales.
Se define un estilo en línea para el fondo del cuerpo de la página, utilizando una imagen de fondo de la serie.
Otro estilo en línea define el color y la fuente del título <h1>.
Se crea un contenedor <div> con la clase "container" que envuelve el contenido principal.
Dentro del contenedor, hay un título <h1> con las clases "mt-5 mb-4" para margen superior e inferior.
Un <div> con el id "characters" y la clase "row" se utiliza para mostrar los personajes, pero no se proporciona contenido directamente en el HTML; probablemente se llenará dinámicamente utilizando JavaScript.
Se incluyen varios archivos JavaScript al final del cuerpo de la página: jQuery, Popper.js y Bootstrap JavaScript, junto con un archivo de script local (../js/rickymorty.js), que probablemente maneja la carga y visualización de los personajes.
