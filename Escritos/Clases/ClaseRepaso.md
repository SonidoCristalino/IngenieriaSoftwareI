
# Clase repaso 13/05:
	https://drive.google.com/file/d/1E_y6z5DmkO9ojXda_zpvQxBeUJMWoh_w/view

# Nota:
	Se puede encontrar el audio de la clase en la Bibibliografía

# La forma en que se evalúa:
	- Escrito: 33 preguntas multiplechoice. Es para pensar cómo aplicar. No hay grandes secretos, no es difícil según el
	  profesor.
	- Oral: se explica cómo se encaró el TP
	- DNI.
	- Cámara abierta.

# Bibliografía:
	Está todo en el campus histórico.

# Concepto de Ingeniería de Software:

Concepto de ingeniería de software: Recordar que no es una ciencia pero toma conocimiento del saber científico, pero no es una
ciencia.

	- Ingeniería de Software (tiene varias definiciones) : Disciplina de la ingeniería que tienen que ver con todos los
	  aspectos de la producción de Software. Es todo lo relacionado con la entrega, operación y el mantenimiento de un
	  software útil.  La evolución del software pasó desde los comienzos de programar con Assembler, el florecimiento de otros
	  lenguajes de software, lo que llevó a que grandes cantidades de líneas de código imposibles de mantener, nacimiento de
	  metodologías de diseño, a entornos de programación y programación automática.

# Fases de la Ingeniería de Software:
	* Primera Fase. Los albores (1945-1955): Programar no es una tarea diferenciada del diseño de una máquina. Uso de lenguaje
	  máquina y ensamblador.

	* Segunda Fase. El florecimiento (1955-1965): Aparecen multitud de lenguajes. Se pensaba que era posible hacer casi todo.

	* Tercera Fase. La crisis (1965-1970): Desarrollo inacabable de grandes programas. Ineficiencia, errores, coste
	  impredecible Nada es posible.

	* Cuarta Fase. Innovación conceptual (1970-1980): Fundamentos de programación. Verificación de programas. Metodologías de
	   diseño.

	* Quinta Fase. El diseño es el problema (1980-?)

# Documentación:

# Concepto de Requerimiento:
	* Descripción de los servicios proporcionado por el sistema y las restricciones operativas.
	* Los requerimientos reflejan las necesidades del cliente.
	* El proceso de descubrir analizar documentar y verificar los servicios y restricciones se denomina ingeniería de
	  requerimientos.

# Requerimientos funcionales:
Los requisitos funcionales son aquellos requisitos que se ocupan de lo que el sistema debe hacer o proporcionar a los usuarios.

Dentro de los Requerimientos Funcionales tenemos:
	* Requerimientos del usuario:  son descriptos en forma abstracta. Declaraciones en lenguaje natural y diagramas de los
	  servicios de las funciones y restricciones del sistema.

	* Requerimientos del sistema: definen en forma detallada de las funciones, servicios y restricciones operativas del
	  sistema.

# Requerimientos NO funcionales:
Los requisitos no funcionales son aquellos que elaboran la característica de rendimiento del sistema y definen las restricciones
sobre cómo lo hará el sistema.

	* Son restricciones de los servicios o funciones ofrecidos por el sistema, estos incluyen las restricciones en el tiempo
	  sobre el proceso de desarrollo estándares.
	* NO hacen referencia a las funciones.
	* Se enfoca en las propiedades; por ejemplo: La fiabilidad, tiempos, almacenamiento, etc.
	* Son más críticos que los Requerimientos Funcionales.
	* No siempre se refieren al sistema de software a desarrollar, alguno pueden hacer referencia al proceso que se utiliza en
	  el desarrollo del software
	* La indicación que el software debe ser desarrollado con una herramienta CASE particular es una especificación no
	  funcional.

	* Surgen de: necesidades del usuario, restricciones económicas, políticas

## Requerimientos de Dominio:
Los requermientos de dominio hacen referencia a una dirección IP.

Por ejemplo:
	- El Sistema debera tener el dominio .net (casa.net).
	- El Sistema debera tener el dominio .edu (casa.edu.ar).

