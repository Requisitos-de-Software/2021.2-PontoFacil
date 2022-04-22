# NFR framework

## Histórico de versão

|Data | Versão | Modificação | Autor(es)|
| -- | -- | -- | -- |
| 07/03/2022 |  0.1   | Criação do documento e Metodologia|  [José Luís](https://github.com/joseluis-rt)|
| 07/03/2022 |  0.2   | Introdução |  [Klyssmann Oliveira](https://github.com/klyssmannoliveira)|
| 07/03/2022 |  0.3   | Metodologia |  [José Luís](https://github.com/joseluis-rt)|
| 07/03/2022 |  0.4   | Criação dos Diagramas |  [José Luís](https://github.com/joseluis-rt) e [Klyssmann Oliveira](https://github.com/klyssmannoliveira)|
| 08/03/2022 |  0.5   | Revisão do documento |  [Kayro César](https://github.com/kayrocesar) e [Eduardo Maia](https://github.com/eduardomr)|
| 19/04/2022 |  0.6   | Implementando legendas |  [José Luís](https://github.com/joseluis-rt)|
| 20/04/2022 |  1.0   |    Melhoria da metodologia   | [Klyssmann Oliveira](https://github.com/klyssmannoliveira)|





## 1. Introdução

<p style="text-align: justify">Diferentemente das abordagens orientadas à funcionalidade, o NFR Framework usa requisitos não funcionais, como por exemplo a segurança, eficiência, desempenho e custo para conduzir o processo geral de design. O <i>Framework</i> visa colocar os requisitos não funcionais em primeiro lugar na mente do desenvolvedor (CHUNG, 2012). </p>

<p style="text-align: justify"> Deste maneira, utiliza-se de um conceito que não possui um critério de satisfação preciso ou um objetivo claro para representar um requisito não funcional, chamado de <i>softgoal</i>. Assim, é possível visualizar o funcionamento do <i>NFR Framework</i> através de um SIG (<i>Softgoal Interdependency Graph</i>), que é um gráfico de interdependência entre os <i>softgoals</i> (SILVA, 2019)</p>

## 2. Metodologia

<p style="text-align: justify"> Por meio do NFR Framework procuramos estabelecer as funcionalidades dos requisitos não-funcionais através da implementação de diagramas e  análises de suas possíveis propagações. Além disso, por meio dos softgoals, que registram as considerações do desenvolvedor a respeito dos softgoals e mostra suas interdependências, conseguimos decompor e organizar os grafos. Os autores se reuniram por meio da ferramenta de comunicação <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/planejamento/ferramentas/">Discord</a> e para realização dos diagramas foi utilizado o <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/planejamento/ferramentas/">Lucidchart</a>. Ademais, para o desenvolvimento do documento os autores simularam a introspecção dos desenvolvedores do aplicativo e participação de um usuário real, Klyssmann de Oliveira, que utiliza o aplicativo para o controle pessoal do banco de horas da empresa onde trabalha.</p>

</br>

**Legenda**

Os tipos de contribuição utilizados nos diagramas foram:


- AND: Caso os softgoals descendentes sejam satisfeitos, serão também os ascendentes.

- OR: Caso algum softgoal descendentes seja satisfeitos, será também os ascendente.

<center>

<figcaption>Figura 8: Legenda</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/legenda.png"></p>

<figcaption>Fonte: Elaboração dos autores</figcaption>

</center>

## 3. Requisitos não funcionais

### Lista de requisitos e suas prioridades
|Identificação | Requisito | Técnica |
| -- | -- | -- |
| RNF01 |O aplicativo deve ter opções de linguagem (português e inglês) | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) |
| RNF02 | O Sistema deverá ser acessível por meio de dispositivos móveis | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) |
| RNF03 | O aplicativo deve ter opções de tema (claro e escuro) | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) |
| RNF04 | O aplicativo deve garantir a segurança dos dados do usuário | [Questionário](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/) |
| RNF05 |O Sistema deve ter layout compreensível e objetivo | [Questionário](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/) |
| RNF06 | O aplicativo deve possuir interface acessível e intuitiva | [Questionário](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/) |
| RNF07 | O aplicativo deve ser capaz de armazenar o backup em contas do Google Drive e Dropbox | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) |
| RNF08 | O aplicativo deve ser capaz de calcular o saldo de horas com base no registro do ponto e tolerância | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) |

<div align="justify">



</div><br>

## 4. Diagramas

### 4.1 Geral

<center>
<figcaption>Figura 1: Geral - NFR Framework</figcaption>

<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/geral.png"></p><br>
  
<figcaption>Fonte: Elaboração dos autores</figcaption>
</center>

<br>
  
### 4.2 Usabilidade

<center>

<figcaption>Figura 2: Usabilidade - NFR Framework</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/usabilidade_NFR.png"></p><br>
  

<figcaption>Fonte: Elaboração dos autores</figcaption>
</center>

<br>

### 4.3 Usabilidade Propagação

<center>
<figcaption>Figura 3: Usabilidade Propagação - NFR Framework</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/usabilidade_propagacao_NFR.png"></p><br>
  

<figcaption>Fonte: Elaboração dos autores</figcaption>
</center>

<br>

### 4.4 Segurança

<center>
<figcaption>Figura 4: Segurança - NFR Framework</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/seguranca_NFR.png"></p><br>
  

<figcaption>Fonte: Elaboração dos autores</figcaption>

</center>

<br>

### 4.5 Segurança Propagação

<center>

<figcaption>Figura 5: Segurança Propagação - NFR Framework</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/seguranca_propagacao_NFR.png"></p><br>
  

<figcaption>Fonte: Elaboração dos autores</figcaption>

</center>

<br>

### 4.6 Suportabilidade

<center>
  
<figcaption>Figura 6: Suportabilidade - NFR Framework</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/suportabilidade_NFR.png"></p><br>

<figcaption>Fonte: Elaboração dos autores</figcaption>

</center>

<br>

### 4.7 Suportabilidade Propagação

<center>

<figcaption>Figura 7: Suportabilidade Propagação - NFR Framework</figcaption>
<p align = "center"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-PontoFacil/master/docs/assets/imagens/propagacao_suportabilidade.png"></p><br>
  
<figcaption>Fonte: Elaboração dos autores</figcaption>

</center>

<br>

## 5. Referências

> CHUNG, Lawrence et al. Non-functional requirements in software engineering. Springer Science & Business Media, 2012.

> SILVA, Reinaldo Antônio da. Nfr4es: Um catálogo de requisitos nao-funcionais para sistemas embarcados. 2019. Dissertação de Mestrado. Universidade Federal de Pernambuco.
