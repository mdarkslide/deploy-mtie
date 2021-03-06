```
# Deployment de entorno de Producción

## MTIE - 501

### Instrucciones a seguir:

### Clonar repositorio
```
git clone https://github.com/mdarkslide/deploy-mtie.git
cd deploy-mtie
```

### Mover carpetas a directorio raíz
```
sudo mv apinetcore/ ../
sudo mv app-angular/ ../
sudo mv deploy-node/ ../
sudo mv docker-compose.yml ../
sudo mv startbootstrap-sb-admin-2/ ../
sudo mv README.md ../
```

### Crear Contenedores
```
docker-compose up --build -d
```