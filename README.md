# Criando-seu-gerenciador-de-super-herois-da-Marvel-e-da-DC-em-uma-API-reativa-com-Spring-Boot

## Executar dynamo:

java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb

aws dynamodb list-tables --endpoint-url http://localhost:8000

swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
