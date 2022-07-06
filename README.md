# Valhalla Frontend Challenge

La idea detrás de este desafío es poder conocerte un poco más y evaluar tu conocimiento técnico.

Debes resolver el desafío y subirlo a un repositorio público (del estilo GitHub).

## ¿Te gustaría trabajar como parte del equipo PentaFinanciero?

Cuéntanos en términos no formales:

1. Una descripción de ti, que incluya (entre otros) pasiones y pasatiempos.
2. ¿Qué es lo que más disfrutas de tu trabajo?
3. ¿Qué es lo que te motiva a participar en esta postulación?

## ¿Conoces el sitio [IMDB](https://www.imdb.com/)?

¿De verdad no lo conoces? Deberías utilizarlo, es muy práctico para evaluar si vale la pena ver una película o serie. :wink:

Es un portal referente con toda (o casi toda) la información respecto a películas, series, programas de televisión, videojuegos y más. Nos percatamos de que hace más de 10 años fue adquirida por el gigante Amazon :scream:.

Lo otro interesante de IMDB es que tiene una [API pública](https://imdb-api.com/) que es la que utilizaremos para este desafío, y para ello te debes [registrar](https://imdb-api.com/Identity/Account/Register) y obtener tu ApiKey.

Bueno, a lo que nos convoca. La [especificación de la API](https://imdb-api.com/swagger/index.html) está en formato OpenAPI 3, pero te recomendamos revisar la documentación que aparece cuando ingresas al [sitio de de la API pública](https://imdb-api.com/).

### El proyecto

Tendrás que desarrollar un proyecto en React que haga uso de la librería Material UI y que entregue como resultado una vista sencilla que plasme la información que te entregue la api https://imdb-api.com/en/API/Top250Movies/{apiKey} a través de algún componente tipo ***data display***. Los campos por mostrar son los siguientes:

- rank
- title
- crew
- image
- year
- imDbRating

La idea es que tengas la libertad de elegir el componente que mostrará la información (siempre considerando que sea de manera clara y ordenada), y para el manejo de la cantidad de registros, implementar algún método de paginación que sea de tu preferencia. No es necesario hacer mucho uso de css, la idea es que puedas utilizar lo que te provee la librería, por lo mismo te ayudamos con un skeleton de referencia a continuación.

<p align="center">
  <img width="514" alt="Skeleton de referencia" src="https://user-images.githubusercontent.com/108825242/177632288-800e0b7a-f9d2-4d5f-8bed-cbf2f9ca7476.png">
  <br/>
  <sub>1. Skeleton de referencia</sub>
</p>

### A tener en cuenta

* **El código debe ser claro**, piensa que no siempre serás tú el que tenga que modificarlo.
* **Organiza tu solución**, siempre es importante aplicar las prácticas necesarias para que, tanto el código como la lógica implementada, sigan una arquitectura bien definida.
* **Estructura**, tal como lo has podido evidenciar en librerías que has usado previamente, es muy importante contar un `README.md`, organización de carpetas y archivos y uso de estándares.
* **Tests**, claves para que futuros cambios al código no afecten las funcionalidades actuales.
* **Performance**, siempre será importante que la solución sea eficiente en el uso de recursos y en tiempos de respuesta, o más bien, un equilibrio entre ambas.
* **Un tip a considerar**, [para que veas que somos buenos partners 😉](https://www.google.com/search?q=imdb+api+limit&rlz=1C5CHFA_enCL986CL987&sxsrf=ALiCzsZ9RLKX55COVW_c0j6mi4ARUvgGgA%3A1657125179295&ei=O7nFYvbXEba75OUPhNeXWA&oq=imdb+api+&gs_lcp=Cgdnd3Mtd2l6EAMYADIGCCMQJxATMgUIABDLATIFCAAQywEyBQgAEMsBMgUIABDLATIFCAAQywEyBQgAEMsBMgUIABDLATIFCAAQywEyBQgAEMsBOgcIABBHELADOgsIABCABBCxAxCDAToICAAQsQMQgwE6EQguEIAEELEDEIMBEMcBEKMCOgQIABADOggILhCxAxCDAToECAAQQzoECC4QQzoQCC4QsQMQgwEQxwEQ0QMQQzoNCC4QxwEQ0QMQ1AIQQzoKCAAQsQMQgwEQQzoKCC4QxwEQ0QMQQzoHCC4Q1AIQQzoLCC4QgAQQsQMQgwE6BQgAEIAEOgUILhCABEoECEEYAEoECEYYAFD3E1jnHmCSJWgBcAF4AIABP4gBjwSSAQE5mAEAoAEByAEIwAEB&sclient=gws-wiz)

¡Éxito! ¡Esperamos tu postulación!
