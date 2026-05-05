# TrainWise - Sistema de Planejamento de Treinos

## 1. Membros do grupo

- Arthur Pereira Carvalho
- Davi Carvalho dos Santos
- Davi Sakamoto Lamounier
- Guilherme Xavier Salles

---

## 2. Explicação do sistema

O sistema será uma aplicação web para gerenciamento de treinos de academia.

A aplicação permitirá que usuários realizem cadastro e login, e, após autenticados, possam gerenciar seus treinos de forma individual. Cada usuário poderá:

- Criar treinos com nome e imagem;
- Visualizar seus treinos em formato de cards;
- Remover treinos existentes;
- Acessar os detalhes de cada treino;
- Adicionar exercícios a um treino, incluindo número de séries e repetições;
- Visualizar a lista de exercícios associados a cada treino.

O sistema será desenvolvido com foco em simplicidade, permitindo validar funcionalidades essenciais e demonstrar o uso de testes automatizados.

Serão implementados testes cobrindo:

- Autenticação (cadastro, login e validações);
- Criação e listagem de treinos;
- Exclusão de treinos;
- Adição e listagem de exercícios;
- Controle de acesso a rotas protegidas.

É esperado que os testes atinjam, pelo menos, **95% de cobertura do código**, garantindo maior confiabilidade e facilitando a manutenção do sistema.

---

## 3. Tecnologias que serão utilizadas

### Backend

**Python**  
Linguagem principal do projeto. Foi escolhida por ser simples, legível e amplamente utilizada no desenvolvimento de aplicações web e testes automatizados.

**Flask**  
Framework web leve que será utilizado para criar a aplicação. Será responsável por definir as rotas do sistema, processar requisições e retornar respostas em formato JSON.

**Flask-SQLAlchemy**  
Biblioteca que implementá o padrão ORM (Object Relational Mapping), permitindo manipular o banco de dados por meio de classes Python. Será utilizada para definir os modelos, como `User`, `Workout`, `Exercise`, e realizar operações de persistência.

**Flask-Login**  
Biblioteca responsável pelo gerenciamento de autenticação. Ela permitirá controlar sessões de usuário, proteger rotas e gerenciar login e logout.

**SQLite**  
Banco de dados leve baseado em arquivo. Foi escolhido por não exigir configuração adicional e ser suficiente para aplicações de pequeno porte.

---

### Frontend

**HTML**  
Responsável pela estrutura das páginas da aplicação, como login, dashboard e visualização de treinos.

**CSS**  
Sera utilizado para estilização da interface, definindo layout, cores e organização dos elementos.

**JavaScript (Fetch API)**  
Será utilizado para comunicação com o backend. Permite enviar requisições HTTP e atualizar dinamicamente a interface sem recarregar a página.

---

### Testes

**Pytest**  
Framework de testes que será utilizado para validar o comportamento do sistema, cobrindo funcionalidades de autenticação, treinos e exercícios.

**Pytest-cov**  
Ferramenta a ser utilizada para medir a cobertura de testes, indicando quais partes do código estão sendo testadas.

---

### Outros

**Werkzeug**  
Biblioteca para funções auxiliares, como geração e verificação de hash de senha, contribuindo para a segurança do sistema.

**Git/GitHub**  
Ferramentas de versionamento de código que permitem controle de versões, colaboração e rastreamento de alterações no projeto.

---
