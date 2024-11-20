# Matemáticas

App para enseñar matematicas, con explicaciones, ejercicios, retos y examenes.

<img src="docs\disenio\diagramas\diagrama.drawio.png">

## Especificación de Actores y Operaciones

<dl><b>Administrador: </b> con permisos completos para gestionar la aplicación y moderar contenidos.<br><br>
    <dd><b>Gestionar cuentas: </b>comprueba que los registros son correctos en cuanto al nombre y la imagen</dd>
    <dd><b>Gestionar contenido: </b> actualiza, elimina o modifica contenido</dd>
    <dd><b>Soporte tecnico: </b> responde a las preguntas que se formulan al soprte tecnico</dd>
    <dd><b>Revisar patrones de uso: </b> revisa donde hay mas utilizcion de la aplicacion y donde menos, para optimizar el contenido</dd>
    <dd><b>Mantenimiento: </b> mantenimiento general de la aplicación</dd>
</dl>

<dl><b>Usuario: </b> que puede crear y modificar su perfil, así como interactuar con contenidos.<br><br>
    <dd><b>Gestinar su perfil: </b>crearse la cuenta para la app, modificarla, eliminarla</dd>
    <dd><b>Solicitar soporte tecnico: </b>preguntar dudas al soporte tecnico</dd>
    <dd><b>Ver explicaciones: </b>modificar su nombre, imagen de perfil</dd>
    <dd><b>Realizar ejerciocios: </b> realizar ejercicios de matemáticas</dd>
    <dd><b>Interactuar con usuarios: </b> chatear, retar a otros usuarios.</dd>
</dl>

<dl><b>Sistema: </b>realiza funciones automatizadas<br><br>
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
| Relaciones | Tambien puede realizar las funciones del usuario |
| Referencias | Gestionar cuentas, Gestionar contenido, Soporte tecnico, Revisa patrones de uso, Mantenimiento |   
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista|
|Fecha | 11/11/2024 |

#### Usuario

| Actor | Usuario |
|---|---|
| Descripción | Usuario común de la app |
| Características ||
| Relaciones ||
| Referencias | Gestionar su perfil, Solicitar soporte tecnico, Ver explicaciones, Realizar ejercicios, Interactuar con usuarios |
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista|
|Fecha | 11/11/2024 |

#### Sistema

| Actor | Sistema |
|---|---|
| Descripción | Sistema que realiza funciones automatizada |
| Características ||
| Relaciones ||
| Referencias | Validar cuenta, Recordatorio de ejercicios |   
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista|
|Fecha | 11/11/2024 |

### Casos de uso

#### Gestionar cuentas

| Caso de Uso CU.1 | Gestionar cuentas |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | Gestiona que las cuentas sean validas |
| Flujo básico ||
| Pre-condiciones | Que un usuario cree una cuenta |  
| Post-condiciones ||  
| Requerimientos | Que un usuario cree una cuenta |
|  Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Gestionar el contenido

| Caso de Uso CU.2 | Gestionar el contenido |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | actualiza, elimina o modifica contenido |
| Flujo básico ||
| Pre-condiciones | Que haya contenido actualizable |  
| Post-condiciones ||  
| Requerimientos | Que haya contenido actualizable |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Soporte tecnico

| Caso de Uso CU.3 | Soporte tecnico |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | responde a las preguntas que se formulan al soprte tecnico |
| Flujo básico ||
| Pre-condiciones | Que haya una solicitud del usuario |  
| Post-condiciones ||  
| Requerimientos | Que haya una solicitud del usuario |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Revisar patrones de uso

| Caso de Uso CU.4 | Revisar patrones de uso |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | revisa donde hay mas utilizcion de la aplicacion y donde menos, para optimizar el contenido |
| Flujo básico ||
| Pre-condiciones | Que los usuarios hayan utilizado la app |  
| Post-condiciones ||  
| Requerimientos | Que los usuarios hayan utilizado la app |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Mantenimiento

| Caso de Uso CU.5 | Mantenimiento |
|---|---|
| Fuentes ||
| Actor | Administardor |
| Descripción | mantenimiento general de la aplicación |
| Flujo básico ||
| Pre-condiciones | Que haya contenido que requiera mantenimiento |  
| Post-condiciones ||  
| Requerimientos | Que haya contenido que requiera mantenimiento |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Gestionar su cuenta

| Caso de Uso CU.6 | Gestionar su cuenta |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción | Crea, modifica y elimina su cuenta |
| Flujo básico ||
| Pre-condiciones ||  
| Post-condiciones ||  
| Requerimientos ||
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Solicitar el soporte tecnico

| Caso de Uso CU.7 | Solicitar el soporte tecnico |
|---|---|
| Fuentes ||
| Actor | Usuario |
| Descripción | preguntar dudas al soporte tecnico |
| Flujo básico ||
| Pre-condiciones | tener una cuenta |  
| Post-condiciones ||  
| Requerimientos | tener una cuenta |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Ver explicaciones

| Caso de Uso CU.8 | Ver explicaciones |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción | Ver explicaciones matemáticas |
| Flujo básico ||
| Pre-condiciones | tener una cuenta |  
| Post-condiciones ||  
| Requerimientos | tener una cuenta |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Realizar ejercicios

| Caso de Uso CU.9 | Realizar ejercicios |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción | realizar ejercicios |
| Flujo básico ||
| Pre-condiciones | tener una cuenta |  
| Post-condiciones ||  
| Requerimientos | tener una cuenta |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Interactuar con usuarios

| Caso de Uso CU.10 | Interactuar con usuarios |
|---|---|
| Fuentes ||
| Actor | Usuario, administrador |
| Descripción |  Chatear, retar a otros usuarios |
| Flujo básico ||
| Pre-condiciones | Tener a otros usuarios agregados |  
| Post-condiciones ||  
| Requerimientos | Tener una cuenta|
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Validar cuenta

| Caso de Uso CU.11 | Validar cuenta |
|---|---|
| Fuentes ||
| Actor | Sistema |
| Descripción | manda un correo para validar la cuenta |
| Flujo básico ||
| Pre-condiciones | que se haya creado una nueva cuenta |  
| Post-condiciones ||  
| Requerimientos | que se haya creado una nueva cuenta |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |

#### Recordatorio de ejercicio

| Caso de Uso CU.12 | Recordatorio de ejercicio |
|---|---|
| Fuentes ||
| Actor | Sistema de notificaciones |
| Descripción | Envia un recordatorio a la hora que estipule el usuario |
| Flujo básico ||
| Pre-condiciones | Que el usuario haya solicitado el recordatorio |  
| Post-condiciones ||  
| Requerimientos | Que el usuario haya solicitado el recordatorio |
| Notas ||
| Autor | Alexander Faustino Diaz Bautista |
| Fecha | 11/11/2024 |