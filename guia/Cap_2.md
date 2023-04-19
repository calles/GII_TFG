# Capítulo 2

## Modelo de dominio
En el modelo de dominio se representan los conceptos más significativos del contexto del sistema como son los objetos de negocio, objetos del mundo real a los que el sistema tiene que hacer seguimiento y eventos que ocurren u ocurrirán en el contexto de nuestro sistema. El modelo de dominio tiene como objetivo asegurar que se comprende el contexto en el que se tiene que desarrollar el software y establecer un vocabulario común entre los stakeholders del proyecto, cliente, los usuarios y desarrolladores, entre otros.

### Ejemplo
Para obtener el modelo de dominio del taller de reparaciones de vehículos, se ha hecho una reunión con el responsable del taller mecánico, donde se detalló el funcionamiento del mismo, cómo se registran los trabajos que hacen los mecánicos y qué vocabulario usan en sus labores diarias.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226901522-95543eba-9204-4cbf-8344-11fc196ed6c0.png" />
</p>
<div align="center">
  <em>Figura 1. Modelo de dominio junto a los objetos de dominio y sus relaciones</em>
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226903056-48c5bc17-cba7-4fd3-88c9-a40d23616af1.png" />
</p>
<div align="center">
  <em>Figura 2. iagrama de estados por los que pasa una intervención</em>
</div>

## Disciplina de requisitos
<table>
 <tbody>
	<tr>
		<td>Encontrar Actores y Casos de Uso</td>
	</tr>
	<tr>
		<td>Priorizar Casos de Uso</td>
	</tr>
	<tr>
		<td>Detallar Casos de Uso</td>
	</tr>
	<tr>
		<td>Prototipar Casos de Uso</td>
	</tr>
	<tr>
		<td>Estructurar la descripción de los Casos de Uso</td>
	</tr>
 </tbody>
</table>

### Actores y casos de uso identificados
<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226904201-b239a26c-31e6-4403-af75-c3126b204f74.png" />
</p>
<div align="center">
  <em>Figura 3. Casos de uso relacionados con la gestión de las intervenciones</em>
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226904323-03dd3e03-68f8-4f6c-951f-dfad54957255.png" />
</p>
<div align="center">
  <em>Figura 4. Casos de uso relacionados con la gestión de los mecánicos</em>
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226904360-b42041c6-2a80-4321-9337-f16c13f75d60.png" />
</p>
<div align="center">
  <em>Figura 5. Casos de uso relacionados con la gestión de los vehiculos</em>
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226904390-0b18d1d4-28ac-448d-92ed-3fc428f754d0.png" />
</p>
<div align="center">
  <em>Figura 6. Casos de uso relacionados con la gestión de los clientes</em>
</div>

### Diagrama de Contexto
El diagrama de contexto nos permite ver de una manera más general todo lo que se permite hacer en el sistema en función de los casos de uso identificados, y la trazabilidad que hay entre ellos. Hay casos de uso que solo se pueden realizar una vez finalizada la realización de otro caso de uso. Todos estos detalles quedan reflejados en el diagrama de contexto.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/226904785-9d476899-8937-4813-91b5-935f02f828db.png" />
</p>
<div align="center">
  <em>Figura 7. Contexto de casos de uso</em>
</div>

### Especificaciones de caso de uso
Mediante estos diagramas de estados se describe el intercambio de información entre el actor y el sistema, constan de un estado inicial, un estado final, una secuencia de acciones que marcan el camino principal (en verde) y secuencias de acciones para caminos alternativos, al fallar alguna validación o si el actor decidiera abortar la realización del caso de uso 

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233085563-f6bedeb8-0f21-4938-8225-385f20686828.png" />
</p>
<div align="center">
  <em>Figura 8. Especificación caso de uso login</em>
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233085922-7fbc26ff-40dd-4d37-95d3-9289989bdf53.png" />
</p>
<div align="center">
  <em>Figura 9. Especificación de caso de uso createIntervention</em>
</div>

### Prototipos de interfaz de usuario
A continuación, se presentan los prototipos de las interfaces de usuario que permiten el intercambio de información que se detalla en los diagramas de especificación de caso de uso vistos anteriormente. En los prototipos se detallan los elementos de interfaz de usuario más representativos para llevar a cabo los casos de uso.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233086467-9ad4c53c-0e2f-428a-9732-81a5f9551b48.png" />
</p>
<div align="center">
  <em>Figura 10. Web map con los prototipos de interfaces de usuario de la aplicación AgrimManager.</em>
</div>

***
[Gestor de taller mecánico AgrimManager](https://www.notion.so/Gestor-de-taller-mec-nico-AgrimManager-a8d44826c2494e15bcb235fc1019938d#cd1d79dbac4146888d6f57438e934567)
***