## Ejemplo:
Si se está desarrollando un sistema de biblioteca para la universidad, entonces los Requerimientos Funcionales se pueden enumerar
como:
	- Instalación de membresía
	- Emisión de libros nuevos
	- Devolución de libros
	- Datos de los miembros
	- Estado de los libros visitantes
	- Reserva previa de libros

Los Requerimientos No Funcionales se pueden enumerar como:
	- Disponibilidad del servicio de rendimiento
	- Seguridad del sistema y
	- Confiabilidad del sistema

Y los Requerimientos de Dominio serían:
	- La página de la biblioteca debería de tener el dominio .edu.ar
	- Debería estar dentro del dominio de la UNAJ.

# SRS-830 / ESRE:
El estándar IEEE 830-1998 para el SRS(en inglés) o ERS (Especificación de Requerimientos de Software) es un conjunto de
recomendaciones para la especificación de los Requerimiento o Requisitos de Software el cual tiene como producto final la
documentación de los acuerdos entre el cliente y el grupo de desarrollo para cumplir con la totalidad de las exigencias
estipuladas.

# Cómo documentar según lo especificado en SRS / Estructura:
Estos documentos tienen una estructura en forma de reporte bastante definida, poseen carátula, historial de cambios, introducción,
definiciones, acrónimos y abreviaturas, especificación de requerimientos funcionales, especificación de requerimientos no
funcionales y casos de uso.

	- Nombre del proyecto.
	- Cliente.
	- Introducción: Describir para qué y porqué se aborda el proyecto, historia detrás y los problemas.
	- Glosarios de términos: términos técnicos, definiciones.
	- Definición de Requerimientos: necesidades de la problemática a solucionar, dar prioridades, funciones, características y
	  restricciones.
	- Definición de Requerimientos Funcionales: interacción entre el sistema y su ambiente; el ambiente donde se embebe el
	  nuevo sistema; definir los servicios que se proporcionan.
	- Definición de Requerimientos NO Funcionales: Definir las limitantes del sistema y el proceso de desarrollo.
	- Requerimientos del Sistema (Factibilidad técnica): descripción del hardware, especificaciones del software, APIs que
	  deben incluirse, Requerimientos de bases de datos.

# Los que leen las especificaciones del Requerimiento:
	- Clientes y Usuarios: lo hacen para validad que el sistema funcione acorde a lo estipulado en la documentación.
	- Analistas: Interesados en leer la documentación como complemento para otros sistemas.
	- Desarrolladores: Deben de ser lo que implementen los requerimientos.
	- Testers: Los que determinan la satisfacción (si cumple o no cumple con el alcance propuesto) de los requerimientos.
	- Managment (personal administrativo y de gerencia): Para medir y controlar el proceso de desarrollo.
	- Otros: Equipo de operaciones (los que administran los recursos materiales donde se irá a implementar); Equipo de soporte
	  (para desarrollar la capacitacion, generan manuales de usuario y procedimientos online); equipo de legales.


# Casos de Uso:

Un casos de uso es una secuencia de transacciones que son desarrolladas por un sistema en respuesta a un evento que inicia un
actor sobre el propio sistema. Los diagramas de casos de uso sirven para especificar la funcionalidad y el comportamiento de un
sistema mediante su interacción con los usuarios y/o otros sistemas. O lo que es igual , un diagrama que muestra la relación entre
los actores y los casos de uso en un sistema. Una relación es una conexión entre los elementos del modelo, por ejemplo la relación
y la generalización son relaciones.

Los diagramas de casos de uso se utilizan para ilustrar los requerimientos del sistema al mostrar como reacciona una respuesta a
eventos que se producen en el mismo. En este tipo de diagrama intervienen algunos conceptos nuevos: un actor es una entidad
externa al sistema que se modela y que puede interactuar con él; un ejemplo de actor podría ser un usuario o cualquier otro
sistema.

Las relaciones entre casos de uso y actores pueden ser las siguientes:

	- Un actor se comunica con un caso de uso.
	- Un caso de uso extiende otro caso de uso.
	- Un caso de uso usa otro caso de uso.

Partes de un caso de Uso:
	- Actor
	- Globo que señala al Caso de uso:
	- Un cuadrado que señala el límite del sistema.
