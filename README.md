Prueba Técnica - Programador (Back-end)
La siguiente es una prueba para evaluar a los postulantes a programador Back-end. (NODEJS)

INTRODUCCIÓN
Este repositorio contiene una serie de requerimientos de un Caso Práctico, que busca evaluar las capacidades técnicas del candidato con respecto a las principales funciones y responsabilidades que se requieren dentro del área de Desarrollo de saana.

¿Qué se busca evaluar?
Principalmente los siguientes aspectos:

Creatividad para resolver los requerimientos,
Calidad del código entregado (estructura y buenas prácticas),
Eficiencia de los algoritmos entregados,
Familiaridad con Frameworks y plataformas de desarrollo.
IMPORTANTE
Recomendamos emplear un máximo de 3 (tres) horas y enviar todo lo que puedas.
Se requiere de una cuenta de GitHub para realizar este ejercicio.
Antes de comenzar a programar:
Realizar un Fork de este repositorio (https://github.com/ORCAapplicants/backend-test).
Clonar el fork a su máquina local git clone git@github.com:USERNAME/FORKED-PROJECT.git
Crear un branch en su cuenta de GitHub utilizando su nombre completo.
Al finalizar, existen 2 (dos) opciones para entregar su proyecto:
Realizar un Commit de su proyecto, enviar un Pull Request al branch con su NOMBRE, y notificar a la siguiente dirección de correo electrónico jesus.eduardo@saana.com.co.
Crear un archivo comprimido (.zip o .rar) de su proyecto y enviar a la siguiente dirección de correo electrónico jesus.eduardo@saana.com.co.




EJERCICIOS
Ejercicio
Se desea administrar el acceso de vehículos a un estacionamiento de pago. El estacionamiento no se encuentra automatizado, por lo que existe un empleado encargado de registrar las entradas y salidas de vehículos.

Los vehículos se identifican por su número de placa. Cuando un vehículo entra en el estacionamiento el empleado registra su entrada y al salir registra su salida y, en algunos casos, cobra el importe correspondiente por el tiempo de estacionamiento.

El importe cobrado depende del tipo de vehículo:

Los vehículos oficiales no pagan, pero se registran sus estancias para llevar el control. (Una estancia consiste en una hora de entrada y una de salida)
Los residentes pagan a final de mes a razón de 50COP el minuto. La aplicación irá acumulando el tiempo (en minutos) que han permanecido estacionados.
Los no residentes pagan a la salida del estacionamiento a razón de MXN$0.5 por minuto. Se prevé que en el futuro puedan incluirse nuevos tipos de vehículos, por lo que la aplicación desarrollada deberá ser fácilmente extensible en ese aspecto.
