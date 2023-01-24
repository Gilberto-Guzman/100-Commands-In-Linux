# 1. cat.

## Obtiene el contenido del archivo como salida en la ventana Terminal.
    cat .bash_logout

# 2. aptitude.

## Es una interfaz muy potente para el sistema de gestión de paquetes de Linux. Puede usar esta interfaz incorporada de aptitude para actualizar,instalar o eliminar cualquier paquete de aplicación en Linux o sus otras distribuciones.
    aptitude

### Nota: Para poder utilizar esta interfaz tienes que instalarla previamente en tu equipo:
    sudo apt install aptitude

# 3. cal.

## Puede usar el comando cal en la ventana de Terminal para ver el calendario.
    cal
## También puede ver el calendario de un año completo ejecutando el comando que se muestra.
    cal 2023

# 4. bc.

## Permite habilitar una calculadora de línea de comandos en la Terminal de Linux.
    bc
## Para finalizar su uso digite:
    exit

# 5. chage.

## Se puede utilizar para cambiar la información de caducidad de la contraseña del usuario.
    chage

# 6. df.

## Puede obtener toda la información de su sistema de archivos.
    df
## Agregando -h, simplificas el formato.
    df -h

# 7. help.

## Enumerará todos los comandos integrados que puede usar en el shell.
    help

# 8. pwd (Directorio de trabajo de impresión).

## Este comando muestra la ruta del directorio en el que se está trabajando actualmente.
    pwd

# 9. ls.

## Le mostrará todo el contenido del directorio en particular.
    ls

# 10. factor.

## Le dará todos los factores posibles del número decimal que ingrese en el shell.
    factor

# 11. uname.

## Muestra información del sistema Linux cuando se ejecuta en el terminal.
    uname
## Para ver toda la información del sistema, escriba uname -a en la Terminal.
    uname -a
## Para obtener información relacionada con el lanzamiento del kernel, solo escriba uname -r.
    uname -r
## Y para obtener información sobre el sistema operativo, escriba uname -o en el shell de la Terminal.
    uname -o

# 12. ping.

## Verifica si su sistema está conectado a un enrutador o a Internet. Utiliza el protocolo ICMP para conectarse a otros dispositivos.
    ping google.com

## nombre de host, por lo que si desea verlas en números, use el comando ping -n.
    ping -n

## Ping -i para especificar el intervalo entre transmisiones, ya que es de 1 segundo por defecto.
    ping -i

# 13. mkdir.

## Se puede usar para crear una nueva carpeta en cualquier directorio usando la Terminal de Linux.
    mkdir archivo

## También puede usar el comando rmdir para eliminar
    rmdir archivo

# 14. gzip.

## Puede comprimir cualquier archivo desde la ventana de Terminal usando el comando gzip pero eliminará el archivo original del directorio. 
    gzip archivo

## Si desea mantener el archivo original, use el comando gzip -k
    gzip -k

## 15. whatis.

## Si desea saber para qué se puede usar el comando de Linux en particular, simplemente ejecute el comando whatis en Terminal shell y le mostrará una breve descripción de una línea de ese comando de Linux en particular.
    whatis sudo
    whatis apt

# 16. who.

## Este es para administradores de sistemas que manejan y administran varios usuarios en sistemas Linux. who commands cuando se ejecuta en Terminal muestra la lista completa de aquellos usuarios que actualmente están conectados al sistema Linux.
    who

# 17. free.

## El comando libre se puede usar para verificar exactamente qué cantidad de almacenamiento está libre y se usa en la memoria física y de intercambio en el sistema.
    free

## También puedes ver los resultados en bytes con free -b
    free -b
## En kilobytes con free -k 
    free -k
## En megabytes con free -m
    free -m
## En Gygabytes con free -g
    free -g
## En terabytes con free -tera
    free --tera

# 18. top.

## top Es un comando simple pero útil para monitorear todos los procesos en curso en el sistema Linux con el nombre de usuario, el nivel de prioridad, la identificación única del proceso y la memoria compartida por cada tarea.
    top

