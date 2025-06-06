# Activación con Token OAuth en la App Protección Calle

**ID de US: US-BTC-72**

En la aplicación Protección Calle, puedes activar tu acceso usando un token OAuth. Cuando te autenticas con un token válido, recibes un access_token y un refresh_token, que te permiten acceder a las funciones de la app. Si el access_token expira, podrás usar el refresh_token para obtener uno nuevo. Si ocurre algún problema al intentar activar, aparecerá un mensaje informando que hubo una falla. La activación de la app también te permite cambiar de dispositivo sin perder el acceso, garantizando que continúes usando la app normalmente con el nuevo deviceId.