# Encurtador de URLs Serverless

Projeto para encurtamento de URLs usando infraestrutura serverless com a AWS. O diferencial dessa aplicação é a proposta de criar um sistema escalável, de fácil manutenção e com custos operacionais reduzidos devido à ausência de servidores dedicados.

## Requisitos

- Java v17;
- Maven;


## HTTP

##### POST `https://ow0nm30gi1.execute-api.us-east-2.amazonaws.com/create`
```json
{
	"expirationTime": "1732926642",
	"originalUrl": "https://github.com/Carolinatxrs"
}
```

