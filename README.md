Sistema de Catálogo de Produtos com CRUD, JDBC e Padrão Singleton
Este projeto é um Sistema CRUD (Create, Read, Update, Delete) simples, desenvolvido em Java, para gerenciar um catálogo de produtos. Ele demonstra a conexão e a interação entre uma aplicação Java e um banco de dados MySQL, utilizando a API JDBC (Java Database Connectivity).

O objetivo é servir como uma base prática para quem está aprendendo a manipular dados, aplicar boas práticas de arquitetura de software e persistência de dados.

Funcionalidades
Create (Criação): Permite inserir novos produtos no banco de dados com seus respectivos atributos (nome, preço, quantidade e categoria).

Read (Leitura):): Lista todos os produtos salvos na tabela.

Update (Atualização): Atualiza as informações de um produto existente com base em seu ID.

Delete (Exclusão): Remove um produto do banco de dados utilizando seu ID.

Tecnologias Utilizadas
Linguagem: Java

Banco de Dados: MySQL

Conexão: JDBC (Java Database Connectivity)

Padrão de Projeto: Singleton, aplicado na classe de conexão (Conexao.java) para garantir uma única instância de conexão com o banco de dados e otimizar a performance.

Como Rodar o Projeto
Clone o Repositório: Faça o download do código para sua máquina.

Configure o Banco de Dados:

Crie um banco de dados no MySQL com o nome que você usou.

Execute o comando CREATE TABLE para criar a tabela de produtos.

Configurações de Conexão:

Abra a classe Conexao.java e configure seus dados de login do MySQL.

Adicione o Driver JDBC:

Baixe o MySQL Connector/J e adicione-o como uma dependência do seu projeto no IntelliJ.

Execute a Classe Main: Rode a classe Main.java para testar as funcionalidades do CRUD.
