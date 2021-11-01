# Manual uso HCE FINAL 8

MANUAL DE USUARIO

HISTORIA CLÍNICA ELECTRÓNICA

![](../.gitbook/assets/0)

| _**Autor del Manual**_ | **Carvajal, Ariel**                   |
| ---------------------- | ------------------------------------- |
|                        | Médico esp. Clínica Medica            |
|                        | Diplomatura en Telemedicina           |
|                        | Posgrado en Auditoria Médica          |
|                        | Maestrando en Informática Médica HIBA |

_**Segunda ed. Diciembre de 2019**_

_**Primera ed. Diciembre de 2018**_

Tabla de contenido

ACERCA DE LA HISTORIA CLÍNICA ELECTRÓNICA 5

REQUISITOS PREVIOS PARA PODER ACCEDER A LA HCE 6

ACERCA DE LOS PERMISOS 6

GUÍA DEL USUARIO PARA MÉDICOS 7

**1. Generalidades del acceso** 7

2\. Mis pacientes: Búsqueda y gestión de pacientes 8

**2.1 Área de internación** 9

2.1.1 En seguimiento 9

2.1.2 Interconsultas (Buzón) 9

Pasos para responder una interconsulta 10

2.1.3 En el Servicio 12

2.1.4 En el Hospital 12

_**2.2 Área de Consultorio**_ 12

2.2.1 Requisitos previos 12

2.2.2 Consulta de turnos 13

_**2.3 Área de Emergencias**_ 14

1.Presentacion módulo de triage 14

2.Funcionamiento 15

**3. Interfaz de consulta de Historia Clínica Electrónica** 18

_**3.1 Resumen de problemas**_ 19

_**3.2 Historial de evoluciones**_ 19

3.2.1 Atención actual 19

3.2.2 Historial de evoluciones 20

_**3.3 Indicaciones/Enfermería**_ 20

_**3.4 Interconsultas**_ 21

_**3.5 Estudios / informes**_ 21

_**3.6**_ _**Gráficos / Seguimiento (no disponible aún)**_ 22

**4. Interfaz de ingreso de registro de Historia Clínica Electrónica** 23

_**Nuevo movimiento**_ 23

_**Antes de comenzar: El concepto de Historia Clínica Orientada al Problema**_ 23

_**4.1 Iniciar Evolución**_ 25

4.1.1 Diagnostico/ Problema 25

4.1.1.1 Búsqueda de problemas 27

4.1.1.2 Carga de Problemas Agudos 29

4.1.1.3 Manejo del “Estado del Problema”: 31

4.1.1.4 Carga de Problemas Crónicos 32

4.1.1.5 Manejo estado de los problemas crónicos 33

4.1.1.6 Carga de Problemas como antecedentes 33

4.1.1.7 Carga de Procedimientos como antecedentes 35

4.1.2 Iniciando 36

4.1.3 Plan/Terapéutica 36

4.1.4 Finalizando Evolución 37

4.1.5 Guardar como borrador 37

¿Dónde encuentro mis borradores? 38

_**4.2 Epicrisis**_ 39

_**4.3 Solicitudes**_ 42

_**4.3.1 Estudios de imágenes**_ 42

A.Guía de usuario para el médico 42

B.Guía para el técnico de rayos 46

_**4.3.1 Solicitud de Hemoderivados**_ 48

A.Guía de usuario para el Médico Prescriptor 48

_**4.4 Indicaciones y recetas**_ 51

_**4.5 Interconsulta**_ 56

_**4.6 Fichas**_ 58

4.6.1 Protocolo Quirúrgico 58

4.6.2 Maniobra invasiva 62

4.6.3 Procedimiento diagnostico 64

_**4.7 Anexar archivos a HCE**_ 66

**5. Imprimir** 67

**6. Firma Digital** 68

6.1 Características 68

_**6.2 Pasos a seguir para firmar un documento**_ 69

**8. Interacción con admisión y egresos** 72

8.1 Medico solicita internación en la plataforma EVA 72

8.2 Otras solicitudes a Admisión 74

8.3 Guía de uso de admisión 75

**9. Preguntas frecuentes** 77

Tengo problemas de visualización de la Historia Clínica Electrónica 77

¿Dónde puedo encontrar la Historia Clínica de un paciente que di de alta? 77

¿Puedo acceder a las interconsultas de un servicio diferente al predeterminado? 77

El servicio que me figura como predeterminado, no es en que estoy actualmente 77

¿Puede más de un especialista realizar seguimiento a un paciente? 78

No se cargó el problema que necesito a la lista de problemas 78

¿Puedo eliminar un problema luego de haberlo agregado? 78

No figura la fecha de alta y días de internación en la epicrisis 79

¿Mis borradores pueden ser vistos por otro usuario? 79

¿Con que fecha se guardan los borradores? 79

Mensaje: OTP incorrecto 79

¿Con que frecuencia debo firmar los documentos de la HCE? 79

No puedo ver el informe de un estudio ya realizado 80

**ESTADO DE SITUACIÓN ACTUAL EN EL HOSPITAL CENTRAL**

Actualmente en el hospital existen diferentes procesos informatizados:

\-Sub sistemas de registro medico de consultorio externo

\-Sub sistema de laboratorio

\-Subsistema de Rayos

\-Subsistema de anatomía patológica

\-Sub sistema de quirófano, etc.

Cada uno de estos módulos se maneja de manera independiente con escasa comunicación entre los mismos, por lo cual la información ingresada en los mismos en ocasiones es difícil de consultar y conlleva una importante pérdida de tiempo cada vez que un profesional desea ver la información de un paciente en particular.

### ACERCA DE LA HISTORIA CLÍNICA ELECTRÓNICA <a href="_toc70505205" id="_toc70505205"></a>

En el contexto del plan de nacional de modernización del ministerio de salud de la nación, surge el proyecto de informatización de los sistemas de información hospitalaria del Hospital Central de Mendoza.

Este proyecto promovido por el director del Hospital Central Dr. Ariel Herrera, pretende crear una historia clínica electrónica para el ámbito de internación que se transformara en la columna vertebral de nuestro sistema de información.

La Historia Clínica Electrónica tiene un diseño que nos permitirá trabajar con una historia clínica orientada al problema, la cual tiene por ventaja sobresaliente ayudarnos a mejorar el cuidado del paciente.

**Objetivos del proyecto HCE**

\- HCE como columna vertebral que conecte los diferentes sistemas de información.

\- HCE única, modular, orientada al problema, centrada en el paciente funcionando sobre una plataforma Web.

\- Utilizar para el funcionamiento de la misma vocabularios estándar como SNOMED CT y CIE 10.

El equipo principal de trabajo para llevar a cabo el desarrollo está conformado por:

| **Integrante**          | **Rol**                                                                                        |
| ----------------------- | ---------------------------------------------------------------------------------------------- |
| **Carvajal, Ariel**     | <p>Informático Médico</p><p>(Maestría en informática médica en Hospital Italiano de Bs As)</p> |
| **Perotti, Gabriel**    | Programador principal                                                                          |
| **Moyano, Maximiliano** | Programador asociado                                                                           |

### REQUISITOS PREVIOS PARA PODER ACCEDER A LA HCE <a href="_toc70505206" id="_toc70505206"></a>

* Tener un legajo en el área de personal del Hospital Central.
* Haber realizado la capacitación de HCE.
* Haber llenado el formulario “solicitud de alta” al sistema de HCE y haberlo presentado en el área de informática (6 piso).
* Tener acceso a una PC, Tablet o Smartphone conectados a la intranet del hospital ya que la HCE solo será accesible desde la intranet desde dispositivos autorizados.

### ACERCA DE LOS PERMISOS <a href="_toc70505207" id="_toc70505207"></a>

Los permisos van a ser diferentes según el rol de usuario: Médico, enfermero, kinesiólogo, técnico o administrativo.

**Personal Medico**

_**a- Permisos de lectura y permisos de escritura**_

Médico tratante, médicos del servicio y médicos de área de urgencias (UTI, UCO o guardia general). Profesionales de un servicio al cual le fue solicitada una evaluación mediante interconsulta.

_**b- Sin permisos**_

Médicos que no se encuentren dentro del grupo anterior. Podrán tener acceso a la HCE previa justificación de la necesidad de acceso.

_**c- Restricción de permisos**_

En este caso los permisos de lectura y escritura estarán limitados al grupo de médicos tratantes. Un médico no tratante podrá tener acceso en caso de necesitarlo, mediante una contraseña, advirtiendo que el acceso no autorizado será auditado.

**Personal de Enfermería**

Permisos de lectura: Solo podrán ver la lista de problemas. Podrá además ver las indicaciones médicas del paciente.

**Personal Kinesiología**

Permisos de lectura limitado: Solo podrán ver la lista de problemas agudos por el cual ingreso el paciente con sus limitaciones correspondientes. Podrá además ver las indicaciones médicas del paciente.

**Técnicos**

_**Laboratorio, Farmacia, Hemoterapia, Anatomía patológica, farmacia y Rayos.**_

Sin Permisos de lectura. Solo podrán ver las solicitudes realizadas.

### GUÍA DEL USUARIO PARA MÉDICOS <a href="_toc70505208" id="_toc70505208"></a>

### **1. Generalidades del acceso** <a href="_toc70505209" id="_toc70505209"></a>

**A- Acceso directo desde la intranet**

Se aconseja utilizar el acceso directo ubicado en la intranet del Hospital para acceder a la plataforma de HCE (Historia Clínica Electrónica). Como en ocasiones necesitamos por cuestiones internas cambiar la dirección de acceso de la HCE, no se aconseja crear accesos directos y se aconseja siempre acceder desde la intranet.

En la siguiente figura se puede ver el acceso directo a HCE.

![](../.gitbook/assets/1)

**B. Login**

![](../.gitbook/assets/2)Al lanzar la aplicación, el sistema solicitara que se ingrese un nombre de usuario y contraseña (suministrado previamente en el departamento de informática).

**C. Lanzador de aplicaciones**

![](../.gitbook/assets/3)

Al ingresar a la plataforma EVA sobre la cual esta desarrollada la HCE del Hospital vamos a tener acceso a una lista de aplicaciones dentro de las cuales vamos a encontrar un acceso directo a la HCE.

**D. Antes de comenzar**

* Es importante tener en cuenta que el nombre de usuario y contraseña son _**personales e intransferibles**_.
* Todos los movimientos realizados en la HCE serán registrados con el nombre de usuario asignado.
* Como medida de seguridad el usuario deberá cerrar su sesión siempre, después de trabajar.

### 2. Mis pacientes: Búsqueda y gestión de pacientes <a href="_toc70505210" id="_toc70505210"></a>

En el ámbito hospitalario podemos distinguir 3 grandes ámbitos asistenciales: _**Internacion, Consultorio y Emergencias**_. Cada una de estas áreas tiene requerimientos particulares, por lo cual el modelo de HCE tendrá adaptaciones teniendo en cuenta estos requerimientos.

![](../.gitbook/assets/4)

### **2.1 Área de internación** <a href="_toc70505211" id="_toc70505211"></a>

A continuación, mostraremos como está organizado el módulo de organización y búsqueda de pacientes internados en el Hospital.

**Mis pacientes (Modulo de gestión y búsqueda de pacientes)**

![](../.gitbook/assets/5)Una vez que el profesional se ha autenticado e ingresa al sistema, va a encontrar en la pantalla inicial un acceso directo a los pacientes internados. En el panel izquierdo se podrá observar 4 accesos para los diferentes módulos de búsqueda y gestión de pacientes _(Ver Fig.1)_:

1. _**Gestión: “En seguimiento” e “Interconsultas”**_
2. _**Búsqueda: “En el servicio” y “En el Hospital”**_
3. _**Herramienta de búsqueda**_

Fig.1: Modulo de gestión y búsqueda de pacientes

### 2.1.1 En seguimiento <a href="_toc70505212" id="_toc70505212"></a>

En este módulo se agrupan los pacientes a los cuales el profesional ha evaluado e iniciado un seguimiento. El paciente aparecerá en la lista mientras se encuentre internado y se borrará de la misma en caso de que el profesional decida terminar el seguimiento o el paciente haya sido dado de alta del hospital.

En el caso de finalizar un seguimiento el nombre del paciente será borrado de la lista de seguimiento, pero seguirá apareciendo en la lista de pacientes internados (a menos que haya sido dado de alta).

### 2.1.2 Interconsultas (Buzón) <a href="_toc70505213" id="_toc70505213"></a>

El buzón está dividido en 2 partes: por una parte, tenemos el buzón general del servicio y por otra parte un buzón personal. En este módulo se agruparán las interconsultas nuevas recibidas desde otros servicios. Una vez que las mismas son contestadas, pasan a ser parte del módulo de seguimiento.

En la imagen a continuación podrá ver una captura del Buzón de Interconsultas:

![](../.gitbook/assets/6)

Con (A) se marca el buzón general de interconsultas del servicio, el profesional tendrá acceso a todas las interconsultas enviadas al servicio al cual pertenece. Con (B) se marca el buzón personal de interconsultas de cada profesional y es aquí donde se agruparán las interconsultas que fueron dirigidas y las interconsultas auto asignadas por el profesional.

El profesional podrá asignarse cualquier interconsulta que llega al servicio. El resto de los profesionales sabrá que interconsultas están tomadas y cuales libres para responder. Todo profesional que necesite responder una interconsulta deberá primero auto asignarse la interconsulta.

#### Pasos para responder una interconsulta <a href="_toc70505214" id="_toc70505214"></a>

1. Auto asignación de interconsulta:

En la lista de pacientes que se muestra en el buzón general del servicio, el usuario deberá seleccionar el paciente de interés con un clic. Una vez seleccionado vamos a ver la ventana que se muestra en la siguiente imagen con un botón que dice “asignarme e iniciar seguimiento”, presionar dicho botón para iniciar seguimiento.

![](../.gitbook/assets/7)

1. Evolucionar:

Una vez que el usuario se auto asignó un paciente como se muestra en la siguiente imagen tiene la opción de “Evolucionar”.

![](../.gitbook/assets/8)

El usuario debe seleccionar dicho botón y se abrirá la ventana con la historia clínica del paciente para poder consultar el historial médico del paciente.

![](../.gitbook/assets/9)

Una vez que la evaluación fue concluida el profesional deberá seleccionar:

Nuevo movimiento Iniciar evolución Seleccionar o cargar el problema a evolucionar Evolucionar Guardar.

Con esta secuencia de pasos la Interconsulta se considera contestada una vez guardada la evolución.

1. Alta del Servicio

Finalmente, cuando el paciente no requiere más seguimiento por parte de la especialidad en cuestión, el profesional deberá dar el alta del servicio.

Haciendo clic en el nombre de un paciente autoasignado aparece la imagen que se muestra a continuación. El usuario debe presionar “Dar alta del Servicio”

![](../.gitbook/assets/10)

En importante recalcar que al hacer esto, la interconsulta es borrada tanto del buzón general como del buzón personal. No modificando su estado en la lista internados.

Para ver cómo crear una interconsulta vea: Pasos para crear una Interconsulta

### 2.1.3 En el Servicio <a href="_toc70505215" id="_toc70505215"></a>

En este módulo se podrá consultar la lista de pacientes ingresados en el servicio de internación en el cual trabaja el profesional. El acceso debería ser total para los profesionales de un mismo servicio a menos que se especifique lo contrario. El profesional o paciente podrían solicitar una restricción de acceso a una historia clínica determinada.

### 2.1.4 En el Hospital <a href="_toc70505216" id="_toc70505216"></a>

En este módulo se podrá consultar la lista de pacientes internados en todo el Hospital. El profesional puede buscar a un paciente internado en cualquier lugar del Hospital, pero con un acceso restringido no pudiendo ver la HCE a menos que justifique su ingreso. La extensión de una interconsulta será la vía oficial de conceder autorización por parte de los profesionales tratantes.

Los médicos no deberían tener restricciones de acceso total, salvo casos puntuales en los que se especifique restricción de acceso, pudiendo acceder solo mediante interconsulta de alguno de los profesionales tratantes o clave de desbloqueo.

### _**2.2 Área de Consultorio**_ <a href="_toc70505217" id="_toc70505217"></a>

En el ámbito de consultorios vamos a encontrar una división (que está en plan de unificación), entre consultorio externo y consultorio del hospital. Desde el punto de vista del usuario no habrá diferencias apreciables y solo podrá ver 2 accesos directos diferentes.

### 2.2.1 Requisitos previos <a href="_toc70505218" id="_toc70505218"></a>

Los datos de acceso que deberá usar el profesional serán los mismos que usa para la internación. En el caso de ser un usuario de consultorio deberá: 1)tener un legajo activo en el área de personal del hospital, luego 2) solicitar el alta del sistema con el [formulario](http://10.101.0.23/intranet/index.php?option=com\_content\&view=article\&id=1597\&Itemid=137) disponible en la intranet para tal fin y 3) hacer el tramite de firma digital para poder firmar los registros generados y recetas.

### 2.2.2 Consulta de turnos <a href="_toc70505219" id="_toc70505219"></a>

Históricamente la base de datos del hospital se encuentra dividida en dos, basada en la ubicación física de los mismos, por lo cual van a encontrar 2 accesos como se muestra en la siguiente imagen.

![](../.gitbook/assets/11)

**Fig:1 Acceso a consultorios**

**Una vez que el profesional ingresa con sus datos de identificación, dependiendo de la ubicación física del consultorio donde atienda el profesional deberá ingresar por uno u otro acceso.**

**CONSULTORIOS HOSPITAL: **Vascular periférico, Oftalmología, Traumatología, Nutrición, ORL, Trasplante renal, Educación en diabetes, Cardiología, Electrofisiología, Oncología, Fertilidad, Cirugía de cabeza y cuello, Fonoaudiología, Cirugía de tórax, Neumonologia, Hematología, etc

**CONSULTORIOS EXTERNOS: **Clínica Médica, Neurología clínica, Neurocirugía, Cirugía, gastroenterología, Inmunología, urología, medicina laboral, Infectología, Medicina Laboral, dermatología, renal, etc

Caso de ejemplo: Suponiendo que tenga que ingresar a consultorio externo porque hoy me toca hacer recetas de _**inmunología**_ y los turno fueron dados a un _**médico genérico.**_

![](../.gitbook/assets/12)

**Fig:2 Busqueda de turnos**

Como puede verse en la figura uno, no me figura ningún turno en mi lista de pacientes debido a que los turnos fueron dados como médico genérico. Por esto es que debo hacer una búsqueda de esos turnos, siguiendo los siguientes pasos: 1- Seleccionar _**Ver Todos**_, 2-Presionar el botón _**actualizar listado**_, 3- _**Buscar**_ el servicio “**Inmuno**” y médico “**genérico**” (o el que corresponda) con lo cual los turnos aparecerán a la derecha (4). Seleccionando el Nombre del paciente se podrá abrir la Historia clínica, evolucionar y hacer recetas normalmente.

Véase: como trabajar con la historia Clínica

### _**2.3 Área de Emergencias**_ <a href="_toc70505220" id="_toc70505220"></a>

Uno de los avances más significativos de la Medicina de Urgencias en los últimos años ha sido la estructuración y aplicación del triage de urgencias.

Existe un consenso generalizado, en que la calidad en la atención del paciente se beneficia de la implementación del triage estructurado y de la categorización de la urgencia en los cuartos de urgencias.

Además, el triage estructurado se ha convertido en un componente fundamental y en piedra de toque de la gestión clínica de los cuartos de urgencias, del análisis de la casuística y de la comparación entre ellos. El triage es ampliamente utilizado en la auditoría y en la mejora de la calidad de los cuartos de urgencias donde se aplica, habiendo demostrado un extraordinario potencial en la investigación.

En el área de Emergencias la gestión de pacientes tiene sus particularidades por lo que se hace indispensable incorporar la funcionalidad de TRIAGE en el mismo con el fin de que la lista de pacientes que se encuentren en la guardia en la sala de espera sean atendidos según la gravedad del caso y dejar de esta manera en segundo lugar como factor de importancia el tiempo de espera.

### 1.Presentacion módulo de triage <a href="_toc70505221" id="_toc70505221"></a>

En el contexto de la Emergencia sanitaria el triage es una herramienta esencial para el proceso asistencial en la guardia de emergencias. Se deja de usar el papel

**Esquema General del flujo de pacientes**

![](../.gitbook/assets/13)

_**Figura1: Captura pantalla principal de Emergencias**_

Dentro del Área de Emergencias, podemos distinguir 3 áreas diferenciadas:

1. **Sala de espera**: En esta sección se van a por visualizar todos los pacientes que aun no ha recibido atención médica ya sea que se le haya realizado o no el TRIAGE.

**Como puede verse en la figura 1, se podrá consultar en esta lista **:

*
  *
    *
      1. Fecha y hora del ingreso en el sistema de guardia
      2. Tiempo de demora
      3. Sección de la guardia para la que el paciente saco turno: Guardia general, Enfermedades Pulmonares, Oftalmología.
      4. Nombre y apellido del paciente
      5. Estado del triage y Color asignado en triage en caso de que haya sido realizado.

1. **En seguimiento**: En esta sección aparecerán todos los pacientes que el profesional (usuario) atendió en algún momento.
2. **Atendidos**: En esta sección se podrá consultar la lista de todos los pacientes atendidos por los diferentes profesionales de la guardia.

### 2.Funcionamiento <a href="_toc70505222" id="_toc70505222"></a>

**A. Sala de espera**

La lista de pacientes de la sala de espera esta ordenada de arriba abajo, de mayor a menor tiempo de espera. Ósea los pacientes que llevan más tiempo esperando estarán primeros en la lista y este es uno de los factores a tener en cuenta al momento de iniciar una atención.

![](../.gitbook/assets/14)

En esta captura de pacientes de la sala de espera podemos ver que los primeros 6 pacientes ya tienen realizado el Triage como pueden ver en la última columna. Este es el otro factor que el profesional deberá tener en cuenta para ver cuál es el paciente que debe llamar a continuación.

Por ejemplo el paciente n° 6 de la lista lleva esperando menos tiempo que el paciente n° 1 de la lista pero está catalogado como ROJO en el triage, así que tendrá la primer prioridad de atención independientemente de la hora de llegada. Le siguen en prioridad el AMARILLO y luego los VERDES que generalmente son la mayoría teniendo en cuenta en estos casos la hora de llegada para llamar a los pacientes.

**B. En seguimiento**: Una vez que el paciente haya sido tomado de la sala de espera por un profesional determinado, el nombre del mismo pasara a formar parte de la lista de pacientes en seguimiento de dicho profesional.

**C. Atendidos**: Todos los pacientes tomados de la lista de espera pasaran a formar parte de esta lista de pacientes, independientemente de quien haya sido el profesional que tomo al paciente. Se podrá además en esta lista consultar quienes fueron los profesionales que atendieron al paciente.

1. **El proceso de TRIAGE**

El proceso de triage habitualmente es llevado a cabo por un enfermero. Para tener acceso al sistema el usuario deberá tener nombre de usuarios habilitados.

1. Para el proceso deberá tenerse en la lista de pacientes de la sala de espera para llamar a los pacientes.
2. Habitualmente se llamará primero a los que llevan más tiempo de espera. Que son los primeros de la lista.
3. Una vez que el paciente acude al llamado se inicia el triage al hacer clic sobre el nombre y apellido del paciente
4. Se abre la ficha de triage en la cual se deberán ingresar una serie de datos y completar un cheklist de síntomas respiratorios (incluido por la pandemia)

![](../.gitbook/assets/15)

1. Una vez completada la ficha se deberá clasificar en ROJO, AMARILLO O VERDE, según la prioridad de atención que se le debería dar al paciente.

_**ROJO:**_ Emergencia que se debe atender de forma inmediata

_**AMARILLO:**_ Urgencia que se debe atender dentro de los próximos 60 min

_**VERDE:**_ Sin urgencia, debe espera a que se lo atienda.

1. Una vez que se selecciona la prioridad deberá guardar el triage.
2. Se puede ver en la lista general los pacientes a los que ya les realizo el triage con la prioridad que se le dio.

![](../.gitbook/assets/16)

1. **Proceso de atención por parte del médico**

Ya sea que los pacientes tengan o no realizado el triage, el proceso en el sistema es el mismo para el médico, solo cambian los parámetros con los que el médico seleccionará al próximo paciente.

En caso de no disponer de personal para realizar el triage, el profesional podrá utilizar el tiempo de espera como un parámetro para llamar a los pacientes.

![](../.gitbook/assets/17)

Una vez que hace clic el nombre y apellido del paciente se abrirá la ficha de triage en blanco y podrá abrir directamente la Historia Clínica del paciente.

_**Al hacer clic en el botón que se muestra en la figura, además de abrir la Historia clínica del paciente:**_

1. Se iniciará automáticamente un seguimiento.
2. El nombre del paciente desaparecerá de la sala de espera
3. El nombre del paciente pasara a “En seguimiento”
4. Se abrirá la Historia clínica del paciente para trabajar

_**Una vez dentro de la historia clínica del paciente se deberá ingresar la información, correspondiente para cada caso:**_

**Verdes: **Agregar al menos el diagnóstico o problema por el que consulta el paciente.

**Amarillos y rojos: **Se deberá agregar el diagnóstico y completar la Historia Clínica. Cada uno de los médicos intervinientes deberá dejar su registro en la Historia Clínica de estos pacientes.

**Véase a continuación Interfaz de consulta y registro**

### **3. Interfaz de consulta de Historia Clínica Electrónica** <a href="_3._interfaz_de" id="_3._interfaz_de"></a>

En el ámbito de internación encontramos diferentes servicios, por lo que la HCE tendrá las adaptaciones que requiera cada servicio. Esta guía pretende mostrar las funciones básicas comunes para facilitar el uso de la HCE a los profesionales.

Una vez que el profesional ingresa a la historia clínica de un paciente, podrá ver en la barra de navegación ubicada a la izquierda, un área de accesos para poder consultar los diferentes movimientos en la Historia Clínica de un paciente, y un acceso para realizar nuevos movimientos dentro de la HCE de un paciente.

![](../.gitbook/assets/18)

Fig.2: Áreas de gestión de información del paciente

### _**3.1 Resumen de problemas**_ <a href="_toc70505224" id="_toc70505224"></a>

A través del mismo vamos a poder visualizar 1- el resumen de problemas del paciente tanto agudos como crónicos, 2- un histórico de procedimientos y 3- un historial de atenciones. En el historial de atenciones se podrá ver un listado unificado de consultas en el ámbito hospitalario y en el sistema sanitario de la provincia (en un futuro).

![](../.gitbook/assets/19)

Fig.3: Áreas de resumen de problemas del paciente.

### _**3.2 Historial de evoluciones**_ <a href="_toc70505225" id="_toc70505225"></a>

Permitirá al profesional consultar la lista de evoluciones de la internación en curso o el histórico de consultas.

![](../.gitbook/assets/20)

Fig.4: Área donde se agrupan la lista de evoluciones del paciente

### 3.2.1 Atención actual <a href="_toc70505226" id="_toc70505226"></a>

Bajo este acceso se listarán las evoluciones, intervenciones y fichas llenadas en el transcurso del periodo de internación en el servicio. Esta lista estará ordenada cronológicamente de manera que los movimientos más recientes queden arriba y los más antiguos abajo.

En la lista podremos ver:

**Columna 1:** Fecha y hora del registro

**Columna 2:** Cama en la que se encontraba el paciente cuando el profesional registró el movimiento.

**Columna 3:** Nombre del profesional

* En caso de tratarse de una evolución: Se mostrará el nombre del problema evolucionado
* En caso de tratarse de un protocolo quirúrgico o maniobra invasiva: mostrar en nombre del procedimiento
* En caso de tratarse de otras fichas el nombre de la ficha.

**Columna 4:** Tipo de movimiento (evoluciones, fichas, protocolo quirúrgico) y problema evolucionado

A la derecha de esta lista podemos ver una ventana donde se cargará la información vinculada con un determinado movimiento.

### 3.2.2 Historial de evoluciones <a href="_toc70505227" id="_toc70505227"></a>

Fig.5: Área donde se agrupan los accesos a los diferentes grupos de registros del paciente

En este apartado se mostrará tanto los registros de las consultas realizadas en consultorio, guardia de emergencias o internaciones.

**1-Actual:** Siempre al ingresar en historial de evoluciones el sistema mostrara los registros de la internación en curso. Pero puedo consultar registros históricos mediante los diferentes accesos.

_**2-Historico:**_ Este acceso directo traerá todos los registros de internaciones anteriores ingresadas en el sistema

_**3-Hosp.:**_ Este acceso directo traerá todos los registros ingresados en los consultorios ubicados físicamente en el edificio principal del Hospital Central.

_**4-C.Ext.:**_ Este acceso directo traerá todos los registros ingresados en los consultorios externos ubicados físicamente en el edificio de Salta y Catamarca.

Adicionalmente el sistema nos da la opción de realizar una búsqueda por profesional, problema o tipo de documento en 1 y 2.

### _**3.3 Indicaciones/Enfermería**_ <a href="_toc70505228" id="_toc70505228"></a>

Permitirá al profesional consultar la lista completa de indicaciones, tanto activas como historicas.

Esquema terapeutico:

Aquí podremos consultar la lista de cuidados generales, fármacos, esquemas de hidratación parenteral y esquema de corrección de insulina indicados al paciente. Además de los ítems particulares a cada cuidado, podremos ver el estado de cada indicación: Confirmada, pendiente y suspendida.

_**Medicación habitual:**_

Aquí podremos consultar la lista de los medicamentos que el paciente consume habitualmente en el ámbito ambulatorio. Durante la internación algunos fármacos son suspendidos por lo que es útil tener esta herramienta de consulta.

_**Controles de enfermería:**_

En esta pestaña podremos consultar los controles registrados por enfermería, los balances de ingresos y egresos y las observaciones realizadas por el personal de enfermería.

### _**3.4 Interconsultas**_ <a href="_6.4_interconsultas" id="_6.4_interconsultas"></a>

Permitirá al profesional, consultar la lista de solicitudes de evaluacines solicitadas a diferentes especialidades para el paciente.

Podemos además ver el estado de las mismas:

**Pendiente:** La interconsulta (IC) aún no fue asignada a un profesional interconsultor. Pendiente asignación.

**Asignada:** en caso de que la interconsulta haya sido asignada a un profesional. La asignación en algunos casos dependerá de la secretaria del servicio al cual se haya solicitado la evaluación, del jefe de servicio o podrá ser realizada en forma directa por el médico solicitante.

**Contestada:** en caso de que el profesional haya evolucionado en la HC del paciente, esta solicitud pasara automáticamente al estado de contestada (al alta).

### _**3.5 Estudios / informes**_ <a href="_toc70505230" id="_toc70505230"></a>

Permitirá al profesional consultar todas las solicitudes de estudio realizadas, el estado de las mismas y los resultados de los estudios en caso de que estos estén concluidos.

En este apartado los profesionales podrán consultar informes digitalizados, traídos desde otra institución en papel, ya sean informes de RMN, de TAC, informes de anatomía patológica, etc.

En la figura puede verse que este paciente tiene una ecografía y una tomografía cargadas.

Se puede consultar además la lista de solicitudes de estudios realizadas desde el sistema como puede verse en la siguiente figura.

Vease también: _**4.7 Anexar archivos a HCE**_

**INTERFAZ MIXTA**

### _**3.6**_ _**Gráficos / Seguimiento (no disponible aún)**_ <a href="_toc70505231" id="_toc70505231"></a>

Permitirá al profesional consultar gráficas de seguimiento que se podrán generar automáticamente con datos ingresados en la HCE. Además de las opciones predeterminadas para generar estos gráficos, la idea es que el profesional pueda crear su propia tabla para generar gráficos personalizados de seguimiento.

Por ejemplo, tomando los registros de peso ingresados al sistema, podemos generar una curva de peso, donde podremos observar como varia el peso en función del tiempo.

### **4. Interfaz de ingreso de registro de Historia Clínica Electrónica** <a href="_toc70505232" id="_toc70505232"></a>

### _**Nuevo movimiento**_ <a href="_toc70505233" id="_toc70505233"></a>

Mediante este acceso el profesional podrá iniciar diferentes acciones que quedaran grabadas en la historia clínica del paciente:

1\) Iniciar una evolución, fichas de maniobras invasivas, protocolo quirúrgico,

