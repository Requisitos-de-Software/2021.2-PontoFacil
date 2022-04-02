# Forward-From

## Histórico de versão

|Data | Versão | Modificação | Autor(es)|
| -- | -- | -- | -- |
| 01/04/2022 |  0.1   | Criação do documento e elaboração do texto |  [](https://github.com/) |




## 1. Introdução

 <p style="text-align: justify"> 
    O rastreamento de requisitos é usado para estabelecer relacionamentos entre requisitos, arquitetura e implementação do sistema e permite uma melhor compreensão dos relacionamentos citados. A rastreabilidade pode ser implementada através de um conjunto de elos ou links entre requisitos inter-relacionados, entre requisitos e suas fontes, e entre requisitos e componentes que os implementam. 
 </p>
<p style="text-align: justify"> 
   A pós-rastreabilidade permite vincular os requisitos ao desenho do sistema e sua implementação. A rastreabilidade <i>forward-from</i> estabelece a ligação entre requisitos e artefatos de desenho e implementação.
 </p>

## 2. Metodologia

 <p style="text-align: justify">
   
   Para representar a rastreabilidade dos requisitos elicitados em nosso projeto, utilizaremos uma tabela que apresenta os épicos, requisitos, histórias de usuários e seus relacionamentos com as telas dos artefatos de desenho (protótipo) utilizando para isso links entre os requisitos e as fontes que implementam estes.  Também utilizaremos a classificação das informações a serem rastreadas e também os elos de rastreabilidade propostos pelo Meta-Modelo de Toranzo.
 </p>

 <p style="text-align: justify">
   As informações a serem rastreadas são classificadas em:
 </p>

   <ul>
    <li><b>Ambiental:</b>  as informações são originadas do contexto no qual a organização está inserida.</li>
    <li><b>Organizacional:</b>  as informações da organização(missão, objetivos e estratégias).</li>
    <li><b>Gerencial:</b>  informações que auxiliam na gerência do projeto.</li>
    <li><b>Desenvolvimento: </b> informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste,etc).</li>
   </ul>

<p style="text-align: justify">
   Os principais elos de rastreabilidade são:
</p>
  <ul>
    <li><b>Satisfação:</b>classe  origem tem dependência de satisfação com a classe destino</li>
    <li><b>Recurso:</b> classe origem tem dependência de recurso com a classe destino</li>
    <li><b>Responsabilidade:</b> registra a participação, responsabilidade e ação de pessoas sobre artefatos.</li>
    <li><b>Representação: </b>captura a representação ou modelagem dos requisitos em outra linguagem.</li>
     <li><b>Alocado: </b>classe de origem está relacionada a classe de destino, que representa um subsistema.</li>
     <li><b>Agregação: </b> indica composição de elementos.</li>
   </ul>



<br>

