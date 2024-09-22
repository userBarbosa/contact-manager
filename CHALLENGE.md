# Desafio: Sistema Gerenciador de Contatos

O desafio consiste em desenvolver um sistema gerenciador de contatos (agenda eletrônica) com as seguintes características:

## Funcionalidades do Sistema

### Cadastro de Usuários

- Tela de cadastro de usuário do sistema contendo os campos:
  - **Usuário**
  - **Senha**
  
- Os dados cadastrados deverão ser registrados em um banco de dados de sua preferência, portanto, você deve desenvolver um backend que exponha uma API para esse processo.

### Tela de Login

- Permitir que o usuário faça login no sistema utilizando seu e-mail e senha cadastrados.
- Após o login, redirecionar o usuário para a tela principal do sistema.

### Gerenciamento de Contatos

- Tela principal onde o usuário poderá:
  - **Cadastrar contatos** com os seguintes dados:
    - Nome
    - Endereço
    - Telefone
    - E-mail
  - **Listar** contatos cadastrados.
  - **Editar** contatos existentes.
  - **Excluir** contatos.

### Autorização

O sistema precisa ter controle de autorização com as seguintes regras:

- **Usuários admin** podem criar contatos, editar contatos e excluir contatos.
- **Usuários que não são admin** não podem excluir contatos, mas podem cadastrar e editar contatos.

## Backend API

- Desenvolver um backend que exponha uma API para realizar todas as operações de cadastro, login e gerenciamento de contatos (cadastrar, listar, editar e excluir).

## Considerações

### Responsividade

- O front-end deve ser responsivo, garantindo uma boa experiência de uso em diferentes dispositivos (Vamos usar o próprio browser para testar).

### Tecnologias

- Você pode escolher as tecnologias que preferir, tanto para o front-end quanto para o back-end.

### Controle de Versão

- Utilizar Git para controle de versão.
- Fazer push das alterações no GitHub durante o desenvolvimento e nos enviar o link do repositório para que possamos acompanhar o progresso.

### Documentação

- Criar um arquivo `README.md` no repositório do GitHub com instruções claras com o passo a passo do build, para que possamos executá-lo localmente.

### Infraestrutura e Backend

- Utilizar Docker para que possamos executar localmente o banco de dados e a API de backend.
