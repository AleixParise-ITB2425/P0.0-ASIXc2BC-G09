# Proyecto

---
## Propuesta sprint inicial

En el primer sprint del proyecto definimos el escenario y la segmentación en tres redes (DMZ, Intranet y salida a Internet). Tras analizar la arquitectura óptima desde las perspectivas de seguridad y prestación de servicios, iniciamos la implantación.

El objetivo principal del sprint fue disponer de un servidor web operativo en la DMZ, manteniéndolo aislado por razones de seguridad. En la red interna se desplegaron los servicios de DHCP y DNS para los clientes corporativos, junto con un servidor de base de datos que da soporte a la aplicación web.

Como entregables del sprint se establecieron:

Servidores instalados y configurados según los requisitos.

Servicios web, DHCP, DNS y base de datos en funcionamiento.

Conectividad verificada entre redes.

Servidor central actuando como router, operativo y validado.

## Escenario del Proyecto

Hemos diseñado este escenario basándonos en nuestro proyecto. Se puede ver que está separado principalmente en tres zonas: la zona DMZ, donde encontramos el servidor que da servicio a la página web y también el servidor FTP, el cual utilizamos para subir y transferir todo tipo de archivos o documentos de un servidor a otro. Hemos situado ambos servidores en la DMZ por motivos de seguridad y conectividad.

Por otra parte, tenemos la zona de la intranet, donde están alojados los servidores que proporcionan servicios como DHCP, DNS, etc., además del servidor que almacena la base de datos. Hemos ubicado estos servicios en la zona más "privada" por razones de seguridad, ya que los datos que almacenan son cruciales. El servidor DHCP da servicio a todos los clientes, en este caso a una máquina Ubuntu y una Windows que se encuentran en la red privada.

Como parte central del escenario, de la cual dependen todas las redes de la empresa, encontramos un servidor “principal”. Este servidor es el encargado de enrutar ambas redes y de garantizar que todos los servidores y clientes puedan acceder a internet de forma segura.

<img width="877" height="745" alt="image" src="https://github.com/user-attachments/assets/a4d2aed8-1f2a-441d-ba90-aa9914de47bc" />

---

## ProofHub

Creación de los diferentes puntos a seguir para llevar el proyecto a cabo de manera ordenada con el grupo.

