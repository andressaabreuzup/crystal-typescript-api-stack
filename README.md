# crystal-typescript-api-stack

A stack de typescript API a capacidade de criação de serviços inteiramente serverless, com lambdas implementadas em Typescript, criação automática de API Gateway, e outros recursos de nuvem.  

Desenvolva e publique Lambdas baseadas em especificação OpenAPI e totalmente integrado com seu ambiente AWS, configurando automaticamente API Gateway que conecta com todas as Lambdas geradas a partir de um arquivo de especificação OpenAPI informado.  

Nossa Stack utiliza um template inicial de um novo projeto com a base para a criação da infraestrutura no seu ambiente AWS, após o template base é possível utilizar o plugin OpenAPI Plugin para adicionar a capacidade de geração do código base das Lambdas seguindo o modelo Hexagonal, deixando o código pronto para o desenvolvimento das regras de negócio.  

A Stack API foi desenvolvida seguindo todas boas práticas de arquitetura de software:

- Clean Architecture;
- Atualização constante de plugins e templates focando em acompanhar modernização tecnológica do mercado, além de garantir compatibilidade com versões anteriores;
- Código facilmente testável;
- Componentes desacoplados;
- Novas funcionalidades que podem ser adicionadas rapidamente pelo time de desenvolvedores.
