
# API Node.js com Serverless Framework em ambiente AWS
Esse projeto foi resultado do Bootcamp da GTF da DIO, que exemplificava o uso do modelo de computação serverless na aws

## Etapas para execução

Pré requisitos: 
 - possuir uma conta na AWS e instalar Node.js na máquina.
 - Instalar o AWS CLI: https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html

### Setup Inicial

#### Credenciais AWS

- Criar usuário: AWS Management Console -> IAM Dashboard -> Create New User -> <nome do usuário> -> Permissions "Administrator Access" -> Programmatic Access -> Dowload Keys
- No terminal: ```$ aws configure``` -> colar as credenciais geradas anteriormente
#### Configurar o framework Serverless
```$ npm i -g serverless```

### Deploy
Para fazer o deploy execute o comando:

```$ cd dio-lab-serverless```

```$ serverless deploy -v ```