# 19. sl.
## Este es solo por diversión durante el trabajo y no es un comando útil. Cuando se ejecuta, una máquina de vapor pasa a través de la ventana de la Terminal. Puedes probarlo por diversión.
    sl

### Nota: Para poder utilizarlo, tienes que instalarla previamente en tu equipo:
    sudo apt install sl

# 20. cowsay.

## cowsay es otro comando divertido para Linux Terminal cuando se ejecuta, mostrará cualquier texto que escriba en un formato de vaca como puede ver.

    cowsay moo

### Nota: Para poder utilizarlo, tienes que instalarla previamente en tu equipo:
    sudo apt install cowsay

# 21. aafire.

## ¿Qué tal si incendiamos la ventana de la Terminal? Simplemente ejecute el comando aafire en la ventana de la Terminal y vea la magia.
    aafire

### Nota: Para poder utilizarlo, tienes que instalarla previamente en tu equipo:
    sudo apt install aafire
    sudo apt install libaa-bin

# 22. echo.

## El comando echo se puede usar para imprimir cualquier texto.
    echo holi

# 23. finger.

## finger mostrará toda la información sobre cualquier usuario en el sistema, como el último inicio de sesión del usuario, el directorio de inicio del usuario y el nombre completo de la cuenta de usuario.
    finger

### Nota: Para poder utilizarlo, tienes que instalarla previamente en tu equipo:
    sudo apt install finger

# 24. groups.

## Si desea saber de qué grupos es miembro un usuario en particular, ejecute el comando de grupos en la ventana Terminal. Mostrará la lista completa de los grupos de los que un usuario es miembro.
    groups

# 25. head.

## Este comando enumerará las primeras 10 líneas del archivo en la ventana de Terminal.
    head texto

## Si desea ver un número particular de líneas, use la opción -n (número) 
    head texto -n 2

# 26. man.

## Aquí man significa manual de usuario y, como sugiere el nombre, man mostrará el manual de usuario para el comando en particular. Mostrará el nombre del comando, las formas en que se puede usar el comando y la descripción del comando.
    man aptitude

# 27. passwd.

## Puede usar el comando passwd para cambiar la contraseña para usted o cualquier usuario
    passwd

# 28. w.

## w Es un comando corto y simple que lo ayudará a ver la lista de usuarios actualmente conectados.
    w

# 29. whoami.

## Este comando lo ayudará a averiguar qué usuario está conectado al sistema o con quién está conectado.
    whoami

# 30. history.

## Cuando se activa en el shell de la Terminal, el comando de history enumerará todos los comandos utilizados por usted en forma de número de serie.
    history

# 31. login.

## Si desea cambiar de usuario o desea crear una nueva sesión, active este comando en la ventana de la Terminal y proporcione los detalles, como el ID de inicio de sesión y la contraseña, como se muestra.
    sudo login

# 32. lscpu.

## Este comando mostrará toda la información de la arquitectura de la CPU, como subprocesos, sockets, núcleos y recuento de CPU.
    lscpu

# 33. mv.

# El comando mv (mover) se puede usar para mover un archivo o directorio a otro archivo o directorio.
    mv texto.gz archivo

# 34 ps.

## Si desea ver la lista de procesos que se están ejecutando actualmente para su sesión o para otros usuarios en el sistema, entonces el comando ps es para usted, ya que muestra los procesos con sus números de identificación de proceso 
    ps
## y también en detalle cuando usa el comando ps -u .
    ps -u

# 35. kill.

## Puede usar este comando para eliminar los procesos actualmente en curso manualmente desde el propio shell de la Terminal. Necesita un PID único, es decir, un número de identificación de proceso para eliminar el proceso.
    kill 38113


# 36. tail.

## El comando tail mostrará las últimas 10 líneas del archivo en la ventana de Terminal como salida. 
    tail texto

## Hay una opción para enumerar un número específico de líneas como desee con el comando tail -n como se muestra.
    tail -n 10 texto

