
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Eduardo Marionucci  

Matrícula: 20241PVAI1003008

Branch: `avaliacao-eduardo`

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Um processo de desevolvimento de software são todas etapas que percorrem durante o ciclo de vida dele. 
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [X] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: 
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3:  O Product Backlog compete a todas as atividades elicitadas para uma sprint, não necessáriamente entrará em desenvolvimento na primeira sprint que é elicitado, mas em algum momento ou não pode entrar em desenvolvimento. A Sprint Backlog compete a todas as atividades propostas a serem implementadas ou não dentro de uma sprint, salvo em casos que a atividade fica como dívida técnica e é passada para a próxima sprint.
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [X] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: Entregar incremento funcional do produto
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: 
Os Épicos são os escopos de um incremento em uma sprint, ele compete ao escopo específico de implementação que contém outras funcionalidades aninhadas a si mesmo.

As histórias de usuário, como o subtentende, são traduções técnica das necessidades do usuário dentro do seu escopo específico (épico), elas são atividades que possuem um propósito de implementação específico para gerar valor ao seu épico. 

As tarefas são atividades que devem ser desempenhadas pelo desenvolvedor dentro de uma história de usuário, ela compete ao trabalho que o mesmo vai desempenhar para entregar a sua HU.
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [X] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: COMO usuário QUERO autenticar PARA acessar o sistema
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: Um branch é uma versão de código de um repositório git. Sua finalidade é poder funcionar como uma versão do código e fornecer um ambiente paralelo de desenvolvimento de um repositório git.
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [X] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8:  feat(login): adiciona autenticação de usuários
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: O gerenciamento de configuração é a matriz essencial de segurança em repositório git. A configuração de um sistema é permeada pelo armazenamento de tokens e senhas importantes de comunicação pela internet. A visibilidade dessas informações podem vulnerabilizar um projeto inteiro e dar acesso a informações sigilosas. A configuração de um sistema é essencial para previnir práticas maliciosas e erros de desenvolvimento.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: 
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: O comando faz a criação de uma branch em um repositório git a partir da branch atual, seguido pela troca imediata para a branch criada.
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [ ] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: 
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: 
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [ ] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: 
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: 
```
---

# Questão 16

Descreva uma sequência possível de passos e comandos para realizar o fluxo de desenvolvimento utilizando Git e GitHub, considerando:

- clonagem de um repositório remoto;
- criação de uma branch individual;
- desenvolvimento na branch criada;
- registro das alterações realizadas;
- envio das alterações para o servidor remoto.

Na resposta:

- enumere os passos;
- apresente os comandos principais envolvidos;
- explique brevemente a finalidade de cada etapa;
- considere que a branch pode ser criada tanto localmente quanto pela interface do GitHub.

```text
Resposta Questão 16: 
```
---