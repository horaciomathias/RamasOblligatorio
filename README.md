
|Materia - Evento           | Fundamentos de ingeniería de software - Obligatorio 1     | 
|---------------------------|-----------------------------------------------------------|
|**Código grupo - Docente** | **N4A - Gerardo Quintana**                                |
|**Estudiantes del Grupo**  | **Horacio Ábalos, Federico Méndez**                       |
|**Fecha de entrega**       | **15/10/2020**                                            |
|**URL Repositorio**        | https://github.com/ORT-FIS-202008/ob1-abalos-mendez       |

![Logo](https://github.com/horaciomathias/Testes/blob/main/Recursos/Imagenes/Logo.png) 

# **Repositorio**

## *Estrategias de commits* 
  
El proyecto usará el servicio de repositorio GitHub utilizando los criterios:   
 
* [Commits Convencionales](https://www.conventionalcommits.org/en/v1.0.0/ "Estandares de commits utilizados en el proyecto")  
* [Comit Atomico](https://www.conventionalcommits.org/en/v1.0.0 "Tipos de commits utilizados") 

## *Flujo utilizando ramas*
Utilizaremos las ramas de acuerdo con la descripción debajo:  

### *Especificación de Requerimientos*
* **Especificación de Requerimientos** - Rama principal de la actividad en la cuál se registrarán los cambios luego de completado el ciclo de especificación. Compuesta de las siguientes subramas:  
    * **Entrevista** - documentos generados luego de cada entrevista;
    * **Requerimientos** - documentos generados para la verificación de los requerimientos derivados del análisis. Luego de validados los requerimientos de las subramas se realizará el merge con *Requerimientos*
        * **Funcionales** - para documentar la validación de los Requerimientos Funcionales
        * **No Funcionales** - para documentar los Requerimientos No Funcionales
    * **Prototipos** - para documentar la validación de prototipos para la interfaz de usuario


### *Desarrollo*
* **Master** – solamente una rama con este nombre;  
* **Release** – se utilizarán tantas ramas como sea necesario para realizar pruebas;  
* **Develop** – rama de desarrollo compuesta de varias subramas *Feature* a las cuáles se incorporan las funcionalidades completas (terminadas). Una vez que la funcionalidad está testeada se realizará el *merge* correspondiente a la rama *develop* generando y controlando el versionado a través de merge con la rama *release*. El criterio utilizado para generar el versionado está descrito más adelante;  
* **Hotfix** – para realizar cambios implementables y testeables en menos de 48 horas desde su requerimientos; y,  
* **Feature** – para generar funcionalidades 




## *Estructura del Repositorio*
El repositorio contará con varias carpetas y subcarpetas en las cuales se guardarán los distintos documentos relacionados con el proyecto:

* **Elicitación**
    * **Análisis de Requerimientos**: Documentación del análisis de los requerimientos identificados;
    * **Modificaciones Solicitadas**: Documentación de modificaciones solicitadas y análisis de impacto;
* **Especificación**
    * **Entrevistas**: Documentación de las entrevistas generadas;
    * **Casos de Uso**: Documentación de los casos de uso;
    * **Historias de Usuario**: Documentación de las historias de usuario;
    * **Modelos**: Documentación de los modelos desarrollados;
    * **Tablas**: Documentación de las tablas generadas vinculando necesidades, requerimientos, casos de uso y features;
    * **Glosario**: Terminología asociada al proyecto;
* **Validación y Verificación** 
    * **Validación**: Documentos con validación del cliente;
    * **Verificación**: Documentación de la verificación de la solución presentada;
* **Recursos**
    * **Imagenes**: Utilizadas en distintos documentos;
    * **Templates**: Archivos necesarios para preparar una reunión con el cliente, plantillas para user stories, plantillas para use cases, etc 

--------------------------------------------------------------------------------------------------------------------------------------------------------
# **Versionado**

## *Metodología de numeración de versiones*
Todos los requerimientos obtenidos serán vinculados a las features y éstas descritas por dos palabras, véase [Tabla Necesidades - Requerimientos - Clasificación - Código](https://github.com/horaciomathias/Testes/blob/main/Especificacion/Tablas/Tabla%20Necesidades%20-%20Requerimientos%20-%20Clasificaci%C3%B3n%20-%20C%C3%B3digo.pdf "Tabla Necesidades - Requerimientos - Clasificación - Código"),  para luego ser vinculadas a un código alfanumérico de identificación inequívoca compuesto por: 
* 3 letras abreviación de la primera palabra;
* punto (.), 
* 3 letras abreviación de la segunda palabra; 
* guión (-); y,
* 4 digitos separados por un punto

Los digitos asignados inicialmente serán 0.0.0.0 para la primer versión de la *feature* representando que se encuentra en fase inicial de desarrollo. Posteriormente, al ser modificada la versión disponible de la *feature*, se actualizarán los dígitos para controlar la versión que está al servicio del cliente. El proyecto seguirá el uso de normas de versionado. Esta política incluye:
* Uso de los 4 dígitos de la numeración para representar: major.minor.revisión.entrega 
* El cambio de cualquiera de estos números depende del tipo de los cambios que aporte la nueva Versión. 
    * *major*: indica la versión principal del software, consistiendo en un conjunto de funcionalidades concretas que son recogidas y cubiertas en dicha versión.
    * *minor*: indican funcionalidad menor cubierta en la versión de software entregada.
    * *revisión*: se modifican cuando hay revisiones de código ante fallos de la aplicación.
    * *entrega*: este dígito tiene el objetivo de llevar la cuenta del número de veces que una entrega se rechaza, por incumplimiento de algún requisito de la gestión de entregas o del proyecto.


## *Criterios para la modificación de versiones*

Los criterios para modificar (incrementar) cada uno de los contadores de la etiqueta de versión son los siguientes:

* *major*: nuevas funcionalidades claves de la aplicación respecto a la versión anterior debido a la inclusión de nuevos requerimientos para el sistema, como la inclusión de nuevos módulos o una revisión completa de los existentes.
* *minor*: cambios significativos en la forma en la que se ofrece la funcionalidad existente, corrección de grandes fallos del sistema o nuevas versiones evolutivas que modifican significativamente la funcionalidad ofrecida.
* *revisión*: se modifica por cada entrega de software que se realice.
* *entrega*: al rechazarse una entrega se incrementa este contador en la siguiente. Cuando la entrega es aceptada se crea un tag público que solo conserva los tres primeros dígitos (mayor.minor.revisión).
 


--------------------------------------------------------------------------------------------------------------------------------------------------------
# **Elicitación**
## *Entrevistas* 
Las entrevistas con el cliente serán registradas en el documento [Modelo de Entrevistas](https://github.com/horaciomathias/Testes/blob/main/Recursos/Templates/Template%20Entrevista.docx "Template para Entrevistas")

## *Casos de Uso* 
Los Casos de Uso serán registrados utilizando el [Template de Casos de Uso](https://github.com/horaciomathias/Testes/blob/main/Recursos/Templates/Template%20Caso%20de%20Uso.docx "Template para Casos de Uso")

## *Historias de Usario*
Las Historias de Usuario serán registradas utilizando el [Template de Historias de Usuario](https://github.com/horaciomathias/Testes/blob/main/Recursos/Templates/Template%20Historia%20de%20Usuario.docx "Template para Casos de Uso")

## *Identificación de usuarios, tareas y contexto*
Los usuarios sus tareas y contextos serán identificados en el [siguiente documento](https://github.com/horaciomathias/Testes/blob/main/Elicitacion/Analisis%20de%20Requerimientos/Usuarios%20-%20Tareas%20-%20Contexto.pdf "Usuarios, tareas y contexto")

---------------------------------------------------------------------------------------------------------------------------------------------------------
# **Especificación**
El proyecto cumplirá el estándar [IEEE STD 830-1998](https://standards.ieee.org/standard/830-1998.html "Recommended Practice for Software Requirements Specifications")

Una vez realizada la entrevista y registrado en el documento todos los detalles pertinentes, el cliente y el responsable aprueban su contenido acordando los compromisos y firmando la propuesta. El archivo se guarda en la carpeta *Entrevistas* bajo el nombre compuesto por el codigo de la entrevista.

Todas las entrevistas serán catalogadas bajo un estándar propio que consta de 3 letras para identificar el nombre del proyecto (GUI en este caso ya que el proyecto se llama GUITARCHILD) y dos dígitos, asignados secuencialmente comenzando a partir del 00 (para la entrevista inicial), separados de las 3 letras por un guión (-). Las entrevistas posteriores aumentarán secuencialmente la numeración.

Los requerimientos derivados de las necesidades planteadas por los interesados serán vinculados, clasificados (según deriven en requerimientos funcionales o no funcionales), y asociados a un código, véase [Tabla Necesidades - Requerimientos - Clasificación - Código](https://github.com/horaciomathias/Testes/blob/main/Especificacion/Tablas/Tabla%20Necesidades%20-%20Requerimientos%20-%20Clasificaci%C3%B3n%20-%20C%C3%B3digo.pdf "Tabla Necesidades - Requerimientos - Clasificación - Código"). 

Los requerimientos funcionales identificados serán asociados a un código de caso de uso y clasificados por funcionalidades, con su respectivo código, para establecer una relación directa entre el requerimiento y su caso de uso asociado, véase [Tabla RF- Código UCRF - Features - Código Feature](https://github.com/horaciomathias/Testes/blob/main/Especificacion/Tablas/Tabla%20RF-%20Codigo%20UCRF%20-%20Features%20-%20Codigo%20Feature.pdf "Tabla RF- Código UCRF - Features - Código Feature")

Para mayor entendimiento de la relación entre requerimientos funcionales se incluye un modelo de Jerarquía Funcional
![Logo](https://github.com/horaciomathias/Testes/blob/main/Especificacion/Modelos/Jerarquia%20Funcional.png "Modelo de Jerarquía Funcional") 

Los requerimientos no funcionales identificados serán clasificados según su tipo, véase [Clasificación de Requerimientos No Funcionales](https://github.com/horaciomathias/Testes/blob/main/Especificacion/Modelos/Clasificacion%20de%20Requerimientos%20no%20Funcionales.png "Clasificación de Requerimientos No Funcionales")

Todos los términos relacionados con el proyecto serán registrados en el [glosario](https://github.com/horaciomathias/Testes/blob/main/Glosario/Glosario.md "Glosario de Terminología asociada al proyecto")


---------------------------------------------------------------------------------------------------------------------------------------------------------

# **Validación y verificación**
## *Validación*
Serán elaborados documentos con los requerimientos derivados para la validación del cliente en una reunión posterior. Dichos requerimientos serán presentados bajo el formato derterminado en el [Template para identificación de necesidades](https://github.com/horaciomathias/Testes/blob/main/Recursos/Templates/Template%20identificacion%20de%20necesidades.docx "Template identificacion de necesidades")

Puede ser posible la utilización de diagramas para explicar la interacción de los actores con el sistema durante las entrevistas.

Tras ser validados por el cliente, los requerimintos serán analizados nuevamente para identificar los aspectos técnicos y elaborar documentos de soporte para el desarrollo de las funcionalidades necesarias.

Todos los requerimientos derivados del análisis serán documentados, validados por el cliente y asociados a un nivel de prioridad (Alto, Medio o Bajo) en el documento [Validación de Necesidades](https://github.com/horaciomathias/Testes/blob/main/Validacion%20y%20Verificacion/Validacion/VALIDACI%C3%93N%20DE%20NECESIDADES%20derivadas%20de%20GUI-01.pdf "Validación de Necesidades") 



## *Verificación*
Será verificado el cumplimiento de los objetivos de calidad para cada requerimiento utilizando una [matriz de seguimiento](https://github.com/horaciomathias/Testes/blob/main/Validacion%20y%20Verificacion/Verificacion/Matriz%20de%20Cumplimiento%20de%20Calidad.pdf)


---
# **Defensa y reflexión** 
## *Defensa* 



## *Reflexión*
