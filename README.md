# notes-course-sql

<details>
<summary><b>Por qué aprender MySQL</b></summary>

Aprender MySQL, un sistema de gestión de bases de datos relacionales, puede ser beneficioso por varias razones:

1. **Popularidad y demanda**: MySQL es uno de los sistemas de gestión de bases de datos más populares y ampliamente utilizados en el mundo. Muchas empresas y organizaciones lo utilizan como su base de datos principal, lo que crea una gran demanda de profesionales que pueden administrarlo y utilizarlo eficazmente.
2. **Aplicaciones web y desarrollo**: MySQL se utiliza comúnmente en el desarrollo de aplicaciones web y sitios web dinámicos. Si deseas trabajar en el desarrollo web, conocer MySQL te permitirá interactuar con bases de datos y crear aplicaciones que almacenen y recuperen datos de manera eficiente.
3. **Escalabilidad**: MySQL es capaz de manejar grandes cantidades de datos y puede escalar para satisfacer las necesidades de aplicaciones en crecimiento. Aprender a diseñar y administrar bases de datos escalables es esencial en un entorno tecnológico cada vez más orientado a grandes volúmenes de información.
4. **Facilidad de uso**: Para aquellos que son nuevos en las bases de datos, MySQL es un buen punto de partida. Es conocido por ser relativamente fácil de aprender y tiene una comunidad activa que ofrece amplia documentación y tutoriales.
5. **Integración con lenguajes de programación**: MySQL se integra bien con varios lenguajes de programación populares como PHP, Python, Java y más. Esto permite que los datos almacenados en la base de datos se utilicen fácilmente en diversas aplicaciones y sistemas.
6. **Costo y código abierto**: MySQL es de código abierto y, en muchas situaciones, puede ser utilizado de forma gratuita, lo que lo hace atractivo para empresas y desarrolladores con presupuestos limitados.
7. **Compatibilidad**: MySQL sigue los estándares SQL, lo que significa que los conocimientos adquiridos en MySQL son transferibles a otros sistemas de gestión de bases de datos relacionales.
8. **Administración de datos**: Conocer MySQL te permitirá gestionar y mantener grandes cantidades de datos de manera eficiente y segura. Esto es importante para garantizar que los datos estén bien organizados, respaldados y protegidos.
</details>

<details>
<summary><b>Introducción a MySQL</b></summary>

MySQL es un sistema de gestión de bases de datos relacionales (RDBMS, por sus siglas en inglés) ampliamente utilizado en todo el mundo. Fue desarrollado por primera vez por Michael Widenius y David Axmark en 1994 y más tarde adquirido por Oracle Corporation. MySQL es una base de datos de código abierto y gratuita en muchas de sus ediciones, lo que ha contribuido a su amplia popularidad en la comunidad de desarrollo y en la industria.

Una base de datos relacional es una colección organizada de datos estructurados en tablas, donde cada tabla tiene filas y columnas. MySQL permite almacenar, organizar y administrar grandes cantidades de datos, lo que lo convierte en una opción popular para aplicaciones web y sistemas que requieren un acceso rápido y eficiente a la información.

Características principales de MySQL:

1. **Lenguaje SQL**: MySQL se basa en el lenguaje SQL (Structured Query Language), que es un lenguaje de consulta estándar utilizado para interactuar con bases de datos relacionales. A través de comandos SQL, puedes realizar operaciones como inserción, actualización, eliminación y consulta de datos.
2. **Multiplataforma**: MySQL es compatible con varias plataformas, lo que permite que se ejecute en diversos sistemas operativos, como Windows, macOS, Linux y más.
3. **Alta velocidad y rendimiento**: MySQL está optimizado para un alto rendimiento y puede manejar grandes cantidades de datos y solicitudes simultáneas.
4. **Seguridad**: MySQL ofrece características de seguridad robustas, como autenticación de usuarios, cifrado de datos y permisos de acceso, para garantizar la protección de la información almacenada.
5. **Replicación y alta disponibilidad**: MySQL permite la replicación de datos, lo que facilita la creación de copias de seguridad y la redundancia para garantizar la disponibilidad continua en caso de fallos.
6. **Escalabilidad**: MySQL es capaz de escalar vertical y horizontalmente para afrontar el crecimiento de los datos y la demanda de usuarios.
7. **Comunidad activa**: MySQL cuenta con una comunidad de desarrolladores y usuarios activos que proporcionan soporte, actualizaciones y mejoras constantes.

