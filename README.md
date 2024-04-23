# Funcionalidades Principais

1. **Cadastro de Pacientes e Médicos:** Permite adicionar novos pacientes e médicos à base de dados, incluindo informações como nome, data de nascimento, histórico médico, especialização (para médicos), entre outros dados relevantes.

2. **Consulta de Pacientes e Médicos:** Possibilita visualizar os detalhes de um paciente ou médico específico com base em seu ID, nome, especialização (para médicos) ou outros critérios de pesquisa.

3. **Atualização de Pacientes e Médicos:** Permite atualizar as informações de um paciente ou médico existente na base de dados, como alterar o histórico médico de um paciente ou a especialização de um médico.

4. **Remoção de Pacientes e Médicos:** Permite excluir um paciente ou médico da base de dados, removendo completamente suas informações do sistema.

5. **Autenticação e Autorização:** Implementa autenticação e autorização para proteger os endpoints da API, garantindo que apenas usuários autorizados possam acessar e modificar os dados médicos dos pacientes.

# Ambiente de Desenvolvimento e CRM em Paralelo

A escolha do Django como framework para o desenvolvimento desta API proporciona várias vantagens, incluindo:

- **Rápido Desenvolvimento:** Django oferece um conjunto abrangente de ferramentas e funcionalidades que permitem o desenvolvimento rápido e eficiente de aplicações web, incluindo APIs.
  
- **Administração Automática:** O Django vem com um painel de administração integrado, que pode ser usado para gerenciar os dados da aplicação de forma fácil e rápida. Isso pode ser estendido para criar um sistema de gerenciamento de registros médicos (MRM - Medical Records Management) em paralelo com a API de gerenciamento de pacientes e médicos.
  
- **Segurança Integrada:** Django possui várias camadas de segurança embutidas, incluindo proteções contra ataques comuns da web, facilitando a construção de uma API segura para dados médicos sensíveis.
  
- **Escalabilidade:** Django é altamente escalável, o que significa que a aplicação pode crescer conforme a demanda, seja para lidar com um grande volume de pacientes e médicos ou para adicionar novos recursos no futuro.

Portanto, ao utilizar Django para desenvolver esta API de gerenciamento de dados médicos, é possível não apenas criar uma API robusta e eficiente, mas também estabelecer uma base sólida para um sistema de MRM em paralelo, se necessário.

# Rodando a API
É necessário, para a instalaçao e ultilização do ambiente de desenvolvimento, a ferramenta de containers **Docker**, para a instalação pode variar do sistema operacional, por isso refira-se a está página para o mesmo: **https://docs.docker.com/engine/install/**

Com ele instalado, podemos Clonar o reposítorio com os devidos acessos, e dentro da pasta executar o comando: **docker compose up --build -d**, assim o processo de instalação e iniciação do Banco de dados Postgres, assim como o ambiente Django e seu server.
Se tudo estiver correto, acesse: **http://0.0.0.0:8000/register**
