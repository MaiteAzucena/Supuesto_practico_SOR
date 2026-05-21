# REDES HETEROGÉNEAS

## 1. Instalación GNU/Linux Mint 22.3
- 2GB RAM
- 1 CPU
- 500GB dinámico con 4 particiones (una partición Bios de 1 MB, una partición Uefi de 512MB, 150GB para el sistema operativo, y el resto para /home).).
- Configuración inicial de la red:

<img width="598" height="249" alt="image" src="https://github.com/user-attachments/assets/34c099a6-01fe-4954-89ed-232a078a3a8c" />

- 🎯 *Debate: Linux Mint vs Ubuntu Desktop*

## 2. Integración del cliente Linux Mint Cinnamon al dominio AD DS
- 1 Configurar las características del equipo y comprobar conexión con el servidor.
- 2 Instalar el software necesario (paquetes sssd heimdal-clients msktutil). Para permitir autenticarnos con una cuenta del dominio desde el equipo cliente GNU/Linux, utilizando el protocolo Kerberos.
- 3 Configurar Kerberos (Protocolo de autenticación). Fichero de configuración: */etc/krb5.conf*
- 4 Comprobar el funcionamiento de Kerberos. Comandos: kinit Administrador klist
- 5 Unir el cliente al dominio. Comando: *msktutil*
- 6 Configurar SSSD. Permite iniciar sesión con una cuenta del dominio en el equipo cliente. Fichero de configuración: */etc/sssd/sssd.conf*
- 7 Ajustar el comportamiento de PAM para iniciar sesión con usuarios del dominio. Ofrece una capa de abstracción para diferentes métodos de autenticación (contraseña, tarjeta, parámetros biométricos, etc
- 8 Convertir al administrador del dominio en administrador local. Asignar privilegios administrativos en el propio equipo al usuario Administrador del dominio.
- 9 Reiniciar el equipo y comprobar el inicio de sesión gráfico.
- 10 Iniciar sesión con cualquier cuenta del dominio.

- 🎯 *Pregunta para el alumando: ¿Se puede iniciar sesión en un equipo Linux Mint con una cuenta de usuario del dominio que no pertenece al grupo de Administradores del dominio?*


