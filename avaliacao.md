
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Mauricio Rodrigues Shiguemoto

Matrícula: 20200016572

Branch: avaliacao-mauricio-shiguemoto

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Processo de Desenvolvimento de software, como todo processo, é uma organização sistemática, métrica e padronizada com o foco no desenvolvimento de um software, independente do seu escopo, regras de negócios e contexto. É uma padronização para da construção de um software.
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
Resposta Questão 3: Product Backlog são todas as tarefas que já foram levantadas para o projeto. Sprint Backlog são todas as tarefas que estão disponíveis para serem desenvolvidas na sprint, que é um período de tempo determinado pelo time, para que haja uma entrega significante à ser apresentada aos Stake Holders.
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
Resposta Questão 5: Épico é um grande contexto que será desenvolvido no software, sendo necessário quebrá-lo em várias histórias de usuário. Exemplo do Sistema de gerenciamento de estacionamentos seria a gerencia dos veículos do estacionamento, enquanto Histórias de usuário são contextos menores onde o usuário deseja fazer tarefas específicas como cadastrar veículo, gerar a guia para pagamento, saída do veículo e uma tarefa é uma alteração no código que afete o funcionamento do software como poder cadastrar um veículo, cadastrar funcionários, deletar veículo, deletar funcionário... Cada tarefa, compôe uma parte de uma história de usuário e várias histórias de usuários compôe um épico.
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
Resposta Questão 7: Branch é uma versão diferente do código e serve para que não atrapalhe o desenvolvimento de outros programadores, isolando o desenvolvimento atual e evitar problemas e erros no código principal em funcionamento. 
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
Resposta Questão 9: Identificar, escolher, alterar, manipular as configurações.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: Clareza entre todo o time. É uma gestão visual das tarefas, mostrando a equipe as tarefas que precisam ser desenvolvidas, o que está em desenvolvimento, as concluídas e as que estão para revisão.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Altera o contexto de desenvolvimento atual para a branch 'minha-branch'
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
Resposta Questão 13: Commits frequentes server para salvar o estado atual de desenvolvimento, versionando o código. Usualmente utilizado para salvar pontos específicos do desenvolvimento, como entregas mínimas que não prejudicaram o código, podendo serem resgatados este estado caso haja algum problema futuro.
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
Resposta Questão 15: Como explicado anteriormente, cada branch é um contexto separado do código, quando é necessário mesclar este código com outra branch que está em um estado diferente, é necessário fazer o merge. Merge é o ato de compatibilizar todas as alterações realizadas em diferentes branchs ao qual aconteceu algum conflito (várias alterações no mesmo arquivo, código), sendo realizado automaticamente caso não haja nenhum conflito entre as alterações. 
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
1 - clonagem de um repositório remoto;
    git clone 'url'
2 - criação de uma branch individual;
    git branch --checkout 'nome-branch'
3 - desenvolvimento na branch criada;
    desenvolva!
4 - registro das alterações realizadas;
    git add.
5 - envio das alterações para o servidor remoto.
    git push

```
---