Conectores:
	- Asociación de comunicación.
	- Extensión ("extends")
	- Inclusión ("include")
	- Generalización

Para visualizar las partes del Caso de Uso se puede ver:
	https://es.wikipedia.org/wiki/Caso_de_uso


# Tipos de relaciones:
- Comunica (<<communicates>>): Relación (asociación) entre un actor y un caso de uso que denota la participación del actor en
  dicho caso de uso.

- Usa (<<uses>>) (o <<include>> en la nueva versión de UML): Relación de dependencia entre dos casos de uso que denota la
  inclusión del comportamiento de un escenario en otro.

- Generalización (sin estereotipo) (En UML 1.3) Indica que un caso de uso es una variante de otro. El caso de uso especializado
  puede variar cualquier aspecto del caso de uso base.

- Extiende (<<extend>>, <<extiende>>)(En UML 1.3): Es un estereotipo de dependencia. Ofrece una forma de extensión más controlada
  que la relación de generalización. El caso de uso base declara un conjunto de puntos de extensión. El caso de uso especializado
  solo puede alterar el comportamiento de los puntos de extensión marcados.

Para la comprensión del Extiende y del Uses, se puede ver el diagrama que se encuentra en:
	https://ejemplos.net/5-ejemplos-de-caso-de-uso/

# Scrum:
Es una metodología ágil que se comienza a utilizar de forma muy primitiva a partir 1986 en empresas de Japón o USA. Los equipos
de trabajo eran multidisciplinares siguiendo patrones de ejecución permitiendo de esta forma aminorar tiempos.

## Artefactos:
	- Product Backlog: Es un documento de alto nivel para todo el proyecto; el cual contiene descripciones genéricas de todos
	  los requerimientos y funcionalidades deseables; es abierto y cualquiera puede modificarlo.
	- Sprint Backlog: Es el documento donde se establecen las horas de cada tarea (proveniente de los Requerimientos
	  Funcionales) que el equipo se compromete a cumplir los durante el desarrollo del Sprint, el cual suele durar de 2 a 4
	  semanas.
	- BurnDown Chart: Scrum: El progreso de un proyecto Scrum puede ser medido por un release burndown chart, sus
	  características más resaltantes son:
		- El ScrumMaster debe actualizar este gráfico al finalizar cada sprint.
		- El eje horizontal del burndown chart muestra los sprints.
		- El eje vertical muestra la cantidad de trabajo pendiente por realizar al inicio de cada sprint
		- En este gráfico se realiza el seguimiento diario de cómo se van desarrollando los Requerimientos Funcionales
		  para el desarrollo del proyecto.

## Roles:
	- Product Owner: Define Funcionalidades, Diseña el Producto, Representa al cliente; Prioriza las funcionalidades; acepta o
	  rechaza los resultados del equipo.

## Equipo:
	- De 5 a 9 integrantes.
	- Auto-organizado
	- Tareas multifuncionales
	- Sólo puede haber cambios cuando finaliza el Sprint.
	- Miembros disponibles full time.

## Scrum Master:
	Durante la iteración el Facilitador (Scrum Master) se encarga de que el equipo pueda cumplir con su compromiso y de que no
	se merme su productividad:
		- Elimina los obstáculos que el equipo no puede resolver por sí mismo.
		- Protege al equipo de interrupciones externas que puedan afectar su compromiso o su productividad.
		- Representa la Gestión del Proyecto
		- Resuelve impedimentos.
		- Asegura un equipo funcional y productivo.
		- Responsable de promover los valores y prácticas de Scrum.
		- Se asegura de que el equipo es completamente funcional y productivo.
		- Permite la estrecha cooperación en todos los roles y funciones.

