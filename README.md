
# Práctica 4: API REST JSON 

### Pedro Cuevas

---

## Introducción

En la web de Telefónica creada para la p3, he añadido una página nueva con un buscador de datos de la pandemia: [https://pedro-cuevas.github.io/p4/info_covid.html](https://pedro-cuevas.github.io/p4/info_covid.html)

El usuario tiene la opción de introducir el país que desea buscar, o alternativamente puede pulsar un botón que detecta el país del usuario alternativamente, por medio de su IP pública. En caso de error, se mostrará un mensaje correspondiente en lugar de los contadores de datos.

## APIs utlizadas

- [COVID-19 API](https://covid19api.com/): API para obtener los datos del coronavirus
- [MY-IP](https://api.my-ip.io/ip.json): API para obtener la dirección IP pública del usuario
- [IP2COUNTRY](https://api.ip2country.info/ip?): esta API devuelve información geográfica sobre una IP. La he usado para saber el país del usuario

## Otros recursos utilizados

Para poder programar de manera más comoda, he utlizado la librería jquery.

## Archivos relevantes

- docs/info_covid.html: el HTML de la web creada
- docs/assets/js/covid.js: el código de javascript creado por mí