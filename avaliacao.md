
---

# avaliacao.md


# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Luan Gabriel da Silva Freitas

Matrícula: 20241PVAI10030007

Branch: avaliacao-luan004

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: 
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [x] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2:  Transparência
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: O Product Backlog contém as atividades correspondentes ao desenvolvimento de todo o projeto, já a Sprint Backlog contém apenas as atividades que serão desenvolvidas durante a sprint.
Inicialmentes as tarefas surgem no Product Backlog e vão sendo movidas ao Sprint Backlog. 
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
Resposta Questão 5: Um épico é uma atividade que tem o objetivo de implementar um detemrinado módulo da aplicação, um épico deve ter uma ou mais histórias de usuários.
Uma história de usuário é parte de um épico, ela é descreve o que deve ser o que, porque e para quem deve ser implementado.
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [x] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: COMO usuário QUERO autenticar PARA acessar o sistema
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: Uma branch é uma ramificação de um repositório. Quando trabalhos com multiplos desenvolvedores, é invíavel que todos os devs, mesmo que não estejam trabalhando na mesma atividade, possam alterar a mesma branch, isso causaria muitos conflitos de alteração. Dividir o repositório em branchs soluciona esse problema pois permite que um desenvolvedor possa realizar alterações sem afetar diretamente o que uma outra pessoa está desenvolvendo.
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
Resposta Questão 9: 
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: O Kanban permite que a equipe tenha uma representação visual do estado atual do desenvolvimento do projeto. Por exemplo, é possível verificar o quão perto estamos do fim do desenvolvimento do projeto vendo a quantidade de itens que ainda existem no product backlog pelo quadro kanban.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Altera a minha branch atual pela branch 'minha-branch'
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [X] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: O sistema deverá permitir login apenas com credenciais válidas
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: commitar em maior frequência mantém os commits menores, se commitamos com menor frequência, muito provavelmente cada commit carregará muitas alterações de uma única vez, o que não é seguro de se fazer.
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [X] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: Garantir que o Scrum seja entendido e aplicado
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: Branch é uma ramificação de um repositório, já o merge é o procedimento de unir as alterações de uma branch em outra.
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

1. Clonar o repositório
`git clone ...`

2. Criar uma nova branch localmente
3. Desenvolver o projeto na branch
4. Commitar as alterações
`git commit -m "feat: mensagem"`

5. Publicar a branch e os commits
`git push`

```
---