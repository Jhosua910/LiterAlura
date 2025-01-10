# **Book Finder App**  
📚 *Una aplicación para buscar libros usando una API externa.*

## **Descripción**  
Book Finder App es una aplicación backend desarrollada en Java que permite a los usuarios buscar libros utilizando una API externa. Los resultados se procesan y almacenan en una base de datos PostgreSQL para consultas rápidas y análisis.

---

## **Características**  
- 🔍 Búsqueda de libros basada en título, autor o categoría.  
- 🌐 Integración con una API externa para obtener información actualizada de libros.  
- 🗄️ Almacenamiento en **PostgreSQL** para consultas persistentes.  
- 📜 Manejo eficiente de datos JSON con **Jackson**.  
- 📖 Escalabilidad para integrar más funcionalidades en el futuro.

---

## **Capturas de Pantalla**  
<!-- Agrega aquí capturas de la interfaz de Swagger o ejemplos de respuestas JSON -->
![Ejemplo de respuesta JSON](/assets/screenshot0.png)
![Ejemplo de respuesta JSON](/assets/screenshot1.png)

---

## **Tecnologías Usadas**  
- ☕ **Java 17**  
- 🌱 **Spring Boot**  
- 🛠️ **Maven**  
- 📜 **Jackson** para el manejo de datos JSON.  
- 🗄️ **PostgreSQL** como base de datos relacional.  

---

## **Instalación y Uso**

### **1. Requisitos Previos**
- Java 17 instalado.  
- Maven configurado.  
- PostgreSQL instalado y configurado.  

### **2. Configuración de PostgreSQL**
1. Crea una base de datos llamada `book_finder`.  
2. Configura las credenciales en el archivo `application.properties` o `application.yml` del proyecto:
   
   spring.datasource.url=jdbc:postgresql://localhost:8080/book_finder
   spring.datasource.username=tu_usuario
   spring.datasource.password=tu_contraseña
   spring.jpa.hibernate.ddl-auto=update

### **3. Clonar el Repositorio**

    git clone https://github.com/tu_usuario/book-finder-app.git
    cd book-finder-app

### **4. Construir y Ejecutar el Proyecto**

    ./mvnw clean install
    ./mvnw spring-boot:run

### **5. Acceso a la API**

    La API estará disponible en:

    http://localhost:8080

### **6. Configuración de la API Externa**

Asegúrate de tener una clave de acceso a la API externa que estás usando para buscar libros.
Configura la clave en el archivo application.properties:

    book.api.key=tu_api_key
    book.api.url=https://api.external-service.com

## **Contribuciones**

¡Contribuciones son bienvenidas! Por favor, sigue los pasos a continuación:

Haz un fork del repositorio.
Crea una nueva rama:

    git checkout -b feature/nueva-funcionalidad

Realiza tus cambios y haz commit:

    git commit -m 'Agregada nueva funcionalidad'

Sube los cambios:

    git push origin feature/nueva-funcionalidad

Crea un pull request.

## **Contacto**

📧 Jhosuaea910@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/jhosua910/)

## **Licencia**

📜 Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más información.