2\) Iniciar Epicrisis de internación

4\) Solicitar interconsulta,

5\) Ficha de solicitud estudio anatomía patológica y cultivos de bacteriología.

6\) Cargar archivos digitalizados en formato PDF

Fig.6: Área de ingreso de datos a la HCE del paciente.

### _**Antes de comenzar: El concepto de Historia Clínica Orientada al Problema**_ <a href="_toc70505234" id="_toc70505234"></a>

Antes de comenzar a desarrollar el módulo de diagnóstico de la HCE, vamos a ver brevemente el concepto de Historia Clínica Orientada al Problema.

En la década del ‘60, el microbiólogo Lawrence Weed desarrolló un modelo de historia clínica que permitía hacer un registro dinámico de la información.

Este modelo nos daba la libertad para consignar aquellos eventos relacionados con los cuidados de los pacientes, que hasta el momento no habían sido tenidos en cuenta porque no eran diagnósticos médicos. A dichos eventos los definió como "problemas “…

_**Entonces. ¿Qué es un problema?**_

"Problema es todo aquello que requiera diagnóstico, manejo posterior, o interfiera con la calidad de vida, de acuerdo con la percepción del paciente ".

Cuadro 1: Ejemplos de problemas

| **Tipo de Problema**                  | **Ejemplo**                                                                                             |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| DIAGNOSTICO/ENEFERMEDAD               | Asma, diabetes                                                                                          |
| DEFICIENCIA, INCAPACIDAD, MINUSVALIA  | Parálisis cerebral, hemiparesia braquial derecha                                                        |
| SINTOMA                               | Dolor torácico, Náuseas                                                                                 |
| SIGNO                                 | Rubicundez, tensión arterial elevada                                                                    |
| EXAMEN COMPLEMENTARIO ANORMAL         | Glucemia elevada, piocitos en orina                                                                     |
| ALERGIA, EFECTO ADVERSO DE UN FARMACO | Alergia a la penicilina, tos por enalapril                                                              |
| INTERVENCION QUIRURGICA               | Apendicitis, colecistectomía                                                                            |
| SINDROME MEDICAMENTE DEFINIDO         | Síndrome de Meniere, síndrome de túnel carpiano                                                         |
| EFECTOS DE UN TRAUMATISMO             | Hematoma, fractura                                                                                      |
| FACTOR DE RIESGO                      | Factor de riesgo laboral/ neumoconiosis, factor de riesgo familiar, cáncer de colon, poliposis familiar |
| TRASTORNO PSICOLOGICO/PSIQUIATRICO    | Depresión, crisis de pánico                                                                             |
| ALTERACION FAMILIAR, SOCIAL O LABORAL | Padres ansíanos, niño recién nacido, desocupación                                                       |

Cuadro2: Clasificación de problemas

**Problemas crónicos: Activos vs Pasivos**

* **Problemas Crónicos Activos: **Son aquellos que requieren una acción en el momento actual.
* **Problemas Crónicos Pasivos: **Estos No requieren una acción en el momento, pero es útil registrarlos porque su existencia afecta el manejo de otros .

_**Nota: Los problemas pasivos pueden volverse activos o al revés.**_

**Problemas Agudos: Activo, Resuelto y Desestimado**

* **Problemas Agudo Activo: **Son aquellos que requieren una acción en el momento actual.
* **Problemas Agudo Resuelto: **El problema ya no requiere ningún tipo de intervención.
* **Problema Desestimado: **En ocasiones la evidencia luego de estudiar un caso puede llevarnos a desechar un diagnóstico.

**NO es problema**

Cuando se consigna en la historia un problema esto debe hacerse según el máximo grado de certeza que se tiene en ese momento; por lo tanto NO es problema:

• **Un término vago o no concreto: **hemopatía, proceso respiratorio

• **Algo a descartar**: descartar hipotiroidismo

• **Una sospecha o diagnóstico probable**: _probable hepatitis_

### _**4.1 Iniciar Evolución**_ <a href="_toc70505235" id="_toc70505235"></a>

Con el objeto de facilitar el proceso de registro medico todas las acciones anteriormente mencionadas pueden realizarse en la interfaz de evolución.

### 4.1.1 Diagnostico/ Problema <a href="_toc70505236" id="_toc70505236"></a>

Una vez realizada la anamnesis, lo primero que debe hacer el profesional es cargar el problema a evolucionar, o seleccionar uno previamente existente.

La herramienta de búsqueda nos permite el ingreso de terminología desde SNOMED CT (_Systematized Nomenclature of Medicine – Clinical Terms_) , que vamos a usar como vocabulario de referencia.

**Presentación de la interface gráfica del gestor de problemas**

Fig.7: Gestor de problemas.

En el caso de tener que agregar un nuevo problema, vamos a utilizar el gestor de problemas. Esta herramienta nos va a permitir mantener ordenados la lista de problemas del paciente, de manera rápida y sencilla.

El gestor está conformado por dos partes:

1. Un área donde se muestran la lista de _**problemas ya cargados**_ (D).

Estos problemas pueden ser _**Crónicos **_(Activo o Pasivo) o _**Agudos**_ (ya sean activos o resueltos).

1. Un área para agregar nuevos problemas mediante una _**herramienta de búsqueda**_ (A y B) y _**clasificación del Problema**_ (C).

**Conociendo los componentes del gestor de problemas**

_**A. Buscador**_

Esta herramienta nos permite buscar terminología de SNOMED ya sea que se encuentre vinculada o no a nuestro tesauro institucional y agregarla a nuestro gestor de problemas.

