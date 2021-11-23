# Prueba-técnica-junior

Repositorio de las pruebas técnicas para el cargo de desarrollador Junior en la empresa Soluciones en epidemiología y salud ocupacional PC

#Notas importantes
1. En la prueba técnica no se pueden utilizar librerías de terceros como Bootstrap o tailwind para el diseño.
2. La estructura de las carpetas de la aplicación es a criterio propio.
3. Estructura del archivo JSON de la API: https://github.com/r-spacex/SpaceX-API/blob/master/docs/landpads/v4/all.md
4. Iconos de la aplicación https://www.flaticon.com/free-icon/startup_1067256?term=rocket&page=1&position=9&page=1&position=9&related_id=1067256&origin=search#
5. Para las peticiones Http puede usar Axios o Fetch API u otra librería que tenga conocimiento.

#Pasos a seguir

Con los siguientes requerimientos realize el desarrollo de la aplicación para Soluciones en epidemiología y salud ocupacional PC:

1. La aplicación consta de varias páginas html, con la cual el usuario puede interactuar, estas se encuentran en la barra lateral del diseño proporcionado.

2. Los vínculos de la barra lateral deben permitir la navegación por los diferentes módulos de la aplicación en una sección independiente. (no una pestaña nueva)

3. En la parte superior de los vínculos de navegación debe ir el nombre del módulo actual, es decir, si se encuentra en “Zona de lanzamiento 1”, en la parte superior debe verse ese texto.

4. Cada vez que el usuario mueva el ratón sobre algún vínculo de la barra lateral, debe tener un evento Hover que sombree el botón como se muestra en la imagen.

5. Cuando el usuario de clic en el botón hamburguesa, debe ocultar la barra lateral.

6. Cuando el usuario de clic en el botón entrar de cada uno de los módulos se debe pasar a una página nueva, conservando la barra superior e inferior y en su interior una etiqueta H1 con el nombre del módulo (se puede añadir cualquier diseño que desee).

7. Cuando se encuentra dentro de cada módulo debe hacer una petición a la API https://api.spacexdata.com/v4/landpads, y rederizar cada lanzamiento como un listado, cada una de los elementos mostrará la descripción, el nombre y otra información que considere relevante. El diseño sera implementado por el programador.

8. Cada fila debe tener un vinculo que abrirá en otra pestana del navegador, la información de wikipedia que proporciona la API.

9. La fuente de toda la aplicación es Montserrat que será descargada desde Google-fonts.

10. Esta aplicación debe ser Responsive, es decir adaptable a dispositivos móviles.

#Gracias por participar en el proceso de selección :D
