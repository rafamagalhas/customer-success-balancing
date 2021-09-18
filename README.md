# CustomerSuccess Balancing

Projeto idealizado para associar consultores (Customer Success) com Clientes (Customers) baseado no score de ambos, ou seja, clientes serão atendidos por consultores capacidados, onde seu score seja superior ao do cliente.

Exemplo: 

| cliente | score |
|---------|:-----:|
| A       | 50    |
| B       | 70    |
| C       | 100   |
| D       | 30    |


| consultor | score |
|-----------|-------|
| A         | 60    |
| B         | 100   |


Baseado nos dados acima, a disposição de ConsultoresxClientes ficará conforme a tabela, abaixo:

| consultor | score | clientes |
|-----------|-------|----------|
| A         | 60    | A, D     |
| B         | 100   | B, C     |


---
## Requisitos

- [NodeJS](https://nodejs.org/en/)
- [Npm](https://www.npmjs.com/)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

## Como rodar os testes

Após clonar o projeto com:
```bash
    git clone https://github.com/rafamagalhas/customer-success-balancing.git
```

No terminal, execute os comandos:

```bash
cd customer-success-balancing 
yarn
yarn test
```

Ou usando o NPM:

```bash
cd javascript
npm install
npm test
```
