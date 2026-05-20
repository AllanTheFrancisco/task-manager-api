# Task Manager API 📋

## 1. Descrição do Projeto
A **Task Manager API** é um sistema de gerenciamento de tarefas desenvolvido para modernizar e organizar o fluxo de trabalho da TechNova Solutions. O projeto resolve o antigo problema de desorganização, bugs recorrentes e perda de rastreabilidade, substituindo o compartilhamento de arquivos ZIP por um fluxo profissional de versionamento via Git.

## 2. Tecnologias Utilizadas
* Python (Simulação)
* Git & GitHub

## 3. Como rodar o projeto
1. Clone este repositório: `git clone https://github.com/SEU-USUARIO/task-manager-api.git`
2. Acesse a pasta do projeto: `cd task-manager-api`
3. Execute o arquivo principal da aplicação.

## 4. Estratégia de Branches
O repositório segue a seguinte estrutura de ramificações para garantir a estabilidade do código:
* **`main`**: Branch de produção, contendo apenas o código altamente estável e sempre versionado.
* **`develop`**: Branch de integração. Todo código novo é testado aqui antes de ir para produção.
* **`feature/*`**: Branches temporárias para o desenvolvimento de novas funcionalidades (ex: `feature/criar-tarefa`).
* **`hotfix/*`**: Branches para correções urgentes de bugs no ambiente de produção.

## 5. Fluxo de Desenvolvimento
Para contribuir com o projeto, adotamos o seguinte fluxo:
1. Crie uma nova feature a partir da branch de integração: `git checkout -b feature/nome-da-feature`.
2. Desenvolva a funcionalidade e faça commits organizados e padronizados.
3. Abra um **Pull Request** claro com descrição do que foi feito e como testar.
4. Após revisão, faça o merge na branch `develop`.
5. Quando a versão estiver consolidada, simulamos a release para a `main`.

## 6. Padrão de Commits
Utilizamos os seguintes prefixos semânticos para manter o histórico coerente:
* `feat:` Adiciona uma nova funcionalidade.
* `fix:` Corrige um bug.
* `docs:` Atualiza documentações como o README.
* `refactor:` Melhora a estrutura do código existente.

## 7. Versionamento
Aplicamos o **Versionamento Semântico** através da criação de Tags no Git para cada release:
* `v1.0.0`: Lançamento da primeira versão oficial.
* `v1.1.0`: Adição de novas funcionalidades (Minor).
* `v1.1.1`: Correções urgentes de bugs e hotfixes (Patch).

## 8. Estrutura do Projeto
A estrutura de arquivos foi organizada da seguinte maneira:
```text
task-manager-api/
│
├── main.py          # Arquivo principal da API
├── .gitignore       # Arquivos ignorados pelo repositório
└── README.md        # Documentação principal de alto nível