# Reuniones:
	- Sprint Planning: Reunión para planificar el trabajo que se incluirá en el siguiente Spring. Se realiza cada 15 o 30
	  días, y tiene una duración de 8hs aprox. Interviene Product Owner junto con el Equipo, donde queda establecido el Sprint
	  Backlog. Los Requerimientos extraen del Product Backlog. Se determina el tiempo que llevará realizar cada una de las
	  tareas.
	- Sprint Review: Es el período donde se lleva a cabo el trabajo. La duración se va definiendo según la experiencia que va
	  ganando el equipo (se comienza con 2 o 4 semanas y luego se va ajustando). Al final de cada Sprint el equipo debe
	  presentar los avances, donde se entregará un producto con características utilizables por el cliente. NO es recomendable
	  cambiar los objetivos del Sprint Backlog, a menos que el éxito del proyecto se vea en peligro.
	- Sprint Retrospective: se realiza finalizado cada Sprint y participa todo el equipo, Scrum Master debe dirigirla y
	  también está presente el Product Owner.
	  	* Qué ha salido bien en el Sprint.
		* Qué cosas hay que mejorar en el Siguiente Sprint.
	  	* Qué problemas han surgido en el último sprint.
		* Qué sugerencias se pueden realizar para el sigueinte Sprint.

	- Daily Scrum Meeting: duración máxima de 15 minutos sin importar el tamaño del equipo , participa todo el equipo de pie
	  para evitar pérdida y se deben responder a las preguntas ¿qué has hecho ayer? ¿Qué se tiene planeado hacer hoy? ¿se tuvo
	  algún problema que haya impedido alcanzar el objetivo? Se reprende la llegada tarde. Pueden haber roles de cerdos y
	  gallinas siendo los primeros el Equipo, product Owner y Scrum Master y los últimos el Usuario, Gerente, PM.
	- Scrum de Scrum (SoS): Un scrum de scrums consiste en un equipo virtual compuesto por delegados con enlaces integrados en
	  los equipos de entrega de origen. La finalidad es coordinar equipos independientes más pequeños. Los equipos que
	  aplican la técnica scrum de scrums no solo coordinan la entrega, sino que también garantizan un producto completamente
	  integrado al final de cada sprint. Por lo tanto, un scrum de scrums actúa como un equipo de publicación que ofrece valor
	  a los clientes.
	  Esto se utiliza en equipos grandes para poder reducir la cantidad de dependencias entre los miembros del equipo, se
	  elijen distinas personas (elegidos por su experiencia) de distintas áreas del Equipo para generar un equipo menor y
	  poder ser manejado de forma más fácil.

# Características de Extreme Programming:
	- Desarrollo iterativo e incremental: pequeñas mejoras, unas tras otras.
	- Pruebas unitarias continuas, frecuentemente repetidas y automatizadas, incluyendo pruebas de regresión. Se aconseja
	  escribir el código de la prueba antes de la codificación. Véase, por ejemplo: las herramientas de prueba JUnit orientada
	  a Java.
	- Programación en parejas: se recomienda que las tareas de desarrollo se lleven a cabo por dos personas en un mismo
	  puesto. La mayor calidad del código escrito de esta manera -el código es revisado y discutido mientras se escribe- es
	  más importante que la posible pérdida de productividad inmediata.
	- Frecuente integración del equipo de programación con el cliente o usuario. Se recomienda que un representante del
	  cliente trabaje junto al equipo de desarrollo (Sería como el Product Owner en Scrum).
	- Corrección de todos los errores antes de añadir nueva funcionalidad. Hacer entregas frecuentes.
	- Refactorización del código, es decir, reescribir ciertas partes del código para aumentar su legibilidad y mantenibilidad
	  pero sin modificar su comportamiento. Las pruebas han de garantizar que en la refactorización no se ha introducido
	  ningún fallo.
	- Propiedad del código compartida: en vez de dividir la responsabilidad en el desarrollo de cada módulo en grupos de
	  trabajo distintos, este método promueve el que todo el personal pueda corregir y extender cualquier parte del proyecto.
	  Las frecuentes pruebas de regresión garantizan que los posibles errores serán detectados.
	- Simplicidad en el código: es la mejor manera de que las cosas funcionen. Cuando todo funcione se podrá añadir
	  funcionalidad si es necesario. La programación extrema apuesta que es más sencillo hacer algo simple y tener un poco de
	  trabajo extra para cambiarlo si se requiere, que realizar algo complicado y quizás nunca utilizarlo.

# Ciclo de Vida del Software:

Estos programas se originan en el hecho de que es muy costoso rectificar los errores que se detectan tarde dentro de la fase de
implementación. El ciclo de vida permite que los errores se detecten lo antes posible y, por lo tanto, permite a los
desarrolladores concentrarse en la calidad del software, en los plazos de implementación y en los costos asociados.

