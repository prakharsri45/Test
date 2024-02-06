# apex-springboot-inventory

=> http://localhost:8080/api/inventory/product/

=> http://localhost:8080/api/inventory/product/2

=> http://localhost:8080/api/inventory/recalled/

---------------------------------------------------------

# Changes are:
=: SRC -> JAVA -> controllers, 
                  entities,
                  helpers,
                  repositories,
                  services,
                  Main
                  
=: SRC -> resources

=: test -> InventoryControllerTest,
           ProductServiceTests

=: pom.xml

---------------------------------------------------------------------------

- Clone the repository (https://github.com/alidadasb/apex-springboot-inventory)

- Setup java 11 and run maven install (for java 8 update pom.xml)

- Import project into Intellij or your favorite IDE 

- The project has dependency on **lombok**, please read documentation on how to set up lombok (annotation processing) on your IDE.

https://projectlombok.org/setup/overview

https://www.baeldung.com/lombok-ide


./mvnw install

./mvnw test

./mvnw spring-boot:run


Run Springboot application and make sure the lombok is properly installed (read more https://projectlombok.org/)
Take a look at the tests
