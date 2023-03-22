# Capítulo 2

## Modelo de dominio
En el modelo de dominio se representan los conceptos más significativos del contexto del sistema como son los objetos de negocio, objetos del mundo real a los que el sistema tiene que hacer seguimiento y eventos que ocurren u ocurrirán en el contexto de nuestro sistema. El modelo de dominio tiene como objetivo asegurar que se comprende el contexto en el que se tiene que desarrollar el software y establecer un vocabulario común entre los stakeholders del proyecto, cliente, los usuarios y desarrolladores, entre otros.

### Ejemplo
Para obtener el modelo de dominio del taller de reparaciones de vehículos, se ha hecho una reunión con el responsable del taller mecánico, donde se detalló el funcionamiento del mismo, cómo se registran los trabajos que hacen los mecánicos y qué vocabulario usan en sus labores diarias. Se ha representado el modelo de dominio mediante 2 diagramas.

* Figura 1. Modelo de dominio junto a los objetos de dominio y sus relaciones.

![Figura 1. Modelo de dominio junto a los objetos de dominio y sus relaciones.](https://user-images.githubusercontent.com/22343642/226901522-95543eba-9204-4cbf-8344-11fc196ed6c0.png)

* Figura 2.  Diagrama de estados por los que pasa una intervención.

![Figura 2.  Diagrama de estados por los que pasa una intervención.](https://user-images.githubusercontent.com/22343642/226903056-48c5bc17-cba7-4fd3-88c9-a40d23616af1.png)

## Requisitos

En este capítulo se detalla cómo se ha gestionado el ámbito del proyecto. El ámbito se establece a través del modelo de casos de uso. Mediante este modelo se representan los requisitos funcionales y sirve para establecer un contrato común entre el cliente, los desarrolladores y los usuarios sobre lo que el sistema debería de hacer y cómo se debería de utilizar. También sirve para dotar a los desarrolladores de una mejor comprensión de lo que debería de hacer el sistema, establecer sus límites, y proveer las bases para la estimación de costes y tiempo en la gestión del proyecto. A través del modelo de casos de uso se representan los requisitos funcionales.

El modelo de casos de uso se ha obtenido realizando las actividades recomendadas por el proceso de desarrollo RUP, mediante las cuales se han ido generando diferentes artefactos que juntos conforman el modelo de casos de uso. Las actividades realizadas en esta disciplina han sido:

1. Encontrar actores y casos de uso
2. Priorizar casos de uso
3. Detallar casos de uso
4. Estructurar el modelo de casos de uso
5. Prototipar interfaz de usuario.

### Actores y casos de uso identificados

* Figura 3. Casos de uso relacionados con la gestión de las intervenciones.

![Figura 3. Casos de uso relacionados con la gestión de las intervenciones.](https://user-images.githubusercontent.com/22343642/226904201-b239a26c-31e6-4403-af75-c3126b204f74.png)

* Figura 4. Casos de uso relacionados con la gestión de los mecánicos

![Figura 4. Casos de uso relacionados con la gestión de los mecánicos.](https://user-images.githubusercontent.com/22343642/226904323-03dd3e03-68f8-4f6c-951f-dfad54957255.png)

* Figura 5. Casos de uso relacionados con la gestión de los vehiculos.

![Figura 5. Casos de uso relacionados con la gestión de los vehiculos.](https://user-images.githubusercontent.com/22343642/226904360-b42041c6-2a80-4321-9337-f16c13f75d60.png)

* Figura 6. Casos de uso relacionados con la gestión de los clientes.

![Figura 6. Casos de uso relacionados con la gestión de los clientes.](https://user-images.githubusercontent.com/22343642/226904390-0b18d1d4-28ac-448d-92ed-3fc428f754d0.png)

### Diagrama de Contexto

El diagrama de contexto nos permite ver de una manera más general todo lo que se permite hacer en el sistema en función de los casos de uso identificados, y la trazabilidad que hay entre ellos. Hay casos de uso que solo se pueden realizar una vez finalizada la realización de otro caso de uso. Todos estos detalles quedan reflejados en el diagrama de contexto.

* Figura 7. Contexto de casos de uso

![Figura 7. Contexto de casos de uso](https://user-images.githubusercontent.com/22343642/226904785-9d476899-8937-4813-91b5-935f02f828db.png)

