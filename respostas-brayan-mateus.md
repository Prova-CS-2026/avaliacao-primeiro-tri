
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Brayan Mateus da Silva de Souza.

Matrícula: 2024110030042

Branch:
avaliacao-brayan-mateus
---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```
Resposta Questão 1: 
```
O processo de desenvolvimento de software transforma uma ideia inicial em um software funcional confiável e pronto..
---

# Questão 2

Qual das alternativas abaixo representa corretamente um dos pilares do Scrum?

- [ ] Compilação
- [X] Transparência
- [ ] Deploy
- [ ] Versionamento

```text
Resposta Questão 2:  
```
transparência..
---

# Questão 3

Explique a diferença entre Product Backlog e Sprint Backlog.

```text
Resposta Questão 3: 
```
O product backlog é a lista onde está todo o produto a ser desenvolvido, já o Sprint backlog é onde fica os itens escolhidos para a sprint..
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [x] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: Entregar incremento funcional do produto..
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: 
O épico são as funcionalidades do sistema, a visão macro do sistema e do que deve ser feito durante o período..
As Histórias de Usúarios descrevem como cada item deve ser feito, ou acontecer, com critérios de aceitação e validações..
As tarefas são os itens técnicos, são utilizadas após a finalização da história, mas por alguma mudança, ela é criada para fazer alterações de códigos..
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
Resposta Questão 7: 

Uma branch é o local onde será desenvolvido o código da tarefa específica, ela tem a finalidade de criar um espaço individual, onde após toda a 
criação, a pessoa que fez, pode enviar para onde todos os códigos estão, evitando questão de conflitos no código final..

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
Resposta Questão 9: 
```O gerenciamento de configurações tem a responsabilidade de controlar as mudanças e manter a integridade, rastreabilidade e 
o padrão do ciclo de vida do software..
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: O kaban possui vantagem principalmente na questão de organização de como será feito o desenvolvimento e 
gerenciamento da equipe entre as tarefas..
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Utilizado para mudar as branchs, ou restaurar arquivos.. 
```
---

# Questão 12

Qual alternativa representa corretamente um critério de aceitação?

- [ ] Criar tela
- [ ] Implementar endpoint
- [X] O sistema deverá permitir login apenas com credenciais válidas
- [ ] Criar branch

```text
Resposta Questão 12: O sistema deverá permitir login apenas com credenciais válidas.
```
---

# Questão 13

Explique a importância de commits frequentes durante o desenvolvimento.

```text
Resposta Questão 13: Os commits frequentes são importantes para salvar o progresso do desenvolvimento e 
criar uma linha do tempo sobre o que foi criado naquele momento..
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [ ] Programar todas as funcionalidades
- [X] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: Garantir que o Scrum seja entendido e aplicado.
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15:  As branchs são criadas para realizar o desenvolvimento da possível tarefa ou história de usuário.
Já o merge, ele é utilizado para juntar as branchs em um único código..
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
1- git clone url do projeto..... Aqui acontece a clonagem através da URL do repositório.. 
2- git checkout -b nova-branch..... a criação da branch individual..
3- Realizado o desenvolvimento do código dentro dessa branch...
4- git add . / git add o-projeto... Salva as alterações no Git..
5- git commit -m "nome do commit"... realizado o commit dentro da branch..
6- git push nome-da-branch... busca e envia a branch pro github..

```
---