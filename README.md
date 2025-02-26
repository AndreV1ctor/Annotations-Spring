<h2 align="center">Anotações Java - Spring</h2>
<p align="center"> Algumas das anotações nas quais já tive contato ou já ouvir falar sobre </p>

<p align="center"><img width="400px" src="https://github.com/AndreV1ctor/assets/blob/master/java_e_spring.png" /></p>

<br>

<p align="center">
  <a href="#-a">A</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-b">B</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-c">C</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-d">D</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-e">E</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-f">F</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-g">G</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-i">I</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-j">J</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-l">L</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-m">M</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-n">N</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-o">O</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-p">P</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-q">Q</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-r">R</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-s">S</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-t">T</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-v">V</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-w">W</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<br>

## 📜 A
- @ActiveProfiles("test"):
>*Sobrescreve as propriedades definidas no arquivo application.properties ao executar os testes, usando o perfil "test".*

- @AfterAll:
>*Indica que o método será executado depois de todos os testes em uma classe de teste.*

- @AfterEach:
>*Indica que o método será executado após cada teste em uma classe de teste.*

- @AliasFor:
>*Permite criar um alias para um atributo de outra anotação.*

- @Autowired:
>*Indica que o Spring deve injetar automaticamente uma dependência no local anotado.*

<br>

## 📜 B
- @Bean:
>*Indica que um método retorna um bean gerenciado pelo Spring.*

- @BeforeAll:
>*Indica que o método será executado antes de todos os testes em uma classe de teste.*

- @BeforeEach:
>*Indica que o método será executado antes de cada teste em uma classe de teste.*

- @Benchmark:
>*Usado para medir a performance de um método.*

-  @BindingAnnotation:
>*Usado no Google Guice para definir anotações personalizadas de injeção de dependência.*

<br>

## 📜 C
- @Cacheable("nomeCache"):
>*Indica que o resultado do método será armazenado em cache.*

- @CacheEvict("nomeCache"):
>*Indica que o cache deve ser removido após a execução do método.*

- @CachePut("nomeCache"):
>*Atualiza o cache com o retorno do método.*

- @Component:
>*Indica que uma classe é um componente gerenciado pelo Spring.*

- @ComponentScan:
>*Define pacotes que devem ser escaneados pelo Spring para buscar componentes.*

- @Configuration:
>*Define uma classe como uma configuração do Spring.*

- @Controller:
>*Indica que uma classe é um controlador no padrão MVC do Spring.*

- @CrossOrigin:
>*Habilita o CORS para permitir requisições de diferentes domínios.*

<br>

## 📜 D
- @Data:
>*Anotação do Lombok que gera automaticamente getters, setters, equals, hashCode e toString.*

- @DependsOn:
>*Define a ordem de inicialização de beans no Spring.*

- @Deprecated:
>*Indica que um método, classe ou atributo está obsoleto.*

- @Documented:
>*Indica que a anotação será incluída na documentação do JavaDoc.*

<br>

## 📜 E
- @EnableCaching:
>*Habilita o suporte a cache no Spring.*

- @EnableJpaRepositories:
>*Habilita a funcionalidade de repositórios JPA no Spring.*

- @EnableScheduling:
>*Habilita o suporte a tarefas agendadas no Spring.*

- @Entity:
>*Indica que uma classe representa uma entidade no banco de dados.*

- @Enumerated(EnumType.STRING):
>*Define como um enum será persistido no banco de dados.*

<br>

## 📜 F
- @Filter:
>*Define um filtro que pode ser aplicado em requisições HTTP.*

<br>

## 📜 G
- @GeneratedValue:
>*Define a estratégia de geração de valores para chaves primárias.*

- @Getter:
>*Anotação do Lombok que gera automaticamente um getter para cada campo.*

<br>

## 📜 H
- @HandlerMethod:
>*Define um manipulador de requisições em controllers.*

<br>

## 📜 I
- @Id:
>*Define o identificador primário de uma entidade JPA.*

- @Import:
>*Importa configurações de outras classes para o Spring.*

<br>

## 📜 J
- @JoinColumn(name = "coluna"):
>*Define a chave estrangeira de uma relação no banco de dados.*

- @JsonIgnore:
>*Indica que um campo deve ser ignorado durante a serialização JSON.*

- @JsonProperty("nome"):
>*Define um nome alternativo para um campo na serialização JSON.*

<br>

