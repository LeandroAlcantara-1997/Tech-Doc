# **Instalação Docker para Distribuição Mint**

## **Distribuição Mint**

~~~mint
sudo apt-get update
~~~

~~~mint
sudo apt-get upgrade
~~~

~~~mint
sudo apt install docker.io
~~~

~~~mint
sudo systemctl start docker
~~~

~~~mint
sudo systemctl enable docker
~~~

## Após execução destes comandos, basta reiniciar a sessão do usuário logado e executar o seguinte comando para verificar se a instalação ocorreu bem:

~~~mint
docker -v
~~~

## Criação de um grupo Docker com permissão de comandos:

~~~mint
sudo groupadd docker
~~~

~~~mint
sudo usermod -aG docker $USER
~~~

~~~mint
newgrp docker
~~~