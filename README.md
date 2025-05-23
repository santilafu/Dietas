# Actividad 1 – Unidad 9: Conexión con base de datos MySQL desde Java

En esta primera actividad he creado una base de datos llamada `Empresa` en MySQL Workbench.  
Dentro de esa base de datos, he creado una tabla llamada `Dietas` con los campos necesarios: id, empleado, departamento, cantidad y concepto.

Luego he creado un proyecto Java en IntelliJ, al que le he añadido el conector JDBC oficial de MySQL.  
He programado una clase que se llama `ConexionBD`, donde hago la conexión con la base de datos utilizando `DriverManager`.

Para probar si la conexión funciona correctamente, he creado una clase `Main` que simplemente llama al método `conectar()` y muestra un mensaje por consola.

Al ejecutar el proyecto, he comprobado que la conexión se realiza correctamente y que no hay errores.
