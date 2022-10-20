# crystal-typescript-api-stack

The **Typescript API** Stack creates an entirely serverless service, with Lambdas implemented in Typescript, automatic creation of API Gateway, and other cloud features.

You can develop and publish Lambdas based on the **OpenAPI** specification and fully integrated with your AWS environment with **Typescript API**. This allows you to automatically configure an **API Gateway**, which connects to all Lambdas generated from a given OpenAPI specification file.

The **Typescript API** Stack still uses an initial Template for a new project as the basis for creating the infrastructure in your AWS environment

After the base Template, it is possible to use the **`OpenAPI Plugin`** plugin to add the ability to generate the base code of Lambdas, following the Hexagonal model. Thus, the code is ready for the development of business rules

Stack was developed following all good software architecture practices, such as
- Clean Architecture;  
- Constant updating of plugins and templates focusing on keeping up with the technological modernization of the market, in addition to ensuring compatibility with previous versions;
- Easily testable code;
- Decoupled components;
- New features that can be quickly added by the dev team;
