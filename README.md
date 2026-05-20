# 📅 Planificación de la actividad: Supuesto práctico SOR
Repositorio con materiales para el supuesto práctico del módulo profesional [SOR]-SISTEMAS OPERATIVOS EN RED - Programa **CONSIGUE+** - 
Academia Básica del Aire y del Espacio de León (ABA) - 
**MODALIDAD**: Presencial - 
**DURACIÓN**: 10 horas (5 horas + 5 horas)

## Objetivo
Aprender a instalar y configurar un entorno de red corporativa con:
- Windows Server 2022 como Controlador de Dominio
- Windows 11 y Linux Mint como clientes
- Active Directory
- Recursos compartidos e impresoras
- Integración Linux-Windows

## Estructura de las jornadas

| Carpeta | Contenido |
|---------|-----------|
| `01_INSTALACION_SO/` | Requisitos, instalación de VirtualBox, ISOs, creación de MVs |
| `02_ACTIVE_DIRECTORY/` | Clonación, grupos, promoción a DC, unión de clientes al dominio |
| `03_GESTION_USUARIOS/` | OUs, grupos, usuarios, horarios, perfiles móviles y obligatorios |
| `04_RECURSOS_COMPARTIDOS/` | Carpetas y permisos, scripts de conexión, servidor de impresión |
| `05_INTEGRACION_LINUX/` | Linux Mint, integración con AD, acceso a recursos Windows-Linux |
| `06_MONITORIZACION/` | Visor de eventos, auditoría, monitor de rendimiento, top/htop |

---

## Jornada 1 (4-5h)

| **HORA** | **ACTIVIDAD** | **CONTENIDO** |
| --- | --- | --- |
| 0:00 - 0:30 | Introducción | Presentación de las jornadas y entorno de trabajo |
| 0:30 - 1:30 | Entorno virtual | Instalación de VirtualBox. Configuración inicial |
| | | Descarga de las imágenes ISO desde las web oficiales |
| | | Creación de MVs: Windows Server. Requisitos para la instalación |
| | | Creación de MVs: Ubuntu Server. Configuración por defecto |
| | | Cuestionario alumnado |
| 1:30 - 2:30 | Active Directory (Parte 1) | Clonación de MVs (Generar nuevas MAC) |
| | | Creación de grupos: "Máquinas limpias" y "Máquinas SOR" |
| | | Instantánea antes de AD |
| | | Instalación del rol AD DS |
| | | Promoción a Controlador de Dominio |
| 2:30 - 3:30 | Active Directory (Parte 2) | Creación de MVs: Windows 11. Requisitos para la instalación |
| | | Unión del equipo W11 al dominio *miempresaXXX.local* |
| | | Inicio de sesión con un usuario del dominio en el cliente W11 | 
| 3:30 - 4:00 | Preguntas y cierre | |

---

👉 Con esta planificación:

* **Horas totales** = 5h + 5h = **10h**.
* Cada sesión incluye **teoría aplicada + ejercicios prácticos**.
