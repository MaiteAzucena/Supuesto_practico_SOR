# ACTIVE DIRECTORY

## 1. Clonación de MVs y creación de grupos
- Generar nuevas Mac.
- Clonación completa y clonación enlazada.
- Grupos: MVs con la configuración inicial y MVs de trabajo.
- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
- 🎯 *Pregunta para el alumando: ¿Qué diferencia existe entre tomar una instantánea y realizar una clonación enlazada?*

## 2. Instantáneas de MVs
- Crear una instántanea antes de cualquier configuración que implique cambios importantes en el sistema.
- 🎯 *Pregunta para el alumando: ¿Qué diferencia existe entre eliminar una instantánea y restaurar una instantánea?*
- *Debate: ¿Por qué resulta conveniente trabajar con instantáneas en un entorno de virtualización?*

## 3. Instalación del Directorio Activo (Active Directory AD DS) en un servidor Windows Server 2022
1.- Instalación el rol **Servicios de dominio de Active Directory**
  
  -- Importante: Lo debe hacer un usuario *Administrador* y la configuración IP del servidor es conveniente que sea estática.
  
2.- Promocionar el servidor como controlador de dominio.
  
  -- Primer controlador de dominio de un nuevo bosque, se llamará *miempresaXXX.local*, nivel de funcionalidad, contraseña de restauración de los 
  servicios del directorio DSRM, servidor DNS, nombre NetBIOS del dominio y la ubicación de los datos del directorio.
- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
- 🎯 *Pregunta para el alumando: En una red con dominio, ¿qué papel juega el servidor respecto a los clientes?*

## 4. Instalación de Windows 11. Configuración inicial
- 4GB RAM
- 2 CPUs
- 100GB dinámico con 2 particiones (una de 50GB para el sistema operativo (SISTEMA) y el resto para DATOS).
- Configuración inicial de la red:

<img width="489" height="266" alt="image" src="https://github.com/user-attachments/assets/327f4720-b302-454b-bf9b-0e14c8ba36be" />

- Cuestionario alumnado ( Kahoot: https://kahoot.it/ )

## 5. Integración del cliente Windows 11 al dominio
- Establecer las características de red
- Ajustar el nombre del equipo cliente
- Unir el equipo al dominio
- **Importante**: Iniciar sesión utilizando una cuenta de usuario de las que ya tenemos definidas en el dominio.
- 🎯 *Pregunta para el alumando: Una vez que hemos integrado el equipo Windows 11 al dominio, ¿podemos iniciar sesión con una cuenta local (no del dominio)*

## 6. Inicio de sesión con un usuario del dominio en el cliente W11
- Formato NetBIOS: *miempresaMGR.local\Administrador*
- Formato UPN - Nombre Principal de Usuario: *Administrador@miempresaMGR.local*

  
