
---

# avaliacao.md

# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Arthur Heiji Voos Shiroshima

Matrícula: 

Branch: avaliacao-arthur-shiroshima

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Um processo de desenvolvimento de software se trata dos meios necessários para se desenvolver uma aplicação, incluindo ferramentas, frameworks, métodos e regras, de forma a atender as necessidades de uma equipe
```
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [x] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2: [x] Transparência
```
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: O Product Backlog é um artefato do Scrum onde estão localizadas os itens de responsabilidade do PO, composto das histórias de usuários e épicos extraídos de requisitos do cliente. Já o Sprint Backlog se trata de um artefato que é de responsabilidade geral, onde é inserido o que será trabalhado naquela sprint, sendo retirado do Product Backlog e adicionado no Sprint Backlog.
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [x] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: [x] Entregar incremento funcional do produto
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: 
- Épico se trata de um conjunto de Histórias de Usuário que conta com informações sobre o negócio da aplicação, dividindo o sistema em fatias, e normalmente sendo desenvolvido por completo em meses

- História de Usuário, ou HU, compõem os casos de uso de um cliente sob determinado épico, contendo informações sobre o ator que realizará a ação, o seu objetivo e a justificativa para aquela HU. Uma HU normalmente é desenvolvida por completo em dias

- Uma tarefa se trata de pontos específicos relacionados à implementação direcionados para os desenvolvedores, a fim de guia-los para o desenvolvimento de uma HU completa. Uma tarefa normalmente é desenvolvida por completo em horas.
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [x] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6: [x] COMO usuário QUERO autenticar PARA acessar o sistema
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: Uma branch no git é uma ramificação de outra branch, onde uma branch filha é criada a partir de uma branch mãe, e todo o conteúdo presente na branch mãe é copiado para a branch filha. Sua finalidade é permitir a criação de várias ramificações de um mesmo projeto, onde desenvolvedores podem trabalhar em uma cópia do projeto principal sem grandes conflitos.
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [x] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: [x] feat(login): adiciona autenticação de usuários
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: Gerenciamento de configuração se trata de um aspecto na engenharia de software que trata do gerenciamento do ambiente de desenvolvimento de uma equipe, visando implementar métodos de versionamento e padrões de desenvolvimento.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: Umas das vantagens do quadro Kanban para equipes de desenvolvimento de software é organização, velocidade e visualização geral de tarefas, permitindo a mudança rápida entre status e fornecendo uma visão geral das tarefas presentes naquele projeto, incluindo tarefas de outros desenvolvedores. 
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: O comando abaixo abre uma branch chamada "minha-branch", criando-a ao mesmo tempo; o comando git checkout minha-branch por si não criaria a branch, caso ela não exista.
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [x] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: [x] O sistema deverá permitir login apenas com credenciais válidas
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: Os commits frequentes permitem o rastreamento das alterações feitas em um projeto de forma atomizada, de forma que, caso haja algum problema em um commit atual, possa ser feito o rollback do projeto para uma versão anterior funcional sem grandes perdas no projeto.
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [x] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: [x] Garantir que o Scrum seja entendido e aplicado
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: Uma branch é uma ramificação de um repositório, que pode ser modificada sem alterar o conteúdo da branch mãe. Um merge é uma ação que une uma branch com a outra, de forma a sincronizar as alterações da branch filha com a branch mãe, por exemplo.
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
```
---