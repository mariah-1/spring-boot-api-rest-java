<h1 align="center" style="color:#4CAF50;">🛠️ API REST com Spring Boot</h1>

<p align="center">
  <em style="color:#2196F3;">Projeto de estudo para consolidar os fundamentos do desenvolvimento backend moderno com Java e Spring Boot.</em>
</p>

---

## ✅ <span style="color:#4CAF50;">Funcionalidades Desenvolvidas</span>

- ⚙️ API RESTful com operações **<span style="color:#FF9800;">CRUD</span>** completas.  
- 🗄️ Conexão com banco de dados relacional usando **<span style="color:#9C27B0;">Spring Data JPA</span>**.  
- 🛡️ Validações de dados com **<span style="color:#E91E63;">Bean Validation</span>**.  
- 🏗️ Mapeamento de entidades com **JPA**.  
- 📜 Versionamento de banco de dados com **<span style="color:#03A9F4;">Flyway</span>**.  
- 📂 Estrutura organizada seguindo boas práticas do **Spring Boot**.  

---

## 🧠 <span style="color:#2196F3;">Conhecimentos Adquiridos</span>

- Diferença entre **Spring tradicional** e **Spring Boot**  
- Criação do projeto com **Spring Initializr**  
- Estrutura de diretórios e papel do `pom.xml`  
- Principais módulos:
  - <code style="color:#FF9800;">spring-boot-starter-web</code>
  - <code style="color:#FF9800;">spring-boot-starter-validation</code>
  - <code style="color:#FF9800;">spring-boot-starter-data-jpa</code>
- Bibliotecas:
  - **Lombok** → menos boilerplate
  - **Flyway** → migrations automáticas
  - **PostgreSQL Driver** → integração com banco
- Camadas implementadas:
  - **Controller**
  - **Service**
  - **Repository**
- Configuração via <code style="color:#FF5722;">application.properties</code>  
- Execução de migrations com **Flyway**  

---

## 🧰 <span style="color:#9C27B0;">Tecnologias Utilizadas</span>

| Tecnologia | Função |
|------------|--------|
| ☕ <span style="color:#FF5722;">Java 21</span> | Linguagem principal |
| 🚀 <span style="color:#4CAF50;">Spring Boot</span> | Framework backend |
| 🗄️ Spring Data JPA | Persistência no banco |
| 🛡️ Bean Validation | Validação de dados |
| 📜 Flyway | Migrations e versionamento |
| 🛠 Lombok | Redução de código repetitivo |
| 🐘 PostgreSQL | Banco de dados |
| 📦 Maven | Gerenciador de dependências |

---

## 🚀 <span style="color:#FF9800;">Como Executar o Projeto</span>

### 1️⃣ Clonar repositório
```bash
git clone https://github.com/seu-usuario/seu-projeto.git
cd seu-projeto
```
---

## 📂 Estrutura do Projeto
```bash
src/
 ├── main/java
 │    ├── controller   # Endpoints REST
 │    ├── service      # Regras de negócio
 │    ├── repository   # Persistência
 │    └── model        # Entidades JPA
 └── main/resources
      ├── application.properties
      └── db/migration # Scripts Flyway

