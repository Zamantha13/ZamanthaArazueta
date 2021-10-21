## Unidad 3: Ingeniería de Requerimientos

# Tema: UML

## *¿Qué es UML?*

El Lenguaje Unificado de Modelado (UML) fue creado para forjar un lenguaje de modelado visual común y semántica y sintácticamente rico para la arquitectura, el diseño y la implementación de sistemas de software complejos, tanto en estructura como en comportamiento. UML tiene aplicaciones más allá del desarrollo de software.

Es comparable a los planos usados en otros campos y consiste en diferentes tipos de diagramas. En general, los diagramas UML describen los límites, la estructura y el comportamiento del sistema y los objetos que contiene.

UML no es un lenguaje de programación, pero existen herramientas que se pueden usar para generar código en diversos lenguajes usando los diagramas UML. UML guarda una relación directa con el análisis y el diseño orientados a objetos.


![imagen 1](          https://lh3.googleusercontent.com/proxy/CtC97Bc1h__vuViibyfoAnlFfXDvC6tPoJGH1ByB-XQxM3j9aBlBXq39t2q0ei9WzOEUTZGXIv2KVccawZvN-MI2oOhkCSnoA3IioPne   "imagen ")
## *¿Para Que Sirve UML?*

UML es la herramienta grafica que Se utiliza para especificar metodos o procesos realizados por el sistema, por medio de una serie de simbolos.

Nos proporciona una serie de herramientas que permiten mostrar el programa en sus diferentes etapas o procesos, delimitarlos y organizarlos de tal forma que sean entendibles por la persona que va a desarrollar el sistema.

## *Caracteristicas de UML*

Lo fundamental de una herramienta UML es la capacidad de diagramación, y los diferentes tipos de diagramas que soporta la herramienta. Sus esquemas de apoyo de diseño, documentación, construcción e implantación de sistema. Así mismo, su flexibilidad para admitir cambios no previstos durante el diseño o el rediseño. En resumen, la herramienta ideal, es aquella que admite diseño desde inicio a fin, diseño inverso (o rediseño) y diseño vise-versa, con esquemas amplios para documentar detalladamente los procesos.

UML se puede usar para modelar distintos tipos de sistemas: sistemas de software, sistemas de hardware,
y organizaciones del mundo real. UML ofrece nueve diagramas en los cuales modelar sistemas.


## *Beneficios UML*

Los principales beneficios de UML son:

Mejores tiempos totales de desarrollo (de 50 % o más).
Modelar sistemas (y no sólo de software) utilizando conceptos orientados a objetos.
Establecer conceptos y artefactos ejecutables.
Encaminar el desarrollo del escalamiento en sistemas complejos de misión crítica.
Crear un lenguaje de modelado utilizado tanto por humanos como por máquinas.
Mejor soporte a la planeación y al control de proyectos.
Alta reutilización y minimización de costos.

## *VENTAJAS*

UML Se puede usar para diferentes tipos de sistemas 
UML consolida muchas de las notaciones y conceptos más usadas orientados a objetos. 
UML es facilmente entendible 

## *DESVENTAJAS*

UML no es un método de desarrollo. 
UML al no ser un método de desarrollo es independiente del ciclo de desarrollo
UML no se presta con facilidad al diseño de sistemas distribuidos.


# Diagramas del UML

## *Que es?*

El UML está compuesto por diversos elementos gráficos que se
combinan para conformar diagramas. Debido a que el UML es un
lenguaje, cuenta con reglas para combinar tales elementos.

## *¿ Para que sirve ?*

La finalidad de los diagramas es presentar diversas perspectivas de un
sistema, a las cuales se les conoce como modelo. Recordemos que un
modelo es una representación simplificada de la realidad; el modelo UML
describe lo que supuestamente hará un sistema, pero no dice cómo
implementar dicho sistema. 


# *¿Qué es un diagrama de objetos en UML?*

Un diagrama de objetos UML representa una instancia específica de un diagrama de clases en un momento determinado en el tiempo. Cuando se lo representa visualmente, verás muchas similitudes con el diagrama de clases.
Elementos del diagramas de objetos
Los diagramas de objetos son sencillos de crear: se componen de objetos, representados por rectángulos, conectados mediante líneas. Echa un vistazo a los elementos principales de un diagrama de objetos.

## Objetos

Los objetos son instancias de una clase. Por ejemplo, si "coche" es una clase, un Altima 2007 de Nissan es un objeto de una clase.

## Títulos de clases

Los títulos de clases son los atributos específicos de una clase dada. En el diagrama de objetos de árbol genealógico, los títulos de clases incluyen nombre, género y edad de los integrantes de la familia. Se pueden listar títulos de clases como elementos en el objeto o incluso en las propiedades del propio objeto (como el color).

![imagen2](    https://d2slcw3kip6qmk.cloudfront.net/marketing/pages/chart/UML-object-diagram-tutorial/Object_Diagram.PNG    "imagen")

## Diagrama de objetos - Títulos de clases
Atributos de clases

Los atributos de clases se representan por medio de un rectángulo con dos pestañas que indica un elemento de software.

## Enlaces

Los enlaces son líneas que conectan dos figuras de un diagrama de objetos entre sí. El diagrama de objetos corporativo siguiente muestra cómo los departamentos están conectados al estilo del organigrama tradicional.

![imagen3]( https://d2slcw3kip6qmk.cloudfront.net/marketing/pages/chart/what-is-an-object-diagram-in-UML/Object-Diagram-Example-3-700x350@2x.png        "imagen ")

# *Diagrama de paquetes*

El objetivo de estos diagramas es obtener una visión más clara del sistema de información orientado a objetos, organizándolo en subsistemas, agrupando los elementos del análisis, diseño o construcción y detallando las relaciones de dependencia entre ellos. El mecanismo de agrupación se denomina Paquete.

Estrictamente hablando, los paquetes y sus dependencias son elementos de los diagramas de casos de uso, de clases y de componentes, por lo que se podría decir que el diagrama de paquetes es una extensión de éstos. En MÉTRICA Versión 3, el diagrama de paquetes es tratado como una técnica aparte, que se aplica en el análisis para la agrupación de casos de uso o de clases de análisis, en el diseño de la arquitectura para la agrupación de clases de diseño y en el diseño detallado para agrupar componentes.

## Descripción

Estos diagramas contienen dos tipos de elementos:

Paquetes: Un paquete es una agrupación de elementos, bien sea casos de uso, clases o componentes. Los paquetes pueden contener a su vez otros paquetes anidados que en última instancia contendrán alguno de los elementos anteriores.
Dependencias entre paquetes: Existe una dependencia cuando un elemento de un paquete requiere de otro que pertenece a un paquete distinto. Es importante resaltar que las dependencias no son transitivas.
Se pueden optimizar estos diagramas teniendo en cuenta cuestiones como: la generalización de paquetes, el evitar ciclos en la estructura del diagrama, la minimización de las dependencias entre paquetes, etc.

## Notación

Paquete

Un paquete se representa mediante un símbolo con forma de ‘carpeta’ en el que se coloca el nombre en la pestaña y el contenido del paquete dentro de la ‘carpeta’. En los casos en que no sea visible el contenido del paquete se podrá colocar en su lugar el nombre.

Si el paquete tiene definido un estereotipo, éste se representa encima del nombre entre el símbolo << ... >>, y si se definen propiedades, se representan debajo del nombre y entre llaves.

La visibilidad de los elementos que forman el paquete se debe indicar anteponiendo a su nombre los símbolos: ‘+’ para los públicos, ‘-‘ para los privados y ‘#’ para los protegidos.

## Dependencia

Las dependencias se representan con una flecha discontinua con inicio en el paquete que depende del otro.

## Ejemplo

Sistema encargado de la gestión de los préstamos y reservas de libros y revistas en una biblioteca.

![imagen4](http://manuel.cillero.es/wp-content/uploads/2013/11/paquetes.png?x17174 "ejemplo" )


# *Diagrama de estructura *

El objetivo de este diagrama es representar la estructura modular del sistema o de un componente del mismo y definir los parámetros de entrada y salida de cada uno de los módulos.

Para su realización se partirá del modelo de procesos obtenido como resultado de la aplicación de la técnica de diagrama de flujo de datos (DFD).

## Descripción

Un diagrama de estructura se representa en forma de árbol con los siguientes elementos:

Módulo: división del software clara y manejable con interfaces modulares perfectamente definidas. Un módulo puede representar un programa, subprograma o rutina dependiendo del lenguaje a utilizar. Admite parámetros de llamada y retorno. En el diseño de alto nivel hay que ver un módulo como una caja negra, donde se contemplan exclusivamente sus entradas y sus salidas y no los detalles de la lógica interna del módulo.

Para que se reduzca la complejidad del cambio ante una determinada modificación, es necesario que los módulos cumplan las siguientes condiciones:

Que sean de pequeño tamaño.

Que sean independientes entre sí.

Que realicen una función clara y sencilla.

Conexión: representa una llamada de un módulo a otro.

Parámetro: información que se intercambia entre los módulos. Pueden ser de dos tipos en funci
ón de la clase de información a procesar:

Control: son valores de condición que afectan a la lógica de los módulos llamados. Sincronizan la operativa de los módulos.

Datos: información compartida entre módulos y que es procesada en los módulos llamados.
Otros componentes que se pueden representar en el diagrama de estructura son:

Módulo predefinido: es aquel módulo que está disponible en la biblioteca del sistema o de la propia aplicación, y por tanto no es necesario codificarlo.
Almacén de datos: es la representación física del lugar donde están almacenados los datos del sistema.
Dispositivo físico: es cualquier dispositivo por el cual se puede recibir o enviar información que necesite el sistema.

![imagen5](http://manuel.cillero.es/wp-content/uploads/2013/11/estrategia-disenio.png?x17174 " holi ")













## *Referencias*

http://aprenderaprogramar.com/index.php?option=com_content&view=article&id=688:ique-es-y-para-que-sirve-uml-versiones-de-uml-lenguaje-unificado-de-modelado-tipos-de-diagramas-uml&catid=46:lenguajes-y-entornos&Itemid=163



