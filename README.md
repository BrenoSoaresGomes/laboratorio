# Trabalho final de laboratorio de redes
## Disciplina: Laboratório de Redes (2023/1).
## Membros do grupo: **Breno Soares Gomes** e **José Eduardo Vilela Zouain**. 

Desenvolvimento de uma aplicação para realizar uma comunicação cliente-servidor, onde o cliente tem a função de enviar arquivos para o servidor.

Na maquina de sua escolha, faça download da aplicação cliente. Para que seja enviado o arquivo Execute os comandos para construir e executar o docker responsavel pelo cliente.

```
docker build -t client

docker run --network=host zezouain/server:v1
```

Na maquina de sua escolha, faça o dowload da aplicação cliente. Para receber o arquivo Execute os comandos para construir e executar o docker responsavel pelo servidor.

```
docker build -t server

Docker run -it --network=host zezouain/client:v1 /bin/bash

```


## Imagens disponiveis nos repositórios do dockerhub:

```
docker pull zezouain/client:v1

docekr pull zezouain/server:v1
```

