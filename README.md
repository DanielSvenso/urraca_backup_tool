Autor

Daniel Svenson, 2024.
danielsvenson@protonmail.com


Descripción

Urraca Backup Tool es un script en Python 3 y Tkinter para realizar salvaguarda de ficheros y directorios usando 
la utilidad rsync y sus opciones presentandolas en una interfaz gráfica de usuario que intenta ser clara y con
opciones fácilmente visibles.
Está realizada sobre un sistema GNU/Linux usando, además de rsync, comandos de este sistema.
Es una aplicación funcional tal como se presenta aunque está en proyecto añadir mejoras tal como añadir
diferentes perfiles de ejecución.
Se ha desarrollado teniendo en consideración las necesidades de usuario, no la de administradores de sistemas
en las que, probablemente se requieran acciones más complejas.

Cuenta con la posibilidad de sincronizar datos de forma local, en un disco duro externo, por ejemplo, y 
la de realizar copias en remoto a través de un acceso por usuario y contraseña o de SSH. Las pruebas
para el trabajo remoto se han realizado desde un sistema GNU/Linux hacia uno Android en el que se ejecuta
el servicio sshd sobre la utilidad Termux. 

Localización de idioma: actualmente puede elegirse entre Español e Inglés.


Instalación

Se necesita la instalación de Python 3 y las librerías de Tkinter.
Actualmente no existe un instalador, pero es posible clonar el repositorio de github donde se halla alojada
o el fichero zip y, una vez descomprimido, ejecutar el fichero .py

Se adjunta un fichero ejemplo de configuración llamado urracabt.conf para una primera visualización rápida
de la interfaz. Sobre este mismo fichero se realizarán a través de la aplicación los cambios elegidos
por el usuario. Si no desea usar este fichero, recibirá notificación de ello y deberá elegir los parámetros
para el funcionamiento. Debe crear el directorio /home/usuario/pruebas_urraca o modificar este parámetro
antes de iniciar una copia si usa el fichero urracabt.conf añadido.


Licencia

Tanto el código como los ficheros de locaclización y el fichero de logo se distribuyen como sofware
libre bajo la licencia GNU GPL para cuya lectura se remite a la información en la web.


Observaciones

Cualquier tipo de sugerencia para la mejora de las funciones o adición de nuevas características
serán bienvenidas.








