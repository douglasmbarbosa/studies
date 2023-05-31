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

Tipos de Volumes: 

Os volumes são utilizados para persirtimirmos os dados. Ou seja, não perdemos os dados quando o container é excluído

- Anonimos (Anonymous Volume)
- Nomeados (Named Volume)
- Bind mount: Salvos na máquina host, o docker não gerencia