_**B. Visualizador de problema seleccionado a cargar**_

En esta pequeña ventana se podrá ver el problema buscado y seleccionado desde el tesauro institucional o SNOMED y que será cargado a la lista de problemas previa clasificación del mismo.

_**C. Herramienta para clasificación de problemas.**_

Todo problema nuevo ingresado, debe ser clasificado previamente antes de presionar el botón agregar (de lo contrario el sistema no permitirá agregar el nuevo problema)

_**D. Lista de problemas**_

Esta lista es única para cada paciente y el profesional puede gestionar la lista de problemas y agregar movimientos a partir de la selección de cualquiera de los problemas de la lista. Todos los cambios de estado de un problema quedaran registrados en un historial dentro del problema.

TRABAJANDO CON EL GESTOR DE PROBLEMAS

Con este ejemplo se pretende mostrar cómo se debe usar el gestor de problemas para ingresar la lista de problemas a la Historia Clínica de un paciente.

* **Búsqueda de problemas**
* **Carga de Problemas Agudos**

**Manejo estado de los problemas**

* **Carga de Problemas Crónicos**

**Manejo estado de los problemas**

* **Carga de Problemas como antecedentes**
* **Carga de Procedimientos**

**Protocolo quirúrgico**

**Maniobra invasiva**

#### 4.1.1.1 Búsqueda de problemas <a href="_7.1.1.1_busqueda_de" id="_7.1.1.1_busqueda_de"></a>

**-SITUACION 1 Encuentro el termino en el tesauro**

Necesito buscar el termino:

**Neumonía adquirida en la comunidad**

Ingreso en el buscador: **NAC **(la abreviatura mas utilizada para esta patología)

Esto me devuelve el termino requerido desde el Tesauro institucional:

**Neumonía adquirida en la comunidad**

Fig.14: Ejemplo de diagnóstico encontrado en tesauro.

**-SITUACION 2: NO Encuentro el término que necesito en el Tesauro**

Necesito buscar el termino:

**Sarcoidosis**

Ingreso en el buscador: **Sarcoidosis **(tener el recaudo de escribir correctamente en termino)

Si bien el termino no se encuentra en el Tesauro institucional, al momento de confeccionar esta guía, el buscador me devuelve el termino requerido desde SNOMED, el cual puedo seleccionar y agregar a la lista de problemas.

Fig.15: Ejemplo de diagnóstico NO encontrado en tesauro pero encontrado en SNOMED.

**-SITUACION 3: No encuentro coincidencia en el Tesauro ni Snomed**

El sistema da la posibilidad de ingresar un diagnostico tal cual fue escrito, si no se encuentran coincidencias, en el tesauro ni en Snomed.

Para ingresar un nuevo problema, 1) asegurarse de que el termino está correctamente escrito en el campo de búsqueda, 2) realizar la clasificación al ¨nuevo¨ problema que desea agregar y 3) hacer clic en “agregar”. Al momento de agregarlo se verá un cartel donde se advierte: “EL PROBLEMA SE AGREGARÁ A LA LISTA DE PROBLEMAS DEL PACIENTE, PERO EL TERMINO SERA AUDITADO”. Agregar

Fig.16: Ejemplo de diagnóstico NO encontrado en tesauro ni en SNOMED y agregado manualmente.

Una vez que haga clic en agregar, el nuevo problema será agregado a la lista de problemas y enviado a un módulo de auditoria con el nombre del usuario que ingreso el problema para realizar un análisis en profundidad y hacer el mapeo terminológico correspondiente.

PARA FACILITAR LA COMPRENSIÓN DEL MANEJO VAMOS A USAR CASOS CLÍNICOS.

**Caso clínico 1:**

Paciente de 72 años con antecedentes de HTA diagnosticada en el año 2008, consulta por tos productiva de 3 días de evolución acompañado de fiebre y dolor en puntada de costado izquierdo. Acompañante refiere que el paciente reside en un geriátrico.

Examen físico: MV conservado, rales en base izquierda, y roncus diseminados. FR 22 SatO2 88% aa que mejora con oxigenoterapia

En este caso clínico podemos observar a grandes rasgos varios problemas que podríamos dividir en 2 grandes grupos: Problemas AGUDOS y CRONICOS.

Exámenes complementarios: GB 14.000 con neutrofilia. Rx tórax opacidad basal izquierda.

Glucemia en ayunas de 2,4 g/L

Gases en sangre: pO2 58 mmHg.

Medicación habitual: Enalapril

En base a esta premisa podemos hacer el siguiente análisis de como debieran tratar los problemas encontrados al momento de la carga.

|   | **PROBLEMA AGUDOS**                               | **PROBLEMAS CRÓNICOS**                                       |   |
| - | ------------------------------------------------- | ------------------------------------------------------------ | - |
|   | <p>Neumonía,</p><p>Insuficiencia respiratoria</p> | <p>Diabetes Mellitus tipo 2,</p><p>Hipertensión arterial</p> |   |

#### 4.1.1.2 Carga de Problemas Agudos <a href="_7.1.1.2_carga_de" id="_7.1.1.2_carga_de"></a>

**PROBLEMAS AGUDOS:**

**¿Como deberían cargarse los problemas agudos encontrados en este caso?**

Estamos ante un problema AGUDO (NEUMONIA) el cual además podría considerarse como PRINCIPAL.

En este caso podemos además encontrar otro problema AGUDO, la INSUFICIENCIA RESPIRATORIA, que se podría considerar ASOCIADO al problema principal Neumonía.

Fig.9: Ejemplo de clasificación de un problema agudo.

Una vez que presionamos el botón agregar “este pasa a formar parte de la lista de problemas”

Fig.10: Ejemplo de lista de problemas

_**Es condición indispensable para cargar un problema asociado, haber cargado antes un problema principal**_. Una vez cargado un problema principal podemos cargar uno asociado

Fig.11: Ejemplo del proceso de asociación de un problema

En la captura de pantalla podemos ver como se vería una asociación entre Insuficiencia respiratoria tipo1 ( problema a agregar) y Neumonía (Problema previamente cargado), donde la neumonía es el problema principal y la insuficiencia respiratoria como problema asociado

Fig.12: Ejemplo del proceso de asociación de un problema finalizado

#### 4.1.1.3 Manejo del “Estado del Problema”: <a href="_toc70505239" id="_toc70505239"></a>

En el caso de los problemas agudos, los estados pueden ser:

1. _**ACTIVO**_: los problemas agudos nuevos, siempre serán cargados como activos.

_p.e. Paciente que ingresa con diagnóstico de Neumonía adquirida en la comunidad_

1. _**RESUELTO**_: Una vez que el paciente supera el cuadro clínico agudo el problema deberá marcarse como resuelto y realizar la evolución correspondiente. Ver Fig. 13.

_p.e. Paciente con diagnostico de Neumonía adquirida en la comunidad finaliza tratamiento ATB endovenoso con buena evolución._

1. _**DESESTIMADO**_: En caso de que se haya cargado un diagnostico presuntivo, pero luego de realizar estudios complementarios se descarta el diagnostico, el problema cargado se deberá marcar como desestimado (Ver Fig. 13.) y se agregará el nuevo diagnóstico.

_p.e Paciente con diagnostico presuntivo de Neumonía adquirida en la comunidad, con clínica y evolución atípica, se realiza TAC helicoidal con contrataste endovenoso con diagnóstico de Tromboembolismo pulmonar._

En la siguiente figura podemos ver el gestor de estado que aparece luego de hacer clic sobre el problema (de la lista de problemas).

Fig.13: Herramienta de gestión de problemas

#### 4.1.1.4 Carga de Problemas Crónicos <a href="_7.1.1.3_carga_de" id="_7.1.1.3_carga_de"></a>

**PROBLEMAS CRONICOS:**

**¿Cómo deberían cargarse los problemas crónicos encontrados en este caso?**

**Diagnóstico de NOVO**

En el caso de DIABETES MELLITUS TIPO 2, estamos ante un problema CRONICO, y podríamos además considerarlo ACTIVO ya que este problema requiere intervención activa por parte de los profesionales de la salud. En el caso de HTA el análisis es el mismo.

#### 4.1.1.5 Manejo estado de los problemas crónicos <a href="_toc70505241" id="_toc70505241"></a>

Estado del Problema:

En el caso de los problemas crónicos, los estados pueden ser:

1\. _**ACTIVO**_: problemas que tienen una intervención activa por parte del equipo de salud.

p.e. Paciente con diagnóstico de hipertensión arterial en tratamiento con Enalapril y dieta hipo sódica.

2\. _**PASIVO**_: problemas que no requieran una intervención activa por parte del equipo de salud.

p.e. Paciente con antecedente de alergia a la penicilina: Si bien no requiere tratamiento por parte del profesional, es un problema a tener en cuenta al momento de indicar un tratamiento antibiótico.

#### 4.1.1.6 Carga de Problemas como antecedentes <a href="_7.1.1.4_carga_de" id="_7.1.1.4_carga_de"></a>

**Antecedentes clínicos, tóxicos, alérgicos, etc.**

Cuando el paciente ya tiene diagnósticos de patologías, previo al ingreso a la internación, vamos a realizar un paso más para cargarlo como antecedente. Luego de realizar la clasificación correspondiente del problema vamos a tildar el casillero “Antecedente” y elegir la subcategoría a la cual pertenece dicho problema con el año en el que se realizó el diagnostico.

**Secuencia de pasos para agregar un problema como antecedente**

1. Ingrese la abreviatura, iniciales de la patología o el nombre completo del problema en el campo de búsqueda.
2. Seleccione el resultado que coincida con lo que desea ingresar.
3. Clasifique el problema en agudo o crónico según el tiempo de evolución.
4. Clasifique el problema en principal y asociado.
5. En caso de que se trate de un antecedente, se podrá marcar como antecedente y seleccionar el tipo y año en el cual se registró por primera vez dicho problema.
6. Una vez completadas estas acciones presione el botón agregar.

Una vez que presione el botón agregar “el problema seleccionado, pasa a formar parte de la lista de problemas”.

Fig.8: Ejemplo de clasificación de un problema crónico marcado como antecedente.

#### 4.1.1.7 Carga de Procedimientos como antecedentes <a href="_toc70505243" id="_toc70505243"></a>

**Antecedentes quirúrgicos**

Cuando el paciente tiene antecedentes quirúrgicos, debemos cargarlo como antecedente. Luego de encontrar el procedimiento deseado y marcarlo como procedimiento vamos a tildar el casillero “Antecedente” y elegir la subcategoría quirúrgico. Se debe introducir el año en el que se realizó el procedimiento.

**Secuencia de pasos para agregar un procedimiento como antecedente**

1. Ingrese el nombre del procedimiento quirúrgico en el campo de búsqueda.
2. Seleccione el resultado que coincida con lo que desea ingresar.
3. Marque el termino encontrado como **procedimiento**.
4. Tildar el casillero de antecedentes
5. Dentro de las subcategorías, seleccione “quirúrgico” e ingrese el año en el cual realizo el procedimiento quirúrgico.
6. Una vez completadas estas acciones presione el botón agregar.

Una vez que presione el botón agregar “el problema seleccionado, pasa a formar parte del Histórico de procedimientos”.

En el ejemplo de la imagen se muestra como cargar un antecedente de una colecistectomía Laparoscópica que se realizó en el año 2008.

En la siguiente imagen se muestra cómo quedaría el procedimiento quirúrgico debajo de la lista de problemas del paciente.

### 4.1.2 Iniciando <a href="_toc70505244" id="_toc70505244"></a>

Una vez cargado el problema y/o haberlo seleccionado para evolucionar se habilitará una serie de pestañas para poder realizar la evolución.

En la pestaña primera de las pestañas que aparecen “Iniciar”, se puede ingresar una evolución con el esquema sugeridos. O ingresar un texto libre según la necesidad del profesional en ese momento.

### 4.1.3 Plan/Terapéutica <a href="_toc70505245" id="_toc70505245"></a>

En este apartado se describe el plan diagnóstico y terapéutico a seguir. Se puede además ingresar el plan de cuidados del paciente y las indicaciones farmacológicas.

Ejemplo:

Retomando el caso clínico del paciente con la neumonía, internado en Clínica Médica.

**CUIDADOS GENERALES**

Dieta hiposódica para diabético

Control se signos vitales cada 6 hs

Curva térmica

Control de glucemias c/ 6 hs

**FARMACOS**

Enalapril 10 mg cada 12 hs VO

Ranitidina 1 amp cada 6 hs EV

Hidrocortisona 50 mg cada 6 hs EV

Ampicilina Sulbactam 1,5 grs cada 6 hs EV

