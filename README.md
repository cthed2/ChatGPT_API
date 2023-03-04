# ChatGPT_API
Este repositorio es para aprender a utilizar la API de CHATGPT.
## Miembros del equipo:
- Ordinola Castillo, Javier Alexander
- Ordinola Mondragon, Martin Andre

## Creacion de ambiente virtual

1. Ejecutar la siguiente linea de dodigo en el terminal.
```
python -m venv venv
```
2. Ejecutar la siguiente linea de codigo en el terminal.
```
.\venv\Scripts\activate
```
Para verificar que se ha creado el ambiente virtual al lado izquierdo de la linea de terminal debera aparecer lo siguiente: **(venv)**, de la siguiente forma.
```
(venv) PS C:\Users\alexz\Documents\ChatGPT\ChatGPT_API>
```
> La ubicación del directorio local es a conceniencia.

> Si se presenta un error de seguridad es necesario activar los permisos desde PowerShell, lo cual se muestra en el siguiente apartado.
3. Ahora se puede proceder con la importación de la libreria OpenAI
## Activación de los permisos en PowerShell
1. Ejecutar PowerShell como Administrador
2. Ingresar lo siguiente nn el terminal qde PowerShell:
```
Get-ExecutionPolicy
```
3. Ingresar lo siguiente nn el terminal qde PowerShell:
```
Set-ExecutionPolicy RemoteSigned
```
4. Aparecese un mensaje donde te pide la confirmación de activacion de permisos, debes ingresar S para activar los permisos.