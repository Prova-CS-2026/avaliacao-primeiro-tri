
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Brayan Barros Teixeira Cordeiro Silva

Matrícula: 20241PVAI10030043

Branch: avaliacao-brayan-barros

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1:
O termo "Processo de Desenvolvimento de Software" é auto-explicativo, porém não é tão simples. Desenvolver um Software sem planejamento, pode ser aterrorizante para todos os stakeholders. Para minimizar os problemas que podem surgir durante o desenvolvimento e aumentar a eficiência da entrega, o Processo de Desenvolvimento de Software evoluiu consideravelmente, envolvendo a Metodologia Scrum, Coleta de Requisitos, Planejamento de Arquitetura, Geração de Código e Disciplina.
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
Os pilares do Scrum são Transparência, Inspeção e Adaptação.
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3:
Product Backlog refere-se a todo o escopo planejado para o produto durante o seu desenvolvimento. Já o Sprint Backlog é uma escopo menor, selecionado do Product Backlog que é o objetivo de desenvolvimento da Sprint. 
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [X] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: 
O objetivo da Sprint é entregar incremento funcional do produto.
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: 
- O Épico é uma grande fatia do produto, e evolve um conjunto de Histórias de Usuários;

- As Histórias de Usuário são partes menores de um Épico, geralmente são escritas como storytelings e possuem várias Tarefas;

- As Tarefas compões as Histórias de Usuário, são curtas e diretas e representam features do software.

```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [X] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: 
História de Usuário geralmente são escritas como storytelings.
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: 
Branchs são codelines derivadas de outras codelines ou da mainline. A finalidade das branchs é isolar versões diferentes do software para que os desenvolvedores possam trabalhar em tarefas paralelamente.
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [X] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: 
Um commit adequado deve apresentar ao menos o tipo e descrição, seguindo o seguinte padrão:

tipo(escopo): descrição
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: 
O gerenciamento de configuração se refere aos fundamentos que regem o versionamento de código e quaisquer outras atividades relacionadas a configuração do ambiente de desenvolvimento de Software.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: 
O quadro Kanban é um recurso organizacional e visual para toda a equipe Scrum, agilizando muito o processo de separação de responsabilidades e tomadas de decisão. Através do Kanban, os membros da equipe Scrum podem consultar o estado do Product Backlog, Sprint Backlog, Atividades que estão Em Progresso, Review e Finalizadas.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: 
A finalidade do código é mudar da branch atual para a minha-branch
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [X] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: 
Critérios de Aceitação devem apresentar as restrições de aceitação de maneira clara e explicita. 
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: 
Commits menores durante o desenvolvimento ajudam na rastreabilidade das modificações realizadas no Software e também na proteção contra perda do progresso durante o desenvolvimento. 
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [X] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: 
A principal função do Scrum Master é prover um ambiente de trabalho propício a aderência da metodologia Scrum e garantir que a Equipe Scrum entenda e aplique os conceitos.
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: 
Como dito anteriormente: Branchs são codelines derivadas de outras codelines ou da mainline. A finalidade das branchs é isolar versões diferentes do software para que os desenvolvedores possam trabalhar em tarefas paralelamente.

Já o Merge, se refere a ação de "mesclar" branchs afim de "sincronizar" as alterações em uma das duas branchs.

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

1 - clonagem de um repositório remoto: 
A clonagem do repositório pode ser efetuada através da interface do GitHub ou a partir do terminal do Sistema Operacional com o comando: 
git clone https://github.com/user/repository

2 - criação de uma branch individual:
É possível criar branchs através da interface do VS Code. Basta identificar o ícone de branchs no canto inferior esquerdo, clicar e selecionar "Criar nova branch", nomear a nova branch e confirmar com enter. Também é possível criar a branch através da interface web do GitHub.

3 - desenvolvimento na branch criada:
Assim que a criação da branch for concluída, através da interface do VS Code, você já estará dentro dela e apto para desenvolver.

4 - registro das alterações realizadas;
O registro das alterações pode ser consultado na interface do VS Code, no menu de "Controle do Código-Fonte" no canto lateral esquerdo.

5 - envio das alterações para o servidor remoto.
O envio de alterações para o GitHub pode ser realizado na interface do VS Code, no menu de "Controle do Código-Fonte" no canto lateral esquerdo. Basta preparar as alterações, descrever o commit, se registrar no GitHub e confirmar o commit.
```
---