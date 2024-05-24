# apipruebaocho
Api Prueba Net 8 de PLE es una API ágil y escalableon múltiples plataformas.
Api Prueba Net 8 
Api Prueba Net 8 es una API RESTful construida con .NET Core 8, que proporciona endpoints para interactuar con un sistema de administración de tareas. Permite a los usuarios crear, leer, actualizar y eliminar tareas, así como asignarlas a diferentes proyectos.
Características

Autenticación basada en JWT para proteger los endpoints.
Documentación de la API con Swagger.
Implementación del patrón de diseño Repository para interactuar con la base de datos.
Uso de EntityFrameworkCore para el acceso a datos y migraciones.
Validación de modelos de entrada y respuestas con FluentValidation.
Manejo de errores y excepciones globales.
Pruebas unitarias y de integración con xUnit y Moq.
Configuración mediante archivos appsettings.json y variables de entorno.

Tecnologías utilizadas

.NET Core 8
ASP.NET Core Web API
EntityFrameworkCore
SQL Server
FluentValidation
Swagger
xUnit
Moq

Requisitos

.NET Core 8 SDK
SQL Server o cualquier otra base de datos compatible con EntityFrameworkCore

Configuración

Clona este repositorio
Abre la solución en Visual Studio o tu IDE preferido
Configura la cadena de conexión a la base de datos en appsettings.json
Ejecuta las migraciones de EntityFrameworkCore para crear la base de datos
Construye y ejecuta la aplicación

Uso
Una vez que la aplicación esté en ejecución, puedes acceder a la documentación de Swagger en https://localhost:5001/swagger. Aquí encontrarás una descripción detallada de todos los endpoints disponibles y podrás probarlos directamente desde la interfaz de Swagger.
Contribuciones
Las contribuciones son bienvenidas. Por favor, sigue las pautas de contribución y el código de conducta de este proyecto.
