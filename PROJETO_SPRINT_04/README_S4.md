<h4>Bootcamp em Análse de dados | Practicum by Yandex</h4>

<h1><b>Sprint 4 - Análise Exploratória de Dados (EDA) </b></h1>
<p>
No quarto <i>sprint</i> do <i>boocamp</i>, foram abordados os conteúdos sobre a teoria da probabilidade, as distribuições mais comuns, métodos estatísticos em Python, amostragem e a significância estatística. Todo o conteúdo foi dividido em 3 capítulos, que foram:
<ul>
<li> Estatística descritiva.
<li> Teoria da probabilidade.
<li> Testando Hipóteses. 


</ul>
<br/>
<font size=+3.5>
<h2><b>Sobre o Projeto</b></h2></font>
<p>
No projeto desse <i>sprint</i> analisamos os dados referentes aos planos da Megaline Telecomunicações, analisamos o comportamento dos clientes e determinamos quais planos pré-pagos trazem a maior receita, para isso tivemos os dados sobre o consumo de mensagens, ligações e uso de internet de 500 clientes da Megaline. Para desenvolver esse projeto recebemos as orientações abaixo.

<br/>
<p>
<h3><b>Orientações para realização de projeto</b></h3>

<p><ul>
<li>Prepare os dados.</li>   
<ul><li>Converta os dados para os tipos necessários.</li>
    <li>Encontre e elimine erros nos dados.</li></ul>
<p>    
<li>Para cada usuário, encontre:</li>   
<ul><li>O número de chamadas feitas e minutos usados por mês.</li>
    <li>O número de mensagens de texto enviadas por mês.</li>
    <li>O volume de dados por mês.</li>
    <li>A receita mensal para cada usuário.</li></ul>
<p>    
<li>Analise os dados.</li>   
<ul><li>Descreva o comportamento dos clientes.</li>
    <li>Encontre os minutos, mensagens de texto e volume de dados que usuários de cada plano necessitam por mês.</li>
    <li>Calcule a média, variância e o desvio padrão.</li>
    <li>Construa histogramas.</li>
    <li>Descreva as distribuições.</li></ul>
<p>    
<li>Teste as hipóteses
<ul><li>A receita média dos usuários dos planos Ultimate e Surf são diferentes.</li>
    <li>A receita média dos usuários da área de NY-NJ é diferente dos usuários de outras regiões.</li></ul>
<p>
    <li>Escreva uma conclusão geral</li></p>   
<p></ul>

<h3><b>Informações</b></h3>
    

<p>
    
A Megaline arredonda segundos para minutos, e megabytes para gigabytes. Para chamadas, cada chamada individual é arredondada para cima: mesmo se uma chamada tenha durado apenas um segundo, será contado como um minuto. Para trafego de web, sessões individuais de web não são arredondadas para cima. Ao invés disso, o total do mês é arredondado para cima. Se alguém usar 1025 megabytes esse mês, eles serão cobrados por 2 gigabytes.
<ul><li>Plano Surf:</li>
<ul><li>Preço mensal: \$20
    <li>500 minutos mensais.</li>
    <li>50 mensagens de texto.</li>
    <li>15 GB de dados.</li>
    <li>Depois de exceder os limites do pacote:
    <ul><li>1 minuto: 3 centavos
        <li>1 mensagem de texto: 3 centavos
        <li>1 GB de dados: \$10</ul></ul>
    <li>Ultimate</li>
<ul><li>Preço mensal: \$70</li>
    <li>3000 minutos mensais
    <li>1000 mensagens de texto
    <li>30 GB de dados</li>
    <li>Depois de exceder os limites do pacote:</li>
    <ul><li>1 minuto: 1 centavo.</li>
        <li>1 mensagem de texto: 1 centavo.</li>
        <li>1 GB de dados: \$7.</li></ul>  

</ul>

<p></ul>
<br/>

<h3><b>Dados</b></h3>


