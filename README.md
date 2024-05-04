# DouraSoft

Desafio Assinaturas

Desenvolvimento de uma API para cobrar assinaturas de seus cadastros em **PHP** e **PostgreSQL**

## Deverá conter
**Cadastros**: ID, Codigo, Nome, Email e Telefone

**Assinaturas**: ID, Cadastro, Descrição, Valor

**Faturas**: ID, Cadastro, Assinatura, Descrição, Vencimento, Valor.

## Instruções 🌄

1. Faça um fork do projeto para sua conta pessoal
2. Crie uma branch com o padrão: `desafio-seu-nome`
3. Submeta seu código criando um Pull Request
4. Estão faltando alguns campos propositalmente, você deve criá-los

## Como o Sistema Deve Funcionar ⚙️
 - Deve possuir um CRUD Listagem/Inclusão/Edição/Exclusão de Cadastros
 - Deve possuir um CRUD Listagem/Inclusão/Edição/Exclusão de Assinaturas
 - Deve possuir um CRUD Listagem/Inclusão/Edição/Exclusão de Faturas
 - Deve possuir uma Task que verifica uma vez ao dia todas as assinaturas que vencem daqui a 10 dias e converta elas em faturas.
 - A Task não pode converter faturas já convertidas hoje.
 
## Você deve 🧯
- Utilizar composer
- Utilizar qualquer Framework PHP. Caso opte por não utilizar, desenvolver nos padrões de projeto MVC.
- Utilizar o Postman para documentar a API. Exporte a documentação junto ao projeto na pasta docs.

## Não esqueça de 📆
- Criar as Migrations
- Criar os Seeds

## Pontos Extras ⏭️
- Criar os casos de testes utilizando PHPUnit
- Criar o frontend em um projeto separado com o framework de sua preferência.

## Dúvidas ❓

Abra uma [issue](https://github.com/dourasoft/desafio-assinaturas/issues/new)

Ou envie um email para: **paulo@dourasoft.com.br**

Boa sorte! 💪


## Tecnologias utilizadas
- Laravel 10
- Postgres
- API
- Restfull
- Linux
- Swagger

## Rodar a aplicação
- Instalar o postgres
- git clone https://github.com/MarkusLima/desafio-markus
- Renomear .env.example para .env
- Informar credenciais do banco no .env
- Execute composer install
- Execute php artisan migrate
- Execute php artisan db:seed
- Execute php artisan serve

## Acessos
``
http://localhost:8000
``

## Documentação completa da API
``
http://localhost:8000/api/documentation
``

## Preview do Projeto

![App Screenshot](/Docs/img1.png)

