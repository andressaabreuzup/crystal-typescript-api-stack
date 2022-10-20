Trabalhe com uma Stack que é serverless, contract first e que tem Lambdas em **TypeScript**.  

Elimine a complexidade de gerar a infraestrutura necessária para expor uma API e concentre-se apenas na codificação das Lambdas que executam as regras de negócio.

A partir de um Contrato OpenAPI, você tem a geração da infraestrutura necessária abaixo:  

- API Gateway;
- Lambdas (no padrão lift lambda, ou seja, uma lambda para cada endpoint);
- Cloudwatch Logs;  
- X-Ray Tracing;  
- Métricas

E ainda conta com a geração de código **`boilerplate`**, como:  
- Componentes Core;  
- Controllers;  
- Use Cases;  
- Error Handling;  
- API Schema Types
