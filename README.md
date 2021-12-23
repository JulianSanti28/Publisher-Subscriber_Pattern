# Publisher-Subscriber_Pattern
Implementation of Publisher-Subscriber pattern in Java
# Ingeniería de Software II 2021-2

## Integrantes:
* Julián S Martinez
* Paula A Peña

## Entregas:
- [x] 22/12/21: Publisher-Subscriber Pattern

### Descripción:

#### Asegúrese que esté corriendo RabbitMQ al momento de iniciar el proyecto. Limpie y construya cada uno de los plugins, luego el common y por último el core. Asegúrese de revisar el archivo plugin.properties ubicado en la raíz del proyecto con el fin de determinar el correcto funcionamiento de cada uno de los plugins. Por último, no olvide revisa las dependencias en tiempo de ejecución en el core. Asegúrese que estén allí los plugins agregados.

#### El proyecto funciona a través de RabbitMQ aplicando el patrón de Publicador y Subscriptor. La forma en como se implementa es a través de el intercambio con ayuda de un exchange de tipo fanout. El mensaje se envía a los subscriptores disponibles pero cada uno de ellos realiza acciones diferentes con la información de llegada.

- [x] Thank you so much! :relaxed:
