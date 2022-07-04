# Control de Acceso de Vehículos (CavAll) &nbsp; NOTA: 10

TFG de Control de Acceso a Vehículos desarrollado por Adrian Lozano Lastras en 2º de Desarrollo de Aplicaciones Multiplataforma


## Resumen 📋

**Proyecto Final del Ciclo Formativo de Grado Superior de Desarrollo de Aplicaciones Multiplataforma, Control de Acceso de Vehículos.**

El presente proyecto pretende desarrollar un sistema para el reconocimiento de matrículas, utilizando visión artificial, que permita detectar automáticamente las matrículas para poder controlar el acceso a una instalación de los diferentes vehículos que deseen acceder, verificando si estos están autorizados o no para poder acceder a un aparcamiento, mejorando de esta forma la seguridad en una empresa, centro, edificio, institución ,etc.


Consta de dos partes, una parte de cliente y otra parte de servidor.

El cliente será el encargado de realizar el reconocimiento de las matriculas, validándolas y realizando peticiones al servidor para saber si dichas matrículas tienen o no acceso a la instalación, mostrando una notificación con la matrícula del vehículo indicando si tiene o no permiso. Para ello se ha realizado un programa ejecutable que conectado a una cámara permita el reconocimiento de matrículas.

El servidor se encargará de obtener las matriculas enviadas por el cliente para cotejarlas con la base de datos y verificarlas, una vez hecho le devuelve una respuesta al cliente y en caso de que la matricula este cotejada se registrará su entrada o salida correspondiente. Para ello se ha realizado una aplicación web que permita realizar las diferentes consultas de las entradas y salidas realizadas, y los vehículos y propietarios registrados.



**Si desea ver el código y tener las credenciales necesarias del proyecto contacteme**



## Desarrollado con 🛠️

**Cliente**
* Visual Studio Code
* Python
* ANPR, OCR y Visión Artificial

**Servidor**
* Visual Studio 2022
* .NET 5
* C#
* SQL Server


## Vídeo Demostración 🚀

* https://youtu.be/YLT_4uDtXdI


## Autor ✒️

* **Adrian Lozano Lastras** 
- https://www.linkedin.com/in/adrianlozanolastras/
- https://github.com/AdrianLozano96
