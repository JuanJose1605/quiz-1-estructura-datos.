# Diferencia de IDE y editor de texto 

# Editor de Texto
Propósito Básico: Un editor de texto está diseñado principalmente para editar texto. Los editores de texto se utilizan para escribir y modificar código fuente, documentos, notas, etc.

Funciones Básicas: Ofrecen características básicas como resaltar la sintaxis, búsqueda y reemplazo de texto, y a veces, funciones de autocompletado simples.

Ejemplos: Notepad++, Sublime Text, Visual Studio Code (aunque Visual Studio Code también puede ser considerado un editor avanzado).

Extensibilidad: Muchos editores de texto permiten la instalación de extensiones o plugins que añaden funcionalidades adicionales, como soporte para distintos lenguajes de programación o herramientas de depuración.

Recursos: Suelen ser más ligeros en cuanto a consumo de recursos del sistema, ya que están diseñados para realizar tareas más básicas.

# IDE (Entorno de Desarrollo Integrado)
Propósito Completo: Un IDE está diseñado para ser una plataforma completa de desarrollo de software. Integra múltiples herramientas necesarias para el desarrollo de aplicaciones, facilitando el proceso de programación desde la escritura del código hasta la depuración y el despliegue.

Funciones Avanzadas: Incluye funcionalidades como depuración avanzada, administración de versiones, integración con bases de datos, diseño de interfaces gráficas, y compilación o ejecución del código dentro del mismo entorno.

Ejemplos: IntelliJ IDEA, Eclipse, Visual Studio, Xcode.

Extensibilidad: Los IDE suelen tener extensiones y plugins, pero también vienen con una suite más completa de herramientas integradas que trabajan juntas de forma más cohesionada.

Recursos: Generalmente son más pesados en cuanto a consumo de recursos, ya que están diseñados para ofrecer una gama más amplia de funcionalidades.



# Lenguajes Tipados
# Lenguajes con Tipado Estático: 
En estos lenguajes, el tipo de cada variable se define en el momento de la compilación y no puede cambiarse en tiempo de ejecución. Esto permite detectar errores relacionados con tipos en la fase de compilación, lo que puede ayudar a mejorar la seguridad y la robustez del código.

Ejemplos:
Java: Las variables deben ser declaradas con un tipo específico, y ese tipo no puede cambiar.
C/C++: Los tipos de datos deben ser especificados al declarar variables y no cambian durante la ejecución.
C#: Similar a Java, las variables tienen un tipo fijo y las comprobaciones de tipo se realizan en tiempo de compilación.

# Lenguajes con Tipado Dinámico: 
En estos lenguajes, los tipos se asignan en tiempo de ejecución, lo que significa que las variables pueden cambiar de tipo durante la ejecución del programa. Esto ofrece más flexibilidad, pero también puede introducir errores que solo se detectan en tiempo de ejecución.

Ejemplos:
Python: Las variables pueden cambiar de tipo a lo largo del tiempo de ejecución.
Ruby: Los tipos de datos se determinan en tiempo de ejecución.
JavaScript: Permite variables de tipos dinámicos, lo que facilita la escritura de código flexible pero puede llevar a errores inesperados.

# Lenguajes No Tipados

# Lenguajes de Tipado Débil: 
En estos lenguajes, el sistema de tipos es más flexible y permisivo. El lenguaje realiza conversiones automáticas entre tipos (conversión implícita), lo que puede llevar a comportamientos inesperados si no se tiene cuidado.

Ejemplos:
JavaScript: Permite operaciones entre tipos de datos diferentes y realiza conversiones implícitas, lo que puede llevar a resultados inesperados.
PHP: Similar a JavaScript en cuanto a la conversión implícita entre tipos de datos.

# Lenguajes de Tipado Fuerte: 
Aunque en estos lenguajes los tipos son definidos y estrictos, la diferencia con los lenguajes con tipado estático es que suelen permitir algunas conversiones entre tipos, pero con restricciones y sin tantas implicaciones automáticas como en los lenguajes de tipado débil.

Ejemplos:
Haskell: Aunque es un lenguaje funcional con tipado estático, el tipo es estricto y las conversiones entre tipos no se realizan automáticamente.
Scala: Permite un tipo de datos fuerte y estático, pero con más flexibilidad en comparación con lenguajes como Java.

# Tipo de datos en java

# Tipos Primitivos
# Numericos
Tipos de Datos Enteros
Estos tipos de datos se utilizan para representar números enteros sin decimales.

# byte

Tamaño: 8 bits (1 byte)
Rango: -128 a 127
Uso: Ideal para ahorrar espacio en grandes arreglos y cuando se sabe que los valores estarán dentro de este rango.
java

# short

Tamaño: 16 bits (2 bytes)
Rango: -32,768 a 32,767
Uso: Similar al byte, pero con un rango más amplio. A menudo se usa cuando se necesita un rango mayor que byte, pero no se requiere la capacidad completa de int.
java

# int

Tamaño: 32 bits (4 bytes)
Rango: -2,147,483,648 a 2,147,483,647
Uso: Tipo de entero más común, adecuado para la mayoría de los casos donde se requieren enteros.
java

# long

Tamaño: 64 bits (8 bytes)
Rango: -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807
Uso: Utilizado para valores enteros muy grandes que exceden el rango de int.
java

# Tipos de Datos de Punto Flotante
Estos tipos de datos se utilizan para representar números con decimales.

# float

Tamaño: 32 bits (4 bytes)
Rango: Aproximadamente ±3.40282347E+38F (7 dígitos decimales de precisión)
Uso: Adecuado para representaciones de punto flotante con precisión simple. Es útil cuando se necesita menos precisión y se desea ahorrar memoria.
java

# double

Tamaño: 64 bits (8 bytes)
Rango: Aproximadamente ±1.79769313486231570E+308 (15-16 dígitos decimales de precisión)
Uso: Utilizado para representaciones de punto flotante con precisión doble. Es la opción más común para cálculos de precisión más alta.
java

# Cadenas
# String
Definición: En Java, las cadenas de texto se representan mediante el tipo de dato String. Una instancia de String es un objeto que representa una secuencia de caracteres.

Inmutabilidad: Los objetos de tipo String en Java son inmutables. Esto significa que una vez que se crea un objeto String, su valor no puede cambiar. Si se realizan modificaciones en una cadena, se crea un nuevo objeto String.

# Clases Relacionadas
Además del String, hay otras clases en Java que son útiles para el manejo de cadenas:

# StringBuilder:

Uso: Se utiliza para construir y manipular cadenas de texto de manera más eficiente cuando se realizan múltiples modificaciones a una cadena. A diferencia de String, StringBuilder es mutable.

# StringBuffer:

Uso: Similar a StringBuilder, pero es sincronizado, lo que lo hace adecuado para uso en entornos concurrentes. Sin embargo, en la mayoría de los casos, StringBuilder es preferido por su mejor rendimiento.

# Fecha

# LocalDate:

Uso: Representa una fecha sin hora (año, mes, día).

# LocalTime:

Uso: Representa una hora del día sin fecha.

# LocalDateTime:

Uso: Combina una fecha y una hora sin zona horaria.
Ejemplo:

# ZonedDateTime:

Uso: Representa una fecha y hora con zona horaria.
Ejemplo:

# OffsetDateTime:

Uso: Representa una fecha y hora con un desplazamiento de zona horaria en lugar de un ID de zona.
