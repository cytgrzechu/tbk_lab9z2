# Instrukcja
W folderze z plikiem run.ps1:
```sh
.\run.ps1
```
Usuwanie:
```sh
.\clean.ps1  
``` 

Polecenia z run.ps1:
```sh
docker swarm init
docker stack deploy -c ./docker-compose.yml images-app
``` 
