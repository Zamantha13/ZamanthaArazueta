## Unidad 4: Modelado

# Tema: ¿Qué es JSON y XML?

## *¿Qué es JSON?*

Los datos son lo más importante. Pero saber cómo trabajar con una variedad de datos se ha vuelto aún más importante. Los programadores, desarrolladores y profesionales de TI necesitan transferir estructuras de datos pobladas de cualquier idioma a formatos reconocibles por otros idiomas y plataformas. JavaScript Object Notation (JSON) es el formato de cambio de datos que lo hace posible.

JSON se ha convertido en un formato de datos popular para los desarrolladores debido a su texto legible por humanos, que es ligero, requiere menos codificación y se procesa más rápido.

![IMAGEN1](https://www.wp-entwickler.at/wp-content/uploads/2017/12/14636491710_d347ce16ae_b_json.jpg)

## *Caracteristicas de JSON*

* JSON es solo un formato de datos.
* Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
* Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione. 
* Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Así, por ejemplo, una cadena o un número único podrían ser objetos JSON válidos.
* A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

## *Ventajas de JSON :* 

* Es autodescriptivo y fácil de entender.

* Su sencillez le ha permitido posicionarse como alternativa a XML.

* Es más rápido en cualquier navegador.

* Es más fácil de leer que XML.

* Es más ligero (bytes) en las transmisiones.

* Se parsea más rápido.

* Velocidad de procesamiento alta.

* Puede ser entendido de forma nativa por los analizadores de JavaScript.

## *Desventajas de JSON:*

* Algunos desarrolladores encuentran su escueta notación algo confusa.

* No cuenta con una característica que posee XML: extensibilidad.

* No soporta grandes cargas, solo datos comunes.

* Para la seguridad requiere de mecanismos externos como expresiones regulares


# *Ejemplos y tipos de datos JSON*

JSON se puede utilizar en programas de JavaScript sin necesidad de analizar o serializar. Es una forma de representar literales basada en texto, matrices y datos escalares de objetos JavaScript.

JSON es relativamente fácil de leer y escribir, y también permite que el software analice y genere con facilidad. A menudo se utiliza para serializar datos estructurados e intercambiarlos a través de una red, normalmente entre un servidor y aplicaciones web.

En el nivel granular, JSON consta de tipos de datos.

Cadena
Número
Booleano
Nulo
Objeto
Serie

## *Cadena*
Una cadena en JSON se compone de caracteres Unicode, con escape de barra invertida (\).

Ejemplo

{ "name" : "Jones" }

## *Número*
El número JSON sigue el formato de punto flotante de precisión doble de JavaScript.

Ejemplo
{
  "number_1" : 210,
  "number_2" : 215,
  "number_3" : 21.05,
  "number_4" : 10.05
}

## *Booleano*
Los valores booleanos se designan como verdaderos o falsos. Los valores booleanos no están rodeados entre comillas y se tratan como valores de cadena.

Ejemplo

{ "AllowPartialShipment" : false }

# ¿Qué es XML?

XML es el acrónimo de Extensible Markup Language, es decir, es un lenguaje de marcado que define un conjunto de reglas para la codificación de documentos. 

Un archivo XML se divide en dos partes: prolog y body. La parte prolog consiste en metadatos administrativos, como declaración XML, instrucción de procesamiento opcional, declaración de tipo de documento y comentarios.

![imagen 2](https://cdn4.iconfinder.com/data/icons/dellios_system_icons/png/xml.png)

## *Caracteristicas de XML*

* XML es un estándar para escribir datos estructurados en un fichero de texto.

 * XML parece HTML pero no lo es.

* XML está en formato texto, pero no para ser leído.

* XML consta de una familia de tecnologías.

* XML es prolijo, pero eso no supone un problema.




## *Ventajas XML:*

* Tiene un formato estructurado y fácil de comprender.

* Separa radicalmente la información o el contenido de su presentación o formato.

* Está diseñado para ser utilizado en cualquier lenguaje o alfabeto.

* Su análisis sintáctico es fácil debido a las estrictas reglas que rigen la composición de un documento.

* Tiene soporte a cualquier tipo de datos.

* Se pueden definir estructuras complejas y reutilizables.

## *Desventajas XML:*

* El formato es sumamente estricto.

* Lleva más tiempo procesarlo.

* Complejidad de analizador (parser).

* Un error en cualquier parte del formato puede hacer que todo el documento sea inválido.
## *Ejemplos de XML*

* *Ejemplo 1: Menú De Comidas En XML
Código:*

< menu_almuerzo>

    < comida>
        <nombre>Waffles</nombre>
        <precio>$2.00</precio>
        <descripcion>Waffles baratos de McDonalds</descripcion>
        <calorias>650</calorias>
    </comida>
    <comida>
        <nombre>Hamburguesa</nombre>
        <precio>$5.00</precio>
        <descripcion>La hamburguesa mas comun de McDonalds</descripcion>
        <calorias>1500</calorias>
    </comida>   
< /menu_almuerzo>

 *  *Ejemplo2:Catálogo De CDs En XML*

Código:

< CATALOGO>

    < CD>
        <TITULO>Tinta roja</TITULO>
        <ARTISTA>Andres Calamaro</ARTISTA>
        <ORIGEN>AR</ORIGEN>
        <PRECIO>5.90</PRECIO>
        <ANO>2006</ANO>
    </CD>
    <CD>
        <TITULO>La Lengua Popular</TITULO>
        <ARTISTA>Andres Calamaro</ARTISTA>
        <ORIGEN>AR</ORIGEN>
        <PRECIO>9.90</PRECIO>
        <ANO>2007</ANO>
    </CD>
< /CATALOGO>

* *Ejemplo 3:Estructura XML*

<xml version=" 1.0 " encoding=" UTF-8 " standalone= " yes "?>

< ficha>

< nombre> Gabriel < /nombre>

< apellido> Molina < /apellido>

< direccion> Alfredo Vargas #36 < /direccion>

< /ficha>


![IMAGEN 3](https://pic.weblogographic.com/img/protocols-formats/difference-between-json-and-xml-1.jpg)










### REFERENCIAS 

https://www.nextu.com/blog/que-es-json/#:~:text=Una%20de%20las%20caracter%C3%ADsticas%20de%20JSON%2C%20al%20ser,para%20codificar%20y%20decodificar%20cadenas%20en%20este%20formato.
https://conocimientoysistemas.wordpress.com/tag/caracteristicas-xml/#:~:text=Sus%20características%20más%20relevantes%20son%3A%201.%20–%20XML,direcciones%20de%20Internet%2C%20hasta%20parámetros%20de%20configuración%2C%20
Fuente: https://www.ejemplode.com/21-xml/522-ejemplo_de_catalogo_de_cds_en_xml.html#ixzz79x54ZgIe






