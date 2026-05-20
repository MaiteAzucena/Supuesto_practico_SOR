# ENTORNO DE TRABAJO

## Equipo anfitrión (Requisitos técnicos)
- Windows 10/11 con VirtualBox
- VT-x/AMD-V habilitado
- Mínimo 16 GB RAM para ejecutar 3 MVs simultáneas
- 150 GB libres en disco

---

### 1. VirtualBox. Configuración inicial
- VT-x habilitado.
- Instalación de VirtualBox + Extension Pack + Guest Additions.
- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
- 🎯 *Pregunta para el alumando: ¿Qué diferencia hay entre el sistema operativo anfitrión y el sistema operativo invitado en una máquina virtual?*

### 2. Imágenes ISO de los sistemas operativos
- Windows Server: https://www.microsoft.com/es-es/evalcenter/download-windows-server-2022
- Ubuntu Server: https://ubuntu.com/download/server
- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
- 🎯 *Pregunta para el alumando: ¿Por qué es importante descargar las imágenes ISO solo desde las páginas oficiales de cada fabricante?*


### 3. Instalación de Windows Server. Configuración inicial
- 2GB RAM
- 2 CPUs
- 500GB dinámico con 3 particiones (una de 150GB para el sistema operativo (SISTEMA), otra de 200GB para DATOS y el resto para poder hacer copias de seguridad (BACKUP)).
- Configuración inicial de la red:
  
    <img width="506" height="188" alt="image" src="https://github.com/user-attachments/assets/d5cf6c27-f6e8-4153-ab0a-02954ed5b691" />

- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
- 🎯 *Pregunta para el alumando: ¿Se puede hacer una instalación de Windows Server sin interfaz gráfica?, ¿Qué ventajas y desventajas ofrece este tipo de instalación?*

### 4. Instalación Ubuntu Server. Configuración por defecto
- 2GB RAM
- 1 CPUs
- 500GB dinámico, configuración del almacenamiento predeterminado (el asistente creará una pequeña partición para el gestor de arranque, y el resto del disco formará una partición única para todo el sistema).
- Configuración inicial de la red:

<img width="571" height="276" alt="image" src="https://github.com/user-attachments/assets/64bc537d-b9c1-45c7-bce2-30712f7024c8" />

- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
- 🎯 *Pregunta para el alumando: ¿Qué ventajas tiene trabajar con una versión LTS en un servidor Linux?*