## 📜 L
- @Lazy:
>*Indica que um bean só será inicializado quando for necessário.*

- @Lob:
>*Indica que um atributo deve ser tratado como um grande objeto binário (BLOB) ou texto (CLOB).*

- @Log4j2:
>*Anotação do Lombok para configurar automaticamente um logger Log4j2.*

<br>

## 📜 M
- @ManyToMany:
>*Define um relacionamento muitos-para-muitos entre entidades.*

- @ManyToOne:
>*Define um relacionamento muitos-para-um entre entidades.*

- @MappedSuperclass:
>*Indica que uma classe pode ser herdada por outras entidades, mas não será mapeada como uma tabela no banco de dados.*

- @ModelAttribute:
>*Usado em métodos de controllers para pré-popular um modelo antes de uma requisição.*

<br>

## 📜 N
- @NotBlank:
>*Indica que um campo não pode ser nulo nem vazio.*

- @NotEmpty:
>*Indica que um campo não pode ser vazio (mas pode ser nulo).*

- @NotNull:
>*Indica que um campo não pode ser nulo.*

<br>

## 📜 O

- @Order:
>*define a ordem de execução de um componente ou método dentro de um sistema.*
- @OneToMany:
>*especifica um relacionamento de banco de dados um-para-muitos.*
- @OneToOne:
>*especifica um relacionamento de banco de dados um-para-um.*
- @Override:
>*indica que um método em uma classe está substituindo um método da classe pai (superclasse) com o mesmo nome e assinatura.*

<br>

## 📜 P
- @PathVariable("id"):
>*Vincula um valor da URL a um parâmetro de método.*

- @PostConstruct:
>*Executa um método automaticamente após a injeção de dependências.*

- @PreDestroy:
>*Executa um método antes da destruição de um bean.*

- @Primary:
>*Define um bean como a escolha prioritária quando existem múltiplos candidatos à injeção.*

<br>

## 📜 Q
- @Query("SELECT u FROM Usuario u WHERE u.nome = :nome"):
>*Define uma consulta personalizada no Spring Data JPA.*

<br>

## 📜 R
- @Repository:
>*Indica que uma classe é um repositório de acesso a dados.*

- @RequestBody:
>*Indica que um parâmetro de método deve ser preenchido com o corpo da requisição HTTP.*

- @RequestMapping("/rota"):
>*Define a URL associada a um método ou classe de controller.*

- @RequestParam("param"):
>*Vincula um parâmetro de requisição a um parâmetro do método.*

- @RestController:
>*Combina @Controller e @ResponseBody, tornando os métodos automaticamente JSON.*

<br>

## 📜 S
- @Scheduled(cron = "0 0 * * * ?"):
>*Agenda a execução de um método em intervalos específicos.*

- @Service:
>*Indica que uma classe é um serviço do Spring.*

- @SpringBootApplication:
>*Configuração principal do Spring Boot, que ativa @ComponentScan, @EnableAutoConfiguration e @Configuration.*

<br>

## 📜 T

- @TestMethodOrder(MethodOrderer.OrderAnnotation.class):
>*executa os testes em ordem especificada pela anotação @Order().*
- @TestMethodOrder(MethodOrderer.MethodName.class):
>*executa os testes em ordem alfabética pelo nome do método.*
- @TestMethodOrder(MethodOrderer.Random.class):
>*executa os testes em ordem aleatória.*
- @TestMethodOrder(MethodOrderer.DisplayName.class):
>*executa os testes em ordem especificada pela anotação @DisplayName().*
- @ToString:
>*gera uma implementação do método toString.*
- @ToString.Include:
>*inclui um campo específico da geração automática do método toString.*
- @ToString.Exclude:
>*exclui um campo específico da geração automática do método toString.*
- @Table:
>*especifica o nome da tabela principal associada à entidade anotada atualmente.*
- @Test:
>*define um método como um teste.*
- @Transactional:
>*utilizada nos métodos que requerem transações, garantindo que as operações sejam executadas atomicamente.*
- @Transient:
>*indica que um campo não deve ser persistido na base de dados.*

<br>

## 📜 V

- @Valid:
>*indica que o valor do objeto virá do corpo da requisição e precisa ser validado de acordo com as regras de validação definidas.*
- @Value:
>*fornece uma maneira de injetar valores de propriedades em componentes.*

<br>

## 📜 W

- @WithMockUser:
>*permite a execução de testes usando um usuário fictício autenticado.*

<br>

