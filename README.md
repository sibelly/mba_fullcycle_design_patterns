# MBA em Arquitetura Full Cycle
<p align="center">
<img src="https://github.com/sibelly/mba_fullcycle_design_patterns/blob/master/.github/fullcycle.svg?raw=true" alt="drawing" style="width:600px;"/>
</p>

## Arquitetura de Software

### SOLID e Design Patterns

- Conceitos básicos sobre Design Patterns
- GOF - Gang of Four
- Padrões Criacionais
- Padrões Estruturais
- Padrões Comportamentais
- [Sobre o SOLID](https://github.com/sibelly/mba_fullcycle_design_patterns/blob/master/solid.md)
- Single Responsibility Principle
- Open/Closed Princicple
- Liskov substitution principle
- Interface segregation principle
- Dependency inversion principle

## Tools

https://refactoring.guru/pt-br/design-patterns/catalog


### Project

node version -> v18.20.3

#### Database
```
psql -U youruser -d yourdb -f create.sql
```
Possible errors
```
DROP SCHEMA
CREATE SCHEMA
psql:create.sql:11: ERROR:  function uuid_generate_v4() does not exist
LINE 2:  id_contract uuid not null default uuid_generate_v4() primar...
```

Enter the database and install the extension *uuid-ossp*
```
psql -U postgres -d yllebs
CREATE EXTENSION IF NOT EXISTS "uuid-ossp";
```

#### Start express api
```
npx nodemon src/main.ts
```

#### Tests
```
npx jest
```