El ciclo de vida básico de un software consta de los siguientes procedimientos:

	- Definición de objetivos: define la finalidad del proyecto y su papel en la estrategia global.
	- Análisis de los requisitos y su viabilidad: recopila, examina y formula los requisitos del cliente y examina cualquier
	  restricción que se pueda aplicar.
	- Diseño general: requisitos generales de la arquitectura de la aplicación.
	- Diseño en detalle: definición precisa de cada subconjunto de la aplicación.
	- Programación (programación e implementación): implementación de un lenguaje de programación para crear las funciones
	  definidas durante la etapa de diseño.
	- Prueba de unidad: prueba individual de cada subconjunto de la aplicación para garantizar que se implementaron de acuerdo
	  con las especificaciones.
	- Integración: garantiza que los diferentes módulos se integren con la aplicación. Este es el propósito de la prueba de
	  integración que está cuidadosamente documentada.
	- Prueba beta (o validación): garantiza que el software cumple con las especificaciones originales.
	- Documentación: sirve para documentar información necesaria para los usuarios del software y para desarrollos futuros.
	- Implementación
	- Mantenimiento: comprende todos los procedimientos correctivos (mantenimiento correctivo) y las actualizaciones
	  secundarias del software (mantenimiento continuo)

# Tipos de Modelo En cascada:
El modelo de cascada define las siguientes etapas que deben cumplirse de forma sucesiva:

	1. Especificación de requisitos
	2. Diseño del software
	3. Construcción o Implementación del software
	4. Integración
	5. Pruebas (o validación)
	6. Despliegue (o instalación)
	7. Mantenimiento

Siguiendo el modelo de cascada de forma estricta, sólo cuando se finaliza una fase, comienza la otra. En ocasiones se realiza una
revisión antes de iniciar la siguiente fase, lo que permite la posibilidad de cambios (lo que puede incluir un proceso de control
formal de cambio). Las revisiones también se utilizan para asegurar que la fase anterior ha sido totalmente finalizada; los
criterios para completar una fase se conocen frecuentemente con el término inglés "gate" (puerta). Este modelo desaconseja
revisitar y revisar fases que ya se han completado. Esta falta de flexibilidad en un modelo de cascada puro ha sido fuente de
crítica de los defensores de modelos más flexibles.

# Modelo de Tipo Espiral:

La principal característica del modelo en espiral es la gestión de riesgos de forma periódica en el ciclo de desarrollo. Este
modelo fue creado en 1988 por Barry Boehm, combinando algunos aspectos clave de las metodologías del modelo de cascada y del
desarrollo rápido de aplicaciones, pero dando énfasis en un área que para muchos no jugó el papel que requiere en otros modelos:
un análisis iterativo y concienzudo de los riesgos, especialmente en el caso de sistema complejos de gran escala.

La espiral se visualiza como un proceso que pasa a través de algunas interacciones con el diagrama de los cuatro cuadrantes
representativos de las siguientes actividades:

	1. Crear planes con el propósito de identificar los objetivos del software, seleccionados para implementar el programa y
	   clarificar las restricciones en el desarrollo del software;
	2. Análisis de riesgos: una evaluación analítica de programas seleccionados, para evaluar como identificar y eliminar el
	   riesgo;
	3. La implementación del proyecto: implementación del desarrollo del software y su pertinente verificación;

Modelo de espiral con énfasis en los riesgos, haciendo hincapié en las condiciones de las opciones y limitaciones para facilitar
la reutilización de software, la calidad del software puede ayudar como una meta propia en la integración en el desarrollo del
producto. Sin embargo, el modelo en espiral tiene algunas limitaciones, entre las que destacan:

	1. El énfasis se sitúa en el análisis de riesgo, y por lo tanto requiere de clientes que acepten este análisis y actúen en
	   consecuencia. Para ello es necesaria confianza en los desarrolladores así como la predisposición a gastar más para
	   solventar los temas, por lo cual este modelo se utiliza frecuentemente en desarrollo interno de software a gran escala.
	2. Si la implementación del riesgo de análisis afectará de forma esencial los beneficios del proyecto, no debería
	   utilizarse este modelo.
	3. Los desarrolladores de software han de buscar de forma explícita riesgos y analizarlos de forma exhaustiva para que
	   este modelo funcione.

