
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Francisco Simoes de Oliveira

Matrícula: 20241PVAI10030033

Branch: https://vscode.dev/github/Prova-CS-2026/avaliacao-primeiro-tri/tree/francisco-prova
```
---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Processo de Desenvolvimento e o que dita como sera feito algo, de todas as estapas 
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
Resposta Questão 3: Product Backlog são as historias de todo o projeto onde o unico a mecher e o PO, Já a sprint Backlog e composta por historias retiradas do product Backlog que serão implementadas na sprint atual
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
Resposta Questão 5: Epico e um grande recorte do projeto e sera composto por historias, uma historia e uma parte de um epico para a incrementação de uma funcionalidade, e a tarefa são requisitos para a comclusão da historia
```
---

# Questão 6

Qual alternativa representa corretamente uma História de Usuário?

- [ ] O sistema deverá validar login
- [ ] Criar endpoint REST
- [x] COMO usuário QUERO autenticar PARA acessar o sistema
- [ ] Corrigir bug da tela inicial

```text
Resposta Questão 6:  COMO usuário QUERO autenticar PARA acessar o sistema
```
---

# Questão 7

O que é uma branch no Git e qual sua finalidade?

```text
Resposta Questão 7: E uma "linha", seria ramificaçoes que são usados para serem alterados sem mecher nas branch principais, e so depois de validas serão fundidas por meio de merge em sua branch principal
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
Resposta Questão 9: e a parte de configurar o seu repusitorio, onde se coloca as permisoes, bloqueia push direta para branch especificas e etc
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: seria a organização, o quadro permite uma maior autonomia da equipe, alem de definir bem o que possivelmente sera implementa, o que esta para ser implementado, o que esta sendo desenvolvido e por quem, e o que ja foi implementado
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: trocar a branch que vc esta, sempre que clonado vc estara na branch principal, emtão para poder acessar a sua branch deve-se fazer este comando
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
Resposta Questão 13: O salvamento de versoes, a cada commit vc tem certeza que esta salvo e que pode retornar a qualquer momento a ela
```
---

# Questão 14

Qual alternativa representa corretamente uma atividade típica do Scrum Master?

- [ ] Definir sozinho todas as tarefas
- [x] Programar todas as funcionalidades
- [ ] Garantir que o Scrum seja entendido e aplicado
- [ ] Aprovar somente código front-end

```text
Resposta Questão 14: Garantir que o Scrum seja entendido e aplicado
```
---

# Questão 15

Explique a diferença entre merge e branch no Git.

```text
Resposta Questão 15: Como respondido anteriormente a branch e uma ramifição, que sera alterada dado o seu proposito, e depois de finalizar o que tinha para fazer, pode-se fazer o merge, que seria a fusão de branch, então se eu tenho uma branch de uma pagina de login, pos terminar eu vou pedir para fazer um merge com a dev, assim passado todos os commits para a linha temporal da dev e os arquivos
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
1. git clone URL_DO_repusitorio // clonando o repusitorio
2. git branch nome-branch // criando a nova branch
3. git checkout -b nome-branch // migrando para a branch
4. git add . // Isso aceita todas as alteraçoes mas pode fazer arquivo por arquvo
5. git commit -m "msg" //Para o registro das alteraçoes aceitas
6. git push -u origin nome-branch // para mandar os commits para a rede remota, se a branch não estiver publicada ela sera neste momento
7. git pull -u origin main/dev //aqui serve para baixar as alteraçoes da branch que vc deseja fazer um pull request, caso tenha a probabilidade de outras branchs ja terem feito o merge
8. git push -u origin main/dev // aqui o pull request foi feito, e se estiver configurado certo entrara em espera ate ser validado por algum 

```
---