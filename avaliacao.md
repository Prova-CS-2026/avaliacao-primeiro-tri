
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Diego Matheus de Carvalho Gonçalves

Matrícula: 20241PVAI10030028

Branch: avaliacao-diego-matheus

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
- [X] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: TRANSPARÊNCIA
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: O Product backlog é o artefato que representa todo o domínio do produto, decorrente das observações/conversas/extrações da comunicação com as partes interessadas (cliente(s)). Tudo que for pertencente ao produto que será implementado. O Sprint Backlog é o resultado do planejamento da spring, onde o time scrum realiza uma reunião e decide o que do Product Backlog deverá ser implementado na iteração/incremento atual.
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
Resposta Questão 5: O Épico representa uma grande fatia do produto. Representa uma parte da camada de visão de negócio do domínio. A história de usuário representa a visão das funcionalidades do sistema através da lupa de usuário. A tarefa representa como o objetivo de alcançar a concretização da funcionalidade dessa história de usuário. Todos são interligados, a diferença é a lupa/ponto de vista que se aplica ao analisar e criar cada um desses artefatos. Como explicado, o épico representa a visão de negócio, a história de usuário representa o usuário/funcionalidade 
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
Resposta Questão 7: Uma branch é um clone de uma baseline com o intuito de criar uma outra codeline independente. O objetivo é isolar os riscos e modularizar o processo de desenvolvimento, permitindo que desenvolvedores trabalhem em suas tarefas sem que hajam conflitos durante o processo.
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
Resposta Questão 9: O gerenciamento de configuração serve para coordenar e trackear a base de código, uma vez que um sistema muda várias vezes por dia (com commits, pushes e merges). Portanto, é necessário uma ferramenta de gestão de versionamento. Versões definitivas de componentes ajudam em repositórios de projetos compartilhados e os devs podem copiar pro seu proprio projeto.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: A vantagem seria um acompanhamento muito melhor de como o projeto está andando. Tendo uma organização em quadros modulares, você consegue facilmente identificar o que precisa de atenção e também organizar e priorizar melhor o que precisa ser feito. Não só em desenvolvimento de software, mas em qualquer projeto SCRUM.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Troca (caso esteja em uma branch diferente) a branch para a designada no comando. Ao fazer o checkout, você já consegue utilizar sua área de trabalho como sandbox para quebrar, modificar ou remover funcionalidades no código sem que o snapshot que está disponível no repositório seja afetado. Ao commitar e pushar, não irá alterar nada que não seja da sua branch.
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
Resposta Questão 13: Os commits requentes ajudam a trackear melhor o progresso da sua tarefa e também permite com que sejam identificados bugs mais facilmente. Ao ter esse gerenciamento do histórico de alteração da codeline, você consegue voltar atrás muito mais facilmente em decisões que possa ter se arrependido ou então fazer um pinpoint de onde os problemas que ocasionaram um bug começaram a correr. Existe MUITO mais coisas importantes, mas essa sem dúvidas é a mais.
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
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: O merging pega uma codeline secundária e funde (merge commit) na baseline. A branch cria uma bifurcação da baseline, criando uma linha temporal alternativa para o desenvolvimento de uma task. A diferença é clara: o merging é o passo final onde você junta as branches (codelines independentes) em uma mainline só. O branching só cria outra codeline independente para que possa ser utilizado posteriormente em um merge.
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
Resposta Questão 16: 1. git clone <<baseline>> 2. git branch -b sua-branch 3. git add -> git commit -m "tipo(opcional): descrição do que esse commit resolve" -> git push 
```
---