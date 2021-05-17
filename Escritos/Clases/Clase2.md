# Clase nº 2

Concepto de Requerimientos:
	- Descripción de los servicios proporcionado por el sistema y las restricciones operativas.
	- Los requerimientos reflejan las necesidades del cliente.

# Tipos de Requerimientos:
	- Funcionales: Definen lo que debe hacer el sistema puntualmente ante determinadas entradas y en algunas ocasiones lo que
	  no debe hacer.
	  	* De usuario: Hechos con lenguaje natural, diagramas de servicios de las funciones y restricciones del sistema
		* Del sistema: detallan funciones, servicios y restricciones operativas del sistema.
	- No funcionales: e refieren a todos los requisitos que no describen información a guardar, ni funciones a realizar, sino
	  características de funcionamiento, por eso suelen denominarse Atributos de calidad de un sistema. Queda entonces el
	  requisito no funcional, que son las restricciones o condiciones que impone el cliente al programa que necesita, por
	  ejemplo el tiempo de entrega del programa, el lenguaje o la cantidad de usuarios.
	  Estos requerimientos son más críticos que los funcionales.
	- De Dominio: Los requermientos de dominio hacen referencia a una dirección IP.
		* Por ejemplo: El Sistema debera tener el dominio .net (casa.net).
		* El Sistema debera tener el dominio .edu (casa.edu.ar).

# ERS (Especificación de Requerimientos de Software)
Es un conjunto de recomendaciones para la especificación de los requerimientos o requisitos el cual tiene como producto final la
documentación de los acuerdos entre el cliente y el grupo de desarrollo para cumplir las exigencias pautadas.

## ¿Quiénes leen el ERS?
	- Clientes y Usuarios: Interesados en validar el sistema y ver la descripción de alto nivel.
	- Analistas: Escriben las especificaciones para que otros interactúen con el sistema.
	- Desarrolladores: Son los que deben implementar los requerimientos.
	- Testers: Determinan la satisfacción de los requerimientos.
	- Managment: Controlan el proceso de desarrollo.
	- Otros interesados:
	 	* Equipo de operaciones
		* Equipos de soporte de usuarios
		* Legales
		* Subcontratistas
		* Entes reguladores

## Estructura de un ERS:
	- Introducción:
		 * Describir la necesidad de crear el sistema y cuáles son sus objetivos.
		 * ¿Cuáles son los antecedentes y la historia detrás de este proyecto?
		 * ¿Cuáles son los acercamientos actuales a este problema?

 	- Glosario de Términos
		* Términos técnicos que se emplearán a lo largo del documento
	- Definición de Requerimientos:
		* Definición de las necesidades de la problemática a solucionar, mencionando los aspectos esenciales, dando
		prioridades, funciones, características y restricciones.
	- Definición de Requerimientos funcionales:
		* Describen la interacción entre el sistema y su ambiente, en forma independiente a su implementación.
		* El ambiente incluye al usuario y cualquier otro sistema externo con el cual interactúa el sistema a desarrollar.
		* Definir los servicios que serán proporcionados.
	- Definición de Requerimientos NO funcionales:
	  	* Define las limitantes del sistema y el proceso de desarrollo.
	- Requerimiento del Sistema (Factibilidad Técnica)
		* Descripción de la plataforma de hardware del     sistema.
		* Especificación del software del sistema.
		* Interfaces de Aplicación del Programa (API) que deben incluirse.
		* Requerimientos de importación y exportación de datos.
		* Requerimientos de las bases de datos o archivos.

	- Evolución del Sistema.
		* Definir las suposiciones fundamentales en las cuales el sistema se basa y en donde se anticipan los cambios.

# Las características del Requerimiento:
	Descripción de los servicios de los sistemas y restricciones operativas (alcance)
	Reflejan los necesidades cliente.

# Funcionales:
	Definen lo que hacen el sistema y lo que hace ante determinadas entradas y salidas.

# No funcionales:
	Son los externos del sistema que inclyen restricciones en el tiempo, sistema operativo que se necestita, se requiere que
	tenga una impresora X, son más críticos que los Requerimientos funcionales.

# Estructura:
	- Lo marca la norma
	- Nombre del proyecto
	- Cliente
	- Introducción
	- Glosario de Términos
	- Definición de Requerimientos
	- Definición de Requerimientos No Funcionales
	- Factibilidad Técnica
	- Evolución del Sistema
	- [Hay una visión general de la estructura de los Documentos]

Caso de uso refleja lo que pide el sistema. Las acciones deben ser en infinitivo.

Extend es optativo. Para que quede completo el caso de uso, tiene que ir en dos vías. El ejemplo está en las imágenes.

Tener en cuenta que presentar en el front es distinto en Web que en móvil.

# Casos de Uso

Un caso de uso es un artefacto que define una secuencia de acciones que da lugar a un resultado de valor observable. Los casos de
uso proporcionan una estructura para expresar requisitos funcionales en el contexto de procesos empresariales y de sistema. Casos
de uso pueden representarse como un elemento gráfico en un diagrama y como una especificación de caso de uso en un documento
textual.
Por ejemplo: Un caso de uso empresarial define una secuencia de acciones que una empresa lleva a cabo y que da lugar a un
resultado de valor observable (una salida de trabajo) para un actor empresarial particular o que muestra el modo en que la empresa
responde a un evento empresarial.

Un caso de uso de sistema es una secuencia de acciones que un sistema lleva a cabo que da lugar a un resultado de valor observable
para un actor particular (alguien o algo fuera del sistema que interactúa con el sistema).

Un diagrama de caso de uso puede incluir varios casos de uso y las relaciones entre casos de uso y las personas, los grupos o los
sistemas que interactúan para llevar a cabo el caso de uso.

# Para el TP2:
A partir de los requerimientos se obtienen los casos de usos.
	Se puede hacer una interfaz,pero no es obligado.

Requerimiento funcionales enel TP2. Es un ABM.

Include ¿se puede finalizar el proceso si no se termina de definir el modo de pago? NO, entonces Include.
El NO FUNCIONAL:
	Sería la cantidad de RAM, el SO necesitado. El paradigma de la base, el lenguaje,bajo qué plataforma, etc.

Ejemplo de Casos de uso:
	Registrar factura
