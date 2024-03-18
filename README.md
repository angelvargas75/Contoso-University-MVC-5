# Documentación de la Aplicación Contoso University

## Descripción

La aplicación Contoso University es un ejemplo práctico que demuestra el uso de Entity Framework en una aplicación web de MVC 5. La aplicación está diseñada para gestionar una universidad ficticia llamada "Contoso University". Los principales escenarios cubiertos incluyen la gestión de cursos, departamentos, estudiantes e instructores.

## Funcionalidades Principales

### Administración de Cursos

- La aplicación permite la creación, edición, eliminación y visualización de cursos.
- Los cursos están asociados a departamentos y pueden tener varios instructores.

### Administración de Departamentos

- Los departamentos pueden ser creados, editados, eliminados y visualizados.
- Cada departamento tiene un administrador y una lista de cursos asociados.

### Administración de Estudiantes e Instructores

- Los estudiantes e instructores pueden ser creados, editados, eliminados y visualizados.
- Los instructores pueden estar asociados a uno o varios cursos.

### Funcionalidades Adicionales

- Control de simultaneidad para evitar conflictos de actualización de datos.
- Uso de procedimientos almacenados para realizar operaciones específicas en la base de datos.
- Gestión de relaciones muchos a muchos entre cursos e instructores.

## Arquitectura de la Aplicación

La aplicación Contoso University sigue una arquitectura de tres capas:

1. **Capa de Presentación (MVC)**: Maneja la interfaz de usuario y las interacciones del usuario. Incluye controladores, vistas y modelos de vista.
   
2. **Capa de Negocio (Servicios)**: Contiene la lógica de negocio de la aplicación. Gestiona las operaciones relacionadas con la base de datos y la lógica de aplicación.
   
3. **Capa de Acceso a Datos (Entity Framework)**: Interactúa directamente con la base de datos a través de Entity Framework. Incluye el contexto de datos, entidades y configuraciones de mapeo.


## Diagrama del diseñador de entidades
<p align="center">
  <img src="https://i.ibb.co/3N5zzJn/Contoso-Models1.png" alt="Contoso 1">
</p>
<p align="center">
  <img src="https://i.ibb.co/59VtfWs/Contoso-Models2.png" alt="Contoso 2">
</p>
<p align="center">
  <img src="https://i.ibb.co/fkZ13fM/Contoso-Models3.jpg" alt="Contoso 3">
</p>


## Requisitos del Sistema

- ASP.NET MVC 5
- NET Framework 4.8
- Entity Framework 6 (Code First)
- Visual Studio 2019 o superior
- SQL Server (LocalDB o instancia de servidor)

## Instalación y Ejecución

1. Clona o descarga el repositorio de la aplicación Contoso University desde el repositorio oficial de Microsoft en GitHub.
   
2. Abre el proyecto en Visual Studio.
   
3. Asegúrate de que la cadena de conexión a la base de datos esté configurada correctamente en el archivo `Web.config`.

4. Compila la solución y ejecuta la aplicación.

## Conclusión

La aplicación Contoso University proporciona un ejemplo práctico y completo de cómo utilizar Entity Framework en una aplicación web de ASP.NET MVC 5. Los conceptos cubiertos en esta aplicación son fundamentales para comprender el desarrollo de aplicaciones web modernas utilizando tecnologías Microsoft.

## Enlace

[Tutorial: Introducción a Entity Framework 6 Code First con MVC 5](https://learn.microsoft.com/es-es/aspnet/mvc/overview/getting-started/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application)