**OXIGENOTERAPIA**

Oxigeno húmedo FiO2 0,5 con flujo de 12 lts por min

NBZ 20 gotas de salbutamol + 40 gotas de ipratropio cada 6 hs

HIDRATACION PARENTERAL

HP SF 500 + 30 mEq Cloruro de potasio a 21 gotas por minuto

**INSULINOTERAPIA**

Corregir glucemia según: Esquema 1 Estándar

### 4.1.4 Finalizando Evolución <a href="_toc70505246" id="_toc70505246"></a>

Una vez que evolucionamos al paciente, esta pestañaa nos permitirá ver los escrito y solicitado de manera resumida antes de guardar la evolución. Una vez que el profesional verifica que la evolución haya quedado como desea puede guardar (B) la evolución, la cual no podrá ser modificada posteriormente.

En esta sección tenemos además la posibilidad de marcar una evolución como resumen del paciente al guardar la evolución (C).

### 4.1.5 Guardar como borrador <a href="_7.1.5_guardar_como" id="_7.1.5_guardar_como"></a>

En ocasiones un profesional ve interrumpido su proceso de registro y puede querer guardar un registro parcial. En este caso el profesional podrá guardar el registro como borrador en cualquier momento del proceso (A).

La función está habilitada dentro de la ruta “_**nuevo movimiento”**_ “_**nueva evolución”**_.

Desde el momento en que se agrega un problema o un procedimiento el sistema permite guardar lo trabajado como un borrador. Se recomienda usar esta función habitualmente ya que permitirá recuperar la información del borrador en caso de un corte eléctrico por ejemplo en casos en los que el registro no fue concluido.

### ¿Dónde encuentro mis borradores? <a href="_toc70505248" id="_toc70505248"></a>

Los borradores creados se agruparán en el gestor de pacientes: _**Inicio**_

Una vez que el usuario presiona _**Guardar borrador**_, se crea un archivo temporal con el que se podrá trabajar, y el borrador se actualizará cada vez que se presiona _**Guardar borrador.**_

Como opciones de trabajo con los borradores podemos:

* **Abrir borrador:** Al hacer clic sobre el apellido del paciente (**1**) se abrirá el borrador
* **Cerrar ventana:** Al hacer clic en el botón **2** se carrara la ventana de borradores. Se puede abrir nuevamente la lista de borradores al hacer clic en el botón internados.
* **Eliminar borrador:** Al hacer clic en el botón **3** el borrador es eliminado y no se podrá recuperar. Los borradores son eliminados automáticamente cuando se finaliza la evolución.

_**Nota: Se recomienda crear solo un borrador por paciente. Recordar retomar el borrador y finalizarlo antes de comenzar una nueva evolución.**_

_**Aclaraciones:**_

El borrador tiene carácter de individual, un usuario puede ver solo sus borradores y no tiene acceso al borrador de otros usuarios.

Los borradores no conforman parte de la historia clínica del paciente hasta que sean finalizados.

Los borradores serán guardados como documento definitivo con la fecha en la que son finalizados.

### _**4.2 Epicrisis**_ <a href="_toc70505249" id="_toc70505249"></a>

La creación y consulta de epicrisis podrá realizarse desde este apartado, en cualquier momento de la internación del paciente.

**Iniciar epicrisis**

Para ingresar una nueva epicrisis el profesional debera dirigirse a:

_**-Nuevo movimiento Epicrisis**_





Fig.17: Captura de gestor de responsables de la epicrisis

Al iniciar una epicrisis el profesional deberá ingresar:

_**\*Jefe de Servicio:**_ Este ítem es obligatorio

_**Jefe de Sala:**_ Ítem opcional

_**Supervisor:**_ Ítem opcional

_**Médico tratante:**_ Se tomará automáticamente el nombre del profesional que inicio la epicrisis. En caso de que haya un cambio de médico de cabecera de internación, en la epicrisis quedara como médico tratante el profesional que finalizó la epicrisis.

**Modificar epicrisis**



Fig.18: Captura de cabecera y cuerpo de la epicrisis

En la cabecera vamos a ver la **lista de responsables**. Esta lista puede modificarse luego de iniciada presionando el botón “responsables” (B).

**-Diagnostico de egreso**

En esta parte de la epicrisis el profesional debera seleccionar el diagnostico de egreso de la lista de problemas ya cargados atravez del gestor de problemas.

**-Campo texto libre**

Tiene ademas para completar un cuerpo en texto libre. La extension de este cuerpo dependera de la complejidad del paciente. Si bien en el cuerpo del mismo se observara un texto precargado, el mismo solo se encuentra a modo de guia para el profesional.

**-Guardar**

Una vez iniciada la epicrisis, el profesional podrá modificarla sin inconvenientes y guardar los cambios en un archivo temporal o borrador presionando el botón “guardar” . Esto permitirá elaborar la epicrisis en múltiples sesiones de trabajo.

**Finalizar epicrisis**

Fig.19: Captura de pie de la epicrisis y botón finalizar

Con respecto al punto 7, procedimientos quirúrgicos: Serán cargados automáticamente, ya que la información será importada desde el sistema de quirófano.

Una vez que el profesional considere que la epicrisis está terminada y el paciente esta listo para el alta, puede dar por finalizada la misma luego de completar los puntos 2,8,9 y 10.

**Finalizar epicrisis:** Esta acción crearía un documento sin posibilidad de modificaciones posteriores, que pasaría al historial de epicrisis. Las epicrisis una vez archivadas pueden ser consultadas o impresas .

Fig.20: Captura de epicrisis finalizada y enviada a historial

**Nota 1: **Las fechas de egreso y días de estadía, se verán en la epicrisis finalizada una vez que el alta haya sido dada por el sistema de admisión.

**Nota 2:** El sistema no permitirá Finalizar la epicrisis, si no se han completado los puntos 2,8,9 y 10. Se sugiere completar estos puntos solo cuando se considera que la epicrisis fue finalizada.

**Imprimir epicrisis completa**

Una vez que se da aviso a admisión, el paciente desaparece de la lista de pacientes internados, pero se puede acceder desde el área de pacientes en seguimiento en **¨ver históricos¨**, para imprimir una copia con la epicrisis con los datos completos.

Fig.21: Captura de botón de acceso a “ver históricos”

### _**4.3 Solicitudes**_ <a href="_toc70505250" id="_toc70505250"></a>

Desde apartado se podrán ver el estado de las solicitudes de:

_**Estudios imágenes, Laboratorio, Bioinsumos**_

A continuación se desarrollaran los pasos que se deberían serguir para solicitar una radiografía. Los pasos en el resto de los tipos de solicitudes serán de similares características.

### _**4.3.1 Estudios de imágenes**_ <a href="_toc70505251" id="_toc70505251"></a>

El modulo de solicitudes de estudios al servicio de diagnostico por imagen esta conformado por 2 partes, una en la que el profesional hace la solicitud del estudio en la HCE y otra en la que el técnico de rayos o administrativo consulta las ordenes generadas

Dentro de la pestaña de estudios de imágenes vamos a tener una lista de determinaciones frecuentes por especialidad y la opción de buscar cualquier otra determinación dentro de la lista de prestaciones del área de diagnóstico por imagen del Hospital.

### A.Guía de usuario para el médico <a href="_toc70505252" id="_toc70505252"></a>

1. **Se habilita la función solicitar estudios (Traumatología)**

En el contexto de la Emergencia sanitaria estamos trabajando para dejar el papel. El próximo paso es el que les voy a presentar a continuación y está relacionado con las solicitudes de estudios. Comenzamos con un esquema básico que luego se irá mejorando.

_**Nota: Las solicitudes de estudios que requieren auditoria como RMN o Tomografías (que no sea de urgencia) deberán ser solicitadas con los formularios de alta complejidad habituales.**_

1. **Nueva solicitud de estudio al servicio de “DIAGNOSTICO POR IMAGEN”**

En caso de que el profesional necesite realizar una solicitud de laboratorio deberá primero ingresar a la HCE del paciente y dirigirse al botón “Nuevo Movimiento”. Dentro de las opciones en la línea solicitud, que aparece se deberá elegir la opción “Diag. x imagen”, como se muestra en la siguiente imagen.

_Figura 1: Acceso a Nueva Solicitud_

Luego de hacer clic en el botón _**“Diag. x imagen”**_, que aparece dentro de la línea de solicitudes, aparecerá entonces un formulario donde deberá rellenar un campo de texto con algunos estudios precargados para seleccionar y la opción de editar el pedido en texto libre en caso de ser necesario.

Se deberá llenar el formulario que se muestra en la siguiente figura. En el mismo hay una división que ayudara a un ingreso homogéneo y de fácil visualización.

_Figura 2: Formulario de solicitud de estudio: Radiografía_

1. **Diagnóstico:** El obligatorio seleccionar al menos un diagnóstico (de los cargados en la lista de problemas).
2. **Lista de determinaciones para carga rápida**: Al hacer clic sobre los ítems de esta lista, estos se cargan en el detalle del pedido. Aparte de del grupo de radiografías como puede verse en la figura 2, podrán seleccionar ecografías y tomografías.
3. **Detalle del pedido**: Se puede completar la solicitud desde la lista de carga rápida como se muestra en la figura 3 y/o escribir en texto libre como se muestra en la figura 4.
4. **Tipo de solicitud:** Una vez que el pedido está completo, el médico debe rotular el pedido según la urgencia. Ya sea una_** Rx de Rutina**_ (No urgente) o _**Rx de Guardia**_ (Urgente).

El médico además deberá especificar si el estudio deberá realizarse en el lugar donde este el paciente (**en cama**) o en la sala de rayos.

En la siguiente figura puede verse como se llenó el formulario con texto libre de un paciente. Como verán es obligatorio seleccionar al menos un diagnóstico y especificar si es urgente (Rx Guardia) o de rutina.

_Figura 3: Ejemplo solicitud radiografía_

En caso de que no pueda encontrar el estudio que necesito en la lista de carga rápida, puedo ingresar manualmente nombre del estudio que necesito como se muestra en la siguiente figura, donde Rx de “Columna lumbar perfil”, fue agregada manualmente.

_Figura 4: Editando manualmente el pedido_

Una vez guardada la nueva solicitud la misma podrá visualizarse en el área de consulta Solicitudes de estudios. Como podemos ver en la figura 5.

Importante: LA SOLICITUD INGRESADA GENERARA UN DOCUMENTO QUE DEBERA SER FIRMADO.

1. **Lista de solicitudes de estudios realizadas**

Aquí se podrá consultar el historial de solicitudes que se realizaron durante la internación. Eventualmente se podrá repetir una solicitud previa, haciendo clic en el logo del lápiz.

_Figura 5: Captura de lista de solicitudes estudios_

Aparte del registro de solicitudes que el medico puede consultar una vez guardada una solicitud, el pedido es enviado automáticamente al servicio de rayos.

El técnico del laboratorio procederá a realizar el estudio solicitado según se trate de un pedido de urgencia (Rx guardia) o de rutina (Rx rutina).

Adicionalmente, el técnico podrá anotar observaciones sobre la solicitud, como puede verse en la siguiente figura 6. En este caso el estudio solicitado ya ha sido realizado.

Figura 6: Observación técnico de rayos

**Importante: 1- Solo se podrán pedir radiografías ya sean guardia o rutina (inicialmente). LAS SOLICITUDES DE ECOGRAFIA y TOMOGRAFIAS MOMENTANEAMENTE DEBERAN CONTINUAR REALIZANDOSE EN PAPEL.**

**2-No es necesario imprimir las solicitudes una vez ingresadas al sistema (salvo alguna excepción).**

**3- En la transición el médico deberá llamar vía telefónica al servicio de rayos en el caso de las urgencias que requieran una radiografía en cama o al camillero en caso de que el paciente deba ser trasladado al servicio de rayos.**

**4- El personal de enfermería encargado habitualmente de gestionar los traslados a rayos en las áreas de HDUD, ginecología y traumatología ala, ya ha recibido una charla de capacitación y los usuarios y contraseñas correspondientes para acceder a la lista de solicitudes de estudios.**

### B.Guía para el técnico de rayos <a href="_hlk68794563" id="_hlk68794563"></a>

**04 de Junio de 2020**

1. **Introducción**

En el contexto de la Emergencia sanitaria estamos trabajando para dejar el papel. Ahora podemos decir que todos los servicios de internación están trabajando con el sistema de Historia Clínica Electrónica. El próximo paso es el que les voy a presentar a continuación y está relacionado con las solicitudes de estudios. Comenzamos con un esquema básico que luego se irá mejorando.

1. **Ingreso a plataforma de HCE**

A continuación, se muestra el acceso al módulo de consulta de solicitudes

1. **Módulo de consulta**

