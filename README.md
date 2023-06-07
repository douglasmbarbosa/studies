# studies
repositório destinado para o desenvolvimento dos meus estudos

Comandos docker:    
- docker ps: lista containers em execução
- docker ps -a: lista containers que foram executados
- docker images: mostra as imagens que estão disponíveis no seu computador para serem usadas
- docker pull <nome_imagem>: faz o download de uma imagem
- docker build -t <nome_imagem> . : cria uma imagem com um nome específico
- docker system prune: elimina espaço, excluindo dados que não estão sendo utilizados
- docker login: faz autenticação e acesso ao docker hub 
- docker logout: encerra seção do docker hub
- docker volume create <nome_volume>: cria um volume
- docker volume rm <nome_volume>: remove um volume
- docker network create <nome_re de>: cria uma network

Tipos de Volumes: 

Os volumes são utilizados para persirtimirmos os dados. Ou seja, não perdemos os dados quando o container é excluído

- Anonimos (Anonymous Volume)
- Nomeados (Named Volume)
- Bind mount: Salvos na máquina host, o docker não gerencia

Tipos de conexão:

- Externas
- Com o host
- Entre containers: utiliza o driver bridge

Tipos de drivers: 

- bridge: mais comum e default do docker;
- host: conexão entre máquina host e o container;
- macvlan
- none
- plugins

Docker Swarm - Conceitos Fundamentais: 

- Node:
- Manager node
- Worker node
- Service
- Task

