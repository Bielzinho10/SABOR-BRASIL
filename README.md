# 🍽️ Sabor do Brasil

Sistema web desenvolvido para a empresa **Sabor do Brasil**, com o objetivo de divulgar fotos dos pratos, permitir pedidos online e obter feedback dos clientes.

---

## 📌 Funcionalidades

✅ Cadastro e login de usuários (modal com opção de criar nova conta)  
✅ Postagens com fotos dos pratos  
✅ Curtidas (like/deslike) contabilizadas no banco de dados  
✅ Feedbacks dos usuários com comentários e nota (1 a 5)  
✅ Tela de pedidos com controle por usuário  
✅ Login/Logout com controle de sessão  
✅ Apenas o autor da postagem pode editar ou excluir  
✅ Conexão com banco de dados MySQL  
✅ Upload de imagens nas postagens  
✅ Diagrama relacional do banco de dados criado com MySQL Workbench

---

## 🛠️ Tecnologias Utilizadas

- ASP.NET Core 8.0  
- Entity Framework Core  
- MySQL  
- MySQL Workbench  
- HTML, CSS e Bootstrap  
- VS Code  
- Git e GitHub  
- Inteligência Artificial (apoio ao desenvolvimento)

---

## 💽 Banco de Dados

### 🗂️ Script de Criação (`script.sql`)

O projeto contém um arquivo `script.sql` na raiz do repositório com as instruções para criação do banco de dados e tabelas:

- `Usuarios`
- `Produtos`
- `Pedidos`
- `ProdutoPedido`
- `Postagens`
- `Feedbacks`
- `Likes`

### 🔄 Dados para Importação

Também foi incluído o arquivo `dados_iniciais.sql` com alguns registros de teste para facilitar a validação.

---

## 🧩 Diagrama ER

O diagrama das tabelas com os relacionamentos foi criado com o MySQL Workbench e se encontra na pasta `Diagramas` com o nome `sabor-do-brasil.mwb`.

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sabor-do-brasil.git