# 37. cksum.

## cksum es un comando para generar el valor de la suma de comprobación para el archivo o flujo de datos arrojados. con el comando en la Terminal de Linux. También puede determinar si la descarga está dañada o no si tiene problemas para ejecutarla.
    cksum texto

# 38. cmp.

## Si alguna vez necesita hacer una comparación byte por byte de los dos archivos, cmp es el mejor comando de Linux para usted.
    cmp texto texto.gz

# 39. env.

## env es un comando de shell muy útil que se puede usar para mostrar todas las variables de entorno en la ventana de Terminal de Linux o ejecutar otra tarea o programa en un entorno personalizado sin necesidad de realizar modificaciones en la sesión actual.
    env

# 40. hostname.

## El comando hostname se puede usar para ver el nombre de host actual y el nombre de host se puede usar para cambiar el nombre de host actual por uno nuevo.


# 41. hwclock.

## Puede usar el comando hwclock para ver el reloj del hardware.
    sudo hwclock

# 42. lshw.

## El comando sudo lshw se puede usar para invocar información detallada de hardware del sistema en el que se ejecuta Linux. Te brinda cada pequeño detalle sobre el hardware, solo pruébalo.
    sudo lshw

# 43. nano.

## nano es un editor de texto de línea de comandos de Linux similar al editor Pico que muchos de ustedes podrían haber usado para programar y otros fines. Es un editor de texto bastante útil con muchas características.
    nano

# 44. rm

## El comando rm se puede usar para eliminar cualquier archivo del directorio de trabajo. 
    rm
## Para mayor comodidad, puede usar el comando rm -i, ya que primero le pedirá su confirmación antes de eliminar el archivo.
    rm -i

# 45. ifconfig.

## ifconfig es otro comando útil de Linux que se puede usar para configurar la interfaz de red en el sistema.
    ifconfig

### Nota: Para poder utilizarlo, tienes que instalarla previamente en tu equipo:
    sudo apt install net-tools

# 46. ​​clear.

## clear es un comando simple para el shell de Terminal de Linux, cuando se ejecuta, borrará la ventana de Terminal para comenzar de nuevo.
    clear

# 47. su.

## El comando su se puede usar para cambiar a otra cuenta directamente desde la ventana de la terminal de Linux.
    su

# 48. wget.

## wget es un comando muy útil para descargar cualquier archivo de internet y lo mejor es que se descarga en segundo plano para que puedas seguir trabajando en tu tarea.
    wget -b https://download.opensuse.org/tumbleweed/iso/openSUSE-Tumbleweed-DVD-x86_64-Current.iso

# 49. yes. 

## El comando yes "your text" se usa para mostrar un mensaje de texto ingresado con el comando yes repetidamente en la ventana de Terminal hasta que lo detenga usando el método abreviado de teclado CTRL + c.
    yes hola amigos

# 50. last.

## Cuando se ejecuta, el último comando mostrará la lista de los últimos usuarios que iniciaron sesión en el sistema como una salida en la Terminal de Linux.
    last

# 51. locate.

## El comando de localización es una alternativa confiable y posiblemente mejor que el comando de búsqueda para ubicar cualquier archivo en el sistema.
    locale

# 52. iostat.

## Si alguna vez necesita monitorear los dispositivos de entrada/salida del sistema, el comando iostat puede ser muy útil para usted, ya que muestra todas las estadísticas de la CPU, así como los dispositivos de E/S en la ventana de Terminal.
    iostat

### Nota: Para poder utilizarlo, tienes que instalarla previamente en tu equipo:
    sudo apt install sysstat

# 53. kmod.

## Puede usar el comando kmod list para administrar todos los módulos del kernel de Linux, ya que este comando mostrará todos los módulos cargados actualmente en el sistema.
    kmod list

# 54. lsusb.

## El comando lsusb mostrará información sobre todos los buses USB conectados al hardware y los dispositivos USB externos conectados a ellos.
    lsusb

