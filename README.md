# Curso-RestAssured
Curso de Rest Assured


### **Temario Completo y Actualizado de REST Assured con IntelliJ IDEA**

#### **1. Introducción a REST Assured**✅
   - **1.1 ¿Qué es REST Assured?**✅
     - Definición: Biblioteca Java para pruebas automatizadas de APIs RESTful.✅
     - Ventajas: Sintaxis clara, soporte para JSON/XML, integración con frameworks de pruebas.✅
     - Comparación con herramientas como Postman, SoapUI o Karate.✅

   - **1.2 Conceptos básicos de APIs REST**✅
     - Principios de REST: Recursos, métodos HTTP, sin estado, representaciones.✅
     - Métodos HTTP: GET, POST, PUT, DELETE, PATCH, OPTIONS, HEAD. ✅
     - Códigos de estado HTTP: 200 (OK), 201 (Created), 400 (Bad Request), 404 (Not Found), 500 (Server Error), etc.✅
     - Formatos de datos: JSON, XML, y cómo manejarlos en pruebas.✅

   - **1.3 Por qué usar IntelliJ IDEA para REST Assured**✅
     - Beneficios: Autocompletado, depuración avanzada, integración con Maven/Gradle, soporte para plugins.✅
     - Comparación con otros IDEs (Eclipse, VS Code).✅

#### **2. Configuración del entorno en IntelliJ IDEA**✅
   - **2.1 Requisitos previos**✅
     - Instalación de Java (JDK 17 o superior recomendado).  ✅
        Agregar este recurso al PATH de tu sistema ✅
     - Descarga e instalación de IntelliJ IDEA (Community o Ultimate).✅
     - Configuración de Maven o Gradle como sistema de construcción.✅

   - **2.2 Creación de un proyecto Maven en IntelliJ IDEA**✅
     - Crear un nuevo proyecto Maven: File > New > Project > Maven.✅
     - Configurar el archivo `pom.xml` con las dependencias de REST Assured✅
     - Agregar dependencias adicionales: TestNG o JUnit para pruebas, JSON Schema Validator, etc.✅

   - **2.4 Instalación de plugins en IntelliJ IDEA**✅
     - Plugins recomendados: Maven Helper, Lombok, JSON Viewer, TestNG/JUnit.✅
     - Configuración de atajos y formato de código para pruebas.✅

   - **2.5 Verificación del entorno**✅
     - Sincronizar el proyecto en IntelliJ (Maven/Gradle).✅
     - Crear una clase de prueba básica para validar la configuración.✅

#### **3. Fundamentos de REST Assured**✅
   - **3.1 Estructura básica de una prueba**✅
     - Sintaxis: `given()`, `when()`, `then()`.`✅

   - **3.2 Configuración de la base URI y parámetros**✅
     - Establecer `baseUri`, `basePath` y puertos.✅
     - Uso de parámetros de consulta (`queryParam`) y parámetros de ruta (`pathParam`).✅

   - **3.3 Métodos HTTP en REST Assured**✅
     - Implementación de GET, POST, PUT, DELETE, PATCH.✅

#### **4. Validaciones en REST Assured**✅
   - **4.1 Validación de códigos de estado**✅
     - Uso de `statusCode()`, `statusLine()`.✅

   - **4.2 Validación de cuerpo de respuesta**✅
     - Uso de Hamcrest Matchers: `equalTo`, `hasItems`, `containsString`.✅
     - Extracción de datos con `extract()` para validaciones personalizadas.✅

   - **4.3 Validación de esquemas JSON**✅
     - Configuración de `json-schema-validator` en IntelliJ IDEA.✅

   - **4.4 Manejo de headers y cookies**✅
     - Validar headers (`header()`, `headers()`).
     - Enviar y validar cookies.✅

#### **5. Configuraciones avanzadas en REST Assured**✅
  https://httpbin.org/#/
   - **5.1 Autenticación**✅
     - Autenticación básica, OAuth 2.0, API Keys.✅
     - Configuración en IntelliJ IDEA:✅

   - **5.2 Manejo de proxies y SSL**✅
     - Configuración de proxies y certificados SSL en IntelliJ.✅

   - **5.3 Filtros personalizados**✅
     - Crear filtros para logging o transformación de solicitudes/respuestas.

   - **5.4 Configuración global**✅
     - Uso de `RestAssuredConfig` para timeouts, codificaciones, etc.✅



