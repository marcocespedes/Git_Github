Por lo general un proyecto puede correr en distintos entornos. Los más comunes de éstos son:

## Desarrollo (development)

> Una aplicación corre en este modo cuando aún se está desarrollando. Por ejemplo, para el caso de una aplicación web, si sigues manipulando el código y haciendo pruebas locales en tu máquina, estás en la fase de desarrollo.

## Prueba (test)

> Si estás haciendo desarrollo con pruebas unitarias (Test Driven Development), programarás pruebas que garanticen que tu aplicación funciona y cumple con una serie de requerimientos. Cuando ejecutas estas pruebas, muchas veces quieres tener ciertos datos fijos y ejecutar tu aplicación con una configuración determinada. Para ello existe este entorno.

## Pruebas de producción (staging)

> Ya que tu aplicación está casi lista, querrás hacer pruebas casi como se verá. Probablemente la cargues a un servidor de prueba, cuya configuración será prácticamente idéntica a la del servidor en la que correrá finalmente tu aplicación. Sin emabrgo, es posible que deshabilites cierta funcionalidad, como envíos de correo o conexión a servicios externos para evitar costos innecesarios en esta etapa. Por lo general en este modo se corren las pruebas de aceptación.

## Producción (production)


> Es el entorno en el que corre la aplicación que ya utilizará el usuario final. Para este punto toda la funcionalidad de la aplicación debe estar disponible y cualquier conexión con un servicio externo debe estar habilitada.