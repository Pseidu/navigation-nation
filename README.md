# navigation-nation (Animated navigation)
En esta práctica partiremos de un HTML y un CSS ya dados y nos centraremos en la navegación.
Vemos que en el index.html tenemos definidas unas secciones con solo un título (h1) dentro.
Cada sección tiene asignado un color (desde el CSS).
Recordatorio: Uso de variables en CSS (https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
Con respecto al uso de una determinada paleta de colores en una página, un recurso nuevo que utilizamos en esta página es:
https://paletton.com/ (Paletton, Color Selection Tool)
Para el menú animado, (hamburguer) hemos tomado como referencia W3Schools.com
[How to create a menu Icon](https://www.w3schools.com/howto/howto_css_menu_icon.asp)
La imagen de fondo, como siempre de [unsplash.com](https://unsplash.com/es)
La fuente que utilizaremos, nunito, también como siempre de [Google Fonts](https://fonts.google.com/?query=nunito)

const menuBars = document.getElementById("menu-bars");
menuBars.classList.toggle("change");
classList hace referencia a las clases que tiene definidas ese elemento HTML
toggle pone la clase si no estaba en la classList, y la quita si ya estaba. (La clase "change" está definida en el CSS. Se "activará" cuando la ponemos y se "desactivará" cuando la quitamos) 