# Trabalho final de laboratorio de redes
## Disciplina: Laboratório de Redes (2023/1).
## Membros do grupo: **Breno Soares Gomes** e **José Eduardo Vilela Zouain**. 

Desenvolvimento de uma aplicação para realizar uma comunicação cliente-servidor, onde o cliente tem a função de enviar arquivos para o servidor.
Primeiramente instale o docker tanto na maquina que funcionará como cliente tanto na que será o servidor, utilizando o seguinte comando:

```
sudo apt install docker.io
```

Na maquina de sua escolha, faça download da aplicação cliente. Para que seja enviado o arquivo Execute os comandos para construir e executar o docker responsavel pelo cliente.

```
sudo docker run --rm -it --network=host zezouain/server:v1 /bin/bash
```

Na maquina de sua escolha, faça o dowload da aplicação cliente. Para receber o arquivo Execute os comandos para construir e executar o docker responsavel pelo servidor.

```
sudo docker run --rm -it --network=host zezouain/client:v1 /bin/bash
```


## Imagens disponiveis nos repositórios do dockerhub:

```
docker pull zezouain/client:v1

docekr pull zezouain/server:v1
```

