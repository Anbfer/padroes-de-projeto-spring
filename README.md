# Sprign Framework - Patterns

>### Singleton:
>    - @Bean e @Autowired
>### Strategy:
>    - @Service e @Repository
>### Facade:
> Uma **API REST** abstraindo a complexidade das integrações  de [**Spring Data JPA**]() e [**ViaCEP**]() - [**Feign**]() utilizando o [**H2**]() salvando apenas na memória
>> ***Opcional***
>>> *Config pra conexão com o H2 no ``application.properties``*
>>> ```java
>>> spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
>>> spring.datasource.url=jdbc:h2:mem:testdb
>>> spring.datasource.driverClassName=org.h2.Driver
>>> spring.datasource.username=sa
>>> spring.datasource.password=password
>>> ```
> ---
#### Links úteis
- Transformar json em objetos Java - [jsonschema2pojo](https://www.jsonschema2pojo.org)
- [ViaCEP](https://viacep.com.br)