A partir del día de la fecha, el sistema de solicitud de estudios pasa del soporte en papel al electrónico para los estudios de radiografías, ecografías y tomografías. Todas las solicitudes se agruparán dentro del módulo de consulta.

Para poder ingresar al módulo de consulta de solicitudes, el técnico deberá previamente solicitar nombre de usuario y contraseña de acceso en el área de informática del hospital.

A continuación, se muestra brevemente como vera el técnico, las solicitudes de estudios al servicio de diagnostico por imagen.

En este caso vemos una captura del módulo de consulta de solicitudes de laboratorio donde se pueden distinguir 3 áreas de interacción.

1. Se puede seleccionar una fecha. Si bien se carga la fecha actual por defecto, se puede seleccionar otra fecha para la consulta.
2. Esta es un área de donde se puede utilizar diferentes filtros de búsqueda, para organizar la lista de solicitudes.

_**B-1**_ Filtro Urgencia: Si/No. Mediante este filtro el técnico podrá diferenciar los pedidos de guardia (Urgente Si), de los pedidos de rutina (Urgente No).

_**B-2 a B-5 **_Filtros para búsqueda pedido: según diferentes datos de identificación. _Apellido, Nombre, DNI, Numero de Historia Clínica._

_**B-6**_ Filtro Profesional: ingresar nombre del solicitante de la práctica.

_**B-7**_ Área de atención: Internación, Guardia, Consultorio.

_**B-8**_ Adicionalmente el técnico tendrá la posibilidad de realizar un comentario sobre una solicitud determinada. _**El médico podrá ver el comentario en la HCE**_, sobre la copia de la solicitud realizada.

_**Técnico de rayos: **deberá colocar en este campo REALIZADO o NO REALIZADO. En caso de que el estudio no se haya realizado deberá colocar el motivo por el cual no se pudo llevar a cabo la solicitud._

1. Se muestra la lista de todas las solicitudes de la fecha seleccionada por defecto.

Puede usarse cualquiera de los filtros disponibles para encontrar una orden o grupo de órdenes.

Una vez que el técnico encuentra la solicitud de interés, podrá visualizar dicha orden al hacer clic en el siguiente logo.

La solicitud podrá imprimirse y se visualizará como se muestra a continuación

Es importante destacar que si bien cambiamos la vía por la cual se moverán las solicitudes de estudios, los demás canales de comunicación deberán continuar usándose como se hace habitualmente.

**Importante: 1- En la transición el médico deberá igualmente llamar vía telefónica si el estudio es urgente.**

**2- Todos los técnicos de rayos ya tienen nombre de usuario y contraseña que les ha sido enviada a su mail.**

### _**4.3.1 Solicitud de Hemoderivados**_ <a href="_toc70505254" id="_toc70505254"></a>

### A.Guía de usuario para el Médico Prescriptor <a href="_toc70505255" id="_toc70505255"></a>

En caso de que el profesional necesite realizar una solicitud de hemocomponentes (glóbulos, plasma, plaquetas, crioprecipitado) o hemoderivados (factores, albúmina, fibrinógeno) deberá primero ingresar a la HCE del paciente y dirigirse al botón _**“Nuevo Movimiento”**_. Dentro de las opciones en la línea solicitud, que aparece se deberá elegir la opción _**“Hemoterapia”**_, como se muestra en la siguiente imagen.

_Figura 1: Acceso a Nueva Solicitud_

Luego de hacer clic en el botón “Hemoterapia”, que aparece dentro de la línea de solicitudes, aparecerá entonces un formulario donde deberá rellenar un campo de texto con algunos estudios precargados para seleccionar y la opción de editar el pedido en texto libre en caso de ser necesario.

Se deberá llenar el formulario que se muestra en la siguiente figura. En el mismo hay una división que ayudara a un ingreso homogéneo y de fácil visualización.

_Figura 2: Formulario de solicitud de hemocomponentes o hemoderivados: Hemoterapia_

1. **Diagnóstico:** El obligatorio seleccionar al menos un diagnóstico (de los cargados en la lista de problemas).
2. **Lista de determinaciones para carga rápida**: Al hacer clic sobre los ítems de esta lista, estos se cargan en el detalle del pedido. Aparte de del grupo de “_**Glóbulos rojos**_” como puede verse en la figura 2, podrán seleccionar _**plaquetas,**_ _**plasma**_ y _**otros**_.

Siempre se debe especificar la cantidad del hemocomponente seleccionado.

1. **Justificación: **El profesional deberá seleccionar uno de los motivos listados o agregar uno manualmente.

**B **y** C **conforman el** Detalle del pedido**: Se puede completar la solicitud desde la lista de carga rápida como se muestra en la figura 2 y/o escribir en texto libre en el detalle del pedido.

1. **Tipo de solicitud:** Una vez que el pedido está completo, el médico debe rotular el pedido según la urgencia. Ya sea una_** solicitud no urgente**_ o _**Urgente**_.

El médico además deberá especificar si el estudio deberá realizarse en el lugar donde este el paciente (**en cama**) o en la sala de internación.

_**Ejemplo solicitud Glóbulos rojos**_

En la figura 2 puede verse como se solicita 2 unidades de Glóbulos rojos

Luego de ingresar al formulario de solicitud de Hemoterapia

1. Seleccionar un diagnóstico (que debe estar previamente cargado)
2. Dentro del grupo de GLÓBULOS ROJOS (que aparece por defecto)

\>>Seleccionar “Glóbulos Rojos desplasmatizados” (para este caso)

\>>>Agregar manualmente la cantidad de unidades que necesito, “2” en este caso.

\>>Seleccionar luego el motivo por el cual estoy solicitando las 2 unidades de GR. En este caso debido a “anemia sintomática…”

1. Finalmente seleccionar el grado de urgencia

\>>Selecciono Urgente “si” (en este caso).

\>>>Debo además indicar el grado de urgencia. En este caso necesito que la transfusión se lleve a cabo “dentro de las próximas 3 horas”.

1. Una vez completa toda esta información se debe “Guardar” la solicitud. Esta solicitud es enviada automáticamente a Hemoterapia una vez guardada.

**Importante:**

**1- LA SOLICITUD INGRESADA GENERARA UN DOCUMENTO QUE DEBERA SER FIRMADO.**

**2- No es necesario imprimir las solicitudes una vez ingresadas al sistema.**

**3- El médico deberá llamar vía telefónica al Servicio de Hemoterapia en el caso de las urgencias.**

B.Guia de consulta para el técnico de hemoterapia

Por las similitudes, se sugiere ver: **Guía para el técnico de rayos**

_**Bio-insumos:**_

Dentro de la pestaña de estudios de laboratorio vamos a tener una lista de insumos más usados por especialidad (que requieran receta médica) y la opción de buscar cualquier otro insumo no habitual dentro de la lista de insumos de farmacia del Hospital.

### _**4.4 Indicaciones y recetas**_ <a href="_toc70505256" id="_toc70505256"></a>

1. **Se habilita la pestaña Indicaciones**

En el contexto de la Emergencia sanitaria estamos trabajando para dejar el papel. Ahora podemos decir que todos los servicios de internación están trabajando con el sistema de Historia Clínica Electrónica. El próximo paso es el que les voy a presentar a continuación y está relacionado con las indicaciones y recetas. Comenzamos con un esquema básico que luego se ira mejorando.

1. **Nueva indicación**

En caso de que se trate de un paciente que ingresa al hospital: luego realizar la Historia Clínica de Ingreso se procederá a cargar las indicaciones mediante el acceso que se muestra en la siguiente figura:

Figura 1: Acceso a Nueva Indicación

El acceso desde _**“Nuevo movimiento”**_ a _**“Indicaciones/Recetas”,**_ se utilizará para ingresar las indicaciones nuevas de pacientes con o sin indicaciones previas. Luego de hacer clic en el botón indicaciones/ recetas, aparecerá un formulario en blanco donde deberá rellenar campos donde se podrá ingresar las indicaciones en texto libre.

Se deberá llenar el formulario que se muestra en la siguiente figura. En el mismo hay una división que ayudara a un ingreso homogéneo y de fácil visualización.

Figura 2: Formulario de indicaciones

En la siguiente figura puede verse como se llenó el formulario con las indicaciones en texto libre de un paciente con diagnóstico de neumonía. Como verán es obligatorio seleccionar al menos un diagnostico.

Una vez completas las indicaciones el usuario deberá hacer clic en guardar.

Figura 3: Ejemplo indicaciones de paciente con Neumonía

Una vez guardada la nueva indicación la misma podrá visualizarse en el área de consulta Indicaciones/Recetas. Como podemos ver en la figura 4.

Importante: LA INDICACION INGRESADA GENERARA UN DOCUMENTO QUE DEBERA SER FIRMADO PARA QUE FARMACIA PUEDA DISPENSAR LOS FARMACOS REQUERIDOS.

1. **Lista de Indicaciones**

Aquí se podrá consultar la lista de indicaciones diarias del paciente

Figura 4: Captura de lista de indicaciones

Se puede ver además en la figura anterior, un acceso para “Modificar” y actualizar una indicación. Las indicaciones deberán actualizarse diariamente. Luego de hacer los cambios necesarios en las indicaciones solo se deberá presionar en “Guardar” y las indicaciones se guardarán con la fecha actualizada.

A partir de estas indicaciones, se generarán recetas automáticamente para farmacia.

En farmacia se usará la receta generada y firmada por el médico con firma digital, para la dispensación de medicamentos.

Adicionalmente desde farmacia el farmacéutico podrá anotar observaciones o realizar sugerencias como puede verse en la siguiente figura 5 sobre la lista de indicaciones.

Figura 5: Sugerencia de farmacéutico

1. **Nueva receta**

En caso de que el profesional necesite indicar un nuevo fármaco deberá generar una nueva receta. Por ejemplo se indica una carga de Fenitoina en un paciente con convulsiones.

Figura 1: Acceso a Nueva Indicación

Figura 6: Indicación de carga de finitima y dosis de mantenimiento

Nota: _**En el caso de que se realice un cambio en las indicaciones que implique por ejemplo la administración inmediata de un nuevo esquema antibiótico, el profesional que actualiza las indicaciones deberá encargarse de informar a la enfermería de los cambios para que el nuevo antibiótico sea retirado de farmacia y administrado al paciente según indicación.**_

1. **Renovación de indicaciones**

Para la renovación diaria de las indicaciones el médico deberá tener en cuenta todas las indicaciones generadas durante la jornada previa para la actualización de las indicaciones.

Figura 7: se puede ver una indicación actualizada con cambios en el esquema antibiótico y con la fecha actualizada.

**Importante: 1- Les recuerdo que el médico debe dejar una copia impresa de las indicaciones en la carpeta de indicaciones de la enfermería.**

**2- Las recetas generadas serán enviadas automáticamente a farmacia.**

### _**4.5 Interconsulta**_ <a href="_toc70505257" id="_toc70505257"></a>

En este apartado se puede enviar solicitudes de evaluación a las diferentes especialidades disponibles en el nosocomio.

**Ejemplo:**

Retomando el caso clínico del paciente con la neumonía.

Supongamos que el cuadro clínico de ingreso empeora con shock séptico e insuficiencia respiratoria que no responde a oxigenoterapia. En este contexto el profesional necesita realizar una interconsulta con la Unidad de Cuidados Críticos.

**Pasos para solicitar una interconsulta**

**- Nuevo movimiento Interconsulta**



Fig.22: Captura de acceso a “solicitud de interconsultas”

1. **Confección de la interconsulta**

En la ventana de nueva interconsulta el profesional debera completar una serie de datos para que la interconsulta pueda ser enviada.



Fig.23: Captura de formulario de interconsulta

**-Servicio al cual se le solicita la interconsulta:**

_**Obligatorio:**_ Toda interconsulta enviada debe ser dirigida a un servicio, del cual necesito la evaluación. _**Excepcionalmente**_ la interconsulta podrá ser dirigida al profesional.

**-Profesional al cuál se dirige la interconsulta**

_**Optativo: **_La designación de un profesional NO es obligatoria, excepto en las urgencias donde generalmente se habla previamente con algún profesional.

**-Seleccione el diagnostico principal por el que se realiza la Interconsulta**

_**Obligatorio: **_Se deberá seleccionar alguno de los diagnósticos previamente cargados desde el desplegable.

**-La urgencia de la interconsulta**

_**Obligatorio: **_Se deberá además marcar si la interconsulta es urgente o no. Las interconsultas urgentes deberán tener respuesta a la mayor brevedad posible.

**-Breve descripción**

_**Obligatorio: **_Aquí el profesional deberá introducir una breve descripción del motivo por el cual envía la interconsulta.

**-Guardar**

