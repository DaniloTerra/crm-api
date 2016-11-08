# Construir a Imagem
```
docker build -t daniloterra/crm-api:v1 .
```

# Rodar um container baseado na imagem
```
docker run -d -p 80:80 --name crm-api -v "$PWD":/var/www/html daniloterra/crm-api:v1
```