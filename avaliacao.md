
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno:

Matrícula:

Branch:

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: O processo de desenvolvimento de Software aborda desde a sua idealização abordando então o primeiro contato com o cliente, as reuniões de alinhamento e extração de requisitos e funcionalidades do sistema. Aborda também as decisões arquiteturais levando em conta as necessidades/funcionalidades, e restrições como uso de uma tecnologia específica ou a integração ao sistema já existente. Aborda também a parte de estruturação do código até o entrega do produto final.
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [X] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: Transparência é um dos pilares do Scrum assim como Visibilidade pois isso permite que todos tenham consciência do que esta sendo feito, quem está fazendo e impedimentos. Mantendo a equipe toda ciente do todo, dos resultados e deixando claro como a participação de cada um faz parte da criação de um produto novo.
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: 
Product Backlog:
Lista priorizada com tudo que pode ser desenvolvido, ou seja vale ressaltar que nem tudo o que existe Product Backlog vai ser de fato desenvolvido

Sprint Backlog: 
é um subconjunto do product backlog ou seja itens do product backlog que foram decididos serem desenvolvidos na sprint apos a sprint planning.
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [X] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: Sprint é o núcleo do scrum com duração de no máximo 4 semanas, onde os itens do sprint backlog serão desenvolvidos para a cada fim de sprint o ser é entregar um incremento funcional do produto.
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: 
Épicos são grandes fátias do produto e são criadas a partir da visão do negócio exemplo poderia ser Modulo de controle de exames, eles possuem objetivos, descrição e critérios de aceitação.
Histórias de usuários são partes de funcionalidades que representam a interação do usuário com aquela mesma funcionalidade, se a funcionalidade for "Consultar exames marcados" uma história de usuário mostra um contexto de interação do usuário com essa funcionalidade, com uma forma narrativa mostrando o valor, motivação e contextualização não so focando no técnico, seguindo o exemplo "Consultar exames marcados" a HU ficaria 
"Eu como paciente que utiliza o sistema, quero poder ver os exames anexados ao meu perfil para poder ter um controle e registro".
HU's possuem tarefas que se relacionam com o objetivo da HU de quem pertecem ou seja tarefa seguindo oexemplo seria - Criar aba de exames relacionados ao paciente.
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [x] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: 
Histórias de usuários são partes de funcionalidades que representam a interação do usuário com aquela mesma funcionalidade, se a funcionalidade for "Consultar exames marcados" uma história de usuário mostra um contexto de interação do usuário com essa funcionalidade, com uma forma narrativa mostrando o valor, motivação e contextualização não so focando no técnico, seguindo o exemplo "Consultar exames marcados" a HU ficaria 
"Eu como paciente que utiliza o sistema, quero poder ver os exames anexados ao meu perfil para poder ter um controle e registro".

```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: 
Uma Branch é uma linha paralela de desenvolvimento, elas permitem que multiplos desenvolvedores trabalhem com a um mesmo arquivo ou projeto onde cada um faz a sua alteração sem interferir na do outro, e futuramente é possivel "mergear" as alterações unindo as alterações onde cada desenvolvedor estava trabalhando. 
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [x] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: 
Mensagens de commit bem estruturadas ajudam na rastreabilidade, existe um padrão que utiliza a etsurturação pelo tipo de alteração com uam breve esplicação como a alternativa.
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: 
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: 
O kanban ele permite uma maior organização com o processo de desenvolvimento pois com as colunas e a movimentação das tarefas/HU's é visível de maneira clara para a equipe oque ainda tem que ser feito, oque esta sendo feito, oque esta sendo revisado etc...
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: 
O comando git checkout -b minha-branch seria uma "junção" de git branch minha-branch e checkout, onde ele cria uma branch nova e ja te coloca nessa nova branch criada.
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
Um critério de aceitação indica oque é necessário para alcançar a necessidade exigida.
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: 
Commits funcionam como um ponto em uma linha no tempo isso permite a rastreabilidade para verificar quando um funcionalidade foi adiciona, ou quando um bug foi corrigido, além disso com commits é possível voltar para uma ponto anterior caso necessário pois o commit como dito marca um ponto em uma linha do tempo permitindo então esse "retrocesso" se necessário voltando para um commit anterior.
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
O papel do Scrum Master é ser um facilitador ou seja permite que o scrum ocorra e resolve impedimentos.
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: 
Uma Branch é uma linha paralela de desenvolvimento é possiverl criar varias branches a partir da main que seria a branch principal do projeto, com isso é possível fazer alterações sem afetar a branch principal. Merge seria um processo de unir branches ou aceitar a alteração de uma outra branch na branch atual, levando como exemplo a branch Main novamente se um DEV esta alterando a branch que ele criou após a modifiações ele pode ter que dar um pull antes pergando outras alterações que foram aceitas na branch principal assim ele devera fazer um merge aceitando as novas alterações para atualizar a sua branch atual, unindo as alterações.
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
    --> clona o repositório localmente
2- git branch avaliacao-gustavo-randi      
    --> cria uma branch nova
3- git checkout avaliacao-gustavo-randi
    --> mudar para a branch criada e poder desenvolver
4- git add . ou git status
    --> git add se quer registrar adiciona as alterações para serem consideradas no commit
    --> git status se com registro quer verificar o registro do que foi alterado
5- git commit -m "fix: mensagem de commit"
    --> commita com uma mensagem deixando salvo localmente as alterações 
6- git push
    --> "empurra" as mudanças para o repositorio

```
---