Una vez guardada la interconsulta será enviada automáticamente al servicio correspondiente.

1. **Impresión de la Interconsulta**

Una vez confeccionada, la interconsulta deberá ser impresa.

Fig.24: Captura de lista de interconsultas enviadas y acceso directo de impresión

Para esta vamos al área de interconsultas del paciente (izquierda) y buscamos la interconsulta que deseamos imprimir y presionamos el logo de la impresora que se ve a la derecha de la interconsulta.

Podemos consultar el estado de todas las interconsultas enviadas en el siguiente enlace: Estado Interconsultas

1. **Entrega de interconsulta impresa a secretaria**

Una vez finalizada la impresión, la interconsulta será entregada a la secretaria (en caso de no ser urgente) para que sea enviada a los servicios correspondientes.

Este paso es necesario para la transición de papel al sistema electrónico. Se les avisara cuando ya no sea necesaria la impresión de las interconsultas.

### _**4.6 Fichas**_ <a href="_7.5_fichas" id="_7.5_fichas"></a>

Acceso directo a diferentes fichas según especialidad, en caso de que el profesional solo desee llenar alguna de estas, sin evolucionar.

### 4.6.1 Protocolo Quirúrgico <a href="_toc70505259" id="_toc70505259"></a>

Las especialidades quirúrgicas deberán confeccionar el protocolo quirúrgico en el sistema.

A continuación, los pasos a seguir para llevar a cabo la tarea, aplicado a un caso hipotético:

**Caso Clínico:**

Paciente de sexo femenino 30 años que consulta por dolor en FID de 36 hs de evolución.

Al examen físico abdomen con defensa y signo de Blumberg +.

Ecografía con hallazgos inespecíficos, Laboratorio con GB 15.000.

Se procede a la realización de la exploración quirúrgica y se encuentra un apéndice con características compatibles con apendicitis aguda gangrenosa por lo que se procede a la apendicetomía.

Previo a ingresar a la ficha de protocolo quirúrgico deberán cargar:

* 1 Diagnostico preoperatorio
* 2 Diagnostico/s posoperatorio/s
* 3 Procedimiento/s realizados/s

_**1 Diagnostico preoperatorio**_

Fig.1: _**Diagnostico preoperatorio**_

En paciente es ingresado a internación con el Problema **“dolor en FID”**, clasificado como problema agudo y por ahora principal.

Fig.2: Una vez agregado, el problema aparecerá en la lista de problemas agudos.

_**2 Diagnostico/s posoperatorio**_

Se procede a la realización de la exploración quirúrgica.



Fig.3: En la cirugía se llega al diagnóstico de **apendicitis aguda gangrenosa (**Diagnostico posoperatorio). En este caso la apendicitis pasa a ser el Problema Principal y el dolor en FID un problema asociado.

_**3 Carga de Procedimiento realizado**_



1. Buscar y seleccionar el procedimiento
2. Clasificar el elemento a agregar como procedimiento y hacer clic en agregar.



Fig.5: Una vez que el procedimiento fue agregado a la lista de procedimientos actuales ingresamos a la ficha de protocolo quirúrgico.

AHORA A COMPLETAR EL PROTOCOLO QUIRÚRGICO:

1-Cirujano y Ayudante/s 1,2,3

2-Procedimiento/s 1,2,3

3-Consentimiento informado

4-Diagnostico Preoperatorio

5-Diagnostico/s postoperatorio/s 1,2,3,4

6-Tipo Urgente/programado

7-Opercion/ hallazgos

8-Destino



Fig.6: En la ficha de protocolo quirúrgico deberán ser completados de manera obligatoria los campos marcados del 1 al 8.



Fig.7: Una vez completado los campos del 1 al 6, aparecerá arriba el botón de finalizar para guardar definitivamente el Protocolo Quirúrgico.

Alternativamente en caso de no estar seguro de querer cerrar el protocolo siempre se puede guardar como borrador hasta finalizar los cambios y estar seguro de querer guardarlo.



Fig.8: En el Historial de Evoluciones se podrá visualizar el protocolo quirúrgico finalizado y se podrá imprimir en el área de imprimir.

### 4.6.2 Maniobra invasiva <a href="_toc70505260" id="_toc70505260"></a>

El procedimiento a seguir para llenar una ficha de maniobra invasiva es muy similar al llevado a cabo para completar un protocolo quirúrgico. Se usará en casos en los que se realicen procedimientos a un paciente que no requiera la intervención de un anestesista.

Ejemplo:

Supongamos que a un paciente con diagnóstico de neumonía intra hospitalaria y shock séptico se le coloca una vía venosa central subclavia derecha. A continuación, vamos a ver una serie de capturas de pantalla para ilustrar como debería registrarse dicho procedimiento.



En el buscador de problemas se debe introducir el nombre del procedimiento que se desea agregar y se lo clasifica como procedimiento. Una vez clasificado se puede presionar el botón agregar.

Una vez llevada a cabo esta acción, podremos ver este nuevo ítem en la lista de procedimientos actuales como se muestra en la figura a continuación.



Una vez que el procedimiento buscado fue agregado exitosamente ya estamos en condiciones de llenar la ficha de maniobras invasivas.

Luego de hacer clic en el botón “Maniobra Invasiva”, aparece la ficha que se muestra a continuación.



### 4.6.3 Procedimiento diagnostico <a href="_toc70505261" id="_toc70505261"></a>

Los especialistas deberán completar las fichas para cargar los informes de los diferentes procedimientos diagnósticos que se realizan en el hospital: VEDA, colonoscopia, fibrobroncoscopia, cinecoronariografia, etc.

A continuación, los pasos a seguir para llevar a cabo la tarea, aplicado a un caso hipotético:

**CASO:**

Se le realiza una VEDA a un paciente de sexo femenino 30 años que consulta hematemesis.

Durante el procedimiento se realizan hallazgos compatibles con varices esofágicas sangrantes, por lo que se realiza banding.

Previo a ingresar a la ficha de protocolo quirúrgico deberán cargar:

* 1 Diagnostico pre procedimiento
* 2 Diagnostico/s pos procedimiento/s
* 3 Procedimiento/s realizados/s

_**1 Diagnostico pre procedimiento**_

* Hematemesis

_**2 Diagnostico/s pos procedimiento**_

* Varices esofágicas sangrantes

_**3 Carga de Procedimiento realizado**_

* VEDA
* colocación de banda en várices gástricas

En este caso encuentro un código para incluir a ambos procedimientos

* Fibroesogafogastroscopia y colocación de bandas en várices esofágicas.

AHORA A COMPLETAR LA FICHA DE PROCEDIMIENTO DIAGNOSTICO:

1- Profesional y Ayudante/s 1,2,3

2-Procedimiento/s 1,2,3

3-Consentimiento informado

4-Diagnostico Pre procedimiento

5-Diagnostico/s pos procedimiento/s 1,2,3

6-Tipo Urgente/programado

7-Descripcion de hallazgos

8-Destino



Fig.6: En la ficha de procedimiento diagnostico deberán ser completados de manera obligatoria los campos marcados del 1 al 8.

Alternativamente en caso de no estar seguro de querer cerrar la ficha, siempre se puede guardar como borrador hasta finalizar los cambios y estar seguro de querer guardarlo.

Fig.7: En el apartado Informes/Estudios se podrá visualizar el protocolo quirúrgico finalizado y se podrá imprimir en el área de imprimir.



Todos los estudios realizados en la institución deberían mostrarse en este apartado con el fin de poder visualizar las prestaciones que se le realizaron al paciente.

**Nota:** Los informes de los estudios podrán ser visualizados en este apartado una vez que hayan sido firmados por el profesional que realizado el estudio.

### _**4.7 Anexar archivos a HCE**_ <a href="_4.7_anexar_archivos" id="_4.7_anexar_archivos"></a>

Acceso a función de carga de archivos que nos permitiría adjuntar archivos externos digitalizados a la Historia Clínica Electrónica.

En ocasiones nos vamos a encontrar con que el paciente tiene un informe de un estudio muy importante en papel. El sistema nos da la posibilidad de agregar dicho documento a la HCE del paciente luego de digitalizarlo.

Para llevar a cabo el proceso, el documento deberá estar previamente digitalizado y guardado en formato PDF. Una vez que tengo el _**documento en formato pdf**_, se debe ingresar a la HCE del paciente en cuestión y dentro de “Nuevo movimiento” seleccione la opción “Cargar Estudios/informes”

En la siguiente ventana deberá seleccionar el tipo de documento que se pretende subir, el nombre del profesional que firmó el informe en caso de tratarse de un estudio de anatomía patológica p.e. Por ultimo seleccionar el _**documento en formato pdf**_ a agregar a la HCE y presionar el botón “Cargar”.

Nota: Si el “Tipo de archivo” que desea subir, no se encuentra en la lista desplegable comunicarse con informática.

### **5. Imprimir** <a href="_toc70505263" id="_toc70505263"></a>

En este apartado el profesional debería poder mandar a imprimir los diferentes movimientos de la HCE:

* _**Evoluciones**_
* _**Epicrisis**_
* _**Protocolo quirúrgico**_

**Proceso de selección de documentos a imprimir**

Para seleccionar un documento se debe hacer clic con el botón derecho del mouse sobre el movimiento requerido. Para sacar de la selección un documento seleccionado por error, simplemente hacer clic nuevamente sobre el movimiento que se quiere sacar de la selección.

_**En la siguiente se puede ver que se han seleccionado las evoluciones de 3 días consecutivos, con un total de 7 movimientos seleccionados para imprimir.**_



_**En el futuro se podrán imprimir, además:**_

* _**Indicaciones médicas**_
* _**Recetas correspondientes a indicaciones farmacológicas actualizadas**_
* _**Solicitud de estudios**_
* _**Consentimiento informado**_
* _**Informe de estudios**_

**Nota:**

Este módulo será muy útil durante la transición entre la Historia Clínica en papel que se usa actualmente en nuestra institución y la Historia Clínica Electrónica, hasta la adopción de la firma digital y adaptación de nuestro sistema de información hospitalaria a dicha herramienta de autenticación que nos permita prescindir totalmente del papel.

### **6. Firma Digital** <a href="_toc70505264" id="_toc70505264"></a>

Nuestra plataforma de HCE permite firmar los documentos generados con una firma digital provista por la plataforma de firma digital remota de la Nación.

**Plataforma de Firma Digital Remota PFDR**

Una solución tecnológica segura y confiable que permite firmar digitalmente documentos electrónicos sin token.

### 6.1 Características <a href="_toc70505265" id="_toc70505265"></a>

_**Seguridad:**_ garantizada por la criptografía asimétrica que asegura la autenticidad de la firma. Contamos con el respaldo de instalaciones seguras y confiables para el almacenamiento de datos biométricos, con roles definidos para cada proceso y persona.

_**Validez jurídica:**_ tener tu firma digital te permite firmar documentos electrónicos digitalmente con la misma validez jurídica que una firma de puño y letra. La firma se encuentra bajo control del firmante en todo momento.

_**Múltiples usos:**_ podés realizar trámites con entidades públicas y privadas, tales como relaciones impositivas, notificaciones judiciales, operaciones bancarias, contratos a distancia y documentos de comercio exterior. El firmador te permite firmar digitalmente cualquier archivo en formato PDF.

_**Autenticidad e integridad del documento:**_ podrás identificar al autor fácilmente y verificar si ese documento fue alterado. Por lo cual se asegura la autoría e integridad del mismo.

**Beneficios**

| <ul><li>Eficiencia y rapidez</li><li>Reducción de costos</li><li>Acceso desde cualquier dispositivo electrónico</li></ul> | <ul><li>Comercio electrónico</li><li>Seguridad jurídica</li><li>Fácil verificación</li></ul> |
| ------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |

### _**6.2 Pasos a seguir para firmar un documento**_ <a href="_toc70505266" id="_toc70505266"></a>

En la pantalla de bienvenida del usuario, se va a mostrar un totalizador con la cantidad de documentos a firmar dicho usuario. Se podrá además ver un acceso a los documentos a firmar.

_**1. Ingresar a ¨Documentos¨**_

Deberá seleccionar el documento a firmar, el cual se carga en la ventana de pre visualización a la derecha. El usuario verifica en esta ventana que realmente se trata del documento que desea firmar. Una vez que esta seguro hace clic en firmar.

Nota: El sistema traerá automáticamente el CUIL del usuario cargado previamente en el sistema de personal.

2\. _**Clic en firmar**_

Una vez que haces clic en firmar el sistema nos lleva a la plataforma de firma digital remota de nación. Aparecerá una pantalla de bienvenida solicitando la contraseña de usuario de firma digital (la contraseña fue establecida por el usuario en la oficina de firma digital).

