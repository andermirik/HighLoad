# Лекция 1
## Spring Initializr
https://start.spring.io/
## Beans
### Bean lifecycle
    https://reflectoring.io/spring-bean-lifecycle/
### Bean scope
    https://www.baeldung.com/spring-bean-scopes
### Component Scan
https://sysout.ru/componentscan-v-springbootapplication-annotatsiya-import/
### Component, Service, Repository
https://stackoverflow.com/questions/6827752/whats-the-difference-between-component-repository-service-annotations-in
### Autowired vs constructor injection
https://stackoverflow.com/questions/40620000/spring-autowire-on-properties-vs-constructor
### Circular reference
https://stackoverflow.com/a/66105382/11843557
### Conditions
https://habr.com/ru/post/462541/
### JSR250
### Primary, Qualifier
https://stackoverflow.com/questions/56642356/when-to-use-qualifier-and-primary-in-spring

## RestController
### RestController vs Controller
### @RequestMapping
### Post/Get/Delete/Put/Patch Mapping
### @RequestParam
### @PathVariable
### @RequestBody
### @RequestHeader
### Multipart File
### Хорошие практики
#### лимитирование findAll
##### пагинация
##### пагинация прокруткой
### Плохие практики
#### скачивание файла через FS
### ResponseEntity
    Отличия ResponseEntity от возвращаемой модели
### @Valid @Validated
### Filter request
### ExceptionHandler

## Spring data Jpa
### @Entity
#### @OneToMany, @ManyToOne, @ManyToMany
#### N+1
##### FetchType
##### FetchMode
### @Id
### @GenerationType
### Sequentions
### Validation
#### @NotNull, @NotEmpty, @NotBlank 
#### @Email
#### @Min, @Max, @Length
### JpaRepository
#### save
#### findById
#### Reflection
#### @Query

## Transaction

- https://sysout.ru/transactional-urovni-izolyatsii/
- https://sysout.ru/transaction-propagation/
- https://medium.com/@paul.klingelhuber/db-lock-issues-with-transactional-requires-new-more-spring-java-transaction-handling-pitfalls-e6430d8a8d30
- https://medium.com/@paul.klingelhuber/transactional-requires-new-considered-harmful-spring-java-transaction-handling-pitfalls-3ed109b3f4f5

### Propagandition
    https://sysout.ru/transaction-propagation/
### Isolation
    https://sysout.ru/transactional-urovni-izolyatsii/

## Liquibase
- https://3-info.ru/post/10089
## junit-jupiter-api
- https://habr.com/ru/post/590607/
## testcontainers
- https://www.testcontainers.org/quickstart/junit_5_quickstart/
## docker
Успеем - хорошо, не успеем - на лабах