![ProofhubImage](https://drive.google.com/uc?export=view&id=1Tgar7wh32cglgoPmw8-iAttw_bJx_Sxt)
![ProofhubImage2](https://drive.google.com/uc?export=view&id=107wAJUgTMDin7j6za1mgbqoWJOhikbS3)


---

## Usuario de administración: bchecker

Creación del usuario en el server para poder administrarlo remotamente.
![UserCreate](https://drive.google.com/uc?export=view&id=1Hd6BYOxugxYPGlYRNr0MWsezTLz0r969)


---

## Interfaces de red

Ifconfig para enseñar las interfaces añadidas al Server
<img width="722" height="659" alt="image" src="https://github.com/user-attachments/assets/17b41a16-f656-4068-8de9-0068e3058ed3" />


---

## Interfaz DMZ

Configuración de rutas para la interfaz DMZ al exterior.

![DMZInterface](https://drive.google.com/uc?export=view&id=118Wk2xjUYwl2Cn4KlzVRplm9mDxsFC8W)
![DMZInterface2](https://drive.google.com/uc?export=view&id=1kahSaRB48N4y8WsGjUaNL46llZPdZldq)

---

## Estado del servicio Apache

Mostrar el estado del servicio Apache tras haberlo instalado y configurado:
![ApacheState](https://drive.google.com/uc?export=view&id=1OPX8adz4LQEmfa4oEbaPwyULFYMmGSKf)


---

## Web:

Acceder desde el navegador a la web via IP y comprobar el correcto funcionamiento de Apache.

![Web](https://drive.google.com/uc?export=view&id=11md9IaqbPE-eLxc0qoqAE4-SOP_TyQQQ)

Mejorar la interfaz de la pagina web (html)

![WebConfigured](https://drive.google.com/uc?export=view&id=1dH3p226LA2XBjGqyrYWsisncxWZi8MZd)

---

## Servicio SSH

Comprobar el estado de SSH para poder administrar el servidor de manera remota

![SSHState](https://drive.google.com/uc?export=view&id=1LyupKs1bgrsIWsB4DS4izW0mdTse1DKE)


---

## Conexión SSH con bcheacker

Hacemos una conexión SSH al server con el usuario creado para administración

![SSHConnect](https://drive.google.com/uc?export=view&id=1I9UAhsEgwgrvGuTVz6mzCBVxvFttMrNK)


---

## Nginx

Instalación y configuración del servicio Nginx

![Nginx](https://drive.google.com/uc?export=view&id=1Wgix6JQHO7fqt7zyG4Y9nufTMl1tZkPI)


---

## Firewall

Instalación de ufw, activar servicio y configuración de políticas:

![UfwInstall](https://drive.google.com/uc?export=view&id=1-sqx3votuq_4N1zFfqgJyN_OfgwJ7fOu)


---
## Configuración y conexion Base de datos y Web en servidor en Servidor de preproducción

En un servidor de preproducción que utilizamos para realizar las pruebas del proyecto, hemos configurado la base de datos para añadir todos los archivos proporcionados para su desarrollo. Hemos conectado la base de datos con la página web para poder visualizarla a través de esta.
Al realizar esta tarea en un servidor de preproducción, de cara al siguiente sprint únicamente tendremos que transferir los datos de la máquina de preproducción a los servidores reales correspondientes, y todo funcionará correctamente.

![web php](https://drive.google.com/uc?export=view&id=1lzIvxs9B6QyjkgWD5Vkjt1B5JT8es8yQ)
![web](https://drive.google.com/uc?export=view&id=1G1Y6ruApYg-vWGu2GKHgSnIdEYnAuM5H)


---
## MYSQL

Instalar MYSQL y activar el servicio 
En el servidor de base de datos final, hemos añadido el codigo pertinente que habiamos desarrollado anteriormente en el servidor de preproducción,
para reproducirlo correctamente en el servidor de producción final.

Instalar el servicio y crear la tabla y usuario con sus permisos:

![set_up_DB](https://drive.google.com/uc?export=view&id=1Btxs17k8AbtvDtauO8fWemHNx9TZPzVL)
![Create Table](https://drive.google.com/uc?export=view&id=1kt4JdQhDrAkAnX1Dy1qjUk6BtOIZL4YZ)

Estado del servicio:

![DB State](https://drive.google.com/uc?export=view&id=1UIH5-PqQm79kOz-oCZHsNe6bxSz7hrRj)

Simplificar el CSV para mostrar contenido relevante:

![Simplificate CSV](https://drive.google.com/uc?export=view&id=1kIJCsGjKU_wgy-ClVT0mJOudll9dK6kF)

Cargar el CSV en la tabla creada:

![load CSV](https://drive.google.com/uc?export=view&id=1y1A7CcPqJIDNA1yr61J0OUvU49jEkyNM)

Comprobar que se ha creado e importado correctamente:

![check table](https://drive.google.com/uc?export=view&id=1aY--xDe_IjvyyVsZQtxlStWW5Asf4XV7)
![check csvimport](https://drive.google.com/uc?export=view&id=12GraajnXWzQ34A0fVYs93CGa_GyC9DlR)


---
## SFTP

Instalacion y configuración del servidor SFTP. Se trata de un servidor cuya unica utilidad sera transferir archivos al servidor web.
En la captura adjuntada vemos como podemos pasar archivos de forma segura y rapida de servidor a servidor.
![Texto alternativo](https://drive.google.com/uc?export=view&id=1TXjBrjG97suJ57XKia49-eJwyQbgdtL5)





---

