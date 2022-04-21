
## Histórico de versão


 | **Data**   | **Versão** | **Descrição**                            |                **Autor(es)**                 |
 | ---------- | :--------: | ---------------------------------------- | :------------------------------------------: |
 | 22/03/2022 |    1.0     |  Criação do documento e elaboração de texto     |        [Kayro César](https://github.com/kayrocesar)         |

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
   A verificação pode ser considerada como uma análise de modelos, sendo que essa tarefa é desempenhada tanto por seres humanos quanto por software e segue regras bem definidas de acordo com modelo a ser analisado. A verificação é importante para analisar se existe algo errado nos modelos em termos de notações, processos, procedimentos e se esse modelo está de acordo com o que é esperado dele.
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
   Utilizaremos o método de verificação por inspeção. O objetivo básico da inspeção é verificar se o modelo está de acordo com a notação e com o que é esperado desse modelo. Para auxiliar no processo de planejamento e execução da inspeção, utilizaremos o método de Fagan que é composto por algumas etapas, que são descritas a seguir:
</p>

### 2.1 Planejamento
<p style="text-indent: 20px; text-align: justify">
        No planejamento, toda a equipe se reunirá para se familiarizar com o processo de verificação por inspeção e para seguir um determinado padrão na inspeção dos artefatos.
</p>

### 2.2 Visão Geral

<p style="text-indent: 20px; text-align: justify">
       A visão geral está relacionada com a visualização do projeto como um todo e nos documentos a serem verificados. O seguintes documentos serão verificados:
</p> 

 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/pre_rastreabilidade/5w2h/">5w2h</a> <br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/modelagem/NFR_framework/">NFR Framework</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/">MoSCoW</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/pre_rastreabilidade/rich_pictures/">Rich Picture</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/modelagem/backlog/backlog/">Backlog</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/modelagem/casos_de_uso/">Casos de Uso</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/modelagem/cenarios/">Cenários</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/modelagem/lexicos/">Léxicos</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/modelagem/especificacao_suplementar/">Especificação Suplementar</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/">Brainstorming</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/">Questionário</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/">Observação</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/">Introspecção</a><br>
 <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/personas/">Personas</a><br>

### 2.3 Preparação
<p style="text-indent: 20px; text-align: justify"> Todos os inspetores deverão utilizar uma tabela com itens a serem verificados no artefato indicando o status do item mencionado, se o item está presente e/ou correto ou se o item está ausente e/ou incorreto. Também deve ser classificado o tipo de erro em cada item a partir da tabela abaixo.</p>
<br>
<center>
<figcaption>Figura 1: Tabela de tipos de erros</figcaption>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/a5e998f752ba2f508f6c6c3ccfea7a7d59520f29/docs/assets/imagens/template_verificacao_tab.PNG">
<figcaption>Fonte: Elaboração dos autores</figcaption>
</center> 
<br>
<p>A partir dos erros apresentados acima os itens devem ser classificados seguindo o modelo da tabela abaixo.</p>
<center>
<figcaption>Figura 2: Tabela modelo</figcaption>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/a5e998f752ba2f508f6c6c3ccfea7a7d59520f29/docs/assets/imagens/template_verificacao_tab_vazia.PNG">
<figcaption>Fonte: Elaboração dos autores</figcaption>
</center> 


<br>
<p>Também deve ser apresentado um gráfico com a representação visual dos itens verificados na tabela de checklist. Um exemplo de gráfico é mostrado abaixo</p>

<br>

<center>
<figcaption>Figura 3: Gráfico modelo</figcaption>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/a5e998f752ba2f508f6c6c3ccfea7a7d59520f29/docs/assets/imagens/template_verificacao.PNG">
<figcaption>Fonte: Elaboração dos autores</figcaption>
</center> 

<p>Ao final da inspeção deve haver uma conclusão relatando as impressões detectadas no checklist em questão.</p>

### 2.4 Inspeção
<p style="text-indent: 20px; text-align: justify">
    Todos os inspetores executam a inspeção seguindo o padrão estabelecido no planejamento.
</p>

### 2.5 Correção
<p style="text-indent: 20px; text-align: justify">
   Após o fim da inspeção, os problemas encontrados no artefato em questão devem ser corrigidos.
</p>

### 2.6 Acompanhamento

<p style="text-indent: 20px; text-align: justify">
        Após a correção, outro integrante do grupo deverá acompanhar e avaliar se as correções realizadas foram executadas corretamente e se podem ser integradas ao projeto sem maiores problemas. 
</p>


      

## 3. Referências bibliográficas

> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 23. 19 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

