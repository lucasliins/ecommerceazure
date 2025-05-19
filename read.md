🛒 Armazenando Dados de um E-Commerce na Cloud
Este projeto demonstra como armazenar dados e imagens de um sistema de e-commerce utilizando serviços em nuvem da Microsoft Azure. A aplicação inclui banco de dados, armazenamento de imagens, frontend em Python e configurações de segurança na nuvem.

🔧 Tecnologias Utilizadas
Microsoft Azure

Resource Group

SQL Database

Storage Account (Blob Storage)

Configurações de segurança (Firewall)

Python (Frontend com Flask ou Streamlit)

SQL (Criação e manipulação de tabelas)

☁️ Recursos Criados no Azure
1. Resource Group
Um grupo de recursos foi criado para organizar e gerenciar todos os serviços relacionados ao projeto.

2. Azure SQL Database
Um banco de dados foi provisionado na nuvem.

Foi criada a tabela Produtos com os seguintes campos:

id (int, PK)

nome (varchar)

descricao (varchar)

preco (decimal)

imagem_url (varchar)

3. Azure Storage Account
Criado para armazenar imagens dos produtos.

Container Blob configurado para upload e acesso seguro às imagens.

🔐 Segurança
Regras de firewall foram configuradas para permitir apenas acessos de IPs autorizados ao SQL Database.

O acesso ao Blob Storage foi feito com chaves de acesso ou SAS Tokens, garantindo segurança no armazenamento das imagens.

🌐 Frontend em Python
Foi desenvolvido um frontend simples utilizando Python com as seguintes funcionalidades:

Interface para cadastro de novos produtos.

Upload de imagens diretamente para o Blob Storage.

Integração com o banco de dados para registrar os produtos.

Exibição da lista de produtos cadastrados com suas respectivas imagens.

Funcionalidades Implementadas
 Criação de Resource Group no Azure

 Criação de Azure SQL Database

 Criação de Storage Account (Blob)

 Criação e configuração da tabela de produtos

 Upload de imagens para o Blob Storage

 Frontend Python para cadastro e exibição de produtos

 Configuração de segurança (firewall e acesso controlado)


 