La primera fase es la búsqueda de un plan para conseguir los objetivos con las limitaciones del proyecto para así buscar y
eliminar todos los riesgos potenciales por medio de un cuidadoso análisis, y si fuera necesario incluyendo la fabricación de un
prototipo. Si es imposible descartar algunos riesgos, el cliente ha de decidir si es conveniente terminar el proyecto o seguir
adelante ignorando los riesgos. Por último, se evalúan los resultados y se inicia el diseño de la siguiente fase.


# Tipo de Modelo Incremental (iterativo y Creciente):
La idea principal detrás de mejoramiento iterativo es desarrollar un sistema de programas de manera incremental, permitiéndole al
desarrollador sacar ventaja de lo que se ha aprendido a lo largo del desarrollo anterior, incrementando, versiones entregables del
sistema. El aprendizaje viene de dos vertientes: el desarrollo del sistema, y su uso (mientras sea posible). Los pasos claves en
el proceso son comenzar con una implementación simple de los requerimientos del sistema, e iterativamente mejorar la secuencia
evolutiva de versiones hasta que el sistema completo esté implementado. En cada iteración, se realizan cambios en el diseño y se
agregan nuevas funcionalidades y capacidades al sistema.

Básicamente este modelo se basa en dos premisas:

	1. Los usuarios nunca saben bien qué es lo que necesitan para satisfacer sus necesidades.
	2. En el desarrollo, los procesos tienden a cambiar.

El proceso en sí mismo consiste de:

	1. Etapa de inicialización
	2. Etapa de iteración
	3. Lista de control de proyecto

# Ventajas del desarrollo incremental:

	- En este modelo los usuarios no tienen que esperar hasta que el sistema completo se entregue para hacer uso de él. El
	  primer incremento cumple los requerimientos más importantes de tal forma que pueden utilizar el software al instante.
	- Los usuarios pueden utilizar los incrementos iniciales como prototipos y obtener experiencia sobre los requerimientos de
	  los incrementos posteriores del sistema.
	- Existe muy pocas probabilidades de riesgo en el sistema. Aunque se pueden encontrar problemas en algunos incrementos, lo
	  normal es que el sistema se entregue sin inconvenientes al usuario.
	- Ya que los sistemas de más alta prioridad se entregan primero, y los incrementos posteriores se integran entre ellos, es
	  muy probable que los sistemas más importantes sean a los que se les hagan más pruebas. Esto quiere decir que es menos
	  probable que los usuarios encuentren fallas de funcionamiento del software en las partes más importantes del sistema.

# PDSA (Mejora Continua):
A grandes rasgos, en el ciclo PDCA de mejora continua, esta planificación consiste en determinar qué se quiere alcanzar y definir
los métodos y formas de acción que se aplicarán para obtener los resultados deseados. Es lo que se denomina «Enfoque».

Al mismo tiempo, el enfoque debe estar relacionado con la estategia de la organización y estar fundamentado; con procesos bien
definidos

El ciclo PDCA es llamado así debido al nombre en inglés de cada una de sus etapas:

	P: del verbo “Plan”, o planear.
	D: del verbo “Do”, hacer o llevar a cabo.
	C: del verbo “Check” comprobar, analizar o verificar.
	A: del verbo “Actuar”, para corregir los errores o fallos.

La metodología PDCA es ampliamente utilizada por las corporaciones que desean mejorar su nivel de gestión a través del control
eficiente de procesos y actividades internas y externas, por medio de la estandarización de la información y reduciendo al mínimo
las posibilidades de errores en la toma de decisiones importantes.

Es importante destacar que, una vez implementado, el ciclo PDCA debe convertirse en una constante en la empresa, un verdadero
círculo virtuoso siempre con el objetivo de mejora continua