Nota: Como ayuda la contraseña establecida debía tener al menos ocho caracteres, una mayúscula y un número.

2\. _**Ingresar OTP**_

El sistema pide ingresar el código OTP el cual es provisto por el Smarphone mediante la app _**Authenticator**_ (generalmente).

4\. _**Ingresar PIN**_

Finalmente, el sistema solicitara ingresar el PIN. El cual también fue establecido por el usuario al momento del alta en la oficina de firma digital.

Una vez que el PIN es ingresado correctamente el sistema mostrara un mensaje de ¨Documento Firmado¨.

Deberá cerrar esta ventana y continuar con el resto de la lista de documentos a firmar.

_**5. Firmar nuevo documento**_

Para firmar un nuevo documento el paciente deberá volver a la lista de documentos a firmar. Una vez que todos los documentos fueron firmados, la lista de pendientes queda vacía, como se muestra a continuación.

Los documentos generados deberán ser firmados diariamente. En caso de no haber podido firmar por problemas técnicos el mismo día, los documentos deberán ser firmados el día siguiente.

_**6.Firma conjunta de documentos**_

Actualmente todos los registros que se ingresan en la nueva plataforma de Historia Clínica Electrónica deben ser firmados por el profesional interviniente.

Con el fin de agilizar el flujo de trabajo de los profesionales se decide unificar algunos registros para su firma conjunta. Sin embargo hay algunos documentos que no podrán unificarse y deberán ser firmados de manera independiente.

**Lista de documentos que podrán unificarse bajo la misma fecha:**

\-Evoluciones

\-Indicaciones

\-Ficha de triage

\-Ficha de control postCovid

\-Ficha de antecedentes

\-ficha de examen físico por sistemas

\-Ficha de signos vitales

\-Solicitud de estudios de radiografía, ecografía, tomografía

\-Solicitudes de laboratorio

\-Solicitudes de Hemoterapia

**Lista de documentos que deberán firmarse de manera individual:**

\-Epicrisis

\-Protocolos quirúrgicos

\-Ficha de procedimientos diagnósticos

\-Solicitud de internación

\-Recetas

Esta lista será actualizada según el sistema baja absorbiendo otras áreas asistenciales.

### **8. Interacción con admisión y egresos** <a href="_toc70505267" id="_toc70505267"></a>

Los médicos podrán hacer diferentes solicitudes al área de Admisión del Hospital desde la Historia Clínica Electrónica. Entre las solicitudes que puede hacer están las de _**Internación, Alta, Pase**_. A continuación, veremos un ejemplo de una solicitud de internación de un paciente desde la guardia general.

### 8.1 Medico solicita internación en la plataforma EVA <a href="_toc70505268" id="_toc70505268"></a>

**A-Seleccione el paciente que va a internar: **Perez, Graciela en este caso

B-Una vez que ingresa a la Historia Clínica del paciente diríjase a **Nuevo mov.Admisión**

C- Deberá **llenar el siguiente formulario** que será enviado a admisión una vez guardado.

En el caso de una internación como este caso, deberá _**completar de manera obligatoria de los pasos 1 al 5 **_y opcional el 6. Como observación en este caso en el punto 6 se puede aclarar si el paciente requiere algún tipo de aislamiento o cama para obeso mórbido p.e.

Una vez guardada la solicitud, la misma será recibida por admisión y le dará curso a la misma asignándole cama al paciente.

El profesional podrá consultar la lista completa de solicitudes realizadas a admisión en el siguiente apartado.

Luego de seleccionar el botón solicitudes, van a poder ver todas las solicitudes” de más recientes (arriba) a más antiguas (abajo). Adicionalmente podrá buscar por rango de fechas (1) por el nombre del paciente o del profesional que solicita la internación.

En la lista de solicitudes van a poder ver en las ultimas 2 columnas el estado de la solicitud (A) ya se que esta se encuentre resuelta o pendiente de resolución. En caso de que haya disponibilidad de cama se podrá ver en la ultima columna (B), la cama asignada.

Como puede apreciarse en la lista de solicitudes realizadas hay una (C) en la que un administrativo de admisión comentó sobre la solicitud: “esposa del paciente romero (NO Vidente)”. La idea es que admisión deje actualizaciones del estado de las solicitudes vía comentario, cada vez que hay una novedad como por ejemplo: “Sin disponibilidad de cama por el momento en Clínica Médica No COVID”.

Una vez que la solicitud es resuelta ya sea porque se le consigue cama en el Hospital o el paciente es trasladado el encargado de admisión cambia el estado de “pendiente” a “asignada”.

### 8.2 Otras solicitudes a Admisión <a href="_toc70505269" id="_toc70505269"></a>

Como había mencionado previamente se podrán además realizar otros 2 tipos de solicitudes a Admisión una vez que el paciente se encuentra internado

_**Pases de servicio o cambio de cama**_

_**Informe de Altas**_. Las altas también podrán ser informadas por este medio

D-Al completar el formulario se generará un documento que deberá ser firmado con la firma digital por el medico solicitante.

E- Admisión recibe la solicitud y la ejecuta.

F-Avisara por el medio que corresponda, que la solicitud ya fue llevada a cabo o en caso de no poder concluirla, deberá informar los inconvenientes o avances.

### 8.3 Guía de uso de admisión <a href="_toc70505270" id="_toc70505270"></a>

Una vez que un usuario de admisión con los permisos adecuados accede al sistema de gestión Hospitalaria, dentro de la solapa de internación va a encontrar el acceso a la lista de solicitudes, como se muestra en la siguiente figura:

Por defecto el sistema mostrara todas las solicitudes realizadas, que inicialmente llegarán de la guardia y serán solicitudes de internación. Se podrán aplicar diferentes filtros de búsqueda y se podrá realizar además una búsqueda utilizando diferentes criterios de búsqueda: Nombre y apellido del paciente, DNI, nombre del profesional solicitante, etc.

**Tratamiento de una solicitud**

Una vez que llega una nueva solicitud el encargado de admisión deberá darle el tratamiento correspondiente con el fin de resolver la solicitud.

_**Ejemplo**_

Suponiendo que se recibe una solicitud de internación en una cama de clínica médica y hay una cama disponible, al hacer clic el administrativo sobre la solicitud, aparecerán los datos prellenados para asignarle la cama al paciente.

Una vez asignada la cama deberá marcarse la solicitud como resuelta en la lista de solicitudes.

Nota: No será necesaria la intervención del administrativo de guardia general para internar un paciente.

_**Acerca de las herramientas de tratamiento de una solicitud**_

Con el fin de ver y comunicar el estado de tratamiento de esa solicitud es que el administrativo contara con diferentes herramientas.

1. Visualizar: Podrá ver la solicitud de internación en cuestión
2. Resolver: Podrá marcar como resuelta una solicitud
3. Comentar: Podrá hacer un comentario acerca del estado de tratamiento de la solicitud.

Actualmente la solicitud muestra 2 estados de tratamiento: Pendiente y Resuelto.

**Pendiente:** Es el estado en el cual aparecen por defecto las solicitudes.

**Resuelto:** En el caso de la solicitud de Internación, se deberá dar por resuelta cuando se le haya asignado una cama o el paciente haya sido trasladado a su centro prestador (en caso de tener obra social).

No se considera resuelta una solicitud si el paciente está internado en la guardia, ya que se deben continuar realizando gestiones para conseguir una cama en un área de internación ya sea en este hospital u otro.

1. **Importancia de los comentarios**

Con el fin brindar información al medico que solicita la internación es importante el uso de esta herramienta.

Se podrá realizar comentarios sobre cualquier solicitud y no hay límite para la cantidad de comentarios. La idea es desactivar en la brevedad el chat de WhatsApp, por lo cual es importante reflejar cualquier novedad con respecto a una solicitud (mientras siga pendiente), por este medio ya que los comentarios podrán ser visualizados tanto por médicos como enfermeros al igual que la cama asignada.

En caso de que el médico desee comunicarse con admisión, deberá llamar al interno destinado para dicho fin.

### **9. Preguntas frecuentes** <a href="_toc70505271" id="_toc70505271"></a>

### Tengo problemas de visualización de la Historia Clínica Electrónica <a href="_toc70505272" id="_toc70505272"></a>

Usar únicamente el navegador Chrome para trabajar con la HCE. El uso de un navegador diferente, puede traer problemas de visualización e impresión.

### ¿Dónde puedo encontrar la Historia Clínica de un paciente que di de alta? <a href="_toc70505273" id="_toc70505273"></a>

Si el profesional tuvo intervención en la atención del paciente fue evolucionado al menos una vez. Podra encontrar un acceso a la HCE del paciente en la siguiente ruta: Internados En Seguimiento ”Ver Históricos”

Luego de hacer clic en “Ver Históricos”

Se mostrará una lista con todos los pacientes atendidos en el área de internación.

### ¿Puedo acceder a las interconsultas de un servicio diferente al predeterminado? <a href="_toc70505274" id="_toc70505274"></a>

Si. Supongamos que hay un médico inmunólogo que tiene un cargo en el servicio de “Guardia general” y tiene una prestación en el servicio de “Inmunología”.

Este médico tendrá como predeterminado el servicio de “Guardia general”.

Sin embargo este profesional podrá acceder a las interconsultas de inmunología escribiendo en el casillero donde figura el nombre del servicio al que quiera acceder en este caso Inmuno.

### El servicio que me figura como predeterminado, no es en que estoy actualmente <a href="_toc70505275" id="_toc70505275"></a>

En el caso de que el servicio que figura como predeterminado no coincida con el servicio al cual el profesional pertenece. Podrá solicitar la actualización en el área de personal.

### ¿Puede más de un especialista realizar seguimiento a un paciente? <a href="_toc70505276" id="_toc70505276"></a>

Si. Solo debe asignarse la interconsulta desde el buzón general.

### No se cargó el problema que necesito a la lista de problemas <a href="_toc70505277" id="_toc70505277"></a>

Si el problema fue adecuadamente seleccionado, clasificado y al hacer clic en agregar no es agregado a la lista de problemas a pesar de presionar 2 veces agregar. _**No**_ continuar intentando. Se debe hacer clic en “cancelar y volver” e intentar cargar el problema nuevamente.

En caso de persistir el problema comunicarse con informática.

Para evitar aparición de errores en la lista de problemas se debe evitar cargar de una lista muy extensa de problemas en un único movimiento.

### ¿Puedo eliminar un problema luego de haberlo agregado? <a href="_toc70505278" id="_toc70505278"></a>

Si. Pero solo si no se ha realizado una evolución luego de agregar el problema.

Ejemplo: Acabas de agregar el Problema “Hipertensión Arterial” a tu lista de problemas, pero por error lo ingresaste como un Problema AGUDO, cuando se trata de un problema CRONICO. En este caso aún no has evolucionado, así que podés hacer clic con el botón izq del mouse sobre el problema que acabas de agregar y en el menú emergente seleccionar ELIMINAR.

### No figura la fecha de alta y días de internación en la epicrisis <a href="_toc70505279" id="_toc70505279"></a>

Estos datos son grabados en la epicrisis una vez la epicrisis es finalizada y que el paciente es dado de alta en el área de admisión del Hospital.

### ¿Mis borradores pueden ser vistos por otro usuario? <a href="_toc70505280" id="_toc70505280"></a>

No. Los borrados son de uso personal. Persisten hasta que son finalizados y consolidados o eliminados.

Ver más acerca de los borradores: Trabajando con borradores

### ¿Con que fecha se guardan los borradores? <a href="_toc70505281" id="_toc70505281"></a>

Los borrados se consolidan en la base de datos con la fecha y hora del momento en que es finalizado. La fecha de creación del borrador no tiene relevancia.

### Mensaje: OTP incorrecto <a href="_toc70505282" id="_toc70505282"></a>

La mayoría de las veces este error se debe a la falta de coincidencia entre la hora de la PC y la del Smartphone.

Probar ajustando la hora del Smartphone.

En caso de persistir el problema, acercarse a la oficina de firma digital.

### ¿Con que frecuencia debo firmar los documentos de la HCE? <a href="_toc70505283" id="_toc70505283"></a>

Los documentos generados deberán ser firmados diariamente. En caso de no haber podido firmar por problemas técnicos el mismo día, los documentos deberán ser firmados el día siguiente.

### No puedo ver el informe de un estudio ya realizado <a href="_toc70505284" id="_toc70505284"></a>

Los informes de los estudios podrán ser visualizados en este apartado una vez que hayan sido firmados por el profesional que realizado el estudio. Por más que el estudio haya sido cargado al sistema no se mostrara hasta que haya sido firmado.

**Esta guía será actualizando según se vayan incorporando funcionalidades en el sistema. Actualizada por última vez en abril de 2021**

**Ariel Carvajal**
