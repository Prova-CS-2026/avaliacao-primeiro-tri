
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Daniel Alves Moura

Matrícula: 20241PVAI10030023

Branch: daniel-alves-moura

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: É uma sequência de ações e etapas executadas com o objetivo de produzir um software completo.
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
Resposta Questão 3: Product Backlog possui todos os épicos e histórias de usuário descrevendo o valor que deve ser gerado e incrementado no produto final. Apenas o Product Owner deverá alterar o Product Backlog pois é ele quem tem contato direto com os Stakeholders e conhece integralmente o produto desejado.
Sprint Backlog possui as histórias que descreverão o valor a ser gerado durante a sprint atual pelos desenvolvedores, que transformaram essas histórias em incrementos funcionais até o final da sprint. Um Product Backlog alimentará diversos Sprint Backlogs.
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
Resposta Questão 5: Épico é uma descrição de uma parte ampla e pouco detalhada do produto. Um épico é dividido em uma ou mais histórias de usuário que descrevem um valor a ser gerado ao épico, e consequentemente, ao produto. Uma história de usuário possui diversas tarefas que são funcionalidades necessárias para produzir o valor descrito pela história de usuário.
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
Resposta Questão 7: Uma branch é uma ramificação da linha de desenvolvimento original que acontece simutaneamente a outras onde será desenvolvido os novos incrementos antes de serem enviados para a linha principal. 
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
Resposta Questão 9: É o processo de criação e atualização das definições da área de armazenamento compartilhado de versões, ou seja, do repositório.
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: O uso do kanban facilita significativamente o trabalho em equipe pois cada desenvolvedor sabe exatamente o que precisa ser desenvolvido, o que já está sendo desenvolvido e por quem, e o que já foi desenvolvido. Em outras palavras, possibilita maior organização. 
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: Trocar para a branch "minha-branch" e passar a desenvolver nela.
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
Resposta Questão 13: Mantem um histórico atualizado de quais mudanças foram feitas em quais momentos, garante que suas mudanças não sejam perdidas, que mudanças problemáticas possam ser revertidas e que quais mudanças causaram um erro atual pois a última mudança funcional foi próxima da versão atual com erro.
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
Resposta Questão 15: Merge é fundir diferentes branches em uma versão contendo os adicionais de cada uma.
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

1. Clone um repositório já criado através do comando "git clone [url do repositório]". Assim, os arquivos já presentes no repositório serão duplicados para que você os altere.

2. Crie uma branch com o comando "git branch [nome da branch]". Assim, uma ramificação da linha de desenvolvimento será criada para que você altere uma versão separada.

3. Troque para a branch criada com o comando "git checkout [nome da branch]".

4. Após realizar as alterações, adicione os arquivos a serem commitados através do comando "git add [nome do arquivo]", ou utilize "git add ." para adicionar todos os arquivos ainda não adicionados.

5. Realize um commit das alterações feitas através do comando "git commit -m "[mensagem do commit]"".

// Você pode utilizar "git status" e "git log" para ver as alterações, commits e branches existentes.

6. Utilize o comando "git push origin [nome da branch]" para enviar os commits locais para a branch determinada no servidor.
```
---