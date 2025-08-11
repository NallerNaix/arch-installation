# Arch Installation
En este repositorio se archivarán los progresos de mi instalación manual de Arch Linux en un pc de uso general, desde ofimática, pasando por videojuegos y finalizando en desarrollo de software.

## Especificaciones del dispositivo.
- Ryzen 5500
- Nvidia GTX 1070
- 16gb DDR4
- Resolución 1920x1080

## Introducción
Las características objetivo del sistema son:
- Arranque UEFI con uso de **Grub**.
- Uso de **Systemd** como surtido de programas principal.
- Sistema de archivos principal **BTRFS**, con capacidad de copias de seguridad atómicas, rápidas y de poco coste de almacenamiento.
- Esquema de subvolúmenes optimizado.
- **SELinux** como software de seguridad
- Entorno de escritorio ligero y personalizado con **Wayland** y **Hyprland** como su compositor.
- Compatibilidad con hardware de Nvidia, haciendo uso de **drivers propietarios**.
- Personalización de atajos de teclado con **Keyd**

## Testing
Como espacio de trabajo se hará uso de **Virtualbox**. El objetivo será crear dentro de la VM una versión estable que exportar a la máquina objetivo.
