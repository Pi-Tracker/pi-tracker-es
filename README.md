### A fecha de 25 de abril de 2026, Pi Tracker ya no se mantiene en servicio.

# Acerca de

Un bot de Discord que proporciona información sobre Pi Network.

# Descargo de responsabilidad

Este repositorio puede no estar siempre actualizado con la versión actual del bot.

Gracias a Gemma por ayudar con la traducción.

# Dependencias

Axios 1.6.7

discord.js 14.14.1

dotenv 5.0.0

# Instalaciones

Asegúrate de tener Node.JS 16.11+

Clona el repositorio

```
git clone https://github.com/ifeeljoy/pi-tracker-es.git
```

Instala las dependencias.

```
npm install discord.js dotenv axios
```

Cambia el nombre de ‘.env-example’ a ‘.env’ y agrega tu token de bot y el ID del cliente.

```
// El token de tu bot de Discord.
TOKEN_DEL_BOT=aquí

// El ID de la aplicación de tu bot de Discord.
ID_DEL_CLIENTE=aquí

// La tasa base actual para el minado. Se puede encontrar en la aplicación Pi.
TASA_DE_MINADO=0.0029378
```

Inicia el bot

```
node index.js
```

# Licencia 

Este proyecto está bajo la Licencia Pública General GNU v3.0. Consulta el archivo LICENSE para más detalles.
