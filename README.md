# DockerParaIniciantes
1 - Lista todos os dockers
```
docker ps
```

2 - Lista os dockers ja executados
```
docker ps -a
```
3- Roda o Ubuntu com o bash 
```
docker run -it ubuntu bash
```
4- Para de rodar o docker
```
docker stop 096c141ef674
```
5 - Volta a rodar o docker
```
docker start 096c141ef674
```
6 - executar o container pausado
```
docker exec -it 096c141ef674 bash```
