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
![NetInterfaces](https://drive.google.com/uc?export=view&id=1GwD_2pB8_Wf6NBXBZGKhkcMUBddn-LXx)

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

## MYSQL

Instalar MYSQL y activar el servicio

Instalar el servicio y crear la tabla y usuario con sus permisos:

![set_up_DB](https://drive.google.com/uc?export=view&id=1Btxs17k8AbtvDtauO8fWemHNx9TZPzVL)
![Create Table](https://drive.google.com/uc?export=view&id=1kt4JdQhDrAkAnX1Dy1qjUk6BtOIZL4YZ)

Estado del servicio:

![DB State](https://drive.google.com/uc?export=view&id=1UIH5-PqQm79kOz-oCZHsNe6bxSz7hrRj)

Simplificar el CSV para mostrar contenido relevante:

![Simplificate CSV](https://drive.google.com/uc?export=view&id=1kIJCsGjKU_wgy-ClVT0mJOudll9dK6kF)

Cargar el CSV en la tabla creada:
![load CSV](https://drive.google.com/uc?export=view&id=1y1A7CcPqJIDNA1yr61J0OUvU49jEkyNM)




---
## SFTP

Instalacion y configuración del servidor SFTP. Se trata de un servidor cuya unica utilidad sera transferir archivos al servidor web.
![Texto alternativo](https://drive.google.com/uc?export=view&id=1YWQKmnoEV_Rrx8UHaXjwQC3iRhUpL8KP)




---

