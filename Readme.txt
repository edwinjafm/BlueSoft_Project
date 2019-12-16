PRUEBA TECNICA .NET CORE BIBLIOTECA DESARROLLADA POR: EDWIN JAVIER FIGUEROA MUÑOZ

Requerimiento Funcionales

1. Crear/Editar/Eliminar Categoria => COMPLETADO
• Nombre - varchar(50)
• Descripción - varchar(50)

2. Crear/Editar/Eliminar Autor => COMPLETADO
• Nombre - varchar(50)
• Apellidos - varchar(50)
• Fecha de nacimiento - date

3. Crear/Editar/Eliminar libro => COMPLETADO (Para registrar un libro primero deben crearse categorias y autores. Pendiente la homologacion de los diccionarios).
• Nombre del libro - varchar(50)
• Autor del libro (Autocomplete) - bigint	
• Categoría (Lista) - bigint
• ISBN - varchar(50)

4. Buscador de libros COMPLETADO (Pendiente categoria y autor).
• Por Nombre
• Por Categoria
• Por Autor

Requerimientos No Funcionales.

• Se debe crear un API REST construido usando el framework .NET Core 2.2 => COMPLETADO

• El acceso a datos debe ser por medio del ORM Entity Framework Core usando Code First 
(La solución debe contener todos los archivos de migración que se usen) => COMPLETADO

• La interfaz gráfica debe ser construida usando framework Angular 7 o superior => COMPLETADO

• La aplicación debe ser una arquitectura de N-capas => COMPLETADO

• El API debe contar con un mecanismo de auditoria a base de archivos de texto. Por ejemplo, Log4Net. => PENDIENTE

• Se puede usar cualquier motor de base de datos relacional. => COMPLETADO (SQL 2017 VS18.4)

• Se puede usar el IDE de preferencia (VS Community o VS Code) => COMPLETADO (VS ENTERPRISE 2019 Y VS CODE)


Entregables

1. Código fuente en algún repositorio accesible: GitHub, GitLab, etc. Se debe enviar la URL para poder descargar la solución.
=> COMPLETADO 
(Se crea un repositorio en GitHub llamado BlueSoft_Project donde se sube una carpeta comprimida 
en 3 partes debido a las resticciones de tamaño. La carpeta contiene el archivo de la solucion llamado "WebApiLibraryProject.sln", 
su respectiva carpeta con todos sus fuentes dentro de la carpeta llamada "WebApiLibraryProject" y la carpeta "LibraryPresentation" 
donde estan localizados los fuentes del proyecto realizado con Angular7)

2. Modelo relacional de la base de datos.
=> COMPLETADO 

3. Readme con las instrucciones de compilación, ejecución de migraciones y ejecución del proyecto.
=> COMPLETADO 
1. Abrir el archivo de la solucion llamado "WebApiLibraryProject.sln", esto abrira el visual studio.
2. Abrir Package Manager Console (Tools / NuGet Package Manager / Package Manager Console y clic sobre este).
3. Digitar en la consola el siguiente comando y luego enter: Update-Database 
4. Con el anterior comando la base de datos fue creada.
5. Abrir el visual studio Core para ejecutar el proyecto de Angular.
6. En la ventana TERMINAL de Visual Studio Core ejecutar el comando: ng serve
7. Volver al Visual Studio e iniciar la ejecucion del proyecto con el metodo abreviado: Ctrl + F5.
8. En cualquier navegador digitar la siguiente direccion para dar inicio al proyecto: http://localhost:4200/
9. Fin.


Cualquier duda o inquietud por favor no dude en contactarme.

Quedo atento a sus comentarios.


Cordialmente,

Edwin Javier Figueroa Muñoz
Celular: 301 4 72 40 58
Correo: edwinjafm@hotmail.com 
