## **Caso de Uso**
Este Caso de Uso é ideal para a construção de endpoints para aplicação web.

### **Visão Geral**  
O Plugin [**typescript-openapi-plugin**](https://github.com/stack-spot/app-typescript-openapi-plugin) adiciona na Stack a capacidade de provisionar serviços Lambda a partir de um arquivo de especificação **OpenAPI**. 

### **Pré-requisitos**
Para usar o Plugin é preciso ter instalado os itens abaixo: 

- [**StakSpot CLI**](https://docs.stackspot.com/v3.0.0/os-cli/installation/);
- [**NodeJS**](https://nodejs.org/en/);
- [**Git**](https://git-scm.com/);
- [**AWS CLI**](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html);
- [**CDK**](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html);

### **Recomendado**
É recomendada a utilização de algumas ferramentas para desenvolvimento, como por exemplo, o [**LocalStack**](https://github.com/localstack/localstack). 

### **Configuração da Stack CLI**
Execute o comando abaixo para atualizar o local com o catálogo que contém o **`OpenAPI plugin`**:

```bash
stk import stack https://github.com/stack-spot/crystal-typescript-api-stack
```

## **Comandos Úteis**
Confira abaixo os comandos utilizados no **`OpenAPI plugin`**:  

Comando   | Descrição
--------- | ------
`npm run build` | Compila Typescript para Jsii.
`npm run watch` | Observa as mudanças e as compila. 
`npm run test` | Executa os testes unitários com Jest. 
`npm run coverage` | Executa a cobertura de testes. 
`npm run local synth` | Sintetiza o projeto CDK com _cdk local_ e gera/atualiza o projeto.
`npm run local deploy` | Faz o deploy para o LocalStack.  
`npm run cdk synth` | Sintetiza o projeto CDK com _cdk_ e gera/atualiza o projeto.
`npm run cdk deploy` | Faz o deploy para a conta AWS configurada no projeto. 

## **Próximos Passos**  
Depois de aplicar o **`OpenAPI plugin`**, edite o arquivo `{{spec_file_name}}.yaml` para permitir a atualização dos stubs de serviço gerados a partir desse arquivo. 
