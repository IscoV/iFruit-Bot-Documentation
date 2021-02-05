# Documentación
- Ejemplo de uso
- [Configuración del bot en supergrupos](#configuración-del-bot-en-supergrupos)
- Registro de usuarios
- [Comandos](#comandos)
  - [Comandos de configuración del bot](#comandos-de-configuraci%C3%B3n-del-bot)
  - [Comandos útiles](#comandos-útiles)
  - [Emojis animados](#emojis-animados)
- [Antibots](#antibots)
- Hashtags
- FAQ - Preguntas frecuentes

## Ejemplo de uso
Para poder usar los comandos, debes usar `/` o `!` junto al nombre del comando.

> Ejemplo de uso:
```js
/profile
```
> o también 
```js
!profile
```
 

## Configuración del bot en supergrupos
El bot permite configurar ciertos parámetros para el correcto funcionamiento de sus comandos en supergrupos haciendo uso del comando `[/ o !] setting`.
- Ejemplos:
  - Lenguaje del bot dentro de un grupo
  - Establecimiento de un mensaje de bienvenida personalizado.
  - Establecimiento del número de advertencias que recibirá un usuario antes de ser expulsado en caso de exceder el limite de las mismas.
  - Habilitar o deshabilitar la función antibots.

## Registro de usuarios

## Comandos
Ciertos comandos requieren parámetros, para que se entienda su funcionamiento exponemos un ejemplo:
```js
/sethash #hashExample Example hash saved
```
Las lista de comandos del bot es la siguiente:
### Comandos de configuración del bot

| Comandos | Descripción |
| -------- | ----------- |
| `/profile` | Perfil de SocialClub (Requiere registro previo con el bot). Permite compartir tu perfil en otros grupos |
| `/setting` | Permite cambiar los ajustes del bot dentro de un grupo |

### Comandos útiles

| Comandos | Parámetros | Descripción |
| -------- | ---------- | ----------- |
| `/hash` | | Permite obtener la lista de #hashtags de un grupo. |
| `/sethash` + `#hash` + `texto`| Funciona mediante respuesta a un mensaje o añadiendo un texto personalizado | Guarda un #hashtag en el grupo. |
| `/delhash` + `#hash`| #hash a eliminar | Elimina un #hashtag del grupo |

### Emojis animados

| Comandos | Descripción |
| -------- | ----------- |
| `/dardos` | Juego de dardos animados |
| `/dados` | Juego de dado animado |
| `/gol`  | Juego de penalti |
| `/basket` | Juego de baloncesto |
| `/slots` | Juego de tragaperras |

### Otros comandos

| Comandos | Parámetros | Descripción |
| -------- | ---------- | ----------- |
| `/di` + `texto` | Texto que el bot repetirá | Todo el texto que añadas, el bot lo repetirá |
| `@admin`| Mediante respuesta a un mensaje | Avisa a todos los administradores |
 
## Antibots
El bot utiliza un sistema de rastreo de IDs de Telegram. Al ingresar un nuevo usuario al grupo, el bot hace una comprobación en este sistema y en base a sus resultados el usuario es baneado directamente e indefinidamente o en caso contrario tendrá que pasar la verificación humana teniendo que pulsar un botón.

[Combot AntiSpam System](https://cas.chat/)

## Hashtags

## FAQ - Preguntas frecuentes
