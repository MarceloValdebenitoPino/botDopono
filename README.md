# DoponoBot - Bot de Telegram

DoponoBot es un bot de Telegram desarrollado en Java utilizando la biblioteca TelegramBots. Este bot guía a los usuarios a través de una serie de pasos interactivos donde pueden tomar decisiones y ganar "fama".

## Funcionalidades

- Comienza cuando un usuario envía el comando "/start".
- Guía al usuario a través de una serie de pasos donde pueden tomar decisiones.
- Registra la "fama" del usuario basada en sus acciones.
- Proporciona una experiencia interactiva y divertida para los usuarios de Telegram.

## Instalación

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Java instalado en tu sistema.
3. Configura el token del bot proporcionado por el BotFather de Telegram en el archivo `MyFirstTelegramBot.java`.
4. Compila el proyecto utilizando Maven: `mvn clean install`.
5. Ejecuta el bot utilizando el método `main` en `MyFirstTelegramBot.java`.

## Configuración

- Asegúrate de configurar correctamente el token del bot en el archivo `MyFirstTelegramBot.java`.
- Verifica que todas las dependencias definidas en el archivo `pom.xml` estén instaladas correctamente.

## Uso

1. Inicia el bot ejecutando el método `main`.
2. Envía el comando "/start" a tu bot en Telegram para comenzar la experiencia interactiva.
3. Sigue las instrucciones y toma decisiones para ganar "fama" en el bot.

## Contribución

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agrega nueva funcionalidad'`).
4. Sube los cambios a tu fork (`git push origin feature/nueva-funcionalidad`).
5. Crea un nuevo Pull Request.
