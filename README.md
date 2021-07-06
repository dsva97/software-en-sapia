# Software a instalar:

## Para desarrollo

- DBeaver

- Cliente para Mongo (Mongo Compass o Robo 3T)

- Postman

  Lo usan de forma estandar en Sapia, incluso tienen una licensia pero es para usuarios de su domino.

- VSCode

  Alan recomendó estas extensiones: ![6 extensiones para VSCode](https://media.discordapp.net/attachments/861674535262093335/861995197700243456/unknown.png?width=675&height=670))

- Docker
 
  - Consideraciones

    - Será necesario reiniciar para finalizar la instación.
 
    - Debe ejecutarse al iniciar el sistema.
    
- Docker Compose (incluído en Docker Desktop para Windows)

    - Mismas consideraciones que con Docker. Si se ejecuta en Windows no es necesario.


- Python 3
- Node JS

  - La más estable actualmente es 14.17.3

  - Consideraciones

    Es posible que más adelante necesitemos programar en una versión específica. Para ese caso hay 3 casos:

    - Desinstalar e Instalar Node JS para cada cambio de versión. (esto pasa en windows)

    - Configurarlo en Docker (puede que esté demás para algunos proyectos que no usen/necesiten docker)

    - Usar NVM

      NVM instala fácilmente versiones de node js y npm, permitiendo cambiar entre ellos sin problema.
      La cuestión es que nvm añade la versión de node js configurada a la variable de entorno PATH. En este caso se necesitará permiso de admistrador pasado por Soporte Técnico de Perú Apps. Si el cambio es frecuente y la urgencia de cambiar de versiones es mayor que la disponibilidad del Soporte Técnico podría llamarse directamente al binario de node JS dentro de la carpeta NVM.

## Para coordinación y diseño

(los siguientes se puede usar desde la web pero es recomendable la aplicación de escritorio)

- Discord
- Figma
- WhatsApp
- Microsoft Teams
