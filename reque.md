1. Gestor de marketing:
   
 | Caso de uso: Revisar campaña|
 |---------------------|
 | *Descripción:*|
 | El gestor de marketing revisa la campaña enviada por el equipo de marketing. |
 | *Flujo de Eventos*:
 |- El gestor de marketing inicia sesión en su cuenta en la página web de Migni Store. <br>- El gerente accede a la sección "campañas propuestas". <br> - Se muestra la vista de campañas propuestas. <br>- El gerente de marketing accede a la opción de "ver más" de la respectiva campaña a revisar. <br>- El gerente de marketing analiza los datos presentados y toma decisiones estratégicas basadas en la información proporcionada. <br>- En caso de que considere correcta la información proporcionada, el gerente de marketing lo publicará. <br>- En caso de que se considere incorrecta la información, serechazará la campaña. <br>- En caso de rechazar la campaña, el gerente de marketing relizará las observaciones y se las enviará al equipo de marketing.|
|*Requerimientos:*|
| Funcionales:|
| - Poder acceder a las campañas propuestas. <br> - Tener a disposición todos los datos necesarios de la campaña. <br> - Permitir la comunicación entre el gestor de marketing y el equipo de marketing. |
| No Funcionales:|        
| - Fiabilidad: El sistema debe ser confiable y estar disponible en todo momento.  <br> -  Eficiencia: El sistema debe ser eficiente en la carga y presentación de datos. <br> - Escalabilidad: El sistema debe ser capaz de manejar un aumento en el número de campañas propuestas |






### 2.1.2. Módulo de Marketing

| Código | R002  |
|----------|----------|
|Nombre  | Proponer Campaña |
| Objetivo | <p align="left"> Permitir que el Equipo de marketing proponga una campaña.</p> | 
| Descripción | Proceso mediante el cual el Equipo de marketing puede proponer una campaña para su posterior revisión de parte del Gestor de marketing. | 
| Actor primario   | Equipo de marketing | 
|Actor secundario| Gestor de marketing |
|Precondiciones | - |

| Código | R003  |
|----------|----------|
|Nombre  | Revisar campañas |
| Objetivo | <p align="left"> Permitir que el Gestor de marketing revise la campaña brindada por el equipo de marketing correspondiente.</p> | 
| Descripción | Proceso mediante el cual el Gestor de marketing puede revisar las campañas propuestas por el equipo de marketing, su criterio definirá si la campaña será aceptada o rechazada, en el caso de ser rechazada se enviarán las observaciones al equipo de marketing.  | 
| Actor primario   | Gestor de marketing | 
|Actor secundario| Equipo de marketing |
|Precondiciones | El equipo de marketing debe haber propuesto una campaña. |

| Código | R004  |
|----------|----------|
|Nombre  | Observar campaña |
| Objetivo | <p align="left"> Enviar observaciones de una campaña es específico al equipo de marketing que la diseño.</p> | 
| Descripción | Proceso mediante el cual el Gestor de marketing envía las observaciones de campañas propuestas al equipo de amrketing correspondiente. | 
| Actor primario   | Gestor de marketing | 
|Actor secundario| Equipo de marketing |
|Precondiciones | El equipo de marketing debe haber propuesto una campaña |

| Código | R005  |
|----------|----------|
|Nombre  | Atender Observaciones |
| Objetivo | <p align="left"> Permitir que el Equipo de marketing realice las correcciones de una campaña.</p> | 
| Descripción | Proceso mediante el cual el Equipo de marketing puede realizar las correcciones de campañas que les corresponda, siguiendo las observaciones realizadas por el Gestor de marketing. | 
| Actor primario   | Equipo de marketing | 
|Actor secundario| Gestor de marketing |
|Precondiciones | El Gestor de marketing debe haber realizado una observación a la campaña. |

| Código | R006  |
|----------|----------|
|Nombre  | Editar campañas vigentes |
| Objetivo | <p align="left"> Permitir que el Gestor de marketing edite las campañas vigentes.</p> | 
| Descripción | Proceso mediante el cual el Gestor de marketing puede editar las campañas que ya están vigentes, se limita a los datos necesarios y posibles de editar. | 
| Actor primario   | Gestor de marketing | 
|Actor secundario| - |
|Precondiciones | Debe existir al menos una campaña vigente. |
