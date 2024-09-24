# Gerenciador de Contatos

## Descrição

Este projeto tem como objetivo desenvolver um sistema gerenciador de contatos completo, incluindo funcionalidades de cadastro de usuários, login, e gerenciamento de contatos. O sistema será desenvolvido com foco em responsividade e usabilidade, utilizando as melhores práticas de desenvolvimento.
Texto do desafio original: [CHALLENGE.md](CHALLENGE.md)

## Nomes e Inspiração

O projeto foi nomeado com base em duas espécies fascinantes do reino animal: a **aranha-fio-de-ouro** (ou néfila) e a **bromélia-imperial**.

* **Backend: Aranha-fio-de-ouro ou Néfila:**
  * As aranhas tecem teias complexas para capturar suas presas, assim como o nosso sistema cria uma "teia" de contatos, conectando informações e facilitando a gestão.
  * A seda amarela característica da teia da aranha-fio-de-ouro simboliza a conexão e a interligação entre os dados do sistema.
  * Repositório: [aranha-fio-de-ouro](https://github.com/userBarbosa/aranha-fio-de-ouro)

* **Frontend: Bromélia-imperial:**
  * Existe uma relação mutualística entre aranhas e bromélias que inspira a ideia de uma interação benéfica e cooperativa entre o usuário e o sistema.
  * A bromélia, especialmente as epífitas, cria um microambiente único, abrigando uma diversidade de vida. Nosso sistema, assim como a bromélia, oferece um ambiente rico e organizado para a gestão de contatos.
  * Repositório: [bromelia-imperial](https://github.com/userBarbosa/bromelia-imperial)

## Tecnologias Utilizadas

* **Frontend:** Angular.
* **Backend:** Node.js com Express.
* **Banco de dados:** MongoDB.
* **Outras:** Docker compose, Git.
* **Plataformas de apoio:** Draw.io (diagramação), DockerHub (armazenamento de containers), GitHub (armazenamento de código), DBDiagram.io (diagramação de banco relacional).

## Funcionalidades

* **Cadastro de usuários:** Permite criar novos usuários com nome de usuário e senha.
* **Login:** Autentica usuários com base nas credenciais cadastradas.
* **Gerenciamento de contatos:** Permite adicionar, editar, listar e excluir contatos.
* **Controle de acesso:** Implementa um sistema de permissões, onde usuários administradores possuem acesso a todas as funcionalidades, enquanto outros usuários possuem acesso limitado.

## Arquitetura

[Diagrama de arquitetura opcional, mostrando a relação entre as diferentes partes do sistema]

## Como Executar o Projeto

### Pré requisitos

* Docker + Docker Compose
* Node.js 18.x
* Angular CLI 18.1.4

### Instalação

#### 1. Clone os Repositórios

Execute os seguintes comandos no seu terminal para clonar os repositórios necessários:

```bash
git clone https://github.com/userBarbosa/contact-manager contact-manager
git clone https://github.com/userBarbosa/bromelia-imperial bromelia-imperial
git clone https://github.com/userBarbosa/aranha-fio-de-ouro aranha-fio-de-ouro
```

Garanta a seguinte estrutura de pastas:

```markdown
/sua-pasta-de-projetos
│
├── contact-manager
│   ├── docker-compose.yml
│   ├── .env
│   └── ...
│
├── bromelia-imperial
│   └── ...
│
└── aranha-fio-de-ouro
    └── ...
```

#### 2. Navegue até a Pasta do Contact Manager

Após clonar os repositórios, navegue até a pasta `contact-manager`:

```bash
cd contact-manager
```

#### 3. Executar o Docker Compose

Execute o seguinte comando para iniciar os serviços:

```bash
docker-compose up
```

Isso irá construir e iniciar os contêineres para o projeto.

## Contribuição

Contribuições são bem-vindas! Abra um problema ou envie uma solicitação pull.

## Licença

Este projeto está licenciado sob a licença MIT.
