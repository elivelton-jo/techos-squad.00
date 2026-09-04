# 🛠️ TechOS - Squad 00

Projeto Integrador de encerramento da unidade curricular do curso Técnico em Desenvolvimento de Sistemas — SENAI.

---

## 👥 Integrantes e Atribuição de Papéis

| Nome do Integrante | Papel no Projeto | GitHub |
| :--- | :--- | :--- |
| **Íthalo Mateus** | Tech Lead (PHP/Backend) | [@ithalo67](https://github.com/ithalo67) |
| **José Elivelton** | Desenvolvedor Frontend (HTML/CSS/JS) | [@elivelton-jo](https://github.com/elivelton-jo) |
| **Kauã Marinho** | Mobile Lead | [@kauamarinho08](https://github.com/kauamarinho08) |
| **Rodrigo Silva** | DevOps / Git Lead | [@codsite](https://github.com/codsite) |

---

## 📋 Gestão do Projeto (Trello)

- **Quadro de Tarefas:** [Acessar Trello do TechOS](https://trello.com/invite/b/6a9b0968c835af411ae74e7f/ATTI649d5db15444dc9514bd59c4565dcd0bE3D3CFC2/techos-squad)

---

## 📊 Matriz Diagnóstica de Habilidades

| Nome do Membro | PHP | HTML/CSS | JavaScript | Git | Banco de Dados | Papel Atribuído na Sprint |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **Íthalo Mateus** | 2 | 2 | 2 | 1 | 3 | Tech Lead (PHP/Backend) |
| **José Elivelton** | 2 | 2 | 2 | 2 | 2 | Desenvolvedor Frontend (HTML/CSS/JS) |
| **Kauã Marinho** | 2 | 2 | 3 | 2 | 2 | Mobile Lead |
| **Rodrigo Silva** | 2 | 2 | 2 | 3 | 2 | DevOps / Git Lead |

> **Escala de Autoavaliação:** `1 - Iniciante` | `2 - Intermediário` | `3 - Avançado`

---

## 🏗️ Modelo Arquitetural

### Justificativa Técnica (API REST em PHP)
Optou-se pelo modelo de **API REST em PHP** (retornando JSON) em detrimento do Monolito Tradicional para garantir o desacoplamento entre a camada de aplicação backend e as interfaces de usuário[cite: 1]. 

Como o projeto precisa atender simultaneamente a uma interface web (Painel Admin Frontend JS) e a uma aplicação mobile (Interface do Técnico de Campo), a centralização da regra de negócios em rotas RESTful fornecendo dados estruturados em JSON possibilita a reutilização de código, facilidade de manutenção e independência no desenvolvimento por parte das frentes de Frontend e Mobile[cite: 1].

### Diagrama de Arquitetura
![Arquitetura TechOS](docs/arquitetura_techos.png)

---