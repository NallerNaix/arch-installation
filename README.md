# Introducción
En este repositorio se archivarán los progresos de mi instalación manual de Arch Linux en un pc de uso general, desde ofimática, pasando por videojuegos y finalizando en desarrollo de software.

## Especificaciones del dispositivo.
- Ryzen 5500
- Nvidia GTX 1070
- 16gb DDR4
- Resolución 1920x1080

## Características Objetivo
- Arranque UEFI con uso de **Grub**.
- Uso de **Systemd** como surtido de programas principal.
- Sistema de archivos principal **BTRFS**, con capacidad de copias de seguridad atómicas, rápidas y de poco coste de almacenamiento.
- Esquema de subvolúmenes optimizado.
- **SELinux** como software de seguridad
- Entorno de escritorio ligero y personalizado con **Wayland** y **Hyprland** como su compositor.
- Compatibilidad con hardware de Nvidia, haciendo uso de **drivers propietarios**.
- Personalización de atajos de teclado con **Keyd**

## Testing
Como espacio de trabajo se hará uso de **Virtualbox** y su sistema de instantáneas será sustituto de git. El objetivo será crear dentro de la VM una versión estable que exportar a la máquina objetivo.

## Problemas
### Registro
Cuando empezó el desarrollo no era un objetivo registrar los avances de este proyecto, sino usarlo como una práctica. Por la espontaneidad del proyecto, se necesitó de la revisión de **bash_history** y de algunos logs desde cada instantánea de VirtualBox en pos de la correcta redacción de los procesos de instalación.
Una opción habría sido subir el .ova al repositorio directamente, de no ser por su gran tamaño y las limitaciones de GitHub. Sin embargo, si es posible acceder a este mismo archivo desde un enlace a Google Drive xxxxxxxxxxxxxxxxxxxxxxx.
RECORDAR BORRAR EL REGISTRO UNA VEZ SE HAYAN ACTUALIZADO LOS CAMBIOS