# 55. pstree.

## El comando pstree muestra todos los procesos que se están ejecutando actualmente en formato de árbol en la ventana de terminal de Linux.
    pstree

# 56. Sudo.

## Si necesita ejecutar cualquier comando como usuario root o permisos de root, simplemente agregue sudo al comienzo de cualquier comando.
    sudo apt-get update

# 57. apt.

## apt (Advanced Package Tool) es un comando de Linux que ayuda a los usuarios a interactuar con el sistema de empaquetado.
    apt

# 58. zip.

## Puede usar el comando zip para comprimir uno o más archivos como puede ver aquí. Es un comando simple pero útil para comprimir cualquier número de archivos de una sola vez.
    zip holamundo texto

# 59. unzip.

## Para extraer archivos de un archivo zip comprimido, use el comando descomprimir en el shell de Terminal. También puede usar este comando para extraer archivos de varios archivos comprimidos del directorio en particular.
    unzip holamundo.zip

# 60. shutdown.

## Puede usar el comando de shutdown para apagar el sistema directamente desde el terminal.
    shutdown

# 61. dir.

## El comando dir (directorio) se puede utilizar para ver la lista de todos los directorios y carpetas presentes en el directorio de trabajo actual.
    dir

# 62. cd.

## El comando cd lo ayuda a acceder a un directorio o carpeta en particular desde el sistema de archivos. También puede usar el comando cd .. para volver a la raíz. 
    cd ..

# 63. reboot.

## Como sugiere el nombre, puede usar el comando de reinicio para reiniciar o apagar el sistema desde la ventana de la Terminal. 
    reboot

# 64. sort.

## El comando ordenar lo ayudará a ordenar archivos u organizar cualquier registro en un orden particular, generalmente de acuerdo con sus valores ASCII. 
    sort
# 65. tac.

## El comando tac mostrará el contenido del archivo en orden inverso.
    tac texto

# 66. exit.

## El comando de exit se puede usar para cerrar la ventana de la terminal directamente desde la línea de comandos.
    exit

# 67. ionice.

## El comando ionice lo ayudará a obtener o establecer la clase de programación de E/S y la prioridad para el proceso en particular.
    ionice

# 68. diff.

## El comando diff comparará los dos directorios y mostrará la diferencia entre ellos.
    diff Downloads Pictures
    diff Descargas Imágenes
    
# 69. dmidecode.

## Hay muchos comandos disponibles para que Linux recupere información de hardware, pero si desea información de un componente de hardware en particular, entonces dmidecode es el comando para usted. Ofrece varias opciones y puede verlas usando dmidecode –help.
    sudo dmidecode -t bios

# 70. Expr.

## Si desea realizar cálculos rápidos durante su trabajo, expr es un comando realmente útil para usted.
    expr 33 + 77

# 71. gunzip.

## El comando gunzip se puede usar para extraer o restaurar archivos comprimidos con el comando gzip.
    gunzip texto.gz

# 72. hostnamectl.

## El comando hostnamectl se puede utilizar para acceder a la información del sistema, cambiar el nombre de host del sistema y otras configuraciones relacionadas.
    hostnamectl

# 73. iptables.

## iptables es una sencilla herramienta de cortafuegos basada en terminal de Linux que ayuda a administrar el tráfico entrante y saliente mediante tablas.
    iptables

# 74. killall.

## El comando killall eliminará todos los programas que coincidan con el nombre de proceso lanzado con el comando killall.
    killall

# 75. netstat.

## Este comando es para aquellos que necesitan monitorear continuamente las conexiones de red entrantes y salientes. El comando netstat muestra el estado de la red, las tablas de enrutamiento y las estadísticas de la interfaz.
    netstat -tulpn

# 76. lsof.

## El comando lsof lo ayudará a ver todos los archivos abiertos relacionados con su aplicación en la ventana de la Terminal de Linux.
    lsof

# 77. bzip2.

## Puede usar el comando bzip2 en la ventana Terminal para comprimir cualquier archivo a un archivo .bz2 
    bzip2 test

