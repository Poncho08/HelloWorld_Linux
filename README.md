# HelloWorld_Linux

## Descripcion
Guia para ejecutar un "Hola mundo" mediante comandos en terminal usando el sistema operativo Linux, en este caso usando una maquina virtual especificamente VMware.

## Instalacion
- Para instalar nuestra maquina virtual, basta con entrar al siguiente enlace (https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-pro/workstation-pro-evaluation.html.html) y descargar la version para windows

- Necesitaremos el archivo .iso para poder ejecutar el SO dentro de la maquina virtual (https://ubuntu.com/download/desktop) descargamos la segunda opcion

- Podemos asignar cuanta memoria y procesadores van a estar dedicados a ese sistema operativo, esto lo podemos modificar desde la configuracion

- La contraseña es ubuntu

## Uso de la shell (terminal)

- Podemos acceder a la terminal desde la lista de aplicaciones o presionando 'ctrl + alt + T' 

## Comandos
Una vez dentro de nuestra terminal ejecutaremos los siguientes comandos

- sudo su / (Iniciar sesión como superusuario (root): Para entrar en el modo de desarrollador, a menudo necesitas privilegios de superusuario.)

- sudo apt update / (Actualizar los repositorios)

- nano hola_mundo.c (Escribe el siguiente comando para abrir el editor nano y crear un archivo llamado hola_mundo.c )


## Codigo 

- En el editor nano, escribe el siguiente código:
#include <stdio.h>

int main() {
    printf("¡Hola, mundo!\n");
    return 0;
}

- Guarda el archivo presionando Ctrl + O, luego presiona Enter y después sale de nano presionando Ctrl + X.

- Compila el programa escribiendo el siguiente comando en la terminal:
gcc hola_mundo.c -o hola_mundo

- Ahora puedes ejecutar el programa escribiendo: 
./hola_mundo


![Captura de pantalla](Screenshot 2024-04-05 193038.png)
