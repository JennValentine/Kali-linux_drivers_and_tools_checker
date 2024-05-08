![logo](https://edteam-media.s3.amazonaws.com/blogs/big/2ab53939-9b50-47dd-b56e-38d4ba3cc0f0.png)

#  Verificador de Controladores y Herramientas - Kali Linux

## :information_source: Descripci�n

Este script de Bash fue desarrollado para facilitar la verificaci�n e instalaci�n de controladores y herramientas comunes en Kali Linux. 
Proporciona una forma r�pida y sencilla de asegurarse de que los controladores y herramientas esenciales est�n instalados y actualizados en tu sistema para auditorias wifi.


## :arrow_down: Instalacion
```bash
cd /opt
sudo rm -rf Kali-linux_drivers_and_tools_checker
sudo git clone https://github.com/JennValentine/Kali-linux_drivers_and_tools_checker.git
sudo chmod +x Kali-linux_drivers_and_tools_checker/*
cd Kali-linux_drivers_and_tools_checker
ls -lthas
```

## :book: Acceso directo
```bash
cd 
sudo echo "cd /opt/Kali-linux_drivers_and_tools_checker && sudo ./kalilinuxdrivertools.sh" > kalilinuxdrivertools
sudo chmod +x kalilinuxdrivertools
sudo rm -rf /usr/local/bin/kalilinuxdrivertools
sudo mv kalilinuxdrivertools /usr/local/bin/
cd
```

## :hammer: Modo de Uso

Ejecutar el scrip:

```bash
sudo kalilinuxdrivertools
```
![logo](https://github.com/JennValentine/Kali-linux_drivers_and_tools_checker/blob/main/Imagenes/kalilinuxdrivertools.jpg)
:books: DATA:

* Verificaci�n y actualizaci�n de repositorios.
* Verificaci�n y actualizaci�n de paquetes instalados.
* Verificaci�n y actualizaci�n de la distribuci�n.
* Instalaci�n de controladores de red Wi-Fi (por ejemplo, rtl8188fu, rtl8188eus).
* Configuraci�n y activaci�n de controladores de audio.
* Instalaci�n de herramientas esenciales para auditor�as de seguridad de redes (por ejemplo, wifite, airgeddon, fluxion, sparrow-wifi).
* Verificaci�n de la configuraci�n del sistema y los dispositivos de red.

Aseg�rate de revisar el c�digo fuente del script para comprender completamente qu� hace y c�mo funciona.

:bookmark_tabs: Disfruta utilizando el script y mant�n tu sistema Kali Linux actualizado y listo para su uso en pruebas de seguridad! 

## :octocat: Cr�ditos
1. [Jenn Valentine](https://t.me/JennValentine) - Update Contributor
