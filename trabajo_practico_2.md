1.- Procesos
a) ¿Qué es un proceso? ¿A que hacen referencia las siglas PID y PPID?
¿Todos los procesos tienen estos atributos en GNU/Linux? Justifique.
Indique qué otros atributos tiene un proceso.
b) Indique qué comandos se podrían utilizar para ver qué procesos están en ejecución en un sistema GNU/Linux.
c) ¿Qué significa que un proceso se está ejecutando en Background? ¿Y en Foreground?
d) ¿Cómo puedo hacer para ejecutar un proceso en Background? ¿Como puedo hacer para pasar un proceso de background a foreground y viceversa?
e) Pipe ( | ). ¿Cual es su finalidad? Cite ejemplos de su utilización.
f) Redirección. ¿Qué tipo de redirecciones existen? ¿Cuál es su finalidad? Cite ejemplos de utilización.
g) Comando Kill. ¿Cuál es su funcionalidad? Cite ejemplos.
h) Investigue la funcionalidad y parámetros de los siguientes comandos relacionados con el manejo de procesos en GNU/Linux.
ps : muestra información sobre una selección de los procesos activos

kill: s un comando utilizado para enviar mensajes sencillos a los procesos ejecutándose en el sistema. Por defecto el mensaje que se envía es la señal de terminación (SIGTERM), que solicita al proceso limpiar su estado y salir.

pstree: Muestra en vista de árbol (de forma jerárquica) una lista de los procesos en ejecución.

killall:este programa es llamado automáticamente cuando se apaga el sistema. Se comporta de forma parecida al comando kill, pero en lugar de enviar una señal a un proceso, se envía a todos los procesos del sistema.Matar todos los procesos.

top: da información acerca del uso de la cpu, de la memoria, de los procesos en ejecución, etc en tiempo real.

nice:Ejecuta un comando con una prioridad determinada, o modifica la prioridad a de un proceso (programa en ejecución). Utiliza una prioridad variable que parte de la prioridad del shell y suma o resta valores. Mientras menor es el valor de la prioridad mayor prioridad tiene el proceso.

2.- Arranque de un Sistema Operativo
a) ¿Qué es el MBR? ¿Que es el MBC?
b) ¿Cuál es la funcionalidad de un “Gestor de Arranque”? ¿Qué tipo existen?
¿Dónde se instalan? Cite gestores de arranque conocidos.
c) Cuáles son los pasos se suceden desde que se prende una computadora hasta
que el Sistema Operativo es cargado (bootstrap).
d) ¿Es posible tener en una PC GNU/Linux y otro Sistema Operativo instalado?
Justifique.
3.- Distribuciones de GNU/Linux
a) ¿Qué es una distribución de GNU/Linux? Nombre las principales distribuciones de
GNU/Linux y cite diferencias básicas entre ellas.
b) ¿En qué se diferencia una distribución de otra?
4.- Estructura de GNU/Linux.
a) Nombre cuales son los 3 componentes más fundamentales de GNU/Linux.
b) Mencione y explique la estructura básica del Sistema Operativo GNU/Linux.
5.- Kernel
a) ¿Qué es? Indique una breve reseña histórica acerca de la evolución del Kernel de
GNU/Linux
b) ¿Cuáles son sus funciones principales?
c) ¿Cuál es la versión actual? ¿Qué versiones existen? ¿Cómo se las diferencian?
d) Es posible tener más de un Kernel de GNU/Linux.
e) ¿Donde se encuentran ubicados dentro del File System?
f) ¿El Kernel de GNU/Linux es monolítico? Justifique.
6.- Intérprete de comandos (Shell)
a) ¿Qué es?
b) ¿Cuáles son sus funciones?
c) Mencione al menos 3 tipos de intérpretes de comandos que posee GNU/Linux.
d) ¿Donde se ubican (ruta) los comandos propios y externos al Shell?
e) ¿Por qué considera que el Shell no es parte del Kernel de GNU/Linux?

7.- Comandos (Investigue su funcionamiento y parámetros más importantes):
lspci
cd
at
ls
touch
pwd
shutdown
head
reboot
mount
halt
umount
find
locate
write
uname
mkfs
dmesg
who
lsusb
ifconfig
man
less
cat
su
8.- Indique en qué directorios se almacenan los comandos mencionados en el ejercicio 

9.- Archivos
a) ¿Cómo se identifican los archivos en GNU/Linux?
b) Investigue el funcionamiento del editor nano, el comando more.
c) Cree un archivo llamado “prueba.exe” en su directorio personal usando el nano. El
mismo debe contener su número de alumno y su nombre.
d) Investigue el funcionamiento del comando file. Pruébelo con diferentes archivos.
¿Qué diferencia nota?
e) Utilice el editor nano para editar el archivo anteriormente creado.
10.- Usuarios
a) ¿Qué archivos son utilizados en un sistema GNU/Linux para guardar la
información de los usuarios?
b) ¿A que hacen referencia las siglas UID y GID? ¿Pueden coexistir UIDs
iguales en un sistema GNU/Linux? Justifique.
c) ¿Qué es el usuario root? ¿Puede existir más de un usuario con este perfil
en GNU/Linux? ¿Cuál es la UID del root?
d) Investigue la funcionalidad y parámetros de los siguientes comandos:
useradd ó adduser
usermod
userdel
groupadd
groupdel
passwd
11.- FileSystem
a) ¿Cómo son definidos los permisos sobre archivos en un sistema GNU/Linux?
b) Investigue la funcionalidad y parámetros de los siguientes comandos
relacionados con los permisos en GNU/Linux:
chmod
chown
chgrp
c) Al utilizar el comando chmod generalmente se utiliza una notación octal asociada para definir permisos. ¿Qué significa esto? ¿A qué hace referencia cada valor?
d) ¿Existe la posibilidad de que algún usuario del sistema pueda acceder a determinado archivo para el cual no posee permisos? Nombrelo, y realice las pruebas correspondientes
e) Explique los conceptos de “full path name” y “relative path name”. De ejemplos claros de cada uno de ellos.
f) ¿Con qué comando puede determinar en qué directorio se encuentra actualmente? ¿Existe alguna forma de ingresar a su directorio personal sin necesidad de escribir todo el path completo? ¿Podría utilizar la misma idea para acceder a otros directorios? ¿Cómo? Explique con un ejemplo
g) Investigue la funcionalidad y parámetros de los siguientes comandos relacionados con el uso del FileSystem:
df
mkdir
ln
rmdir
mount
pwd
umount
cp
du
mv

