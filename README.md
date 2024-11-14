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
| Referencias | Registrarse, Gestionar su perfil, Solicitar el soporte tecnico, Relizar ejercicios, Examinarse, Interactuar con otros usuarios |
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

### Casos de uso

#### Buscar libro

| Caso de Uso CU.1 | Gestionar registros |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | Gestiona que los registros sean validos |
| Flujo básico ||
| Pre-condiciones | Que un usuario se registre |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.2 | Gestionar el contenido |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | actualiza, elimina o modifica contenido |
| Flujo básico ||
| Pre-condiciones | Que haya contenido actualizable |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.3 | Atender el soporte tecnico |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | responde a las preguntas que se formulan al soprte tecnico |
| Flujo básico ||
| Pre-condiciones | Que haya una solicitud del usuario |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.4 | Comprobar la utilizacion de la aplicación |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | revisa donde hay mas utilizcion de la aplicacion y donde menos, para optimizar el contenido |
| Flujo básico ||
| Pre-condiciones | Que los usuarios hayan utilizado la app |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.5 | Mantenimiento |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | mantenimiento general de la aplicación |
| Flujo básico ||
| Pre-condiciones | Que haya contenido que requiera mantenimiento |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.6 | Registrarse |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción | crearse la cuenta para la app |
| Flujo básico ||
| Pre-condiciones | tener un correo electronico |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.7 | Gestionar su perfil |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción | modificar su nombre, imagen de perfil |
| Flujo básico ||
| Pre-condiciones | tener una cuenta |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.8 | Solicitar el soporte tecnico |
|---|---|
| Fuentes ||
| Actor | Usuario |
| Descripción | preguntar dudas al soporte tecnico |
| Flujo básico ||
| Pre-condiciones ||  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.9 | Utilizar las funciones de la aplicacion |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción | realizar ejercicios y examenes |
| Flujo básico ||
| Pre-condiciones ||  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.10 | Interactuar con otros usuarios |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción |  Chatear, retar a otros usuarios |
| Flujo básico ||
| Pre-condiciones | Tener a otros usuarios agregados |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.11 | Validar cuenta |
|---|---|
| Fuentes ||
| Actor | Sistema de notificaciones |
| Descripción | manda un correo para validar la cuenta |
| Flujo básico ||
| Pre-condiciones | que se haya creado una ueva cuenta |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

| Caso de Uso CU.12 | Recordatorio de ejercicio |
|---|---|
| Fuentes ||
| Actor | Sistema de notificaciones |
| Descripción | Envia un recordatorio a la hora que estipule el usuario |
| Flujo básico ||
| Pre-condiciones | Que el usuario haya solicitado el recordatorio |  
| Post-condiciones ||  
| Requerimientos ||
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |