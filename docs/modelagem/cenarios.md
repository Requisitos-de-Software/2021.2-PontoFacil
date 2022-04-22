# <center> Cenários

### Histórico de versão
|Data | Versão | Modificação | Autor(es)|
| -- | -- | -- | -- |
| 04/03/2022 | 0.1 | Criação do documento | [Lorenzo Santos](https://github.com/lorenzo7377) |
| 06/03/2022 | 0.2 | Revisão | [Klysssmann Oliveira](https://github.com/klyssmannoliveira) |
| 20/04/2022 |  1.0   |    Melhoria da metodologia   | [Klyssmann Oliveira](https://github.com/klyssmannoliveira)|


## 1. Introdução
<p align="justify">&emsp;Cenários são situações imaginários bastante detalhadas que demonstra as pessoas realizando atividades no sistema. Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever
uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da
atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e
avaliar se um produto satisfaz a necessidade dos seus usuários. Sua principal vantagem é o baixo custo quando comparado a outros métodos mais complexos (BARBOSA; SILVA ,2010).</p>

## 2. Metodologia
<p align="justify">&emsp;Para realizarmos essa parte do trabalho, foram inaginadas algumas situações que o usuário do aplicativo pode encontrar no contidiano. Também foi realizado com a participação das <a href="https://requisitos-de-software.github.io/2021.2-PontoFacil/elicitacao/personas/">personas</a> para a construção do artefato. Assim, os elementos dos cenários foram:</p>

<ul>
  <li>Título</li>
  <li>Objetivo</li>
  <li>Contexto</li>
  <li>Autor</li>
  <li>Recursos</li>
  <li>Episódios</li>
  <li>Restrições</li>
  <li>Exceções</li>
</ul>

## 3. Cenários

### C01 - Criar um ponto de entrada
|Elementos | Descrição |
| -- | -- | 
| Título | Criar um ponto de entrada; |
| Objetivo | Registrar um ponto para começar a marcar as horas trabalhadas; |
| Contexto | Pré-condição: Ter o aplicativo instalado;<br> Pós-condição: É criado um ponto de entrada; |
| Autor | Usuário; |
| Recursos | Aplicativo instalado; <br> Acesso ao aplicativo; |
| Episódios | <ol><li>O usuário acessa o aplicativo;</li> <li>O usuário clica no bitão no canto inferior direito;</li> <li>O usuário coloca a hora do ponto, uma descrição e se quer adicionar uma foto ou se é na virada do dia;</li><li>O usuário clica em "Registrar";</li></ol>|
| Restrições | Fluxo intuitivo; |
| Exceções | O aplicativo não estar funcionando;<br>Já existe um ponto no horário selecionado;<br> O aplicativo foi encerrado antes da ação ser completada; |

<br>

### C02 - Criar um ponto de falta ou de feriado
|Elementos | Descrição |
| -- | -- | 
| Título | Criar um ponto de falta/feriado; |
| Objetivo | Registrar um ponto para contar um dia de falta/feriado; |
| Contexto | Pré-condição: Ter o aplicativo instalado;<br> Pós-condição: É criado um ponto de falta/feriado; |
| Autor | Usuário; |
| Recursos | Aplicativo instalado; <br> Acesso ao aplicativo; |
| Episódios | <ol><li>O usuário acessa o aplicativo;</li><li>O usuário clica no "+" no canto superior direito;</li><li>O usuário seleciona "falta/feriado";</li><li>O usuário informa se vai ser o dia todo, quando se repete a falta/feriado, quanto tempo vai durar, qual será a descrição e se ele colocará uma foto;</li><li>O usuário clica em salvar;</li></ol>|
| Restrições | Fluxo intuitivo; |
| Exceções | O aplicativo não estar funcionando;<br>Já existe uma falta/feriado com a mesmas características;<br> O aplicativo foi encerrado antes da ação ser completada; |

<br>

### C03 - Criar um ponto de férias ou de folga
|Elementos | Descrição |
| -- | -- | 
| Título | Criar um ponto de férias/folga; |
| Objetivo | Registrar um ponto para contar um dia de férias/folga; |
| Contexto | Pré-condição: Ter o aplicativo instalado;<br> Pós-condição: É criado um ponto de férias/folga; |
| Autor | Usuário; |
| Recursos | Aplicativo instalado; <br> Acesso ao aplicativo; |
| Episódios | <ol><li>O usuário acessa o aplicativo;</li><li>O usuário clica no "+" no canto superior direito;</li><li>O usuário seleciona "férias/folga";</li><li>O usuário informa quantos dias de duração e coloca uma descrição;</li><li>O usuário clica em salvar;</li></ol>|
| Restrições | A duração só poderá ser de 30 dias no máximo; |
| Exceções | O aplicativo não estar funcionando;<br>Já existe um ponto batido no dia em específico;<br> O aplicativo foi encerrado antes da ação ser completada; |

<br>

### C04 - Apagar um ponto registrado
|Elementos | Descrição |
| -- | -- | 
| Título | Apagar um ponto registrado; |
| Objetivo | Deletar um registro de ponto existente; |
| Contexto | Pré-condição: Ter um ponto já registrado;<br> Pós-condição: O ponto já não existe mais; |
| Autor | Usuário; |
| Recursos | Aplicativo instalado; <br> Acesso ao aplicativo; |
| Episódios | <ol><li>O usuário acessa o aplicativo;</li><li>O usuário pressiona o ponto por dois segundos;</li><li>O usuário clica nos três pontos no canto superior direito;</li><li>O usuário clica em "Apagar";</li><li>O usuário confirma clicando em "Apagar" no pop-up;</li></ol>|
| Restrições | Fluxo intuitivo; |
| Exceções | Não haver ponto para ser apagado; <br> O aplicativo foi encerrado antes da ação ser completada;|

<br>

### C05 - Editar um ponto registrado
|Elementos | Descrição |
| -- | -- | 
| Título | Editar um ponto registrado; |
| Objetivo | Corrigir os dados de um registro de ponto existente; |
| Contexto | Pré-condição: Ter um ponto já registrado;<br> Pós-condição: O ponto terá dados diferentes; |
| Autor | Usuário; |
| Recursos | Aplicativo instalado; <br> Acesso ao aplicativo; |
| Episódios | <ol><li>O usuário acessa o aplicativo;</li><li>O usuário clica nos três pontos ao lado do horário do ponto;</li><li>O usuário clica em "Editar";</li><li>O usuário altera as informações e clica em "Salvar" no pop-up;</li></ol>|
| Restrições | Fluxo intuitivo; |
| Exceções | Não haver ponto para ser editado; <br> Já haver um ponto com os mesmos dados novos;<br> O aplicativo foi encerrado antes da ação ser completada; |

<br>

### C06 - Visualizar saldo de horas
|Elementos | Descrição |
| -- | -- | 
| Título | Visualizar saldo de horas; |
| Objetivo | Visualizar saldo de horas do dia e no total; |
| Contexto | Pré-condição: Ter pelo menos ponto já registrado;<br> Pós-condição: o saldo será a diferença entre ponto de entrada e o de saída, ou apenas a quanto tempo o ponto de entrada foi batido; |
| Autor | Usuário; |
| Recursos | Aplicativo instalado; <br> Acesso ao aplicativo; |
| Episódios | <ol><li>O usuário acessa o aplicativo;</li><li>O usuário olha para o canto inferior esquerdo da tela e verá o saldo do dia, o total e a quantidade de tempo trabalhado;</ol>|
| Restrições | Fluxo intuitivo; |
| Exceções | Não haver pontos no registro; |

<br>

## 4. Referências
> BARBOSA, S.; SILVA, B. Interação Humano-Computador. Rio de Janeiro: Elsevier Editora Ltda, 2010.
