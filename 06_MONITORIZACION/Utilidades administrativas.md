# MONITORIZACIÓN Y AUDITORIA DEL SISTEMA

## 1. Auditoria informática: El Visor de eventos
- *Ejemplo de utilización*: auditar los inicios de sesión en el controlador de dominio DC.
- Configuración inicial del servidor para que guarde información de los inicios de sesión. Directivas de grupo GPO.
- Analizar los eventos producidos en el sistema con el *Visor de Eventos*.
- *Ejemplo de utilización*: auditar el acceso a carpetas compartidas.
- Configuración inicial del servidor para que guarde información de los intentos de acceso a recursos compartidos. Directivas de grupo GPO.
- Configuración de la carpeta compartida para que se pueda auditar esta acción.
- Analizar los eventos producidos en el sistema con el *Visor de Eventos*.
- Vistas personalizadas para buscar los eventos.

## 2. Monitorización: El Monitor de rendimiento (Windows)
 - *Ejemplo de utilización*: comprobar el rendimiento de la CPU en el controlador de dominio DC.  - Utilizar contadores (CPU, Memoria, Disco y Red).
 - *Ejemplo de utilización*: monitorizar la actividad de un servidor que tiene programadas tareas administrativas por la noche.
 - Utilizar recopiladores de datos creados manualmente (dentro de estos, utilizamos contadores definidos por el sistema).
   
 - Cuestionario alumnado ( Kahoot: https://kahoot.it/ )
 - 🎯*Pregunta para el alumando: ¿Diferencia entre monitorización y auditoria?*

## 3. Monitorización sistemas GNU/Linux
- Monitorización básica del sistema. Comandos: *top* y *htop*
- Monitorización básica del sistema. Interfaz gráfica: *Monitor del sistema* (similar a Windows)

🎯 *Debate:*
  
   **Situación**: Imagina que eres el encargado de administrar un servidor que empieza a funcionar muy lento. Tienes dos formas de averiguar qué ocurre:
   1. Opción A: Usar comandos de texto (top o htop).
   2. Opción B: Usar la interfaz gráfica (como el Monitor del sistema de Linux o el Administrador de tareas de Windows).
      
   **Pregunta para debatir:** ¿Qué opción crees que es mejor para descubrir por qué va lento el servidor, la A (comandos de texto) o la B (interfaz        gráfica)? ¿Por qué?
  