Para comenzar a utilizar MySQL, necesitarás instalar el software del servidor MySQL y un cliente MySQL en tu computadora. El servidor es responsable de almacenar y administrar los datos, mientras que el cliente te permite interactuar con la base de datos y ejecutar consultas SQL.

</details>

<details>
<summary><b>Instalación MySQL en windows</b></summary>

1. **Descarga del instalador**: Ve al sitio web oficial de MySQL (**https://dev.mysql.com/downloads/installer/**) y descarga el instalador de MySQL para Windows. Asegúrate de elegir la versión adecuada para tu sistema operativo (32 o 64 bits).
2. **Ejecutar el instalador**: Una vez que hayas descargado el instalador, haz doble clic en el archivo descargado para ejecutarlo.
3. **Seleccionar la configuración**: Al iniciar el instalador, te mostrará varias opciones para instalar componentes de MySQL. Para una instalación básica, puedes seleccionar "Developer Default" o "Server Only", que incluyen el servidor MySQL, las herramientas de desarrollo y otros componentes necesarios para empezar.
4. **Configuración de MySQL**: Durante la instalación, se te pedirá que configures la contraseña del usuario root de MySQL. Asegúrate de recordar esta contraseña, ya que la necesitarás para acceder al servidor MySQL.
5. **Elegir el tipo de configuración**: Puedes seleccionar entre "Standalone MySQL Server / Classic MySQL Replication" o "InnoDB Cluster". Si estás empezando, la primera opción es más adecuada.
6. **Iniciar la instalación**: Una vez que hayas seleccionado todas las opciones, haz clic en el botón "Execute" o "Next" para iniciar la instalación.
7. **Finalizar la instalación**: El instalador instalará todos los componentes seleccionados y configurará MySQL en tu sistema. Una vez que se complete la instalación, verás un mensaje de confirmación.
8. **Comprobar la instalación**: Para asegurarte de que MySQL se ha instalado correctamente, puedes abrir el "MySQL Command Line Client" desde el menú de inicio o ejecutar el comando **`mysql`** en la línea de comandos. Si se abre el cliente de línea de comandos de MySQL y te pide la contraseña del usuario root, significa que la instalación fue exitosa.

¡Listo! Ahora tienes MySQL instalado en tu computadora con Windows y estás listo para empezar a utilizarlo para crear y administrar bases de datos. Puedes utilizar el cliente de línea de comandos o interfaces gráficas como MySQL Workbench para interactuar con la base de datos de forma más visual.

</details>

<details>
<summary><b>Instalación MySQL en MacOS</b></summary>

La instalación de MySQL en macOS es relativamente sencilla y puede hacerse siguiendo estos pasos:

1. **Descarga del instalador**: Ve al sitio web oficial de MySQL (**https://dev.mysql.com/downloads/installer/**) y descarga el instalador de MySQL para macOS. Asegúrate de elegir la versión adecuada para tu sistema operativo.
2. **Montar el paquete de instalación**: Una vez que hayas descargado el instalador, haz doble clic en el archivo descargado para montar el paquete de instalación.
3. **Iniciar la instalación**: Después de montar el paquete, verás un archivo llamado "mysql-installer-community.pkg". Haz doble clic en este archivo para iniciar el asistente de instalación.
4. **Configuración del paquete de instalación**: El asistente de instalación te guiará a través de los pasos para configurar MySQL en tu macOS. Asegúrate de seleccionar "Developer Default" o "Server Only" para una instalación básica que incluya el servidor MySQL y las herramientas de desarrollo.
5. **Configuración de MySQL**: Durante la instalación, se te pedirá que configures la contraseña del usuario root de MySQL. Asegúrate de recordar esta contraseña, ya que la necesitarás para acceder al servidor MySQL.
6. **Finalizar la instalación**: Una vez que hayas completado todos los pasos del asistente de instalación, haz clic en "Install" para iniciar el proceso de instalación.
7. **Inicio del servidor MySQL**: Una vez que la instalación se haya completado con éxito, el servidor MySQL debería iniciarse automáticamente. Si no se inicia automáticamente, puedes iniciar el servidor manualmente desde las "Preferencias del Sistema" > "MySQL" > "Start MySQL Server".
8. **Comprobar la instalación**: Para asegurarte de que MySQL se ha instalado correctamente, puedes abrir el "MySQL Shell" desde la carpeta de aplicaciones o ejecutar el comando **`mysql`** en la terminal. Si se abre el cliente de línea de comandos de MySQL y te pide la contraseña del usuario root, significa que la instalación fue exitosa.

¡Listo! Ahora tienes MySQL instalado en tu macOS y puedes comenzar a utilizarlo para crear y administrar bases de datos. Puedes utilizar el cliente de línea de comandos o interfaces gráficas como MySQL Workbench para interactuar con la base de datos de forma más visual.

</details>

<details>
<summary><b>Creación de Bases de Datos y Tablas</b> </summary>

En MySQL, puedes crear bases de datos y tablas utilizando comandos SQL a través del cliente de línea de comandos o mediante una herramienta de administración gráfica como MySQL Workbench. A continuación, te mostraré cómo crear bases de datos y tablas utilizando el cliente de línea de comandos:

1. **Crear una base de datos**:

Para crear una nueva base de datos, puedes utilizar el comando **`CREATE DATABASE`** seguido del nombre que deseas asignarle. Por ejemplo, para crear una base de datos llamada "mi_base_de_datos", ejecuta el siguiente comando en el cliente de línea de comandos de MySQL:

```sql
CREATE DATABASE mi_base_de_datos;

```

1. **Seleccionar una base de datos**:

Antes de crear tablas, debes asegurarte de estar trabajando en la base de datos que acabas de crear. Para seleccionar la base de datos, utiliza el comando **`USE`** seguido del nombre de la base de datos. Por ejemplo:

```sql
USE mi_base_de_datos;

```

1. **Crear una tabla**:

Para crear una tabla dentro de la base de datos seleccionada, utiliza el comando **`CREATE TABLE`**. Define el nombre de la tabla y luego especifica las columnas y sus tipos de datos. Por ejemplo, crearemos una tabla llamada "libros" con algunas columnas para almacenar información sobre libros:

```sql
CREATE TABLE libros (
    id INT AUTO_INCREMENT PRIMARY KEY,
    titulo VARCHAR(100),
    autor VARCHAR(100),
    precio DECIMAL(8, 2),
    existencias INT
);

```

En este ejemplo, hemos creado una tabla llamada "libros" con las siguientes columnas:

- "id": un número de identificación único y autoincremental para cada registro.
- "titulo": una cadena de hasta 100 caracteres para almacenar el título del libro.
- "autor": una cadena de hasta 100 caracteres para almacenar el nombre del autor del libro.
- "precio": un número decimal con 8 dígitos en total y 2 decimales para almacenar el precio del libro.
- "existencias": un número entero para almacenar la cantidad de existencias del libro.

Una vez que hayas ejecutado los comandos anteriores, habrás creado una base de datos llamada "mi_base_de_datos" y una tabla llamada "libros" dentro de esa base de datos. Ahora puedes empezar a insertar datos en la tabla y realizar consultas para interactuar con la información almacenada.

</details>

<details>
<summary><b>INSERT, ALTER TABLE y SHOW CREATE</b> </summary>

1. **INSERT**:

El comando "INSERT" se utiliza para agregar nuevos registros (filas) a una tabla existente en la base de datos. Es como colocar nueva información en una tabla. La sintaxis básica del comando INSERT es la siguiente:

```sql
INSERT INTO nombre_de_la_tabla (columna1, columna2, columna3, ...)
VALUES (valor1, valor2, valor3, ...);
```

Por ejemplo, si tenemos una tabla llamada "personas" con las columnas "nombre", "edad" y "ciudad", podemos insertar un nuevo registro así:

```sql
INSERT INTO personas (nombre, edad, ciudad)
VALUES ('Juan', 30, 'Madrid');
```

Este comando añadirá un nuevo registro en la tabla "personas" con el nombre "Juan", edad "30" y ciudad "Madrid".

2. **ALTER TABLE**:

El comando "ALTER TABLE" se utiliza para modificar la estructura de una tabla existente. Puedes agregar nuevas columnas, eliminar columnas, cambiar el tipo de datos de una columna y más. La sintaxis básica del comando ALTER TABLE es la siguiente:

```sql
ALTER TABLE nombre_de_la_tabla
accion_a_realizar;
```

Por ejemplo, si queremos agregar una nueva columna "correo_electronico" a la tabla "personas", podemos usar este comando:

```sql
ALTER TABLE personas
ADD correo_electronico VARCHAR(100);
```

Esto agregará una nueva columna llamada "correo_electronico" a la tabla "personas" con un límite de 100 caracteres.

3. **SHOW CREATE TABLE**:

El comando "SHOW CREATE TABLE" se utiliza para ver la definición completa de una tabla, incluyendo todos los detalles de sus columnas y restricciones. La sintaxis es la siguiente:

```sql
SHOW CREATE TABLE nombre_de_la_tabla;
```

Por ejemplo, si queremos ver la definición de la tabla "personas", podemos ejecutar este comando:

```sql
SHOW CREATE TABLE personas;
```

Este comando mostrará la estructura completa de la tabla "personas", incluyendo el nombre de las columnas, los tipos de datos, las claves primarias, restricciones, etc.

</details>

<details>
<summary><b>SELECT, UPDATE y DELETE</b> </summary>

1. **SELECT**:

El comando "SELECT" se utiliza para recuperar datos de una tabla en la base de datos. Es como una consulta que le haces a la base de datos para obtener información específica. La sintaxis básica del comando SELECT es la siguiente:

```sql
SELECT columna1, columna2, columna3, ...
FROM nombre_de_la_tabla
WHERE condicion;
```

Por ejemplo, si tenemos una tabla llamada "empleados" con las columnas "nombre", "edad", "salario" y queremos obtener los nombres y salarios de todos los empleados mayores de 25 años, podemos usar este comando:

```sql
SELECT nombre, salario
FROM empleados
WHERE edad > 25;
```

2. **UPDATE**:

El comando "UPDATE" se utiliza para modificar registros existentes en una tabla. Es como actualizar la información de la tabla con nuevos valores. La sintaxis básica del comando UPDATE es la siguiente:

```sql
UPDATE nombre_de_la_tabla
SET columna1 = valor1, columna2 = valor2, ...
WHERE condicion;
```

Por ejemplo, si queremos aumentar el salario de un empleado específico en la tabla "empleados", podemos usar este comando:

```sql
UPDATE empleados
SET salario = salario * 1.10
WHERE nombre = 'Juan';
```

Este comando aumentará el salario de "Juan" en un 10%.

3. **DELETE**:

El comando "DELETE" se utiliza para eliminar registros de una tabla. Es como borrar información de la tabla de la base de datos. La sintaxis básica del comando DELETE es la siguiente:

```sql
DELETE FROM nombre_de_la_tabla
WHERE condicion;
```

Por ejemplo, si queremos eliminar a un empleado de la tabla "empleados" que ya no trabaja en la empresa, podemos usar este comando:

```sql
DELETE FROM empleados
WHERE nombre = 'Ana';
```

Este comando eliminará todas las filas que coincidan con la condición donde el nombre sea "Ana".

Recuerda que estos comandos son poderosos y deben utilizarse con cuidado para evitar la pérdida accidental de datos importantes. Siempre asegúrate de tener copias de seguridad adecuadas antes de realizar cambios significativos en la base de datos.
</details>

<details>
<summary><b>Condiciones en profundidad</b> </summary>


<details>
<summary><b>WHERE</b> </summary>

La cláusula WHERE se utiliza en la sentencia SELECT, UPDATE o DELETE para filtrar filas basadas en una condición específica. La sintaxis básica es la siguiente:

```sql
SELECT columna1, columna2, ...
FROM nombre_de_la_tabla
WHERE condicion;

```

Por ejemplo, para seleccionar todos los empleados con un salario mayor a 3000:

```sql
SELECT nombre, salario
FROM empleados
WHERE salario > 3000;

```

En este caso, la condición "salario > 3000" filtra solo aquellos registros donde el salario es mayor a 3000.
</details>

<details>
<summary><b>Operadores de comparación</b> </summary>

MySQL ofrece varios operadores de comparación que se pueden utilizar en las condiciones, como:

- **`=`**: igual a
- **`<>`** o **`!=`**: diferente de
- **`<`**: menor que
- **`>`**: mayor que
- **`<=`**: menor o igual que
- **`>=`**: mayor o igual que

Puedes combinar múltiples condiciones utilizando operadores lógicos como **`AND`** y **`OR`**. Por ejemplo:

```sql
SELECT nombre, edad
FROM empleados
WHERE salario > 3000 AND edad <= 35;
```

Esta consulta seleccionará empleados con un salario mayor a 3000 y una edad menor o igual a 35 años.
</details>

<details>
<summary><b>Operadores LIKE</b> </summary>

El operador **`LIKE`** se utiliza para realizar búsquedas de patrones en cadenas de texto. Puedes usar **`%`** para representar cualquier cantidad de caracteres y **`_`** para un solo carácter. Por ejemplo:

```sql
SELECT nombre
FROM empleados
WHERE nombre LIKE 'J%';
```

Esta consulta seleccionará empleados cuyos nombres comiencen con la letra 'J'.
</details>

<details>
<summary><b>IN y NOT IN</b> </summary>

Los operadores **`IN`** y **`NOT IN`** se utilizan para comparar un valor con una lista de valores. Por ejemplo:

```sql
SELECT nombre
FROM empleados
WHERE departamento IN ('Ventas', 'Marketing');
```

Esta consulta seleccionará empleados cuyo departamento sea "Ventas" o "Marketing".
</details>

<details>
<summary><b>IS NULL e IS NOT NULL</b> </summary>

Estos operadores se utilizan para verificar si un valor es nulo o no nulo. Por ejemplo:

```sql
SELECT nombre
FROM empleados
WHERE telefono IS NULL;
```

Esta consulta seleccionará empleados que no tengan un número de teléfono registrado.
</details>

</details>

<details>
<summary><b>Seleccionando columnas</b> </summary>

Para seleccionar columnas específicas en MySQL, utilizamos la cláusula **`SELECT`**. La sintaxis básica para seleccionar columnas es la siguiente:

```sql
SELECT columna1, columna2, columna3, ...
FROM nombre_de_la_tabla;
```

Donde **`columna1`**, **`columna2`**, etc., son los nombres de las columnas que deseas recuperar de la tabla **`nombre_de_la_tabla`**.

Por ejemplo, si tenemos una tabla llamada "empleados" con las columnas "nombre", "edad", "departamento" y "salario", y queremos seleccionar solo los nombres y salarios de todos los empleados, utilizaríamos el siguiente comando:

```sql
SELECT nombre, salario
FROM empleados;
```

Esto nos dará un resultado que contiene solo las columnas "nombre" y "salario" de la tabla "empleados".

También puedes seleccionar todas las columnas de una tabla utilizando el asterisco **`*`**. Por ejemplo:

```sql
SELECT *
FROM empleados;
```

Esto seleccionará todas las columnas de la tabla "empleados".

Adicionalmente, puedes utilizar funciones de agregación como **`SUM`**, **`COUNT`**, **`AVG`**, **`MIN`** y **`MAX`** en la cláusula **`SELECT`** para realizar cálculos en los datos de una columna o grupo de columnas. Por ejemplo:

```sql
SELECT COUNT(*) AS total_empleados, AVG(salario) AS salario_promedio
FROM empleados;
```

Esta consulta devolverá el número total de empleados y el salario promedio de todos los empleados en la tabla "empleados".

Recuerda que al seleccionar columnas, puedes utilizar alias con la cláusula **`AS`** para cambiar el nombre de las columnas en los resultados, como se muestra en el ejemplo anterior. Esto puede ser útil para hacer que los resultados sean más legibles y comprensibles.
</details>

<details>
<summary><b>Agregar varios registros a una base de datos</b> </summary>

Para agregar varios registros (filas) a una base de datos en MySQL, puedes utilizar el comando **`INSERT INTO`** junto con la sintaxis **`VALUES`** para insertar múltiples conjuntos de datos en una sola sentencia. Esto te permite agregar varios registros de una vez en lugar de ejecutar un comando **`INSERT`** por cada registro individual. Aquí tienes un ejemplo de cómo hacerlo:

Supongamos que tienes una tabla llamada "productos" con las siguientes columnas: "id" (número de identificación), "nombre" (nombre del producto) y "precio" (precio del producto).

Para agregar varios productos a la tabla "productos" al mismo tiempo, puedes hacer lo siguiente:

```sql
INSERT INTO productos (nombre, precio)
VALUES
  ('Producto A', 19.99),
  ('Producto B', 24.50),
  ('Producto C', 12.75),
  ('Producto D', 8.99);
```

En este ejemplo, hemos utilizado una sola sentencia **`INSERT INTO`** con múltiples conjuntos de datos separados por comas en la cláusula **`VALUES`**. Cada conjunto de datos corresponde a un nuevo registro que queremos agregar a la tabla "productos". Cada conjunto de datos contiene los valores para las columnas "nombre" y "precio" respectivamente.

Cuando ejecutes esta sentencia, se agregarán los cuatro productos a la tabla "productos" en una sola operación.

Es importante asegurarse de que los valores que insertes cumplan con las restricciones y tipos de datos definidos para cada columna en la tabla. También es recomendable hacer copias de seguridad de la base de datos antes de realizar operaciones masivas de inserción, para evitar pérdida accidental de datos en caso de errores.
</details>

<details>
<summary><b>left join</b> </summary>

La cláusula **`LEFT JOIN`** en MySQL se utiliza para combinar dos tablas en una consulta, recuperando todas las filas de la tabla de la izquierda y las filas coincidentes de la tabla de la derecha. Si no hay coincidencias en la tabla de la derecha, se mostrarán valores NULL en las columnas correspondientes. Esta operación es útil cuando deseas recuperar información de una tabla principal junto con información relacionada de otra tabla.

La sintaxis básica del **`LEFT JOIN`** es la siguiente:

```sql
SELECT columnas
FROM tabla_izquierda
LEFT JOIN tabla_derecha
ON tabla_izquierda.columna = tabla_derecha.columna;
```

Por ejemplo, supongamos que tienes dos tablas: "productos" y "categorias". La tabla "productos" contiene información sobre los productos, y la tabla "categorias" contiene información sobre las categorías a las que pertenecen los productos. Queremos recuperar todos los productos junto con sus categorías correspondientes, incluso si algunos productos no tienen una categoría asociada.

```sql
SELECT productos.nombre, productos.precio, categorias.nombre AS categoria
FROM productos
LEFT JOIN categorias
ON productos.categoria_id = categorias.id;
```

En este ejemplo, estamos seleccionando las columnas "nombre" y "precio" de la tabla "productos" y la columna "nombre" de la tabla "categorias" (que hemos renombrado como "categoria" usando **`AS categoria`**). Hacemos un **`LEFT JOIN`** entre las dos tablas en la columna "categoria_id" de la tabla "productos" y la columna "id" de la tabla "categorias".

El resultado mostrará todos los productos junto con sus precios y la categoría a la que pertenecen. Si un producto no tiene una categoría asociada (es decir, si no hay una coincidencia en la tabla "categorias"), la columna "categoria" mostrará un valor NULL para ese producto.

El **`LEFT JOIN`** es útil cuando deseas asegurarte de obtener todas las filas de la tabla de la izquierda, incluso si no hay coincidencias en la tabla de la derecha. Esto te permite tener una visión completa de los datos incluso si algunos registros no tienen datos relacionados en la otra tabla.
</details>