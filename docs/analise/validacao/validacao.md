# Validação

## Histórico de versão

|Data | Versão | Modificação | Autor(es)|
| -- | -- | -- | -- |
| 22/03/2022 |  0.1   | Criação do documento e introdução |  [Kayro César](https://github.com/kayrocesar) |
| 22/03/2022|  0.2  | Metodologia e protótipo | [Kayro César](https://github.com/kayrocesar) e [Eduardo Maia](https://github.com/eduardomr) |
| 23/03/2022 |  0.3   | Revisão |  [José Luís](https://github.com/joseluis-rt) |



## 1. Introdução

<p style="text-align: justify"> 
   A validação de software é a confirmação de que o produto é realmente o desejado pelo usuário. Esse processo ocorre, geralmente, no fim do ciclo de vida. Existem várias estratégias para validar um software como a comprovação informal, a prototipação e a baseada em ponto de vista. Em nosso projeto utilizaremos a prototipação como a principal estratégia de validação.
 </p>

## 2. Metodologia

<p style="text-align: justify">A prototipação é baseada na ideia de que podemos validar os requisitos/especificações com base nas expectativas do usuário. Ela é proposta com o objetivo de obter uma retroalimentação do universo de informações e pode ser apresentada em linguagem de alto nível ou em linguagens de especificação executáveis. </p>

<p style="text-align: justify">
 Construímos um protótipo que representa alguns dos requisitos elicitados no projeto. A escolha dos requisitos foi baseada na prioridade de cada um, os do tipo "must" e "should" representam a maioria deles.
   A tabela 1 mostra os requisitos presentes no protótipo:
 </p>
 <br>

 <center>
<figcaption>Tabela 1: Requisitos presentes no protótipo </figcaption>
   
|Identificação | Requisito | Prioridade |
| :--: | :--: | :--: |
| [RF01](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de registrar o ponto de entrada | Must |
|[RF02](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)   | O usuário deve ser capaz de registrar o ponto de saída | Must |
| [RF03](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de registrar o ponto de saída para o almoço | Must |
| [RF04](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de guardar informações do horário de trabalho  para cada dia da semana | Must |
| [RF05](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de apagar registros passados | Should |
| [RF06](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de copiar registros passados | Could |
| [RF07](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve poder inserir o saldo de horas já existente | Should |
| [RF08](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve registrar o ponto de retorno do almoço | Must |
| [RF16](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de visualizar seu banco de horas no período desejado no formato de gráfico de linhas | Could |
| [RNF02](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O Sistema deverá ser acessível por meio de dispositivos móveis | Must |
| [RNF05](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)   |O Sistema deve ter layout compreensível e objetivo | Could |
| [RNF06](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O aplicativo deve possuir interface acessível e intuitiva | Could |
| [RF18](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário pode adicionar uma foto do registro do ponto | Should |
| [RF21](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de visualizar seus registro no dia, na semana e no mês | Must |
| [RF23](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário pode ser capaz de apagar todos os registros |  Must |
| [RF27](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O Usuário deve ser capaz de consultar o saldo de horas do dia |  Should |
| [RF29](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de editar registro passados |  Should |
| [RF31](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O usuário deve ser capaz de escrever uma descrição para cada registro |  Would |
| [RF33](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/priorizacao/moscow/)  | O Usuário deve ser capaz de consultar o saldo de horas total (do mês) |  Must |


<figcaption>Fonte: Elaboração dos autores </figcaption>
</center>

### 2.1 Protótipo


<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FSW8QdAxkEQd84Y7IHtT2CH%2FRequisitos%3Fnode-id%3D2%253A6%26scaling%3Dscale-down%26page-id%3D0%253A1%26starting-point-node-id%3D2%253A6" allowfullscreen></iframe>


## 3. Conclusão

<p style="text-align: justify">
  Concluimos que os requisitos escolhidos foram validados através do protótipo, o mesmo se mostrou funcional e objetivo na satisfação das necessidades descritas pelos requisitos.
 </p>


## 4. Referências

> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 23. 52 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

