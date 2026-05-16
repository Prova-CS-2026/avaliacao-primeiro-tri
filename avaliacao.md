
---

# avaliacao.md


# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Isaque Carvalho Xavier

Matrícula: 20241PVAI10030012

Branch: avaliacao-isaque

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: O processo de desenvolver software não é apenas sair programando, e sim pensar em qual seria a maneira mais viável de entregar o produto de acordo com as necessidades do usuário. Após a elicitação dos requisitos, é realizado um planejamento sobre como esse software dewve ser desenvolvido. Após isso, dá-se início ao seu desenvolvimento. Após o desenvolvimento ser finalizado, são feitos testes e quando estiverem testados e validados, o produto será entregue. E mantendo atualizações e manutenções desse software mesmo após a entrega ao usuário. 
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [x] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: Segunda alternativa: Transparência.
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: Product Backlog são todas as funcionalidades que deverão ser implementadas no software como um todo, enquanto que Sprint Backlog são todas as funcionalidades que deverão ser implementadas ao final da Sprint.
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [x] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: Segunda alternativa: Entregar incremento funcional do produto.
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: Épico seria uma área do Sistema, um grande escopo daquela funcionalidade. História de Usuário seria uma das necessidades que devem ser solucionadas dentro daquele Épico. E a Tarefa é uma parte específica dentro daquela mesma História, dentro do mesmo Épico. Ou seja, podem existir vários Épicos dentro do Product Backlog, e dentro desse Épico podem haver várias Histórias de Usuário para que esta área do sistema seja entregue, e dentro da História podem haver várias Tarefas para que aquela necessidade seja suprida.
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [x] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: Terceira Alternativa: COMO usuário QUERO autenticar PARA acessar o sistema
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: Uma branch no git é uma ramificação paralela do código, ela serve para que o dev possa implementar sua tarefa sem estas implementações interfiram no código principal, permitindo testes e mantendo o código principal livre de alterações indesejadas. Se ao final da implementação da branch estiver tudo certo, as alterções dela poderão então se unirem á ramificação principal.
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [x] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: Terceira Alternativa: feat(login): adiciona autenticação de usuários.
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: É o que permite controlar as mudanças e versões do código. Esse gerenciamento é o que permite versionar o código, tornando cada alteração restreável e identificável, a fim de que o software seja produzido com organização.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: Uma das vantagens é visualizar o fluxo de trabalho da equipe. Sendo assim, é possível visualizar quais são as próximas tarefas a serem desenvolvidas e se preparar para a implementa-las, como em caso do desenvolvedor não possuir todo o conhecimento necessário para a concluir.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Criar uma branch nova e entrar nessa branch.
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [x] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: Terceira Alternativa: O sistema deverá permitir login apenas com credenciais válidas.
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: Permite maior rastreabilidade sobre o progresso feito, podendo ir em uma alteração específica ao invés de procurar em um commit gigante.
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [x] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: Terceira Alternativa: Garantir que o Scrum seja entendido e aplicado.
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: Branch é apenas uma ramificação do código, o qual o desenvolvedor pode implementar o que for necessário sem alterar o código principal. Merge é a ação de acoplar as alterações de uma branch em outra, e deve ser analisado com cuidado antes de ser feito, pois um erro dessa branch pode alterar todo o código estável da outra branch.
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
1 - clonar o repositório remoto para fazer alterações, sejam adições ou correções. para clonar pelo terminal, é necessário realizar o comando 'git clone nome-do-repo.git'.
2 - entrar na pasta desse repositório, para que consiga realizar as alterações, usando o comando 'cd nome-da-pasta'.
3 - criar sua própria branch, para que suas alterações sejam feitas separadamente do código principal, usando o comando 'git checkout -b sua-branch'.
4 - para registrar as alterações, é necessário seguir os comandos: 
    4.1 'git add suas/alteracoes/nessa/pasta', se necessário repita os comandos em caso de pastas diferentes. para adicionar todas as alterações, execute 'git add .'.
    4.2 'git commit -m"ação(escopo): descrição da(s) alteração(ões)"'.
5 - para enviar suas alterações para o servidor, caso elas não estejam registradas é necessário fazer isso primeiro. se já estiverem todas commitadas, utilize o comando 'git pull origin branch-alvo-do-envio'.
```
---