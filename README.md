# Commons Lib

Essa é uma biblioteca de utilidades que pode ser utilizada em outros projetos. A biblioteca foi criada com o intuito de centralizar funcionalidades que são compartilhadas entre diferentes projetos.

## Funcionalidades

- `RabbitMQConstants`: Classe que contém as constantes utilizadas para a conexão e configuração do RabbitMQ. As seguintes constantes estão disponíveis:
  - `EXG_NAME_MARKETPLACE`: nome da exchange utilizada para o marketplace
  - `QUEUE_PRODUCT_LOG`: nome da fila utilizada para logs de produtos
  - `RK_PRODUCT_LOG`: routing key utilizado para enviar mensagens para a fila de logs de produtos
- `ProductDTO`: Classe que representa um produto. Possui os seguintes atributos:
  - `id`: ID do produto
  - `name`: nome do produto
  - `price`: preço do produto

## Como utilizar

Para utilizar essa biblioteca em seus projetos, basta adicionar a dependência ao `pom.xml` do seu projeto:

```xml
<dependency>
    <groupId>com.example</groupId>
    <artifactId>commons-lib</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Desenvolvimento

### Tecnologias utilizadas
- Java
- Maven

### Como contribuir
1. Faça um fork desse repositório
2. Crie uma nova branch para suas alterações: `git checkout -b my-new-feature`
3. Faça suas alterações e adicione commits: `git commit -am 'Add some feature'`
4. Envie suas alterações para o seu repositório: `git push origin my-new-feature`
5. Crie um pull request para esse repositório