Os dados sobre o comportamento dos usuários foram disponibilizados pela Practicum e estão armazenados nos arquivos abaixo, também listadas abaixo as colunas de cada um dos arquivos:</p>
    <p><ul>
<li><code><b>megaline_calls.csv</b></code>
    <ul>
    <li><b>id</b> — identificador de chamada unívoco.</li>
    <li><b>call_date</b> — data da chamada.</li>
    <li><b>duration</b> — duração da chamada (em minutos).</li>
    <li><b>user_id</b> — o identificador do usuário que faz a chamada.</li> 
        </ul></p>
        
</font>     
<li><code><b>megaline_internet.csv</b></code>
    <ul>
    <li><b>id</b> — identificador de sessão unívoco.</li>
    <li><b>mb_used</b> — o volume de dados gasto durante a sessão (em megabytes).</li>
    <li><b>session_date</b> — data da sessão web.</li>
    <li><b>user_id</b> — o identificador do usuário.</li> 
        </ul></p>
<p>
<li><code><b>megaline_messages.csv</b></code>
    <ul>
    <li><b>id</b> — identificador unívoco de mensagem de textos.</li>
    <li><b>message_date </b> — data da sessão web.</li>
    <li><b>user_id</b> — o identificador do usuário.</li> 
        </ul></p>
<p>
<li><code><b>megaline_plans.csv</b></code>
    <ul>
    <li><b>plan_name</b> — o nome do plano de chamadas.</li>
    <li><b>usd_monthly_fee</b> — preço mensal em dólares dos EUA.</li>
    <li><b>minutes_included</b> — pacote de minutos mensal.</li>
    <li><b>messages_included</b> — pacote de mensagens de texto mensal.</li> 
    <li><b>mb_per_month_included</b> — pacote de volume de dados (em megabytes). </li> 
    <li><b>usd_per_minute</b> — preço por minuto depois de exceder o limite do pacote (por exemplo, se o pacote inclui 100 minutos, o primeiro minuto excedente será cobrado).</li>
    <li><b>usd_per_message</b> — preço por mensagem de texto depois de exceder o limite do pacote.</li> 
    <li><b>usd_per_gb</b> — preço por gigabyte extra de dados após exceder o limite do pacote (1 GB = 1024 megabytes).</li>
    </ul></p>
    <p>
<li><code><b>megaline_users.csv</b></code>
    <ul>
    <li><b>user_id</b> — identificação do usuário.</li>
    <li><b>first_name</b> — nome do usuário.</li>
    <li><b>last_name</b> — último sobrenome do usuário.</li>
    <li><b>age</b> — idade do usuário (em anos).</li> 
    <li><b>reg_date</b> — data da inscrição (dd, mm, aa). </li> 
    <li><b>churn_date</b> — a data que o usuário parou de usar o serviço (se o valor for ausente, o plano estava sendo usado quando esse dado foi gerado).</li>
    <li><b>city</b> — cidade de residência do usuário.</li> 
    <li><b>plan</b> — nome do plano.</li>
    </ul></p></ul>
    
<p>

<h3><b>Conclusões</b></h3>
Após análise dos dados chegamos as seguintes conclusões:
<ol>
<li>A receita média do plano Ultimate é maior em relação ao plano Surf, a receita média por usuário são USD 70,00 e USD 21,88.
<li>A receita média dos usuários de NY-NJ é maior em relação as demais regiões, na região de NY-NJ é USD 38,16 e demais regiões USD 29,21.
<li>A receita total do plano Ultimate em 2018 foi de USD 50.696,66.
<li> A receita total do plano Surf em 2018 foi de USD 35.419,18.

</ol>
<br>

<font size=+3.5>
<h2><b>🛠 Tecnologias</b></h2></font>
<p>
As análises foram realizadas na linguagem Python, utilizando o Jupyter Notebook e as seguintes bibliotecas: Pandas, NumPy, SciPy, Seaborn e Matplotlib.