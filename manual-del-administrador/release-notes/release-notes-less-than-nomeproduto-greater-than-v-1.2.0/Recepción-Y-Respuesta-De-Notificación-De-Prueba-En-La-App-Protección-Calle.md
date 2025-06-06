# Recepción y Respuesta de Notificación de Prueba en la App Protección Calle

**ID: US-BTC-356**

Descripción: La aplicación Protección Calle ahora puede recibir notificaciones de prueba enviadas por el BackEnd. Cuando la app recibe esta notificación, envía un mensaje de vuelta para confirmar que todo ocurrió correctamente, incluyendo un identificador único del dispositivo en esta respuesta. Si esta respuesta no se envía con éxito, la app guarda el error para intentar nuevamente más tarde. Esto ayuda a garantizar que las notificaciones de prueba están funcionando correctamente en el celular.