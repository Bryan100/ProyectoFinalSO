# ProyectoFinalSistemas Operativos

### Integrantes

Estudiante | Código
--- | --- | ---
Bryan Estiben Pérez Parra | 12203030
Dylan Torres | 1210
Jose Luis Sacanamboy |

# Modulo 0 -  Prerrequisitos
Se equiere el software de virtualización para arquitecturas x86/amd64 'Oracle VM VirtualBox'. En este tutorial se asume que ya el lector lo ha instalado con anterioridad, dentro de su equipo 

![alt tag]("Icono Virtual Box")

# Modulo 1 - Configuración de Centos 7
Vamos a hacer las configuraciones pertinentes, para ejecutar una aplicacón Python. 

1. Dirigirse a la página oficial de centOS. Hacer clic en el link, a continuación:
https://www.centos.org/download/

2. Hacer clic en el botón que dice "Minimal ISO", no es necesario, para el alcance de este proyecto, descargar la versión completa.

![alt tag]("Imagen de la pagina Oficial")


3. Una vez ubicado dentro de la página web, hacer clic en alguno de los URL's disponibles para la descarga de archivo .iso de Centos. Para nuestro caso de ejemplo, se descargó la imagen desde el sgte link:
http://centos.uniminuto.edu/7/isos/x86_64/CentOS-7-x86_64-Minimal-1511.iso

Nota: Se recomienda el uso de software como "MD5" para verficiar que los datos fueron correctamente descargados y la informacion no está dañada

4. Una vez completada la descarga, iniciar el software 'virtualBox' y crear una nueva maquina virtual y configurarla con las caracteristivas que ya se han definido en clase. Para lo anterior, se recomienda ver el PDF 'Configurar una Nueva Maquina', disponible en el sgte link:
https://github.com/Bryan100/ProyectoFinalSO/blob/master/Configurar%20una%20Nueva%20Maquina%20Virtual.pdf

![alt tag]("nueva Maquina Virtual Oficial")

Dentro de la guia se eplica el uso de la imagen .iso que se descargo anteriormente.
Las configuraciones recomedadas en la guia anterior son las sgtes:

![alt tag]("Imagen ISO Almacenamiento")
![alt tag]("Configuracion Maquina")

5. tuvo que haber quedado una maquina asi, una vez creada, :

![alt tag]("Icono Maquina Creada")

Nota: Dentro de la guia 'Configurar una Nueva Maquina' se habla sobre la configuracion de una interfaz tipo 'Solo Anfitrion'. Se debe ignorar esa parte, en caso de que no se tengan los permisos necesarios dentro de la red en la que se va a ejecutar la maquina virtual.



# Modulo 2 - Despliegue de la Aplicación












