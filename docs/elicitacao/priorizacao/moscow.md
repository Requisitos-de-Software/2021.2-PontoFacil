# <center> MosCoW


## Histórico de versão<br>

|    Data    | Versão |                Modificação                |       Autor        |
| :-------- | :---- | :--------------------------------------- | :---------------- |
| 14/02/2022 |  0.1   | Criação do documento e elaboração do texto |  [Eduardo Maia](https://github.com/eduardomr)   |
| 16/02/2022 |  0.2   | Inserção dos requisitos e sua classificação |  [Eduardo Maia](https://github.com/eduardomr)   |
| 19/02/2022 |  0.3   | Revisão do documento |  [Lorenzo Santos](https://github.com/lorenzo7377)   |
| 19/02/2022 |  0.4   | Correção de Links |  [Eduardo Maia](https://github.com/lorenzo7377)   |
| 20/04/2022 |  1.0   |    Melhoria da metodologia   | [Klyssmann Oliveira](https://github.com/klyssmannoliveira)|

## 1. Introdução

<p align="justify">&emsp;
  MoSCoW é  um método que tem o intuito de encontrar um entendimento em comum entre as partes interessadas no projeto sobre a importância que elas atribuem a cada requisito. Essa técnica está ligada às metodologias ágeis e define a prioridade dos requisitos de um sistema ou projeto.
O nome dessa técnica é dada devido as classificações de prioridade possíveis:
</p>




* Must: tarefas que vão agregar valor ao produto final e são indispensáveis;
* Should: os requisitos que recebem essa prioridade são aqueles que são importantes mas não são vitais para o sistema;
* Could: são requisitos que seriam desejáveis, porém não são estrategicamente essenciais;
* Would/Want/Won't : requisitos menos críticos que possuem menor retorno sobre o investimento quando comparado a outros.

## 2. Metodologia

Para a elaboração deste documento, o autor analisou os documentos e artefatos utilizados nas técnicas de elicitação de requisitos e, desta forma, realizou-se as classificações dos requisitos com base nos princípios MoSCoW.


## 3. Resultados

### Proporções entre as classificações
| Prioridade | Quantidade de Requisitos |
| -- | -- |
| Must | 11 |
| Should | 13 |
| Could | 9 |
| Would | 9 |

<p align = "center"><img src="../../../assets/imagens/moscow.png" width="700"><br>Figura 01 - Gráfico de pizza representando as proporções de requisitos classificados como Must, Should, Could e Would</p><br>

### Lista de requisitos e suas prioridades

|Identificação | Requisito | Técnica | Prioridade |
| -- | -- | -- | -- |
| RF01 | O usuário deve ser capaz de registrar o ponto de entrada | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Must |
| RF02 | O usuário deve ser capaz de registrar o ponto de saída | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Must |
| RF03 | O usuário deve ser capaz de registrar o ponto de saída para o almoço | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Must |
| RF04 | O usuário deve ser capaz de guardar informações do horário de trabalho  para cada dia da semana | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Must |
| RF05 | O usuário deve ser capaz de apagar registros passados | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Should |
| RF06 | O usuário deve ser capaz de copiar registros passados | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Could |
| RF07 | O usuário deve poder inserir o saldo de horas já existente | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Should |
| RF08 | O usuário deve registrar o ponto de retorno do almoço | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Must |
| RF09 | O usuário deve ser capaz de configurar os horários de entrada e saída do dia de acordo com registros do mesmo dia | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Could |
| RF10 | O usuário deve ser capaz de configurar o horário e o dia do backup | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Would |
| RF11 | O usuário deve ser capaz alterar as opções de intervalo, como por exemplo definir um horário de intervalo mínimo | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Could |
| RF12 | O aplicativo deve ser capaz de identificar inconsistências no registro de ponto, como por exemplo a ausência de registro no dia | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Should |
| RF13 | O usuário deve ser capaz de registrar o ponto eletrônico através de uma Tag NFC | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Would |
| RF14 | O aplicativo deve ser capaz de armazenar a tolerância da jornada de trabalho | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Should |
| RF15 | O usuário deve ser capaz de zerar o saldo de horas total | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Should |
| RF16 | O usuário deve ser capaz de visualizar seu banco de horas no período desejado no formato de gráfico de linhas | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Could |
| RNF01 |O aplicativo deve ter opções de linguagem (português e inglês) | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Would |
| RNF02 | O Sistema deverá ser acessível por meio de dispositivos móveis | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Must |
| RNF03 | O aplicativo deve ter opções de tema (claro e escuro) | [Brainstorming](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/brainstorming/) | Would |
| RNF04 | O aplicativo deve garantir a segurança dos dados do usuário | [Questionário](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/) | Must |
| RNF05 |O Sistema deve ter layout compreensível e objetivo | [Questionário](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/) | Could |
| RNF06 | O aplicativo deve possuir interface acessível e intuitiva | [Questionário](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/questionario/) | Could |
| RF17 | O usuário deve ser capaz de registrar falta | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Should |
| RF18 | O usuário pode adicionar uma foto do registro do ponto | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Should |
| RF19 | O usuário deve ser capaz de configurar as notificações que o aplicativo informa (aviso de horário de entrada, saída, intervalo) | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Would |
| RF20 | O usuário pode optar por idiomas (português e inglês) | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Would |
| RF21 | O usuário deve ser capaz de visualizar seus registro no dia, na semana e no mês | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Must |
| RNF07 | O aplicativo deve ser capaz de armazenar o backup em contas do Google Drive e Dropbox | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Could |
| RF22 | O usuário deve ser capaz de configurar a qualidade e resolução da foto armazenada | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Would |
| RNF08 | O aplicativo deve ser capaz de calcular o saldo de horas com base no registro do ponto e tolerância | [Introspecção](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/introspeccao/) | Must |
| RF23 | O usuário pode ser capaz de apagar todos os registros | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Must |
| RF24 | O usuário deve ser capaz de ativar a notificação de alarme | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Could |
| RF25 | O usuário deve ser capaz de filtrar os parâmetros do gráfico de linhas (primeiro ponto, ponto de saída, saldo total, saldo do dia) | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Would |
| RF26 | O usuário deve ser capaz de registrar folga | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Should |
| RF27 | O Usuário deve ser capaz de consultar o saldo de horas do dia | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Should |
| RF28 | O usuário deve ser capaz de fazer um backup dos seus registros automaticamente em nuvem ou local | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Could |
| RF29 | O usuário deve ser capaz de editar registro passados | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Should |
| RF30 | O usuário deve ser capaz de registrar férias | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Should |
| RF31 | O usuário deve ser capaz de escrever uma descrição para cada registro | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Would |
| RF32 | O Usuário deve ser capaz de gerar um extrato dos seus registros de acordo com os parâmetros que ele quiser | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Should |
| RF33 | O Usuário deve ser capaz de consultar o saldo de horas total (do mês) | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Must |
| RF34 | O usuário deve ser capaz de registrar hora extra | [Observação](https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/tecnicas/observacao/) | Should |



<div align="justify">



</div><br>


## 4. Referências

> BECKER , Alice. Aprenda como o método MoSCoW poderá ajudá-lo a priorizar as tarefas da sua empresa. 1 ago. 2020. Disponível em: https://www.voitto.com.br/blog/artigo/metodo-moscow. Acesso em: 16 fev. 2022.
