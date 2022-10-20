## **Use Case**
This Use case is ideal to construct endpoint to web applications.

### **General Vision**
The plugin [**typescript-openapi-plugin**](https://github.com/stack-spot/app-typescript-openapi-plugin) adds in the Stack the capacity to provide Lambda services from a OpenAPI specification file. 

### **Requirements**
You need to install the following items:
- [**StakSpot CLI**](https://docs.stackspot.com/v3.0.0/os-cli/installation/);
- [**NodeJS**](https://nodejs.org/en/);
- [**Git**](https://git-scm.com/);
- [**AWS CLI**](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html);
- [**CDK**](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html);

The recommendation is to use some development tools, like [**LocalStack**](https://github.com/localstack/localstack). 

### **StackSpot CLI Configuration**
Execute o comando abaixo para atualizar o local com o catálogo que contém o **`OpenAPI plugin`**:
```bash
stk import stack https://github.com/stack-spot/crystal-typescript-api-stack
```

## **Useful Commands**
Check the commands used in **`OpenAPI plugin`**:  

Command | Description
--------- | ------
`npm run build` | Compiles Javascript to Typescript.
`npm run watch` | Watch the changes and compiles.
`npm run test` | Runs the unit tests with Jest.
`npm run coverage` | Runs tests coverage.
`npm run local synth` | Synthesize the CDK project with _cdk local_ generates and updates de lambda sources.
`npm run local deploy` | Realize the deployment to LocalStack.
`npm run cdk synth` | Synthesize the CDK project with _cdk_ generates and updates de lambda sources.
`npm run cdk deploy` | Realize the deployment to the AWS account configured in the environment.

## **Next Steps**
After aply the **`OpenAPI plugin`**, edit the file `{{spec_file_name}}.yaml` to allow updates of the service stubs generated based on this file.
