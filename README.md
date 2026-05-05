# git-estefania
🚀 Guía Práctica: Git y GitHub
¡Bienvenido a este repositorio! Aquí encontrarás los conceptos fundamentales, comandos y el flujo de trabajo esencial para dominar el control de versiones y el trabajo colaborativo.

📚 Contenido
¿Qué es Git?

¿Qué es GitHub?

Flujo de Trabajo Básico

Comandos Esenciales

Buenas Prácticas

🗂️ ¿Qué es Git?
Git es un sistema de control de versiones distribuido. En términos sencillos, es como una "máquina del tiempo" para tus archivos. Te permite:

Guardar el historial de cambios de tu proyecto.

Volver a versiones anteriores si algo sale mal.

Trabajar en paralelo sin sobrescribir el trabajo de otros mediante ramas (branches).

🌐 ¿Qué es GitHub?
GitHub es una plataforma en la nube que aloja proyectos utilizando Git. Funciona como un centro de colaboración para desarrolladores. Te permite:

Almacenar copias de seguridad de tu código en la nube.

Colaborar en equipo mediante revisiones de código (Pull Requests).

Gestionar el ciclo de vida de tu software con tableros de tareas e incidencias (Issues).

🔄 Flujo de Trabajo Básico
Para llevar un cambio desde tu computadora hasta el repositorio en la nube, sigue este flujo paso a paso:

Revisar el estado: ```bash
git status

*(Te muestra qué archivos han cambiado).*

Preparar los archivos: ```bash
git add .

*(Selecciona todos los cambios para el siguiente guardado).*

Guardar localmente (Commit): ```bash
git commit -m "Descripción corta y clara del cambio"

*(Crea un punto de control en tu computadora).*

Subir a la nube (Push): ```bash
git push origin main

*(Sube tus guardados al servidor remoto).*

🛠️ Comandos Esenciales
Aquí tienes un resumen de los comandos que usarás en tu día a día:

Comando	¿Qué hace?
git init	Inicializa un nuevo repositorio en la carpeta actual.
git clone [url]	Descarga un proyecto existente desde GitHub a tu equipo.
git pull origin main	Descarga las últimas actualizaciones de la nube a tu equipo.
git branch	Muestra o crea nuevas ramas para trabajar de forma aislada.
git checkout [nombre]	Cambia entre diferentes ramas o puntos del historial.
git merge [rama]	Une los cambios de otra rama en tu rama actual.
✨ Buenas Prácticas
Mensajes de commit claros: Escribe siempre de forma descriptiva qué hace el cambio (ej. feat: añadir barra de búsqueda).

Uso de ramas: Desarrolla nuevas características en ramas separadas y déjalas listas antes de unirlas a la rama principal (main).

Sincronización frecuente: Actualiza tu rama local antes de empezar a trabajar para evitar conflictos de código.

📄 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