# Las cuatro etapas o enfoques:
	- Planificación: Un proyecto bien diseñado es de suma importancia para el ciclo PDCA pues evita fallas futuras y genera un
	  enorme ahorro de tiempo. Realice la planificación de acuerdo con la misión, la visión y los valores de la empresa,
	  estableciendo metas y objetivos y definiendo la mejor manera para lograrlos.
		- Establecer los objetivos de mejora.
		- Detallar las especificaciones de los resultados esperados.
		- Identificar los puntos de medición.

	- Ejecución: Después de hacer una planificación cuidadosa, póngala en práctica literalmente, es decir, intente no saltar
	  etapas ni improvisar, para no comprometer todo el ciclo PDCA. La fase de ejecución se divide en otras tres etapas:
	  formación de todos los empleados y directivos involucrados en el proyecto, seguido por la realización propiamente dicha
	  y la “recolección” de datos para su posterior evaluación.
		- Aplicar soluciones.
		- Documentar las acciones realizadas.

	- Comprobación: Es la etapa del ciclo PDCA en que se identifican las posibles brechas en el proyecto. Los objetivos
	  alcanzados y los resultados obtenidos se miden a través de los datos recogidos y del mapeo de procesos al final de la
	  ejecución. La comprobación se puede, y se debe hacer de dos maneras: de forma paralela a la ejecución, con el fin de
	  asegurarse de que el trabajo se está haciendo bien, y al final de esta, para un análisis estadístico más amplio que
	  permita las adaptaciones y las medidas necesarias.

		- Vigilar los cambios que se hayan realizado.
		- Obtener retroalimentación.

	- Acción: La “última” etapa, en la que se aplican las medidas correctivas para perfeccionar el proyecto siempre y
	  continuamente. Es a la vez el final y el principio, porque después de una exhaustiva investigación sobre la causa de los
	  errores del pasado, todo el ciclo PDCA se vuelve a realizar con nuevas directrices y parámetros.

		- Realizar los ajuste necesarios.
		- Aplicar nuevas mejoras.
		- Documenta

# Análisis de Riesgo:
Es la estimación del grado de exposición a que una amenaza se materialice sobre uno o varios activos de información causando daños
o perjuicios a la organización. El riesgo nos indica qué sucedería si no se protegen adecuadamente los activos. El análisis de
riesgos se define como la utilización sistemática de la información disponible, para determinar los peligros y estimar los
riesgos.

Este análisis permite averiguar cuáles son los peligros a los que se enfrenta la organización y la importancia de cada uno de
ellos. Con esta información podemos hacer una toma de decisiones bien fundamentada acerca de qué medidas de seguridad deberían
implementarse.

Para realizar el análisis de riesgos, se debe partir del inventario de activos. Si este último no es extenso, se puede decidir
hacer el análisis sobre todos los activos de información involucrados. Si por el contrario es muy extenso, es más recomendable
agrupar los Activos de Información, decidiendo esto sobre los que tienen más valor, o los que son más estratégicos.

# Tipos de Enfoques:
Independientemente de la Metodología que se utilice para realizar el análisis de riesgos, se puede abordar el mismo con varios
enfoques dependiendo del grado de profundidad con que se quiera realizar el análisis. Dichos enfoques puede ser:

	- Enfoque de Mínimos: se escoge un conjunto mínimo de activos de información y se hace un análisis conjunto, de manera que
	  se emplean una cantidad mínima de recursos, consumiendo menos tiempo y con un costo menor. Este enfoque tiene la
	  desventaja de que puede ser difícil actualizar los controles o añadir otros según vayan dándose cambios significativos

	- Enfoque Informal: aquí no se necesita una formación especial ni tantos recursos de tiempo ni personal. Las desventajas
	  son que al no estar basado en métodos estructurados, puede suceder que se pasen por alto riesgos o amenazas importantes
	  y al depender de las personas que los realizan, el análisis puede resultar con cierto nivel de subjetividad. Si no se
	  argumenta bien la selección de controles, puede ser difícil después justificar el gasto de implantación.

	- Enfoque Detallado: con este enfoque se consigue una idea muy exacta y objetiva de los riesgos a los que se enfrenta la
	  organización. Se puede decidir un nivel de seguridad apropiado para cada activo de información y de esa forma escoger
	  los controles con precisión. Es el enfoque que más recursos necesita en tiempo, personal y dinero para llevarlo a cabo.

	- Enfoque Combinado: con un enfoque de alto nivel al principio, permite determinar cuáles son los activos de información
	  en los que habrá que invertir más antes de utilizar muchos recursos en el análisis. De esta manera ahorra recursos al
	  tratar antes y de manera exhaustiva los riesgos más importantes mientras que al resto de los riesgos sólo se les aplica
	  un nivel básico de seguridad, con lo que se consigue un nivel razonable de seguridad con recursos ajustados. Es el
	  enfoque más eficaz en cuanto a costos y adaptabilidad a empresas chicas, Pymes, ONG.

