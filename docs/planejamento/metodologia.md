# Metodologia

## Histórico de versão

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 02/02/2022 | 0.1 | Criação da primeira versão do documento | [@klyssmannoliveira](https://github.com/klyssmannoliveira) |
| 03/02/2022 | 0.2 | Criação da política de branchs | [@Lorenzo7377](https://github.com/Lorenzo7377) |
| 22/04/2022 | 0.3 | Deleção da política de branchs | [@Lorenzo7377](https://github.com/Lorenzo7377) |


## Introdução

<p style='text-align: justify;'>Quando se fala em metodologia de desenvolvimento de um software logo se pensa em desenvolvimento ágil. Essa ampla adoção de metodologias ágeis culminou no movimento ágil em 2001. Assim, visando um desenvolvimento mais colaborativo com equipes multidisciplinadas, este produto foi desenvolvido com base nos ritos do SCRUM.</p>

<p style='text-align: justify;'>O SCRUM é uma estrutura simples e iterativa para o gerenciamento de projetos, seguindo os principais princípios: flexibilidade dos resultados, times pequenos, revisões constantes (denominadas de sprints) e coloboração mútua. Por se tratar de uma disciplina de requisitos, teremos apenas os papéis de Scrum Master e Product Owner.</p>

## Papéis

### Scrum Master
* Ajudar todos do Time a entenderem a metodologia e atividades ágeis utilizadas;
* Atuação em equipe com o Product Owner;
* Dimensionamento de responsabilidades e tarefas;
* Documentar cada Sprint;
* Auxiliar a equipe na melhor forma da solução de um problema, removendo impedimentos no desenvolvimento do projeto.


### Product Owner
* Responsável pelo gerenciamento do Backlog do Produto e por garantir o valor do trabalho realizado pelo Time;
* Manter o contato com o cliente;
* Assegurar que os Desenvolvedores entendam o Backlog do produto;
* Mostrar a visão do produto em um documento.


## Atividades da Metodologia
<p style='text-align: justify;'>O presente documento tem como objetivo elicitar as ferramentas utilizadas para poder cumprir os ritos do SCRUM.</p>

### Sprint
* É o período determinado pela equipe para a definição e realização das tarefas;
* Duração de uma semana com início toda terça-feira;
* É documentado pelos arquivos de abertura e fechamento das sprints.

### Planejamento da Sprint

* Reuniões entre o Scrum Master e o Product Owner para o planejamento das tarefas e atividades (issues);
* Definição do pareamento da equipe parar a elaboração das tarefas em conjunto.

### Revisão da Sprint

* Reunião com toda a equipe para a revisão do que foi entregue em cada atividade (issue);
* Verifica-se, nessa reunião, o cumprimento das atividades atribuídas para cada membro;
* Caso haja débito, observa-se o motivo e a atividade é repassada ou dividida para próxima sprint.

### Retrospectiva da Sprint

* Reunião com toda a equipe para a discussão dos pontos positivos e negativos da sprint;
* Elaboração de um plano de melhorias para os pontos negativos.

## Atividades do Extreme Programming (XP)

<p style='text-align: justify;'>O XP é uma metodologia focada em agilidade de equipes e qualidade de projetos, apoiada em valores como simplicidade, comunicação e feedback.</p>

### Pair Programming

* Trata-se da elaboração de duplas para o desenvolvimento de alguma tarefa do projeto.

### Daily Meeting

* Reunião rápida com no máximo 15 minutos para o acompanhamento das atividades.

### Rodízio de pessoas

* Rodagem das pessoas da equipe em cada um dos papéis ágeis.


## Cronograma de encontros

|  Dia | Horário  | Integrantes  |  Objetivo |
|:-:|:-:|:-:|:-:|
|  Terças e Quintas |  Após a aula |  todos os integrantes | Reunião interna de cada time  |
|  Quintas |  20h |  Product Owners e Scrum Masters | Alinhamento de informações e definição da Sprint subsequente |

## Política de Commits

<p style='text-align: justify;'>Os commits são essenciais para acompanharmos as alterações e adições ao projeto.</p>

<p style='text-align: justify;'>Deve ser usado o modo imperativo (ações e ordens assertivas) para mencionar o que foi feito e deve ser feito da seguinte forma:</p>

```
git commit -m "#IdIssue - Mensagem"
```