## 3. Resultados
<table>
    <thead>
        <tr>
            <th style="text-align:center">Épico</th>
            <th style="text-align:center">Tela(s)</th>
            <th style="text-align:center">Requisito</th>	
            <th style="text-align:center">US ID</th>
            <th style="text-align:center">História de Usuário</th>
            <th style="text-align:center"></th>
        </tr>
    </thead>
    <tbody >
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="17"><a href="#epico-01" >Épico 01 -  Gerenciamento de Registros </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="17"><a href="https://www.figma.com/" >TE01</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF01</a></td>
             <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us01/" >US01</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um novo usuário do sistema,desejo registrar o ponto de entrada, para que eu saiba quando iniciei o trabalho.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF02</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us02/" >US02</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar o ponto de saída para que eu saiba quando eu saí do trabalho.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF03</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us03/" >US03</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar o ponto de saída para o almoço para que eu saiba quando eu sai para almoçar.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF04</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us04/" >US04</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo guardar informações do horário de trabalho para cada dia da semana que eu mantenha os registros organizados e separados.</td>
        </tr>
        <tr>
           <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF05</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us05/" >US05</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo apagar registros passados para que eu possa manter apenas os registros desejados.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF06</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us06/" >US06</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo copiar registros passados para que eu possa mover o registro para outro dia.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF08</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us07/" >US07</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar o ponto de retorno do almoço para que eu saiba quando eu voltei do almoço.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF13</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us08/" >US08</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar o ponto eletrônico através de uma Tag NFC para que eu tenha mais praticidade e agilidade no registro.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF15</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us09/" >US09</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo zerar o saldo de horas total para que eu possa recomeçar os registros do zero.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF17</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us10/" >US10</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar falta para que eu saiba quando eu faltei.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF18</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us11/" >US11</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo adicionar uma foto do registro do ponto para que tenha certeza que registrei o ponto.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF23</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us12/" >US12</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo apagar todos os registros para que eu possa apagar tudo que registrei.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF26</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us13/" >US13</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar folga para que eu saiba quando eu folguei.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF29</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us14/" >US14</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo editar registros passados que possa corrigir erros que cometi.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF30</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us15/" >US15</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar férias para que eu saiba quando eu entrei de férias.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF31</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us16/" >US16</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo escrever uma descrição para cada registro, de forma que possa descrever mais detalhadamente informações sobre o registro.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF34</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us17/" >US17</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo registrar hora extra para que eu saiba quantas horas extra eu trabalhei.</td>
        </tr>
        <tr>
       </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="4"><a href="#epico-02" >Épico 02 - Backup </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="4"><a href="https://www.figma.com/" >TE02</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF10</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us18/">US18</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo configurar o horário e o dia do backup,para que possa escolher a hora e o dia mais adequado para backup.</td>    
        </tr>
         <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RNF7</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us19/" >US19</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo armazenar o backup em contas do Google Drive ou Dropbox, para que eu tenha os meus dados salvos em nuvem.</td>
        </tr>
         <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF28</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us20/" >US20</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo fazer backup dos meus registros automaticamente em nuvem ou local, para que eu tenha mais de um tipo de cópia de segurança.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF07</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us21/" >US21</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um usuário do sistema, desejo restaurar um backup, para que eu possa resgatar registros anteriormente salvos.</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="6"><a href="#epico-02" >Épico 03 - Definição de Padrões  </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="6"><a href="https://www.figma.com/" >TE03</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF09</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us22/">US22</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo configurar os horários de entrada e saída do dia de acordo com registros do mesmo dia , para que eu possa controlar os horários de acordo com a minha rotina.</td>    
        </tr>
        <tr>
             <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF11</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us23/" >US23</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo alterar as opções de intervalo, como por exemplo definir um horário de intervalo mínimo, para que eu possa adaptar os registros de acordo com a minha rotina.</td>
        </tr>
        <tr>
             <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF24</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us24/" >US24</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo configurar a tolerância da jornada de trabalho, para que eu tenha controle total sobre as horas trabalhadas. </td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF19</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us25/" >US25</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo configurar as notificações que o aplicativo informa (aviso de horário de entrada, saída, intervalo), para que eu escolha qual é a notificação mais adequada para mim.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF22</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us26/" >US26</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo configurar a qualidade e resolução da foto armazenada, para que eu possa escolher a qualidade desejada na foto.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF24</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us27/" >US27</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo ativar a notificação de alarme , para que eu seja avisado acerca de alguma atividade que devo realizar</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="8"><a href="#epico-02" >Épico 04 - Visualização de Registros  </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="8"><a href="https://www.figma.com/" >TE04</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF12</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us28/">US28</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuario, desejo visualizar inconsistências no registro de ponto, para que eu possa corrigir os erros no registro de ponto.</td>    
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF16</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us29/" >US29</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo visualizar meu banco de horas no período desejado no formato de gráfico de linhas, para que eu tenha noção do volume de horas trabalhadas.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF25</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us30/" >US30</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo filtrar os parâmetros do gráfico de linhas, para que eu possa inferir informações mais específicas no gráfico.</td>
        </tr>
         <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF20</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us31/" >US31</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo escolher diferentes opções de idiomas, para que eu possa entender as informações apresentadas.</td>
        </tr>
         <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF21</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us32/" >US32</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo visualizar meus registros no dia, na semana e no mês, para que eu acompanhe meu volume de horas trabalhadas no período que desejo.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF27</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us33/" >US33</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo  consultar meu saldo de horas do dia, para que eu acompanhe meu volume de horas trabalhadas .</td>
        </tr>
         <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF32</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us34/" >US34</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo  gerar um extrato dos meus registros de ponto em qualquer período determinado, para que eu possa apresentar ao meu empregador.</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../elicitacao/priorizacao/moscow" >RF33</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="../../modelagem/backlog/userstories/us35/" >US35</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário do sistema, desejo consultar o saldo de horas total (do mês), para que eu acompanhe meu volume de horas mensal trabalhadas.</td>
        </tr>
        <tr>
        </tr>
    </tbody>
</table>

## 4. Conclusão

 <p style="text-align: justify">


 </p>

## 5. Referências

> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 4. 17 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

> 




