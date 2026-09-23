# Notas de la práctica de Git

Tres cosas que aprendí (o repasé) en esta práctica:

1. **Git y GitHub no son lo mismo.** Git es el control de versiones que corre en tu
   computadora (commit, push, pull); GitHub es el servicio web donde viven los repos.
   Usar uno no implica tener el otro instalado.

2. **La configuración global (`git config --global`) se hace una sola vez por
   computadora.** Nombre, correo y editor por defecto quedan guardados y no hay que
   repetirlos cada vez que empiezas un proyecto nuevo.

3. **Las tablas en Markdown se arman con | y una fila de guiones (`---`)** que
   separa encabezados del contenido — y conviene revisarlas en la vista previa antes
   de subirlas, porque un | mal puesto rompe la tabla sin que nos demos cuenta.

4. **Un commit debe explicar el "qué" en pocas palabras.** El mensaje de commit no es
   para detallar todo el cambio, es para que alguien (incluidos nosotros mismos) entienda
   de un vistazo qué pasó revisando el historial con `git log`.

> En relaidad uso normalmente Git en mi carrera, así que la mayoría de esto era repaso más 
> que descubrimiento — pero creo que no está de más ver el flujo completo desde cero nuevamente.