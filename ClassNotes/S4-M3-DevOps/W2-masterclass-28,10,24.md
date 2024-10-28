## Capstone checkpoint

> [!CAUTION]
> Revisar los puntos claves de la presentacion final
#### Puntos a revisar
- Estado del proyecto
- Requisitos claros?
- Identificacion de desafios tecnicos

### Temas de la semana **API's Avanzadas**

> [!CAUTION]
> BUscar si es una opcion viable para back o para front

### Que es ODta?
Es un camino para mejores practicas en cuanto consumo de API's.
Los comandos HTTP cpn cruciales en las API's, ademas lo ideal seria que se contara con el certificado de seguridad (HTTP**S**).
- Sigue los principios REST
- Manejo Simple: Abodar los casos comunes y proporciona extensibidad dond esea necesario.
- Construye dde forma incrementa: In servicio debe ser basico y conform debe ser facil de construir, requeriendo traba adicional solo para adminir capaciodades adicionales.
- La extensibilidad es importante: los servicios deben poder adminir funcionalidades extendidas sin afectar a los clientes.

#### Admite varios tipos de consultas
> - Permire filtrado con el parametro $filter.
> - Pagina lo sresultados utilizando $top y $skip.
> - Ordena los resultadios usando $orderby
> - Obten los datos adicionales usando $expend
> - Reduce los datos no deseados utilizando $select

> [!WARNING]
> Son comandos muy parecidos a los de SQL pero no se deben confundir.

#### Odata - $filter
La opcion permite a los clientes filtrar una coleccion de recursos que se direccionan mediante una URL de solicitud.
La expresion especificada evalua para cada recurso en la coleccion, y solo los elementos donde la expresion resulte verdadera se incluira la respuesta.

#### Odata - $orderby
La opcion permite a los clientes solciitar recursos en orden ascendente **asc** o en orden descendente utilizando **desc**.
Si no se especifica asc o desc, los recursos se ordenaran en orden ascendente.

#### Odata - $top
 La opcion solciita el numero de elementos en la coleecion consultada que se incluiran en el resultado, la opcion de consulta $skip solicita el numero de elementos en la coleccion consuktada que se deben omiitir y no incluir en el resto.
 
 ## JSON:API
 Es una especificacion sobre como un cliente debe solicitart recursos sean obtenidos o modfificados y com un servidor debe responder a esas solicitudes, puede ser facilmente ampliado con extensiones y perfiles.
 
Esta diseniado para minimizar el numero de solicitudes asi como la cnaidad de datos transmitidos entre clientesd y servidores, esta eficiencia sd logra sin comprometer la legibilidad, flexibilidad o capacidad de descubrimiento.



















