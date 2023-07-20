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
<summary><b>Instalación MySQL en windows</b>

1. **Descarga del instalador**: Ve al sitio web oficial de MySQL (**https://dev.mysql.com/downloads/installer/**) y descarga el instalador de MySQL para Windows. Asegúrate de elegir la versión adecuada para tu sistema operativo (32 o 64 bits).
2. **Ejecutar el instalador**: Una vez que hayas descargado el instalador, haz doble clic en el archivo descargado para ejecutarlo.
3. **Seleccionar la configuración**: Al iniciar el instalador, te mostrará varias opciones para instalar componentes de MySQL. Para una instalación básica, puedes seleccionar "Developer Default" o "Server Only", que incluyen el servidor MySQL, las herramientas de desarrollo y otros componentes necesarios para empezar.
4. **Configuración de MySQL**: Durante la instalación, se te pedirá que configures la contraseña del usuario root de MySQL. Asegúrate de recordar esta contraseña, ya que la necesitarás para acceder al servidor MySQL.
5. **Elegir el tipo de configuración**: Puedes seleccionar entre "Standalone MySQL Server / Classic MySQL Replication" o "InnoDB Cluster". Si estás empezando, la primera opción es más adecuada.
6. **Iniciar la instalación**: Una vez que hayas seleccionado todas las opciones, haz clic en el botón "Execute" o "Next" para iniciar la instalación.
7. **Finalizar la instalación**: El instalador instalará todos los componentes seleccionados y configurará MySQL en tu sistema. Una vez que se complete la instalación, verás un mensaje de confirmación.
8. **Comprobar la instalación**: Para asegurarte de que MySQL se ha instalado correctamente, puedes abrir el "MySQL Command Line Client" desde el menú de inicio o ejecutar el comando **`mysql`** en la línea de comandos. Si se abre el cliente de línea de comandos de MySQL y te pide la contraseña del usuario root, significa que la instalación fue exitosa.

¡Listo! Ahora tienes MySQL instalado en tu computadora con Windows y estás listo para empezar a utilizarlo para crear y administrar bases de datos. Puedes utilizar el cliente de línea de comandos o interfaces gráficas como MySQL Workbench para interactuar con la base de datos de forma más visual.

</summary>

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
<summary><b>Creación de Bases de Datos y Tablas</b>

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

</summary>

</details>