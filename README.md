# Literalura

**Descripción:**  
Literalura es una aplicación desarrollada en Java utilizando el framework Spring. 


## Requisitos Previos

Antes de instalar y ejecutar la aplicación, asegúrate de tener instalados los siguientes componentes:

- **Java Development Kit (JDK):** Versión 17 o superior. Puedes descargarlo desde [Oracle](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html) o [OpenJDK](https://openjdk.java.net/install/).
- **Apache Maven:** Utilizado para la gestión de dependencias y construcción del proyecto. Descárgalo desde [Maven](https://maven.apache.org/download.cgi).
- **Base de Datos:** [Indica la base de datos que utilizas, por ejemplo, MySQL, PostgreSQL, etc.] Asegúrate de que esté instalada y en funcionamiento.

## Instalación

Sigue estos pasos para configurar y ejecutar la aplicación en tu entorno local:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/keheez/literatura.git
   ```
2. **Navega al directorio del proyecto:**
   ```bash
   cd literalura
   ```
3. **Configura la base de datos:**
   - Crea una base de datos nueva en tu gestor de bases de datos preferido.
   - Actualiza el archivo `application.properties` o `application.yml` en el directorio `src/main/resources/` con las credenciales y URL de conexión de tu base de datos.
4. **Construye el proyecto con Maven:**
   ```bash
   mvn clean install
   ```
5. **Ejecuta la aplicación:**
   ```bash
   mvn spring-boot:run
   ```

## Uso

Una vez que la aplicación esté en funcionamiento, puedes acceder a ella mediante `http://localhost:8080`.
## Pruebas

Para ejecutar las pruebas integradas en el proyecto, utiliza el siguiente comando de Maven:

```bash
mvn test
```

## Contribuciones

Si deseas contribuir al desarrollo de Literalura, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad o corrección de errores:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y haz commits descriptivos.
4. Envía una solicitud de pull para su revisión.

