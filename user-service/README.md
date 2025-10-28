## Creación del Dockerfile

### Generar el JAR del proyecto Spring Boot
```declarative
mvn clean package -DskipTests
```
- -DskipTests : Omite la ejecución de las pruebas

### Verificar que el JAR se haya creado correctamente
```declarative  
ls target/
```
### Verificar que el JAR se ejecute correctamente
```declarative  
java -jar target/nombre-del-archivo.jar 
```
