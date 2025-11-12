markdown Copiar# API REST para Gestión de Productos

## Descripción del Proyecto
Esta es una API REST desarrollada con **Spring Boot** para la gestión de productos en un sistema de e-commerce. La API permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre productos, aplicando arquitectura en capas, validaciones, manejo de errores, persistencia con Spring Data JPA y documentación con Swagger/OpenAPI.

---

## Tecnologías Utilizadas
- **Java 17**
- **Spring Boot 3.5.7**
- **Spring Data JPA**
- **H2 Database** (base de datos en memoria)
- **Lombok** (para reducir código boilerplate)
- **SpringDoc OpenAPI** (para documentación con Swagger)
- **Maven** (gestión de dependencias)

---

## Instrucciones para Clonar y Ejecutar

### Requisitos Previos
- Java 17 instalado.
- Maven instalado.
- IDE (IntelliJ IDEA, Eclipse, etc.).

### Pasos para Ejecutar el Proyecto
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git

Navega al directorio del proyecto:
bash Copiarcd tu-repositorio

Compila y ejecuta el proyecto con Maven:
bash Copiarmvn clean install
mvn spring-boot\:run

La aplicación estará disponible en:
 Copiarhttp://localhost:8080



Tabla de Endpoints
Método HTTPRutaDescripciónGET/api/productosLista todos los productosGET/api/productos/{id}Obtiene un producto por su IDGET/api/productos/categoria/{categoria}Filtra productos por categoríaPOST/api/productosCrea un nuevo productoPUT/api/productos/{id}Actualiza un producto completoPATCH/api/productos/{id}/stockActualiza el stock de un productoDELETE/api/productos/{id}Elimina un producto

Instrucciones para Acceder a Swagger UI y Consola H2
Swagger UI

Accede a la documentación interactiva de la API en:
 Copiarhttp://localhost:8080/swagger-ui.html


Consola H2

Accede a la consola de la base de datos H2 en:
 Copiarhttp://localhost:8080/h2-console

Usa los siguientes datos para conectarte:

JDBC URL: jdbc:h2:mem:productosdb
Usuario: sa
Contraseña: (dejar vacío)




Conclusiones Personales
Durante el desarrollo de este proyecto, aprendí a:

Diseñar y construir una API REST completa desde cero.
Aplicar correctamente los métodos HTTP según su propósito.
Implementar una arquitectura en capas profesional.
Trabajar con DTOs para desacoplar las capas de presentación y dominio.
Validar datos de entrada con Bean Validation.
Manejar errores de forma centralizada y profesional.
Documentar APIs con Swagger/OpenAPI.
Probar endpoints de forma interactiva usando Swagger UI.


Autor

Nombre: Joaquín Funes
Legajo: 50909