12.- Otros comandos de Linux:
a) ¿A qué hace referencia el concepto de empaquetar archivos en GNU/linux?
b) Seleccione 4 archivos dentro de algún directorio al que tenga permisos y sume el tamaño de cada uno de estos archivos. Cree un archivo empaquetado conteniendo estos 4 archivos y compare los tamaños de los mismos. ¿Qué característica nota?
c) ¿Qué acciones debe llevar a cabo para comprimir 4 archivos en uno solo?
Indique la secuencia de comandos ejecutados
d) ¿Pueden comprimirse un conjunto de archivos utilizando un único comando?
e) Investigue la funcionalidad de los siguientes comandos:
tar
grep
gzip
zgrep
wc
13.- Indique que acción realiza cada uno de los comandos indicados a continuación
considerando su orden. Suponga que se ejecutan desde un usuario que no es root ni
pertenece al grupo de root. (Asuma que se encuentra posicionado en el directorio de
trabajo del usuario con el que se logueo). En caso de no poder ejecutarse el comando
indique la razón:
ls -l > prueba
ps > PRUEBA
chmod 710 prueba
chown root:root PRUEBA
chmod 777 PRUEBA
chmod 700 /etc/passwd
passwd root
rm PRUEBA
man /etc/shadow
find / -name *.conf
usermod root –d /home/newroot -L
cd /root
rm *
cd /etc
cp * /home –R
shutdown
14.- Indique que comando sería necesario ejecutar para realizar cada una de las siguientes acciones:
a) Terminar el proceso con PID 23
b) Terminar el proceso llamado init. ¿Qué resultados obtuvo?
c) Buscar todos los archivos de usuarios en los que su nombre contiene la cadena “.conf”
d) Guardar una lista de procesos en ejecución el archivo /home/<su nombre de usuario>/procesos
e) Cambiar los permisos del archivo /home/<su nombre de usuario>/xxxx a:
a. Usuario: Lectura, escritura, ejecución
b. Grupo: Lectura, ejecución
c. Otros: ejecución
f) Cambiar los permisos del archivo /home/<su nombre de usuario>/yyyy a:
a. Usuario: Lectura, escritura.
b. Grupo: Lectura, ejecución
c. Otros: Ninguno
g) Borrar todos los archivos del directorio /tmp
h) Cambiar el propietario del archivo /opt/sodata al usuario so2014.
i) Guardar en el archivo /home/<su nombre de usuario>/data el directorio donde me encuentro en este momento, en caso de que el archivo exista no se debe eliminar su contenido anterior
15.- Indique que comando sería necesario ejecutar para realizar cada una de las siguientes acciones:
a) Ingrese al sistema como usuario “root”
b) Cree un usuario. Elija para como nombre, por convención, la primer letra de su
nombre seguida de su apellido. Asígnele una contraseña de acceso.
c) ¿Qué archivos fueron modificados luego de crear el usuario y qué directorios
se crearon?
d) Crear un directorio en /tmp llamado cursada2015
e) Copiar todos los archivos de /var/log al directorio antes creado.
f) Para el directorio antes creado (y los archivos y subdirectorios contenidos en
él) cambiar el propietario y grupo al usuario creado y grupo users.
g) Agregue permiso total al dueño, de escritura al grupo y escritura y ejecución a
todos los demás usuarios para todos los archivos dentro de un directorio en forma recursiva.
h) Acceda a otra terminal virtual para loguearse con el usuario antes creado.
i) Una vez logueado con el usuario antes creado, averigüe cual es el nombre de su terminal.
j) Verifique la cantidad de procesos activos que hay en el sistema.
k) Verifiqué la cantidad de usuarios conectados al sistema.
l) Vuelva a la terminal del usuario root, y envíele un mensaje al usuario anteriormente creado, avisándole que el sistema va a ser apagado.
m) Apague el sistema.
16.- Indique que comando sería necesario ejecutar para realizar cada una de las siguientes acciones:
a) Cree un directorio cuyo nombre sea su número de legajo e ingrese a él.
b) Cree un archivo utilizando el editor de textos nano, e introduzca su información personal: Nombre, Apellido, Número de alumno y dirección de correo electrónico. El archivo debe llamarse LEAME.
c) Cambie los permisos del archivo LEAME, de manera que se puedan ver reflejados los siguientes permisos:
Dueño: ningún permiso
Grupo: permiso de ejecución
Otros: todos los permisos
d) Vaya al directorio /etc y verifique su contenido. Cree un archivo dentro de su directorio personal cuyo nombre sea leame donde el contenido del mismo sea el listado de todos los archivos y directorios contenidos en /etc. ¿Cuál es la razón por la cuál puede crear este archivo si ya existe un archivo llamado LEAME en este directorio?
e) ¿Qué comando utilizaría y de qué manera si tuviera que localizar un archivo dentro del file system? ¿Y si tuviera que localizar varios archivos con características similares? Explique el concepto teórico y ejemplifique 
f) Utilizando los conceptos aprendidos en el punto e), busque todos los archivos cuya extensión sea .so y almacene el resultado de esta búsqueda en un archivo dentro del directorio creado en a). El archivo deberá llamarse ejercicio_f
17.- Indique que acción realiza cada uno de los comandos indicados a continuación considerando su orden. Suponga que se ejecutan desde un usuario que no es root ni pertenece al grupo de root. (Asuma que se encuentra posicionado en el directorio de trabajo del usuario con el que se logueó). En caso de no poder ejecutarse el comando indique la razón:
1) mkdir so2015
2) cd ./so2015; ps > f0
3) ls > f1
4) cd /
5) echo $HOME
6) ls -l > $HOME/so2015/ls
7) cd $HOME; mkdir f2
8) ls –ld f2
9) chmod 341 f2
10) touch dir
11) cd f2
12) cd ~/so2015
13) pwd >f3
14) ps | grep 'ps' | wc -l >> ../f2/f3
15) chmod 700 ../f2; cd ..
16) find . -name etc/passwd
17) find / -name etc/passwd
18) mkdir ejercicio5
Inicie 2 sesiones utilizando su nombre de usuario y contraseña. En una sesión vaya siguiendo paso a paso las órdenes que se encuentran escritas en el cuadro superior. En la otra sesión, cree utilizando algún editor de textos un archivo que se llame ejercicio_explicacion dentro del directorio creado en el ejercicio 18-a y, para cada una de las órdenes que ejecute en la otra sesión, realice una breve explicación de los resultados obtenidos.
