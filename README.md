# Sitio Web Aerolineas

Se deberá realizar un sitio web para una aerolínea en donde a continuación se detallarán las páginas webs a crear:

1) Primera página que debe llamarse “login.html” la cual deberá permitir ingresar un mail y contraseña para poder acceder al sistema.
Se deberá validar (Jquery validate) que el mail sea correcto (formato email) y no esté en vacío, lo mismo para el password.
Cuando se hace el submit la validación será correcta si el email es “tup2022@tup.com.ar” y el password sea “123456”.
Si la validación es exitosa se deberá redirigir a la siguiente página, en caso contrario se deberá mostrar mensaje de error.

2) Segunda página donde se deba realizar el submit del formulario para dar de alta
un piloto, en donde se deberá validar (Jquery validate) los campos obligatorios
(todos). En caso de algún error de validación se deberá mostrar un alert con
dicho error, y si las validaciones son exitosas se deberá mostrar el mensaje de
éxito.

Titulo: Alta de piloto
Campos: 
* Nombre (requerido, no mayor a 30)
* Apellido (requerido, no mayor a 20)
* Cantidad de hs de vuelo (requerido, no menor a 50)
* Sexo (requerido)
* Nacionalidad (requerido)

### Aclaraciones:

El campo “Nacionalidad” deberá ser un select con los siguientes ítems
cargados:
* Seleccionar
* Argentina
* Uruguay
* Chile

## Mock ups

### Login
![image](https://github.com/fpiemontesi/utn-prog3-exam1-practice/assets/32469880/bfc0955e-4d70-42e3-ae08-27ed86e5aa29)

### Alta Piloto
![image](https://github.com/fpiemontesi/utn-prog3-exam1-practice/assets/32469880/837ee5a4-d958-4e3e-9344-2c10b088cffc)


## Consideraciones:
* TODAS LAS PÁGINAS DEBERÁN ESTAR DESARROLLADAS USANDO EL
FRAMEWORK DE BOOTSTRAP, UTILIZANDO LAS CLASES, Y LOS ESTILOS
PERTINENTES PARA QUE DICHAS PÁGINAS SEAN RESPONSIVES Y SE LOGREN
ADAPTAR A TODO TIPO DE PANTALLA.
* CON LA FINALIDAD DE QUE LA CARPETA DEL PROYECTO PESE LO MENOS
POSIBLE, SE DEBERAN REFERENCIAR LAS IMÁGENES, SCRIPTS, Y ARCHIVOS CSS A
SUS RESPECTIVOS LINKS DE INTERNET Y NO REFERENCIARLOS LOCALMENTE.
* TODOS LOS FORMULARIOS DEBERÁN ESTAR COLOCADOS EN UN CONTENEDOR
QUE POSEA MÁRGENES EN LA IZQUIERDA Y EN LA DERECHA.
