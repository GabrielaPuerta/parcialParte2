**PROPIEDADES**

- **spring.cloud.gateway.mvc.routes[0].id**

Descripción: Esta propiedad define un identificador único para la primera ruta ([0]) dentro de la configuración de Spring Cloud Gateway MVC.

- **spring.cloud.gateway.mvc.routes[0].uri**

Descripción: Esta propiedad especifica la URI destino a la cual el gateway reenviará las solicitudes que coincidan con esta ruta.

- **spring.cloud.gateway.mvc.routes[0].predicates**

Descripción: Esta propiedad define una lista de condiciones (predicados) que se deben cumplir para que se considere la ruta. Las solicitudes solo se reenvían a la URI destino si todos los predicados se evalúan como verdadero.

- **spring.cloud.gateway.mvc.routes[0].filters**

Descripción: Esta propiedad define una lista de filtros que se aplican a las solicitudes y respuestas antes y después de reenviarlas a la URI destino. Los filtros se pueden usar para diversos fines, como agregar encabezados de autenticación, registrar solicitudes o modificar respuestas.

**GENERICOS DEN JAVA**

Los genéricos en Java son una característica introducida en la versión J2SE 5.0 (2004) que permite escribir código más seguro, flexible y reutilizable. Se basan en el concepto de tipos parametrizados, donde los tipos de datos específicos se pasan como parámetros al definir clases, interfaces o métodos.

**Ventajas de los genéricos en Java**

- Seguridad de tipos mejorada: Los genéricos eliminan en gran medida la necesidad de conversiones de tipo explícitas y verifican los tipos de datos en tiempo de compilación. Esto reduce significativamente los errores de tipo en ejecución y aumenta la confiabilidad del código.

- Mayor flexibilidad: Los genéricos permiten escribir código que puede trabajar con diferentes tipos de datos sin necesidad de crear código duplicado. Esto mejora la reutilización del código y facilita la adaptación a nuevos requisitos.

- Código más legible y expresivo: El uso de genéricos hace que el código sea más autodocumentado, ya que el tipo de datos utilizado se declara explícitamente. Esto mejora la legibilidad y mantenibilidad del código.

**Usos comunes de los genéricos en Java**

- Colecciones: Los genéricos se utilizan ampliamente en las colecciones de Java, como List, Set y Map. Esto permite almacenar y recuperar elementos de diferentes tipos de forma segura y eficiente.

- Clases parametrizadas: Se pueden crear clases parametrizadas que pueden trabajar con diferentes tipos de datos relacionados. Esto promueve la reutilización del código y reduce la necesidad de crear clases específicas para cada tipo de dato.

- Métodos parametrizados: Los métodos parametrizados permiten definir métodos que pueden operar en diferentes tipos de datos compatibles. Esto aumenta la flexibilidad y la reutilización del código.