Con todo esto, podemos identificar las amenazas, las vulnerabilidades que dichas amenazas podrían explotar y el impacto en caso de
que se materialicen. Esto nos permite identificar los riesgos y cuáles deben ser tratados primero o con más detalle. Se debe
escoger cual es el nivel de riesgos que la organización está dispuesta a tolerar. De esta manera, debajo de ese nivel el riesgo
será aceptable, pero por el contrario si el mismo está por encima de dicho nivel, se deberá tomar alguna decisión al respecto.
Sobre los riesgos no aceptables, hay 4 tipos de decisión que podemos tomar:
	- Transferirlo: el riesgo se traspasa a otra organización, por ejemplo una Compañía de Seguros.
	- Eliminarlo: está decisión no suele ser viable, ya que eliminar el riesgo significa eliminar el activo de información que
	  lo genera.
	- Mitigarlo: reducir el riesgo, normalmente aplicando controles de seguridad.
	- Aceptarlo: aceptar que no se puede hacer nada y por lo tanto, se acepta ese riesgo, pero la organización sabe que existe

# Casos de Prueba:
Los casos de prueba son especificaciones de las entradas para la prueba y la salida esperada del sistema más una afirmación de lo
que se está probando. Los datos de prueba son las entradas que han sido ideadas para probar el sistema; los datos de prueba a
veces pueden generarse automáticamente.

## Pruebas Unitarias:
En programación, una prueba unitaria es una forma de comprobar el correcto funcionamiento de una unidad de código. Por ejemplo en
diseño estructurado o en diseño funcional una función o un procedimiento, en diseño orientado a objetos una clase. Esto sirve para
asegurar que cada unidad funcione correctamente y eficientemente por separado. Además de verificar que el código hace lo que tiene
que hacer, verificamos que sea correcto el nombre, los nombres y tipos de los parámetros, el tipo de lo que se devuelve, que si el
estado inicial es válido, entonces el estado final es válido también.

## Pruebas de Integración:
Pruebas integrales o pruebas de integración son aquellas que se realizan en el ámbito del desarrollo de software una vez que se
han aprobado las pruebas unitarias y lo que prueban es que todos los elementos unitarios que componen el software, funcionan
juntos correctamente probándolos en grupo. Se centra principalmente en probar la comunicación entre los componentes y sus
comunicaciones ya sea hardware o software.

## Automatización de Pruebas:
En las pruebas de software, la automatización de pruebas consiste en el uso de software especial (casi siempre separado del
software que se prueba) para controlar la ejecución de pruebas y la comparación entre los resultados obtenidos y los resultados
esperados. La automatización de pruebas permite incluir pruebas repetitivas y necesarias dentro de un proceso formal de pruebas ya
existente o bien adicionar pruebas cuya ejecución manual resultaría difícil.

## Pruebas de Aceptación:
Dichas pruebas manuales primero son hechas por usuarios internos en entornos intermedios: ambientes típicos de producción donde se
verifica que se desempeña del modo necesitado. Luego viene el acceso beta a los clientes que así lo soliciten repitiendo de nuevo
el ciclo pero en esta oportunidad en entornos realistas y muchas veces muy diferentes entre sí en cuanto a otros softwares
agregados.

Las pruebas de aceptación van mucho más allá de cuando finalmente se libera el software al público en general. Se presta atención
en recabar los detalles y comentarios por medio de encuestas o envíos de datos estadísticos no sin antes presentar un cuadro de
diálogo al usuario primerizo o con una versión nueva.

Recordar que cuando los clientes se implican en las pruebas de entregas, éstas a menudo se denominan pruebas de aceptación. Si la
entrega es lo suficientemente buena, el cliente puede entonces aceptarla para su uso.

