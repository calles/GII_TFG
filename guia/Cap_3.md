# Capítulo 3

## Análisis y Diseño
En las actividades del análisis, se refinan y estructuran los casos de uso especificados. El propósito de las actividades del análisis es conseguir una comprensión más precisa de los requisitos, evitar redundancias e inconsistencias. En el análisis los requisitos se empiezan a traducir en funcionalidades del sistema y clases

### Análisis de la arquitectura
<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233075604-dfb711bb-a84e-486c-b519-c609e1d73ba7.png" />
</p>
<div align="center">
  <em>Diagrama de la arquitectura MVC</em>
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233076401-e08a7baa-1f9e-4ec9-8df0-eab7e5e2b3a2.png" />
</p>
<div align="center">
  <em>Diagrama de clases de MVC</em>
</div>

### Análisis de casos de uso
Mediante los diagramas de colaboración se identifican las clases modelo, vista y controlador, esenciales para llevar a cabo el caso de uso concreto. Se identifican cuales son las responsabilidades más importantes de esas clases y mediante qué métodos se relacionan entre ellas

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233089268-a49b67b2-0838-4ba0-a62d-6dee0f10bbc2.png" />
</p>
<div align="center">
  <em>Diagrama de colaboración del caso de uso Login</em>
</div>

### Análisis de clases
Una vez analizados los casos de uso, lo siguiente es revisar los diagramas de colaboración obtenidos e ir localizando con qué clases se relaciona cada una de las clases y qué mensajes se lanzan entre ellas.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233092767-55950517-1e80-41bc-9b7d-ac031f1b32eb.png" />
</p>
<div align="center">
  <em>Diagrama de clases de la clase LoginController y sus relaciones</em>
</div>

### Diseño de la arquitectura
Los objetivos del diseño de la arquitectura son identificar clases arquitectónicas significativas de diseño, subsistemas específicos de la aplicación e identificar el software y las tecnologías en las que se va a apoyar. Este software pueden ser servidores, navegadores web o componentes software, entre otros.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22343642/233095433-436c3695-4b3d-4aa5-b129-3b66937a85af.png" />
</p>
<div align="center">
  <em>Aplicación web multipágina, cliente y servidor esctructurado por capas</em>
</div>

#### Capa de presentación, Capa de negocio y Capa de datos
[Estructura MVC](https://user-images.githubusercontent.com/22343642/233102062-85cb6b2e-47b7-466f-b1ba-d77ac3b97bf7.png)
[Ejemplo de diagrama de paquetes](https://user-images.githubusercontent.com/22343642/233102671-107bc8a8-1537-4940-b878-dbbce6525578.png)




***
[Gestor de taller mecánico AgrimManager](https://www.notion.so/Gestor-de-taller-mec-nico-AgrimManager-a8d44826c2494e15bcb235fc1019938d?pvs=4#0a1fbda23e2e4946ae7ae12bcd724a9d)
***
