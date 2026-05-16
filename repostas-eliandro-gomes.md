
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Eliandro Gomes da Silva

Matrícula: 20241PVAI10030027

Branch: avaliacao-eliandro-gomes
```

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: O processo de desenvolvimento de software é e o como e o por que de recursos utilizados para a produção de um software. Indo das ideias do cliente ao método de escolha para transcrever essas ideias, como o PO no scrum. Indo para a escolhas de como fazer e programar sendo SCRUM ou o XP. Até a implementação. São essas escolhas, passos, ferramentas, frameworks e etc que são utilizados ao longo do processo.
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [x] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: Transparência
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: Product Backlog é tudo aquilo que se foi pedido e idealizado de se estar no produto, não necessáriamente implicando que aquilo estará de fato no produto final, mas que foi em algum momento almejado estar, nele pode se defirnir a prioridade dos pedidos para que os essenciais sejam de fato encaminhados para o Sprint Backlog.

O Sprint backlog já contém um número menor escolhidos para que sejam garantido a entrega dentro de determinada data. O time faz uma escolha dos items (conselhando os mais priorizados do product backlog) e com essa escolha os encaminha para o sprint backlog. esses por si possuem uma garantia que durante op tempo de duração daquela sprint serão entregues ao final agregando mais no produto.
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [x] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: Entregar incremento funcional do produto
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: Um épico é uma grande parte que geralmente leva messes pra ser pronta. Ele engloba todo um contexto significativo e que dele pode ser gerado uma ou mais histórias de usuário que derivam dessa épico.

Agora, a história de usuário é justamente como o próprio nome diz, ela descreve uma história que o usuário tem, mostrando como um ATOR diz aquilo que ele QUER ou PRECISA dizendo o RAZAO para tal.

Tendo essa história do usuário são geradas as Tarefas, que são ações que deverão ser tomadas seja para completar o pedido da história do usuário ou ações que serão tomadas durante o complete da história.
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
Resposta Questão 7: Uma branch é uma ramificação do código que traz consigo tudo aquilo do código (ou branch) de origem mas de modo que o trabalho feito nela não interfira com o código de ondela ela veio. Sua finalidade é poder trabalhar e realizar alterações em um ambiente controlado sem que a modificação de diversas pessoas entrem em conflito, junto também ao versionamento, onde nela fica salvo todo o histórico de alterações pra aquilo que ela foi criada para fazer.
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
Resposta Questão 9: É o gerenciamento de mud. durante o desenvolvimento. Indo dos Repositórios sendo o baco de dados com as versões, a área de trabalho. a baseline com a versão MAIN dos componentes. Codeline sendo as BRANCHS, o branching sendo a criação dessas codelines (branches) a partir de outras, o merging sendo a fusão das branches e o release sendo a versão entregue aos usuários.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10:  O Kanban facilita a organização do processo de desenvolvimento das tarefas. Nele podemos ver o que pode ser feito na sprint, quem pegou tal tarefa, quem está trabalhando e o que já foi feito e por quem. Ele proporciona essa rastreabilidade para o estado das issues.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Esse comando cria uma nova branch e já faz o checkout para ela, ou seja, já muda o ambiente para essa determinada branch.
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
Resposta Questão 13: Os commits permitem a rastreabilidade e o controle do código, podendo saber quando tal trecho/funcionalidade foi adicionado/alterado. podem servir também como pontos de ancoragem caso algum problema venha a ocorrer, podendo voltar para essas versões mais estáveis.
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
Resposta Questão 15: Branchs são as ramificações em si cada uma com seu próprio código. Já o merge é quando ocorre a fusão entre elas, onde as alterações e modificações de uma branch serão adicionadas em outra.
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
1° git clone "url-do-projeto" (com esse comando o repositório presente na url sera clonado no caminho presente), pode ser feito pelo CMD. assim uma cópia do projeto ficara presente locamente no seu pc.

2° podemos fazer pelo github ento no repositório na aba de branchs e criando uma nova branch (por padrão é criado uma main ou master) ou tendo clonado e entrado na raiz da pasta ou por uma idea, podemos utilizar git checkout -b nova-branch-do-projeto (com esse comando uma nova branch é criada e já é alterado para ela). assim criamos uma propria ramificação para que podemos commitar sem causar problemas ao ramo de origem do projeto.

3° aí é só fazermos as alterações nessa branch, seja criando novos arquivos, deletando ou alterarndo já existentes. aqui é onde podemos então trabalhar a vontade.

4° o registro pode ser feito pelo git add . (para tudo que alterou) ou git add arquivos onde serão adicionados os arquivos prontos para serem confirmados as alterações, git commit -m "mensangem registrando todas as alterações feitas nesses arquivos" e com esse comando são confirmadas as alterações. assim salvamos na nossa propria branch nossas proprias alterações e o histórico delas. 

5° por fim para enviar para o remoto, basta após a realização das confirmações o uso do git push origin main. feito isso asseguramos que todas nossas alterações estejam pressentes remotamente, para caso venhamos a perder acesso ao que temos local podermos acessa-lo novamente por meio de rebase, checkout ou outra clonagem.

```
---