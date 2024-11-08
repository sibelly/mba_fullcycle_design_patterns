### DTO - Data Transfer Object
Objeto que só tem propriedades, sendo utilizado para transporte entre camadas da aplicação

### Repository
Realizar a persistência de aggregates (clusters de objetos de domínio como entities e value objects), separando essa responsabilidade da aplicação

### Adapter (structural design pattern)
Converte a interface de uma classe em outra esperada pelo cliente, permitindo que classes incompatíveis trabalhem juntas

### Strategy
Criar comportamento intercambiável

### Factory (creational design pattern)
Criar uma instância com base em uma string

### Presenter
Formatar e adequar um determino conjunto de dados às necessidades do cliente

### Decorator (structural design pattern)
Permite acrescentar funcionalidades a um objeto existente (OCP - SOLID)

### Controller
Conecta o driver com a aplicação, repassando os dados de entrada e retorno a saída de acordo com o drive

### Composition Root
Entrypoint da aplicação, onde são criadas as instâncias utilizadas pelos componentes, monta o grafo de dependências da aplicação

[main.ts](https://github.com/sibelly/mba_fullcycle_design_patterns/blob/master/src/main.ts)

https://refactoring.guru/design-patterns/composite


### Mediator (behavioral design pattern)
Cria um mecanismo de notificação para reduzir o acoplamento entre os objetos.

n para n

https://refactoring.guru/design-patterns/mediator

## Livros

- GoF
- Head First - Design Patterns
- Patterns of Enterprise Application Architecture
