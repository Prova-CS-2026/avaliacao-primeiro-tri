
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Felipe Fabris Leite Victorino

Matrícula: 20241PVAI10030041

Branch: avaliacao-felipe-victorino
```
---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
O Processo de desenvolvimento de software consiste em todas as ações realizadas pelos desenvolvedores e gerentes de uma equipe que resultam na geração de um artefato incremental, que traz valor aos stakeholders interessados com o desenvolvimento daquele software. Esse processo pode ou não pode ter a utilização de frameworks, etapas ou filosofias de desenvolvimentop, mas em geral se busca adquirir o máximo de valor para a realização de um software que atenda as necessidades requisitadas.
```


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
Resposta Questão 3: O Product Backlog é definido como um artefato do projeto que contém todos os requisitos necessários para o sistema existir. O Sprint Backlog por outro lado consiste no artefato que contém todos os requisitos que devem ser realizados em uma sprint para atingir a definicição de feito e gerar um incremento.
```
---

# Questão 4

Qual o principal objetivo de uma Sprint?

- [ ] Criar documentação definitiva
- [x] Entregar incremento funcional do produto
- [ ] Corrigir apenas bugs críticos
- [ ] Substituir reuniões diárias

```text
Resposta Questão 4: A sprint tem como seu artefato gerado o incremento, que representa tudo que foi realizado no período da sprint. 
```
---

# Questão 5

Explique a diferença entre Épico, História de Usuário e Tarefa.

```text
Resposta Questão 5: O épico é uma definição de uma parte do projeto que consolida um objetivo único, o progresso realizado, o valor adquirido e as necessidades especificas. Uma história de usuário é um elemento que consolida as necessidades de um ou qualquer usuário, buscando visualizar as suas necessidades. As histórias são contidas em um épico. As tarefas consistem em partes pequenas para serem desenvolvidas em uma sprint, uma tarefa pode ser uma história de usuário ou uma tarefa técnica independente como um bugfix.
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
Resposta Questão 7: Uma branch é uma divisão de versionamento nomeada. Ela tem a função de agregar commits relacionados para então se ter uma revisão e adição em um momento oportuno. Ao usar branchs tanto bugs como testes serão limitados a aquela versão, sem afetar as linhas principais oou base.
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
Resposta Questão 9: O gerenciamento da configuração é
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: O kanban representa o progresso de todas as ações necessárias para o sistema estar em uma definição de completo. Cada tarefa passa por etapas até a sua conclusão, e entre cada etapa se há uma validação daquela tarefa, fazendo com que cada parte inidividual do sistema seja desenvolvida sem conflitos entre partes e com validações constantes.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: O comando 'git checkout' troca a branch atual para uma outra, no caso 'minha-branch'. A flag '-b' no caso irá criar a branch caso ela não existir. Em conjunto o comando irá criar uma branch se ela não exisitir e automaticamente alterar a vizualização para ela
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
Resposta Questão 13: Commits frequentes irão representar o progresso daquela seção de desenvolvimento, demonstrando as várias partes que compoões aquele projeto. E no caso que uma alteração errõnea tenha sido feita, os commits realizados podem ser revertidos sem afetar outras adições ao sistema sem grandes paradas para refatoração.
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
Resposta Questão 15: O merge é uma ação de mesclagem que se opera entre duas branches, um merge consiste na análise e mesclagem dos históricos de cada branch, considerando adições remoções e mudanças de arquivos, a masclagem deles e caso não haja conflitos, a atualização da branch onde o merge ocorreu. A branch como operando de um merge é um conjunto nomeado de commits, formando um histórico paralelo a outra branch. 
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

Considerando um repositório existente, é necessário ter um link para aquele reposítório, tanto HTTPS quant SSH, mas geralmente o HTTPS é mais comum.

O comando 'git clone <link>' irá criar uma cópia dos arquivos e histórico de arquivos localmente. Issó permitirá o desenvolvimento em um dispositivo não remoto, geralmente o seu próprio.

Após a clonagem, uma branch individual deve ser feita para não alterar a branch principal, a criação de uma nova branch pode ser feita com o comando 'git branch <nome-da-branch>', para entra trocar para a nova branch se usa 'git checkout <nome-da-branch>'. Existe também uma versão mais curta dessa sequência, onde se usa o 'git checkout -b <nome-da-branch>' para criar e trocar para uma nova branch.

Com a branch criada, pode então modificar os arquivos daquele repositório. Cada modificação não é versionada automaticamente, é preciso marcar as mudanças par ao preparo de um commit, para adicionar um arquivo ao preparo se usa 'git add </caminho/do/arquivo>'. Isso adicionará os arquivos para o preparo recursivamente, ou seja ele também adicionará pastas e o conteudo dentro das pastas, usar o comando 'git add .' no diretório principal adicionara todas as modificações para alteração.

Com alterações suficientes se pode criar um commit com comando 'git commit -m "descrição do commit"', isso irá salvar todas as mudancas na branch atual como um commit. Um commit não é facilmente revertido, ficando permanentemente no histórico da branch, mas ele pode ser alterao com um outro commit posteriormente.

Quando se agrega commits o suficiente se pode
```
---