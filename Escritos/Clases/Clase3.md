
# Dudas de la clase pasada.

Cada caso de Uso genera una interfaz.
Un presupuesto o Ingresar datos NO es un caso de uso.

¿Es obligatorio que algo suceda cuando se procese una interfaz? NO.

	Cancelar venta -> extend de Registrar Venta

¿Qué significa Extend? Se puede cancelar la venta cuando se Registra la Venta, o sino directamente desde el Administrador se
elije la opción Cancelar venta.
	El ejemplo está en el grupo del Whatsapp.

# Include y Extend

Gráficamente lo que se muestra, es una relación de dependencia entre el par de casos de uso, con el nombre correspondiente al tipo
de relación de la que se trate: ya sea <<include>> o <<extend>>.

Estas, son relaciones que usamos para ligar gráficamente dos casos de uso, cuyos flujos de eventos están unidos, normalmente en
una sola sesión del usuario. En otras palabras, un caso de uso que está ligado, por medio de una de estas dos relaciones, a otro
caso de uso; también podría leerse o ejecutarse como un sólo caso de uso en lugar de dos. Obviamente, hay una razón por la cual
decidimos separarlos en dos, lo cual explicaremos más adelante.

Imagina el conjunto de pasos que ocurren al realizar una compra en una tienda departamental. Seguramente no tendrás problema en
visualizar el conjunto de pasos para solicitar la autorización de la tarjeta de crédito con la que vas a pagar, ligado a los pasos
donde el vendedor registra los productos a comprar. Es decir, los flujos de eventos de ambos procesos forman una sola cosa; juntos
podrían formar un solo caso de uso, en lugar de dos casos de uso unidos por alguna de estas relaciones que aquí estamos tratando.

## Include

Include: En términos muy simples, cuando relacionamos dos casos de uso con un “include”, estamos diciendo que el primero (el caso
de uso base) incluye al segundo (el caso de uso incluido). Es decir, el segundo es parte esencial del primero. Sin el segundo, el
primero no podría funcionar bien; pues no podría cumplir su objetivo. Para una venta en caja, la venta no puede considerarse
completa si no se realiza el proceso para cobrarla en ese momento. El caso de uso “Cobrar Renta” está incluido en el caso de uso
“Rentar Video”, o lo que es lo mismo “Rentar Video” incluye (<<include>>) “Cobrar Renta”.

## Extend

Extend: La polémica al querer seleccionar una de las dos relaciones es que en el “extend” también podemos ver, desde la
perspectiva del usuario, a los dos flujos como si fueran uno sólo. Y en ciertos escenarios el caso de uso base no podría cumplir
su objetivo si no se ejecutara la extensión. Pero, una de las diferencias básicas es que en el caso del “extend” hay situaciones
en que el caso de uso de extensión no es indispensable que ocurra, y cuando lo hace ofrece un valor extra (extiende) al objetivo
original del caso de uso base. En cambio en el “include” es necesario que ocurra el caso incluído, tan sólo para satisfacer el
objetivo del caso de uso base. Ejemplo: Puedes “Realizar Venta” sin “Acumular Puntos de Cliente VIP”, cuando no eres un cliente
VIP. Pero, si eres un cliente VIP sí acumularás puntos. Por lo tanto, “Acumular Puntos” es una extensión de “Realizar Venta” y
sólo se ejecuta para cierto tipo de ventas, no para todas.

Todo sacado de: https://www.abiztar.com.mx/articulos/casos-a-incluir-casos-a-extender.html

# Estudio de Factibilidad

El estudio de factibilidad es un instrumento que sirve para orientar la toma de decisiones en la evaluación de un proyecto y
corresponde a la última fase de la etapa pre-operativa o de formulación dentro del ciclo del proyecto. Se formula con base en
información que tiene la menor incertidumbre posible para medir las posibilidades de éxito o fracaso de un proyecto de inversión,
apoyándose en él se tomará la decisión de proceder o no con su implementación.


https://www.gestiopolis.com/que-es-el-estudio-de-factibilidad-en-un-proyecto/
https://www.gestiopolis.com/formulacion-evaluacion-de-proyectos/

3 Elementos
	- Tecnicos (toda la parte física, redes, hardware, etc)
	- Económico (el dinero que se tiene para tal fin)
	- Operativa (el recurso humano que se tiene disponible)

Responde a la pregunta de: ¿Es viable el proyecto?

¿Por qué 3 pupuestas por cada un elemento?
	Para que sea más objetivo la factibilidad.

Ponderación: es el peso que tiene cada elemento
	Cada atributo

Hay que hacer con perfiles

Cuando se elige la opción de los perfiles en la ponderación, hay que poner por qué nos quedamos con determinado equipo, hay que
justificar.

# Trabajo Práctico para después del 21.

Es un hospital, hay que trabajar con costos reales y con pesos argentinos.
Enfocado a salud.
El alcance lo considera cada uno de los alumnos.

La factibilidad se encarga el alumno.

El costo inicial del dinero disponible, es a nuestro parecer

Se puede hacer en la nube, pero hay que justificar todas las elecciones que se hagan.
