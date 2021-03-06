# Software a instalar:

- [OpenVPN](#openvpn)
- [DBeaver](#dbeaver)
- [Robo 3T](#robo-3t-recomendable) (y/o [Mongo Compass](#mongo-compass)]
- [Postman](#postman)
- [VSCode](#vscode)
- [Docker Desktop](#docker)
- [Node JS](#node-js)
- [Python 3](#python-3)
- [Discord Desktop](#discord)
- [Figma Desktop](#figma)

## Detalle

### Para desarrollo

- #### OpenVPN

  (https://openvpn.net/community-downloads/)

  (añadir usuario al grupo "OpenVPN Administrator")

- #### DBeaver

  (https://dbeaver.io/)

- #### Cliente para Mongo

  Cualquiera de los siguientes:

  - #### Robo 3T (Recomendable)
    (https://robomongo.org/download)
  - #### Mongo Compass
    (https://www.mongodb.com/try/download/community)

- #### Postman

  (https://www.postman.com/downloads/)

  Lo usan de forma estandar en Sapia, incluso tienen una licensia pero es para usuarios de su domino.

- #### VSCode

  (https://code.visualstudio.com/)

  Alan recomendó estas extensiones: 
  
  ![6 extensiones para VSCode](https://media.discordapp.net/attachments/861674535262093335/861995197700243456/unknown.png?width=675&height=670))

- #### Docker

  (https://www.docker.com/products/docker-desktop)

  (añadir usuario al grupo "docker-users")

  - Consideraciones

    - Será necesario reiniciar para finalizar la instación.

    - Debe ejecutarse al iniciar el sistema.

- Docker Compose (incluído en Docker Desktop para Windows)

  - Mismas consideraciones que con Docker. Si se ejecuta en Windows no es necesario.

- #### Python 3

  (https://www.python.org/downloads/)

- #### Node JS

  (https://nodejs.org/es/)

  - La más estable actualmente es 14.17.3

  - Consideraciones

    Aunque por ahora basta con la versión 14.17.3, es posible que más adelante se necesite programar en una versión específica. Para ese caso hay 3 casos:

    - Desinstalar e Instalar Node JS para cada cambio de versión. (esto pasa en windows)

    - Configurarlo en Docker (puede que esté demás para algunos proyectos que no usen/necesiten docker, aunque cumpliría el objetivo)

    - Usando NVM
      (En linux: https://github.com/nvm-sh/nvm)
      (En windows: https://github.com/coreybutler/nvm-windows)

      NVM instala fácilmente versiones de node js y npm, permitiendo cambiar entre versiones sin problema.

      Para instalar una versión específica:
      `nvm install v14.17.3`

      Para configurarla la versión a usar en el directorio actual:
      `nvm use v14.17.3`

      Para configurarla la versión por defecto en todo el sistema:
      `nvm alias default v14.17.3`

      La cuestión es que nvm añade la versión de node js configurada a la variable de entorno PATH. En este caso se necesitará permiso de admistrador pasado por Soporte Técnico de Perú Apps. Si el cambio de versiones es frecuente y su urgencia de cambiar de versiones es mayor que la disponibilidad del Soporte Técnico, entonces sólo quedaría ejecutar node desde la carpeta de NVM. Por defecto en Windows es: C:\Users\[Usuario]\AppData\Roaming\nvm
      De todas formas, si se elige NVM, es recomendable correr los comandos anteriores inmediatamente despues de la instalación en presencia del Soporte Técnico porque, como se mencionó, se necesita el permiso del administrador.

### Para coordinación y diseño

(los siguientes se puede usar desde la web pero es recomendable la aplicación de escritorio)

- #### Discord
  (https://discord.com/download)
- #### Figma
  (https://www.figma.com/downloads/)
- #### WhatsApp
  (https://www.whatsapp.com/download/?lang=es)
  
### Nota
Si se está haciendo la instalación en conjunto con Soporte técnico entonces es recomendable que se pruebe todo (incluso las conexiones a la VPN, ejecución automática de Docker al iniciar el sistema, etc.) en ese momento.

✌️
