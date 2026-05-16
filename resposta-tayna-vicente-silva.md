
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Tayná Vicente Silva

Matrícula: 20241PVAI10030034

Branch: feat/adicionar-respostas-prova-cs

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Um processo de desenvolvimento de software é um conjunto de atividades, práticas e métodos utilizados para planejar, criar, testar e evoluir um sistema.
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [X] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: Transparência
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: O Product Backlog contém todas as histórias de usuário que foram adicionadas em qualquer momento pelo PO. Agora Sprint Backlog entram todas as atividades que foram definidas com o cliente a serem entregues nessa sprint/pacote.
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
Resposta Questão 5: Épico é a funcionalidade num geral. Ela descreve de maneira bem objetiva o contexto daquela atividade. Uma História de usuário, é uma parte mais detalhada da épico, onde descreve os critérios de aceitação e as tarefas, que são as atividades ou funcionalidades a serem desenvolvidas naquela história de usuário.
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
Resposta Questão 7: Um branch é uma subspasta do repositório, a finalidade dela é trazer organização, agilidade e trabalho simultâneo. 
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [x] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: feat(login): adiciona autenticação de usuários
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: São as configurações que abragem todo o processo de desenvolvimento.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: O Quadro Kanban é essencial no desenvolvimento de software, é possível acompanhar todo o trabalho da equipe só visualizando esse quadro. Temos uma visão de como estão o andamento das atividades, e o que será entregue ou não. Além de facilitar o desenvolvimento das atividades. 
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Ele cria e já entra na branch no mesmo momento. 
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [x] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: O sistema deverá permitir login apenas com credenciais válidas
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: Durante o desenvolvimento, é importante manter uma frequencia de commit para garantir que o seu trabalho não seja perdido. Por exemplo: Você está desenvolvendo a 4h sem pausas, e não realizou nenhum commit você corre um grande risco desse trabalho de 4h ser perdido, ou pensa também, você trabalha por 4h e realiza um commit gigantesco, isso é muito ruim para legibilidade e também não seguiria os padrões de commit.
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [x] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: Garantir que o Scrum seja entendido e aplicado
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: Um merge é uma mesclagem entre duas branchs, sendo ela, a origin ou a base. Uma branch é um local isolado, que pode ser criado com base em outras branch mais atualizadas, dessa forma você garante que está atualizado com a branch main geralmente, e pode fazer um trabalho separado e depois mergia com a branch main novamente. 
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

1- git clone https://github.com/Prova-CS-2026/avaliacao-primeiro-tri.git
2- git fetch
3- git checkout main *ou branch principal do projeto
4- git checkout -b "feat/minha-branch"
5- git push --set-upstream origin feat/minha-branch
6- git status
7- git add . *ou arquivos especificos que eu queria subir
8- git commit -m "descricao do commit"
9- git push

```
---