# Matemáticas

App para enseñar matematicas, con explicaciones, ejercicios, retos y examenes.

<img src="img/matematicas.drawio.png">

## Especificación de Actores y Operaciones

<dl><b>Administrador: </b> con permisos completos para gestionar la aplicación y moderar contenidos.<br><br>
    <dd><b>Gestionar registros: </b>comprueba que los registros son correctos en cuanto al nombre y la imagen.</dd>
    <dd><b>Gestionar el contenido: </b> actualiza, elimina o modifica contenido.</dd>
    <dd><b>Atender el soporte tecnico: </b> responde a las preguntas que se formulan al soprte tecnico.</dd>
    <dd><b>Comprobar la utilizacion de la aplicación: </b> revisa donde hay mas utilizcion de la aplicacion y donde menos, para optimizar el contenido.</dd>
    <dd><b>Mantenimiento: </b> mantenimiento general de la aplicación.</dd>
</dl>

<dl><b>Usuario: </b> que puede crear y modificar su perfil, así como interactuar con contenidos.<br><br>
    <dd><b>Registrarse: </b>crearse la cuenta para la app.</dd>
    <dd><b>Gestionar su perfil: </b>modificar su nombre, imagen de perfil.</dd>
    <dd><b>Solicitar el soporte tecnico: </b>preguntar dudas al soporte tecnico.</dd>
    <dd><b>Utilizar las funciones de la aplicacion: </b> realizar ejercicios y examenes.</dd>
    <dd><b>interactuar con otros usuarios: </b> chatear, retar a otros usuarios.</dd>
</dl>

<dl><b>Sistema de notificaciones: </b>manda mensajes a los usuarios.<br><br>
    <dd><b>Validar cuenta: </b>manda un correo para validar la cuenta.</dd>
    <dd><b>Recordatorio de ejercicio: </b> Envia un recordatorio a la hora que estipule el usuario.</dd>
</dl>

## Especificación de casos de uso

### Actores

#### Administrador

| Actor | Administrador |
|---|---|
| Descripción | Administrador de la app |
| Características ||
| Relaciones ||
| Referencias | Gestionar registros, Gestionar el contenido, Atender al soporte tecnico, Comprobar la utilización de la app, Mantenimiento |   
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista|
|Fecha | 11/11/2024 |

#### Usuario

| Actor | Usuario |
|---|---|
| Descripción | Usuario común de la app |
| Características ||
| Relaciones ||
| Referencias | Registrarse, Gestionar su perfil, Solicitar el soporte tecnico, Relizar ejercicios, examinarse, Interactuar con otros usuarios |   
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista|
|Fecha | 11/11/2024 |

#### Sistema de notificación

| Actor | Sistema de notificación |
|---|---|
| Descripción | Sistema que envia notificaciones |
| Características ||
| Relaciones ||
| Referencias | Validar cuenta, Recordatorio de ejercicios |   
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista|
|Fecha | 11/11/2024 |