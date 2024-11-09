# Ejercicio Práctico: Implementación de SASS y Framework CSS en el Sitio Web del Hospital
## Descripción
El repositorio "tarea_3" contiene el código desarrollado para una página web de “Clínica Chillán”. Para el desarrollo de este proyecto se han utilizado los lenguajes HTML, el preprocesador SASS y Bootstrap personalizado.

### Modalización de estilos SASS
Para la modalización de los estilos se utilizó Sass, utilizando características propias como mixins, declaración de variables, y anidación. para mejorar el orden y mantenibilidad los estilos se utilizó una estructura de carpetas basada en el patrón 7-1, implementada en la subcarpeta styles de la carpeta assets, su estructura es la siguiente: 
- abstract: carpeta que contiene 2 archivos asociados a la creación de variables y mixims
- base: carpeta que contine archivo asociada a la tipografía general asociada a la página web.
- components: carpeta que contine código sass asociado a 3 componentes desarrollados buttons, card, map.
- layout: carpeta que contiene archivos sass asociados a os estilos de header, footer, navegación, formularios, lista y main.
- pages: estilos específicos asociadas a las paginas principales del sitio web home, equipment y contact.
- themes: estilos asociados a temas claro y oscuro
- vendors: carpeta que contiene archivos asociados a librerías externas, en esta ocasión, esta carpeta toma importancia ya que contiene la carpeta Bootstrap donde se encuentra la personalización de sus estilos.
- main.scss: archivo encargado de importar todos los ficheros Sass descritos anteriormente.

### Uso de metodología BEM
Para la creación de clases de estilos propios se utilizó una nomenclatura de nombres basada en la metodología BEM, distinguiendo los estilos de acuerdo así representaban un bloque, un elemento o un modificador, por ejemplo, una de la convención de nombres utilizada es la siguiente: 
```bash
  <nav class="header__nav">
            <ul class="nav__list">
                <li class="nav__item"><a class="nav__link" href="home.html">Inicio</a></li>
                <li class="nav__item"><a class="nav__link" href="equipment.html">Equipo</a></li>
                <li class="nav__item"><a class="nav__link" href="contact.html">Contacto</a></li>
            </ul>
        </nav>
```
### Integración de Bootstrap
En este proyecto también se integró el framework Bootstrap el cual permitió añadir componentes con estilos establecidos, como footers, navs, buttons y card. sin embargo, y una de los grandes aportes de su integración es que también nos permitió la personalización de algunos estos estilos, los cuales se encuentran presente en la carpeta assets/styles/vendors/_boostrap

### Visualización del proyecto
Para visualizar este proyecto se necesita que previamente cuentes con la instalación de:
- Git: [sitio de descarga] (https://git-scm.com/downloads)
- Node.js: [sitio de descarga] (https://nodejs.org/en/download/package-manager)
 -Visual Studio Code: [sitio de descarga] (https://code.visualstudio.com/download)
  
Para visualizar este proyecto debes clonar este repositorio, mediante el siguiente comando:
```bash
git clone https://github.com/lorenasotosanmartin/tarea_3
```
Luego mediante tu consola (cmd) posicionarte en la carpeta donde alojaste el proyecto y escribir el siguiente comando: 
```bash
npm  nit
```
Esto permitirá se cree los archivos y la carpeta node modules, necesario para la integración de los nuevos estilos y componentes utilizados.

Una vez cuentes con estos pases es recomendable que utilices un editor como Visual Studio Code para visualizar el código de cada archivo de una forma adecuada, para ello, es necesario contar con dos extensiones, las cuales pueden instalar escribiendo su nombre en la sección extensiones de Visual Studio Code y presionar la opción Install, la primera es Live Server, la cual, una vez instalada aparecerá una opción en la esquina inferior derecha de Visual Studio Code titulada como "Go live" la cual debes presionar, esto permitirá abrir una pestaña en tu navegador predeterminado y podrás visualizar todo el contenido de la página web. la segunda extensión que debes instalar es Live Sass Server, esta extensión, una vez instalada, te mostrara la opción "watch Sass" en la esquina inferior derecha la cual al ser seleccionada permitirá que se compile el código Sass incluido y ver los estilos creados en la página web. cabe destacar, que ambas opciones deben de ser seleccionadas de forma paralela para visualizar correctamente el sitio web de la clínica.

### Créditos y recursos de terceros
- Bootstrap: [sitio oficial] (https://getbootstrap.com/)
- Bootstrap icons: [Sitio oficial] (https://icons.getbootstrap.com/)
- Sass: [Sitio oficial] (https://sass-lang.com/)
- Estructura de patrón 7-1: [Repositorio utilizado como referencia] (https://gist.github.com/rveitch/84cea9650092119527bc)

  
