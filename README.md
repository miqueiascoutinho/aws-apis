# aws-apis

#### Objetivo:
O objetivo desse projeto é demonstrar a integração com o ambiente cloud AWS

#### Swagger do projeto:
http://localhost:9080/swagger-ui.html

#### Controllers disponíveis:
##### - API Amazon S3:
    - Listar buckets S3 disponíveis
    - Listar conteúdo de um Amazon Bucket S3 específico
    - Criar um Amazon Bucket S3 (região default está como São Paulo: sa-east-1)
    - Remover um Amazon Bucket S3 específico
    - Fazer upload (put) de um arquivo local para um Amazon Bucket S3
    
    
#### Configurações de Amazon Credenciais:
Por default, esse projeto utiliza as credenciais da AWS que estão configuradas em ~/.aws 

Para mais informações, olhar a documentação disponível em: 
```sh
aws configure help
```

Caso você tenha as credenciais de um usuário do Amazon IAM, você pode inseri-las diretamente em:
``
br.com.miqueiascoutinho.aws.apis.configurations.AmazonS3Client
``
