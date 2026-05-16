
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Ana Beatriz Tavares Malaquias

Matrícula: 20241PVAI10030002

Branch: avaliacao-ana-tavares

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
- [ ] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: Transparência
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: Product Backlog é uma lista priorizada com tudo que deve ser desenvolvido, já o Sprit Backlog seria um subconjunto do Product Backlog, criado durante o Sprint Planning
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [ ] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: Entregar incremento funcional do produto
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: ÉPICO: é o todo do produto. A partir dela que é fatiado incrementos para o produto
História de Usuário: é uma funcionalidade que nasce a partir de uma épica, ela é o fatiamento que ocorre na épica, uma HU deve ser independente, negociavel, trazer valor, ser estimável, pequena e testável
Tarefa: é os afazeres que nasce de uma HU
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [ ] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: COMO usuário QUERO autenticar PARA acessar o sistema
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: As branches são cópias da versão da baseline, elas criam a possibilidade de trabalhar em novas funcionalidades e correções de forma isolada e segura, sem quebrar o código principal da baseline
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [ ] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: feat(login): adiciona autenticação de usuários
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: é uma forma de controlar, registrar e gerenciar as versões e mudanças feitas pela equipe ao longo tempo
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: é um método visual que auxilia a equipe e demais a ver o progresso e andamento das tarefas criadas e entender caso alguma etapa esteja muito cheia e verificar o motivo por trás
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: você está criando uma nova branch
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [ ] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: O sistema deverá permitir login apenas com credenciais válidas
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
Resposta Questão 14: Garantir que o Scrum seja entendido e aplicado
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: merge é quando você está enviando suas modificações da sua branch (a codeline atual que você trabalhou) para a baseline que é a atual, por conta disso, se 2 branches diferentes modificaram as mesmas linhas da baseline, haverá o merge conflit, pois o sistema precisará de uma intervenção humana para saber qual modificação aceitar
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
1. clonagem de um repositório remoto: git clone repositorio -> aqui voce está copiando um repositorio para sua maquina local
2. criação de uma branch individual: git checkout -b nome-branch -> aqui voce esta criando uma branch para trabalhar no repositorio sem fazer alterações diretas no repositorio
3. desenvolvimento na branch criada: git add . -> voce está preparando suas alterações para envio
4. registro de alterações: git commit -m "alteração feita" -> voce está enviando sua alteração com uma mensagem do que foi feito, mas ainda remotamente, nao chegou no repositorio original
5. envio: git push -> agora aqui voce ja esta enviando suas alterações para o repositorio original, fazendo o merge
```
---