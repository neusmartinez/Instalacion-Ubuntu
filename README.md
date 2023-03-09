# INSTALACIÓN UBUNTU
## ¿Que es Ubuntu?

Ubuntu es una distribución Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto.

Puede utilizarse en ordenadores y servidores. Está orientado al usuario promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia del usuario. Está compuesto de múltiple software normalmente distribuido bajo una licencia libre o de código abierto. Estadísticas web sugieren que la cuota de mercado de Ubuntu dentro de las distribuciones Linux es, aproximadamente, del 52 %, y con una tendencia a aumentar como servidor web.

## Proceso de instalación

### Instalación de VirtualBox

Descargaremos [VirtualBox](https://www.virtualbox.org/)

### Configuración de VirtualBox
Arrancamos Virtual y hacemos click en "Nueva":

![VirtualBox1](https://github.com/neusmartinez/InstalacionUbuntu/blob/main/VIRTUALBOX1.png)

Escribimos el nombre de la máquina vi4tual, en nuestro caso "Ubuntu". Vemos que se selecciona automáticamente el tipo de sistema a Linux y la version a "Ubuntu (64-bit)":

![VirtualBox2](https://github.com/neusmartinez/InstalacionUbuntu/blob/main/VIRTUALBOX2.png)

Configuramos el tamaño de memoria para la máquina virtual. Para Ubuntu 22.04 se recomiendan 4GB (4096):
![]

Creamos un nuevo disco duro virtual:
![]

Elegimos el tipo de disco duro virtual de tipo VDI (Virtual Disk Image):
![]

Le indicamos que el fichero del disco duro virtual crezca dinámicamente, a medida que necesitemos más espacio:
![]

Configuramos el tamaño del disco duro virtual a 25 GB,  ya que es el tamaño recomendado en la instalacióń de Ubuntu 22.04:


Ya tenemos creada la máquina virtual, solo nos falta introducir el disco virtual del sistema operativo:

Nos descargamos previamente el archivo ISO de la distribución Linux que queramos. En nuestro caso hemos elegido la distribución [Ubuntu](https://ubuntu.com/), en su versión 22.04.

El siguiente paso es "montar" la ISO en el lector visual de la máquina virtual. Para ello hacemos click en "Configurar y posteriormente vamos a la sección "Almacenamiento":


Hacemos click en "Vacio" dentro del árbol "Controlador IDE"  y elegimos el archivo ISO desde el icono de "Unidad Óptima"


Por último, le damos a "Iniciar" en la máquina virtual y vemos como empieza a arrancar.

## Referencias
"Ubuntu", Wikipedia. Disponible en: https://es.wikipedia.org/wiki/Ubuntu (Accedido: 6 Marzo, 2023). 
