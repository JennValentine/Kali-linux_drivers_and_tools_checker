![logo](https://edteam-media.s3.amazonaws.com/blogs/big/2ab53939-9b50-47dd-b56e-38d4ba3cc0f0.png)

# Kali Linux - Drivers and Tools Checker

## :information_source: Descripci�n
El script Kali Linux - Drivers and Tools Checker est� dise�ado para automatizar la 
instalaci�n y verificaci�n de diversos controladores y herramientas esenciales para 
la auditor�a de seguridad en Kali Linux. El objetivo principal es asegurar que todos 
los componentes necesarios est�n instalados y configurados correctamente para 
realizar auditor�as de red y pruebas de penetraci�n.

## :computer: Instalaci�n
```bash
cd /opt
sudo rm -rf Kali-linux_drivers_and_tools_checker
sudo git clone https://github.com/JennValentine/Kali-linux_drivers_and_tools_checker.git
sudo chmod +x Kali-linux_drivers_and_tools_checker/*
cd Kali-linux_drivers_and_tools_checker
ls -lthas
```

## :key: Acceso Directo
```bash
cd 
sudo echo "cd /opt/Kali-linux_drivers_and_tools_checker && sudo ./kalilinuxdrivertools.sh" > kalilinuxdrivertools
sudo chmod +x kalilinuxdrivertools
sudo rm -rf /usr/local/bin/kalilinuxdrivertools
sudo mv kalilinuxdrivertools /usr/local/bin/
cd
```

## :computer: Instalaci�n en una L�nea
```bash
wget https://raw.githubusercontent.com/JennValentine/Kali-linux_drivers_and_tools_checker/main/install.sh; sudo chmod +x install.sh; sudo ./install.sh; sudo rm -rf install.sh
```

## :rocket: Modo de Uso

Ejecutar el scrip:

```bash
sudo kalilinuxdrivertools
```
![logo](https://github.com/JennValentine/Kali-linux_drivers_and_tools_checker/blob/main/Imagenes/kalilinuxdrivertools.jpg)
:memo: Notas: Caracter�sticas y Funcionalidades Principales

1 - Comprobaci�n de Permisos de Root:

* El script verifica si se est� ejecutando con permisos de superusuario (root) y, en caso contrario, solicita que se ejecute con sudo.

2 - Actualizaci�n de Repositorios y Paquetes:

* Opci�n para actualizar los repositorios (apt-get update).
* Opci�n para actualizar los paquetes instalados (apt-get upgrade).

3 - Instalaci�n de Controladores de Red:

* Instalaci�n de controladores espec�ficos para adaptadores de red Realtek, como rtl8188eus, rtl8188fu, y opcionalmente rtl8814au-dkms.

4 - Configuraci�n de Controladores de Audio:

* Intenta configurar y activar los controladores de audio, asegurando la correcta funcionalidad del sonido en el sistema.

5 - Instalaci�n y Verificaci�n de Herramientas Esenciales y Opcionales:

* Verificaci�n e instalaci�n de herramientas esenciales como git, aircrack-ng, wifite, hcxdumptool, pyrit, airgeddon, fluxion, entre otras.
* Instalaci�n de herramientas adicionales como sparrow-wifi, feedingbottle, lazyaircrack, y Wifi-Hack.

6 - Configuraci�n y Creaci�n de Diccionarios de Contrase�as:

* Creaci�n de un diccionario combinado a partir de m�ltiples fuentes de listas de contrase�as para usar en ataques de fuerza bruta.

7 - Mostrar Informaci�n del Sistema:

* Muestra la configuraci�n de red, interfaces inal�mbricas, dispositivos USB y capacidades inal�mbricas del sistema.


Este script es una herramienta poderosa para cualquier profesional de la seguridad 
inform�tica que utilice Kali Linux, ya que simplifica y automatiza muchas de las 
tareas comunes de configuraci�n y actualizaci�n necesarias para una auditor�a de 
seguridad eficaz.

:bookmark_tabs: Disfruta utilizando el script y mant�n tu sistema Kali Linux actualizado y listo para su uso en pruebas de seguridad en redes! 

## :email: Contacto
* :busts_in_silhouette: [Jenn Valentine](https://t.me/JennValentine) - Update Contributor :octocat:
