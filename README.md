# bar-system

A simple system for take orders and controlling the management of a bar

## Idea inicial

Se busca crear un sistema donde la carta sea virtual, pero que no haya una necesidad de contar con conexión a internet para realizar el pedido de la orden. Sino que el cliente ingrese a un sitio web donde tendrá disponible toda la carta (sera principalmente para acceder desde dispositivos móviles), seleccione su pedido y genere un código QR en su dispositivo, para que luego el personal del establecimiento se acerque a dicha mesa con otro dispositivo Movil, y en la otra parte de lo que seria este sistema, escanee dicho QR donde se cargara el pedido de la mesa. La ubicación o identificador de la mesa tendrá que se cargado manualmente por el personal a la hora de tomar el pedido.

La parte del sistema donde se escanea el código QR, es solo para el acceso del personal del establecimiento, entonces se debe tener una autenticación y también la asignación de roles. Al cargar el pedido por QR se podrán realizar distintas alternativas. Como imprimir una "comanda" desde una impresora en el local (en caso que se prefiera tener un control de esa forma en la cocina), como también cargarla digitalmente y mostrarla en pantallas y/o otros dispositivos móviles.

Parte de la idea viene a ser una opción mas amigable con establecimientos que no tienen tanta implementación de la tecnología en sus sistema. Osea, de esta forma podemos hacer una implementación sencilla que en un futuro puede avanzar para volverse cada vez mas automatizada y compleja, a cambio de obtener mayor información y control del negocio, asi como también aumentar el confort o mejorar la experiencia del usuario en el establecimiento.

## Aplicación destinada al cliente

La función de esta es ofrecer una interfaz agradable, principalmente que sea mobile friendly donde el cliente pueda revisar, leer, consultar y seleccionar los elementos de su pedido para luego generar un código QR con la información de dicho pedido. Esta sera independiente del sistema del establecimiento. Algunas de las funcionalidades que tendrá serán:

- [ ] Ver información de la carta del establecimiento
- [ ] Definir si la cuenta se pagara por toda la mesa o por cada persona en la mesa
- [ ] Poder definir la cantidad de cada elemento del pedido
- [ ] Poder escribir notas o alguna aclaracion respecto a alguna parte del pedido
- [ ] Poder visualizar un carrito donde se vea el pedido completo, con el precio total
- [ ] Permitir modificar el pedido
- [ ] Generar un codigo QR del pedido
- [ ] Permitir editar el QR para modificar algun parametro del pedido
