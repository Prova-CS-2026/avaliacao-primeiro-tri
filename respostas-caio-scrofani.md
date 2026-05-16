
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Caio Scrofani Ferreira

Matrícula: 20241PVAI10030021

Branch: avaliacao-caio-scrofani

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Um Processo de Desenvolvimento de Software se refere a todas as etapas seguidas para a criação, desenvolvimento e lançamento de um projeto de software. Ele sempre começa com a criação do repositório do projeto em si, geralmente em uma plataforma como o Github, e envolve a criação de novas versões do código que serão refinadas até o seu eventual lançamento.
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
Resposta Questão 3: O Product Backlog é a lista de todas as tarefas que devem ser realizadas ao longo do desenvolvimento do projeto. Idealmente, no fim da última Sprint o Product Backlog estará vazio e todas as tarefas foram entregues. O Sprint Backlog é a lista de todas as tarefas do Product Backlog que o Scrum Team se dispôs a realizar e entregar em uma determinada Sprint. No começo de cada Sprint, o time escolhe tarefas do Product Backlog e as move para o Sprint Backlog.
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
Resposta Questão 5: Um épico é uma parcela significativa do produto, geralmente se referindo a um tema ou conjunto de funcionalidades relativamente independente do resto do projeto. Uma história de usuário é a descrição de uma interação que um usuário em potencial gostaria de ter ao utilizar o produto, e serve como uma orientação detalhada para o desenvolvimento de uma funcionalidade do produto. Uma tarefa é uma diretriz que um desenvolvedor deve cumprir para que um dado Épico ou História de Usuário possa ser entregue. Épicos contém tarefas abrangentes que geralmente podem gerar múltiplas Histórias de Usuários, e estas Histórias terão tarefas mais específicas que orientam a implementação da História e do Épico que a contém. 
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
Resposta Questão 7: Uma branch é uma instância do projeto feita para receber modificações que serão testadas e validadas com segurança antes de serem aplicadas ao projeto como um todo (nesse caso, a versão base).
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [X] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: feat(login): adiciona autenticação de usuários
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: Gerenciamento de configuração se refere às políticas usadas na organização, desenvolvimento, e entrega das diferentes versões de um projeto de software ao longo de toda a sua existência.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: Pela utilização do Kanban, a equipe se torna capaz de monitorar de forma fácil e intuitiva o progresso de um projeto, facilitando a identificação de obstáculos, gargalos na produção, entre outros.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: O comando em questão realiza a troca para a branch de nome minha-branch, saindo assim da branch anterior e permitindo a visualização e modificação dos arquivos de minha-branch.
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
Resposta Questão 13: Cada commit é como um registro das modificações feitas em um código. Quanto mais frequentes os commits, mais fácil é para um time identificar possíveis obstáculos ou erros em um código, e mais fácil é reverter pequenas mudanças sem grandes efeitos colaterais no resto do código.
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
Resposta Questão 15: Branch é a criação de uma nova instância de um código base, resultando em uma "ramificação" deste código que pode ser alterada à vontade. Merge é mesclar duas branches, uma ramificação e sua base original, para "transferir" as mudanças feitas na ramificação para a branch base.
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
1. Clonar o repositório remoto para uma máquina local, para que se tenha uma cópia do projeto em que se possa fazer alterações: git clone [link do repositório].
2. Criar uma branch a partir de uma base, para que seja possível avaliar alterações individuais sem modificar a versão original: git create branch from [nome da branch].
3. Criar e desenvolver os arquivos relevantes para a branch, através de adições e mudanças: git add [nome do arquivo que foi alterado ou modificado].
4. Realizar registro das alterações para que a validação, comparação e análise das mudanças seja mais fácil e organizada no futuro: git commit -m "[descrição do commit]".
```
---