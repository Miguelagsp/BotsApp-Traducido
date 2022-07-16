<p align="center">
  <img src="images/BotsApp_Logo.png" height="400px"/>
</p>


# 💠[BotsApp](https://mybotsapp.com/)💠
> Tu asistente personal, ¡en WhatsApp!
---
![GitHub top language](https://img.shields.io/github/languages/top/BotsAppOfficial/BotsApp) [![Publicación en GitHub](https://img.shields.io/github/release/BotsAppOfficial/BotsApp.svg)](https://github.com/bkimminich/juice-shop/releases/latest)
 ![Colaboradores de GitHub](https://img.shields.io/github/contributors/BotsAppOfficial/BotsApp) ![Pull requests cerradas en GitHub](https://img.shields.io/github/issues-pr-closed/BotsAppOfficial/BotsApp) ![Solicitudes de extracción de GitHub](https://img.shields.io/github/issues-pr-raw/BotsAppOfficial/BotsApp) ![GitHub Repo stars](https://img.shields.io/github/stars/BotsAppOfficial/BotsApp?style=social) ![Tamaño del repositorio de GitHub](https://img.shields.io/github/repo-size/BotsAppOfficial/BotsApp)
 

![Docker Pulls](https://img.shields.io/docker/pulls/princemendiratta/botsapp?style=flat-square&label=Docker+Pulls) ![Docker Image Size](https://img.shields.io/docker/image-size/princemendiratta/botsapp?style=flat-square&label=Docker+Image+Size)

BotsApp es un UserBot de WhatsApp optimizado y fácil de usar escrito en Node.js.

Utiliza tu asistente personal de chat/gestor de grupos para sacar el máximo partido a WhatsApp. 



## Documentación

[Enlace a la documentación](https://mybotsapp.com/documentation)


## Tutorial

Aquí tienes un tutorial para configurar BotsApp en tu propia cuenta en *menos de 3 minutos.* Por ahora, el Bot Multidispositivo sólo puede usarse localmente, cuyo tutorial se adjunta a continuación.

[![Cómo desplegar](https://img.shields.io/badge/How%20To-Deploy-red.svg?logo=Youtube)](https://www.youtube.com/watch?v=tGrjEZ3roY0&ab_channel=BotsApp)

[![Dispositivo múltiple](https://img.shields.io/badge/Host%20Multi%20Device%20bot%20on-Windows-red.svg?logo=Youtube)](https://youtu.be/NZy4sZqncjg&ab_channel=BotsApp)


## Despliegue

<b>Por ahora sólo funciona el despliegue local.</b>

### La manera más fácil

Puedes desplegar BotsApp en un tiempo mínimo y sin ningún conocimiento previo utilizando este método.

1. Dirígete al [sitio web oficial] de BotsApp (https://mybotsapp.com/) y crea una cuenta en heroku utilizando tu ID de correo electrónico.
2. Una vez iniciada la sesión, haz clic en el botón "Desplegar BotsApp" en la barra lateral.
3. Escanea el código QR que se muestra con tu cuenta de WhatsApp (3 puntos en la esquina superior derecha -> Dispositivos vinculados -> ENLAZAR UN DISPOSITIVO). Pulsa el botón 'Continuar' una vez hecho.
4. Una vez que el bot esté vinculado a tu cuenta, te encontrarás con un formulario que se puede utilizar para gestionar los ajustes/permisos de BotsApp. Si es necesario, cambia los campos del formulario. A continuación, haz clic en el botón de envío.
5. Espere de 1 a 3 minutos para que el bot se inicie. Este es un proceso único. Intenta utilizar el comando '.alive' en cualquiera de tus chats para verificar si tu bot se ha desplegado con éxito.

Ya está. Has desplegado tu bot en 5 sencillos pasos. Una vez que el bot haya arrancado con éxito, verás un mensaje de integración en tu cuenta de whatsapp.

### Manualmente en Heroku

<b>¡El despliegue a heroku usando el botón no está funcionando por ahora!</b>

¡Puedes desplegar el bot el heroku tú mismo usando el botón de abajo!

[![Despliegue en Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FBotsAppOfficial%2FBotsApp%2Ftree%2Fmain&template=https%3A%2F%2Fgithub.com%2FBotsAppOfficial%2FBotsApp%2Ftree%2Fmainhttps://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FBotsAppOfficial%2FBotsApp%2Ftree%2Fmain&template=https%3A%2F%2Fgithub.com%2FBotsAppOfficial%2FBotsApp%2Ftree%2Fmain)

### Usar Docker localmente

Para seguir este método, necesitarás tener docker instalado en tu máquina y tener algo de experiencia usando docker.

Para alojar el bot en tu propio dispositivo usando docker, sigue los siguientes pasos en tu terminal / command prompt -

```bash
wget -O BotsApp.tar.gz https://github.com/BotsAppOfficial/BotsApp/archive/refs/tags/v2.0.0-beta.tar.gz
tar -xvzf BotsApp.tar.gz
cd BotsApp-2.0.0-beta
docker build -t botsapp .
docker run --rm --name botsapp botsapp
```

Esto creará un contenedor que ejecute BotsApp. Tendrás que escanear el QR al menos una vez.

### El camino del legado de GNU/Linux

Para usar este método, necesitarás ffmpeg, nodejs, npm instalados en tu dispositivo.

Para ejecutar el bot en su dispositivo manualmente, puede utilizar los siguientes comandos -

```bash
git clone https://github.com/BotsAppOfficial/BotsApp.git
cd BotsApp
yarn
npm start
```

## Volver a escanear el código QR
Si tiene problemas al ejecutar localmente, se recomienda escanear el código de nuevo. Para obtener el código QR de nuevo, siga estos comandos -
```
rm -rf BotsApp.db session.data.json
npm start
```

## Grupos de apoyo y debate

No dude en publicar sus preguntas o dudas en cualquiera de los foros de debate que se mencionan a continuación:

[![Únase al grupo de WhatsApp](https://img.shields.io/badge/Join-WhatsApp%20Group-bl.svg?logo=WhatsApp)](https://chat.whatsapp.com/GPEHkFlspzOKpSBTsYx7Wt)

[![Únete al grupo de Telegram](https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=Telegram)](https://t.me/BotsAppChat)

[![Únase al canal de Telegram](https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram)](https://t.me/BotsAppOfficial)



## Contribuidores

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Prince-Mendiratta"><img src="https://avatars.githubusercontent.com/u/54077356?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Prince Mendiratta</b></sub></a><br /><sub><i>Project Lead Developer</i></sub></td>
    <td align="center"><a href="https://github.com/Prashant-singla"><img src="https://avatars.githubusercontent.com/u/83973641?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Prashant Singla</b></sub></a><br /><sub><i>Core Developer</i></sub></td>
    <td align="center"><a href="https://github.com/Keshav-Pahwa"><img src="https://avatars.githubusercontent.com/u/83963387?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Keshav Pahwa</b></sub></a><br /><sub><i>Core Developer</i></sub></td>
    <td align="center"><a href="https://github.com/j0h4nn1410"><img src="https://avatars.githubusercontent.com/u/72455289?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Johann Jose</b></sub></a><br /><sub><i>Core Developer</i></sub></td>
    <td align="center"><a href="https://github.com/Mohit161220"><img src="https://avatars.githubusercontent.com/u/83974093?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mohit Singh Rana</b></sub></a><br /><sub><i>Core Developer</i></sub></td>
    <td align="center"><a href="https://github.com/thegeek-dev"><img src="https://avatars.githubusercontent.com/u/70193222?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Neeraj Patel</b></sub></a><br /><sub><i>Moderator</i></sub></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->



## Inspiración

- Baileys Library

- Yusuf Usta 

- [X-tra-Telegram](https://github.com/Prince-Mendiratta/X-tra-Telegram)

## Derechos de autor y licencia
- Copyright (C) 2021 - 2022 by [BotsAppOfficial](https://github.com/BotsAppOfficial)

- Con licencia en los términos de [GNU GENERAL PUBLIC LICENSE](https://github.com/BotsAppOfficial/BotsApp/blob/main/LICENSE)

## Legal
Este código no está de ninguna manera afiliado, autorizado, mantenido, patrocinado o respaldado por WhatsApp o cualquiera de sus filiales o subsidiarias. Se trata de un software independiente y no oficial. Utilícelo bajo su propia responsabilidad.
