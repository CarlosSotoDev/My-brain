# QUE ES KAFKA
Kafka es una plataforma de event streaming distribuida diseñada para publicar, consumir, almacenar y procesar eventos en tiempo  real, de forma escalable, tolerante a fallos y de alto rendimiento.

Se utilizar principalmente para integración de sistemas, arquitecturas event-driven y procesamiento de datos en tiempo real

## Componentes principales de Kafka
- **Producer**: Publica (Envía) eventos o mensajes a kafka.
- **Topic**: Canala lógico donde se organizan los mensajes.
- **Partition**: División interna de un topic que permite paralelismo y escalabilidad.
- **Broker**: Nodo del clúster kafka que almacena y gestiona los mensajes.
- **Consumer**: Lee y procesa mensajes desde los topics.
- **Consumer Group**: Conjunto de consumidores que trabajan coordinadamente sobre un Topic.
- **Offset**: Identificador de la posicion de un mensaje dentro de una partición.
- **Zookeper / KRfat**: Mecanismo de coordinación del clúster (Zookeper en versiones antiguas, KRaft en las modernas)