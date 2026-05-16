
---

# avaliacao.md

```md
# Avaliação Teórica — Scrum, Kanban, Git e Gerenciamento de Configuração

Aluno: Gabriel Dos Anjos Lucim 

Matrícula: 20241PVAI10030005

Branch: avaliacao-gabriel-lucim

---

# Questão 1

Explique com suas palavras o que é um Processo de Desenvolvimento de Software.

```text
Resposta Questão 1: Trata-se de um conjunto de atividades relacionadas que levam à produção de um produto de software
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
Resposta Questão 3: 

Product Backlog: Trata-se da lista de tudo que é necessário no produto, está lista nunca pode ser denominada como completa, histórias de usuários mais altas no quadro Kanban são mais claras e tem prioridade maior para serem desenvolvidas, além disso está lista pode ser atualizada pelo PO constantemente.

Sprint Backlog: Trata-se do conjunto de tarefas/funcionalidades/histórias selecionados do product backlog para incremento durante o período da sprint.
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
Resposta Questão 5: 

Épico: Grande fatia do produto, composta por uma coleção de histórias de usuário, podendo ser descrito como fluxo de trabalho, papel, entre outros.

História de Usuário: Experiência do usuário com a aplicação naquele determinado setor, tendo um conjunto de tarefas que devem ser realizadas e o critério de aceitação para validação no desenvolvimento, como exemplo; uma tela de login, a qual possui diversas tarefas que devem ser implementadas para uma boa experência de usuário.

Tarefa: Uma funcionalidade que deve ser implementada no produto, como exemplo; um botão para direcionamento ou envio de dados.
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
Resposta Questão 7: 

Uma branch é um banco de dados para desenvolvimento de componentes do produto, é nela onde será armazenado tudo que está sendo desenvolvido no setor que ela foi designada, por exemplo, branch de uma dashboard, nesta branch é onde será armazenado tudo que está sendo desenvolvido pelo DEV ou uma equipe de DEV que trabalham na dashboard, além de possuir meta-informações sobre as mudanças que foram feitas, branchs são utilizadas para que o desenvolvimento não aconteça direto no código original do produto, o que corre grandes riscos de ocasionar em erros fatais por um desenvolvimento tratar-se de alterações constantes. Sendo assima  branch mantém o código original seguro, enquanto todos os testes e validações são feitos na branch, para só depois de todas as verificações e e funcionalidades corretas serem implementadas, o código original ser atualizado para a versão mais recente.
```
---

# Questão 8

Qual das alternativas abaixo representa um commit seguindo um padrão adequado?

- [ ] atualização
- [ ] commit final
- [x] feat(login): adiciona autenticação de usuários
- [ ] alteracoes diversas

```text
Resposta Questão 8: 
```
---

# Questão 9

Explique o que é gerenciamento de configuração.

```text
Resposta Questão 9: 

Baseia-se na gestão de versões e itens de configuração de um produto, mantendo um gerenciamento padrão de baselines, codelines, merging, mainline, release, branchs e versões do produto final 
```
---

# Questão 10

Descreva uma vantagem da utilização de Kanban em equipes de desenvolvimento de software.

```text
Resposta Questão 10: 

O Kanban possui uma implementação de experiência mais facilitada e intuitiva para desenvolvimento, como pode-se ver no quadro Kanban, aonde todas as informações são minuciosamente escritas de forma simples e intuitiva, descrevendo tudo que deve ser feito, como será utilizado, por quem será utilizado, e os critérios para que aquela funcionalidade esteja de acordo com o produto.
```
---

# Questão 11

Qual a finalidade do comando abaixo?

```bash
git checkout -b minha-branch
```
```text
Resposta Questão 11: 

acessar a branch "minha-branch".

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
Resposta Questão 13: 

A utilização de commits frequentes é uma boa prática pelo fato de todo commit ser documentado sobre o que foi alterado e o que foi implementado, assim podendo ter um melhor controle de todas as versões, caso o que foi implementado resulte em um erro fatal, é possível voltar em algum outro commit recente onde esse erro não persiste, caso a frequencia de commits seja baixa, com várias funcionalidades diferentes implementadas em poucos commits, pode resultar na confusão de compreender o que foi feito e o que foi alterado, além de um erro fatal poder ocasionar na necessidade de voltar ao commit anterior que tenha muito desenvolvimento atrasado comparado ao que estava sendo desenvolvido e não commitado, sendo necessário refazer tudo novamente.
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
Resposta Questão 15: 

Merge: Criação de nova versão de um componente do sistema baseado na fusão de versões separadas em diferentes branchs.

branch: conjunto de versões de um componente de software e outros itens de configuração dos quais esse componente depende.
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

1-Clonar repositório do GitHub no terminal.
git clone URL(Exemplo: git clone https://github.com/Prova-CS-2026/avaliacao-primeiro-tri.git)

2-Criação da branch a partir da história de usuário no GitHub para separar corretamente e sem confusão de qual história aquela branch se trata.
Acessar a história a qual será desenvolvida no GitHub, no quadro Kanban, veja ao lado da barra de rolagem, um campo descrito como "Developmet", onde possui um botão para criar uma nova branch para a história selecionada e nomea-lá corretamente, vale ressaltar que é muito importante submeter-se ao desenvolvimento da história e relatar isso no github, para fazer isso é semelhante a criação da branch, ao lado da barra de rolagem da página novamente, possui o campo "Assignees" onde é possível assign yourself para relatar que você está comprometido naquele desenvolvimento

3-Acesso do repositório.
Para acessar o repositório clonado, no terminal insira:
cd nome-repositorio

4-Desenvolvimento na branch criada.
Para acessar a nova branch criada e desenvolver nela, basta inserir no terminal:
git checkout nome-da-branch

5-Registro das alterações realizadas.
Para dar commits e registrar as alterações feitas basta seguir:
add .
git commit -m "nomenclatura do commit"


6-Envio das alterações para o servidor remoto.
Comando que envia os commits registrados ao servidor remoto:
git push
```
---