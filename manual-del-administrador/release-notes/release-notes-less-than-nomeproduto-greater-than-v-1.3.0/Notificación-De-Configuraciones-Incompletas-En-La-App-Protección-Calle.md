# Notificación de Configuraciones Incompletas en la App Protección Calle

**ID: US-BTC-528**

La aplicación Protección Calle avisa a los usuarios sobre configuraciones que aún necesitan ser completadas cuando inician sesión por primera vez o después de cambios en el registro. Esta funcionalidad garantiza que todos los pasos sean finalizados para que la app funcione correctamente y de forma segura. Si la app no logra enviar las notificaciones al servidor, intentará de nuevo hasta tres veces, aumentando el tiempo de espera entre los intentos. Una vez que las configuraciones estén completadas, la notificación desaparece, asegurando que el usuario vea solo información que es realmente importante.