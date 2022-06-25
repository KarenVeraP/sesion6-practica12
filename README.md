# Práctica 12 - Base de datos SQL

Abrimos el Cloud Shell de Azure e introducimos el siguiente comando
_git clone https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals dp-900_

![Práctica 12 - parte 1](imagenes\p12p1.png)

Usamos los comandos _ls_ y _cd dp-900/sql_, para luego usar _bash setup.sh_ y la base de datos comenzará a crearse.

![Práctica 12 - parte 2](imagenes\p12p2.png)

En un grupo de recursos de creará un SQL server, una cuenta de almacenamiento y una Base de datos SQL.

![Práctica 12 - parte 3](imagenes\p12p3.png)

Abrimos la base de datos SQL y en información general elegimos _Establecer firewall de servidor_.

![Práctica 12 - parte 4](imagenes\p12p4.png)

Seleccionamos "Agregar la dirección OPv4 del cliente" y guardamos.

![Práctica 12 - parte 5](imagenes\p12p5.png)

Ahora, en la base de datos, buscamos el Editor de consultas (versión preliminar).

![Práctica 12 - parte 6](imagenes\p12p6.png)

Iniciamos sesión.

![Práctica 12 - parte 7](imagenes\p12p7.png)

Podemos ver las tablas que se crearon.

![Práctica 12 - parte 8](imagenes\p12p8.png)

En la terminal ejecutamos el comando 
SELECT * FROM Inventory
Para ver lo que hay en la tabla de inventario.

![Práctica 12 - parte 9](imagenes\p12p9.png)

Con SELECT * FROM CustomerOrder podemos ver a los clientes y sus órdenes.

![Práctica 12 - parte 10](imagenes\p12p10.png)

Para agragar un valor al inventario podemos usar el comando:
INSERT INTO Inventory (Id, Name, Stock) values(7, 'Strawberry', 500);

![Práctica 12 - parte 11](imagenes\p12p11.png)

Veremos que se agrega a la taba un nuevo renglón.

![Práctica 12 - parte 12](imagenes\p12p12.png)