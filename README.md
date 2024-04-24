# Rodando a API
É necessário, para a instalaçao e ultilização do ambiente de desenvolvimento, a ferramenta de containers **Docker**, para a instalação pode variar do sistema operacional, por isso refira-se a está página para o mesmo: 
**https://docs.docker.com/engine/install/**

Com ele instalado, podemos Clonar o reposítorio com os devidos acessos, e dentro da pasta executar o comando: 
**docker compose up --build -d** 
Assim o processo de instalação e iniciação do Banco de dados Postgres, assim como o ambiente Django e seu server.
Se tudo estiver correto, acesse: **http://0.0.0.0:8000/register**
