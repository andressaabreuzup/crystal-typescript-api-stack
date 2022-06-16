## **Caso de Uso**
Ideal para construção de endpoints para aplicação web.

### Visão Geral
O plugin [**typescript-openapi-plugin**](https://github.com/stack-spot/app-typescript-openapi-plugin) adiciona na stack a capacidade de provisionar serviços Lambda a partir de um arquivo de especificação OpenAPI

### Pre-requisitos
Necessário a configuração de alguns pré-requisitos para utilização do plugin.
- [**Instalação StakSpot CLI**](https://docs.stackspot.com/v3.0.0/os-cli/installation/)
- [**NodeJS**](https://nodejs.org/en/)
- [**Git**](https://git-scm.com/)
- [**AWS CLI**](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)
- [**CDK**](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html)

### Recomendado
Recomendamos a utilização de algumas ferramentas para desenvolvimento
- [**LocalStack**](https://github.com/localstack/localstack)

### Configuração Stack CLI
Executar comando abaixo para atualização de local com catálogo que contém OpenAPI plugin:
```bash
stk add stack https://github.com/stack-spot/skynet-typescript-api-stack
```

## Comandos Úteis

- `npm run build` compila typescript para jsii
- `npm run watch` observa mudanças e compila
- `npm run test` executa testes unitários com jest
- `npm run coverage` executa cobertura de testes
- `npm run local synth` sintetiza o projeto CDK com _cdk local_ e gera/atualiza o projeto
- `npm run local deploy` realiza o deploy para o localstack
- `npm run cdk synth` sintetiza o projeto CDK com _cdk_ e gera/atualiza o projeto
- `npm run cdk deploy` realiza o deploy para a conta AWS configurada

## Next steps

After OpenAPI Plugin has been applied, editing the file `{{spec_file_name}}.yaml` enables update the generated service stubs based on this file  