## y usar el comando bzip2 -d para extraer los archivos del archivo comprimido.
    bzip2 -d test

# 78. service.

## El comando de servicio mostrará los resultados de los scripts de inicio de System V en la ventana Terminal. Puede ver el estado de un servicio en particular o de todos los servicios.
    service --status-all

# 79. vmstat.

## El comando vmstat mostrará el uso de la memoria virtual de los sistemas en la ventana Terminal.
    vmstat

# 80. mpstat.

## Cuando se ejecuta, el comando mpstat mostrará toda la información sobre la utilización de la CPU y las estadísticas de rendimiento en la ventana de la terminal de Linux. 
    mpstat

# 81. usermod.

## Si desea editar o modificar los atributos de una cuenta de usuario ya creada, el inicio de sesión de usermod es el mejor comando para usted.
    usermod

# 82. touch.

## Usando el comando touch en la ventana de Terminal, puede crear archivos vacíos en el sistema de archivos y también puede cambiar la hora y la fecha, es decir, la marca de tiempo de los archivos a los que accedió recientemente, así como de los directorios.

# 83. uniq.

## uniq es un comando estándar de terminal de Linux cuando se lanza con un archivo, filtra las líneas repetidas en el archivo.
    uniq

# 84. wc.

## El comando wc lee el archivo lanzado con el comando y muestra el recuento de palabras y líneas del archivo.
    wc texto

# 85. pmap.

## El comando pmap muestra el mapa de memoria del pid que proporciona. También puede ver mapas de memoria para múltiples procesos.
    ps
    pmap

# 86. rpm.

## El comando rpm -i se puede usar para instalar paquetes basados ​​en rpm en Linux.
    rpm -i

## Para eliminar el paquete rpm, use el comando rpm -e en el terminal.
    rpm -e

# 87. ssh.

## El acrónimo ssh de Secure Shell es un protocolo que se utiliza para conectarse de forma segura a un sistema host.
    ssh
## ssh username@host es el comando para conectarse a la computadora host como usuario.

# 88. telnet.

## El comando telnet utiliza el protocolo telnet para conectarse a otro sistema como usuario.
    telnet

# 89. nice.

# Si necesita cambiar la prioridad de los procesos en ejecución, ejecute bien en la Terminal de Linux.
    nice

# 90. nproc.

## El comando nproc mostrará la cantidad de unidades de procesamiento asignadas al proceso que se está ejecutando actualmente.
    nproc

# 91. scp.

## El acrónimo scp de Secure Copy es el comando de Linux que se puede usar para copiar archivos y directorios entre hosts en la red.
    scp

# 92. sleep.

## El comando de suspensión retrasará o pausará la ejecución del comando durante un período de tiempo determinado, es decir, especificado con el comando de suspensión.
    sleep

# 93. split.

## Si necesita dividir un archivo grande en un archivo pequeño, use el comando split en la terminal de Linux.
    split

# 94. stat.

## Puede ver el estado de un archivo o de un sistema de archivos completo mediante el comando stat en la terminal de Linux.
    stat texto

# 95. lsblk.

## El comando lsblk lee el sistema de archivos sysfs y muestra la información del dispositivo de bloque en la ventana de Terminal.
    lsblk

# 96.hdparm.

## Usando el comando hdparm, puede manejar el disco duro y otros dispositivos de disco en Linux usando Terminal shell.
    hdparm

# 97. chrt.

## El comando de prioridad chrt se utiliza para manipular los atributos en tiempo real del proceso.
    chrt

# 98. useradd.

## El comando de inicio de sesión useradd lo ayudará a agregar una cuenta de usuario a su sistema
    useradd

# 99. userdel.

## El comando de inicio de sesión userdel le permitirá eliminar cualquier cuenta de usuario del sistema.
    userdel

# 100. ip link show. 

## Enumera el dispositivo de red disponible en el servidor Linux junto con su estado de enlace.
    ip link show
