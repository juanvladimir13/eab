# Formularios basicos

> Los atributos en la etiqueta ```<form></form>``` significan:

> ```enctype```  
> Formato del contenido para enviar el formulario al servidor  
* **multipart/form-data**: Valor para enviar archivos  
* **application/x-www-form-urlencoded**: Valor por defecto  
* **autocomplete**: Controles del formulario completados automáticamente
por el navegador si tiene el valor en igual a `on`

> Las etiquetas de tipo ```<input type="checkbox">``` se utilizan para enviar multiples datos al servidor  

> Las etiquetas de tipo ```<input type="radio">``` se utilizan para enviar un solo dato al servidor, ademas todos los atributos de tipo `name` deben tener el mismo nombre

## Requisitos para ejecutar el ejemplo

Verificar si esta instalado `PHP`

* Ingresar al `cmd` o `terminal`, escribir el comando ```php --version``` presionar `Enter` en caso de mostrar la version de PHP prosigue a ejecutar el ejemplo

* Ingresar a la carpeta donde se encuentra el ejemplo utizando ruta relativa o absoluta con el `cmd`

* Ejecutar en el `cmd` el comando `php -S localhost:8080 -t .`

* Abrir el navegador web la ruta `localhost:8080/index.html`