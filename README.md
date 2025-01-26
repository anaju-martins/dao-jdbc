
# Estudo de Acesso a Banco de Dados com JDBC 

Este projeto foi desenvolvido com o objetivo de estudar e praticar o acesso a banco de dados utilizando JDBC (Java Database Connectivity). Durante a execução do projeto, foram explorados conceitos fundamentais para a manipulação de dados em bancos relacionais utilizando Java.

## 🚀 Tecnologias usadas
- Java 21
- JDBC
- MySQL

## O que foi aprendido

1️⃣ Conexão com o Banco de Dados

- Como estabelecer uma conexão utilizando DriverManager.
- Configuração correta da URL do banco, usuário e senha.
- Tratamento de exceções ao conectar com o banco.

2️⃣ Execução de Comandos SQL via JDBC
- Uso de PreparedStatement para executar INSERT, UPDATE, DELETE e SELECT.
- Diferença entre Statement e PreparedStatement e suas vantagens.
- Recuperação de chaves geradas automaticamente (RETURN_GENERATED_KEYS).

3️⃣ Mapeamento de Dados do Banco para Objetos Java
- Como transformar ResultSet em objetos Java (ORM manual).
- Relacionamento entre entidades, como Seller e Department.
- Uso de Map<Integer, Department> para evitar duplicações.

4️⃣ Transações no Banco de Dados
- Como controlar transações utilizando setAutoCommit(false) e commit().
- Como lidar com rollback em caso de erros durante a inserção de múltiplos dados.

5️⃣ Gerenciamento de Recursos
- Fechamento de ResultSet, Statement e Connection corretamente para evitar vazamentos de memória.
- Utilização de uma classe utilitária (DB.java) para facilitar a gestão da conexão.
