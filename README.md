# 🍎 Projeto NutriBaby — Banco de Dados


### 📖 Sobre o Projeto

O NutriBaby é um sistema de banco de dados desenvolvido para fins acadêmicos no curso do SENAI Morvan Figueiredo.
O projeto simula uma plataforma de delivery especializada em alimentação infantil — semelhante a um iFood, porém voltado exclusivamente para refeições e produtos direcionados a crianças, levando em conta restrições alimentares, observações nutricionais e acompanhamento de pedidos.

O objetivo foi projetar e implementar um banco de dados relacional completo, passando por:

Modelagem Conceitual (DER — Diagrama Entidade-Relacionamento);

Modelagem Lógica (normalização até a 3ª Forma Normal);

Modelagem Física (implementação no SQL Server, com criação de tabelas, chaves, relacionamentos, views e dados de teste).

### 🛠️ Tecnologias Utilizadas:

SQL Server — Implementação do banco de dados

Linguagem: SQL (DDL e DML)

BRModelo — Modelagem conceitual e lógica

Notion — Documentação das etapas do projeto

## 📂 Estrutura do Repositório:

📁 Projeto_BD_NutriBaby-SENAI
│

├── 📄 01-NutriBaby-Modelo_Conceitual.brM3   # Modelo conceitual (DER)

├── 📄 02-NutriBaby-Modelo_Logico.brM3       # Modelo lógico (3FN)

├── 📄 03-NutriBaby-Modelo_Fisico-Query.sql  # Script SQL do modelo físico

└── 📜 README.md                             # Documentação do projeto


## 📌 Etapas do Desenvolvimento:

### 1️⃣ Modelo Conceitual

Identificação das entidades, atributos e relacionamentos;

Definição de cardinalidades e integridade referencial;

Entidades principais:

Usuário

Perfil_Criança

Entregador

PedidoVenda

Tipo_Produto

Produto

Promoção

Fornecedor

Pedido_Compra

Produto_PedidoCompra

### 2️⃣ Modelo Lógico:

Transformação do DER em tabelas relacionais;

Aplicação da Normalização até a 3ª Forma Normal;

Definição de chaves primárias (PK) e estrangeiras (FK);

Ajustes de atributos e tipos de dados para o SQL Server.

### 3️⃣ Modelo Físico:

Implementação no SQL Server com:

Criação de tabelas;

Definição de PKs e FKs;

Inserção de dados de exemplo;

Criação de 3 Views para consultas estratégicas:

VW_USUARIO_E_PERFIL_CRIANCA — Relaciona usuários com os perfis de crianças;

vw_PRODUTO_COM_PEDIDO_E_VENDA_INCLUSOS — Relaciona produtos com pedidos e vendas;

vw_PRODUTOS_COMPRADOS_DOS_FORNECEDORES — Lista produtos comprados de fornecedores.

### ▶️ Como Executar o Projeto:

Baixe ou clone o repositório:

git clone https://github.com/Felipe-Magalhaes-A-Carneiro/Projeto_BD_NutriBaby-SENAI.git


Abra o arquivo 03-NutriBaby-Modelo_Fisico-Query.sql em seu SGBD (SQL Server Management Studio).

Execute o script para criar o banco de dados e tabelas.

Utilize as views e consultas de exemplo para explorar os dados.

### 👥 Autores

Allan

Fábio Magalhães A. Carneiro

Felipe Magalhães A. Carneiro

Katlyn

### 📎 Links Relacionados

Documentação no Notion: Projeto Banco de Dados

### 📜 Licença

Este projeto foi desenvolvido para fins acadêmicos e está sob a licença MIT.
