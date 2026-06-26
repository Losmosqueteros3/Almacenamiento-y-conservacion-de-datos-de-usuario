# Almacenamiento-y-conservacion-de-datos-de-usuario
En JavaScript se pueden guardar datos de los usuarios para utilizarlos mas adelante cuando tengamos que hacer una pagina web y esto nos puede ayudar a recordar informacion importante como los nombres o las preferencias y para poder hacer esto necesitamos utilizar herramientas como localStorage y sessionStorage que nos ayudan a conservar los datos mientras el usuario usa la pagina o incluso despues de cerrarla

EJEMPLO:
# localStorage.setItem("nombre","Naomi");

# USO DE COOKIES
Las cookies son los pequeños archivos que muchas veces se nos guardan en nuestros navegadores y su funcion es poder recordar buena informacion para que la pagina sea mucho mejor y pues tambien ayudan mucho por que muchas veces nosotros mismos olvidamos los datos que ponemos siempre y pues esto recuerda los datos que nosotros como usuarios ya hemos puesto

EJEMPLO:
# document.cookie = "usuario=Naomi";

# CREACION DE SESIONES
Las sesiones nos sirven para poder identificar un usuario mientras el navega por una pagina web y en JavaScript podemos utilizar sessionStorage para poder guardar alguna informacion temporalmente y esta permanece disponible mientras nuestra pestaña del navegador este abierta 

EJEMPLO:
# sessionStorage.setItem("usuario","Naomi");

# ELIMINACION DE SESIONES 
Cuando nosotros como usuarios terminamos de utilizar nuestra pagina la informacion que ponemos puede eliminarse para que nuestros datos esten protegidos y esto nos ayuda a mantener todo en privacidad y la seguridad de toda nuestra informacion y todo es super mas seguro

EJEMPLO:
# sessionStorage.clear( );
Y tambien podemos borrar un solo dato que querramos 
# sessionStorage.removeItem("usuario");

# JavaScript nos ofrece muchas herramientas para que podamos almacenar nuestra informacion y podemos usar todas estas funciones que son importantes por que nos ayudan a mejorar nuestra experiencia y podemos proteger nuestros datos.


