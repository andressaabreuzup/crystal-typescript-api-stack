# crystal-typescript-api-stack

A Stack de **Typescript API** possibilita criar serviços inteiramente serverless, com Lambdas implementadas em Typescript, criação automática de API Gateway e outros recursos de nuvem.  

Com a **Typescript API** você pode desenvolver e publicar Lambdas baseadas em especificação **OpenAPI** e totalmente integradas com seu ambiente AWS. Isso permite com que você configure automaticamente uma **API Gateway**, que conecta com todas as Lambdas geradas a partir de um arquivo de especificação OpenAPI informado.  

A Stack **Typescript API** ainda utiliza um Template inicial de um novo projeto com a base para a criação da infraestrutura no seu ambiente AWS. 

Depois do Template base, é possível utilizar o plugin **`OpenAPI Plugin`** para adicionar a capacidade de geração do código base das Lambdas, seguindo o modelo Hexagonal. Assim, o código fica pronto para o desenvolvimento das regras de negócio.  

A Stack foi desenvolvida seguindo todas boas práticas de arquitetura de software, como por exemplo:

- Clean Architecture;  
- Atualização constante de plugins e templates focando em acompanhar a modernização tecnológica do mercado, além de garantir a compatibilidade com versões anteriores;  
- Código facilmente testável;  
- Componentes desacoplados;  
- Novas funcionalidades que podem ser adicionadas rapidamente pelo time de desenvolvedores.  
