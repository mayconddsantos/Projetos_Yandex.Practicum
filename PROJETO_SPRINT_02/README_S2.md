<h4>Bootcamp em Análse de dados | Practicum by Yandex</h4>

<h1><b>Sprint 2 - Pré-processamento de Dados</b></h1>
<p>
No segundo <i>sprint</i> do <i>boocamp</i>, aprendemos sobre compensação de dados imperfeitos. Como lidar com dados ausentes e duplicados. Como alterar o tipo dos dados e pensamento sistêmico para analistas. Segue abaixo os tópicos abordados nesse sprint:
<ul>
<li> Introdução ao Pré-processamento de Dados.
<li> Lidando com Valores Ausentes.
<li> Alterando o Tipo dos Dados. 
<li> Procurando por Duplicatas. 
<li> Categorizando Dados.
<li> Pensamento Sistêmico e Crítico para Analistas.
</ul>
<br/>
<font size=+3.5>
<h2><b>Sobre o Projeto</b></h2></font>
<p>
O projeto desse <i>sprint</i> foi preparar um relatório para a divisão de empréstimos de um banco. Onde precisamos descobrir se o estado civil de um cliente e o número de filhos têm impacto sobre a inadimplência de um empréstimo, utilizando alguns dados sobre a capacidade de crédito dos clientes que o banco já possuia.
O relatório seria considerado ao criar uma pontuação de crédito de um cliente em potencial.
<br/>
<p>
<h3><b>Objetivo</b></h3>
O objetivo do projeto foi elaborar um relatório que respondesse as seguintes perguntas:
<ol>
<li>Existe uma correlação entre o nível de renda e o pagamento em dia?
<li>Existe uma correlação entre o status familiar e o pagamento em dia?
<li>Existe uma correlação entre a quantidade de crianças e o pagamento em dia?
<li>Como a finalidade do crédito afeta a taxa de inadimplência?
<li>Existe uma correlação entre a educação e o pagamento em dia?
</ol>
<h3><b>Dados</b></h3>
Os dados analisados foram disponibilizados pela Practicum e estão armazenados no arquivo <code>credit_scoring_eng.csv</code>, eles possuiam algumas inconsistências que foram tratados na fase de pré-processamento de dados. Abaixo a descrição das colunas:
<ul>
<li><code>children</code> — o número de crianças na família.
<li><code>days_employed</code> — quanto tempo o cliente trabalhou.
<li><code>dob_years</code> — a idade do cliente.
<li><code>education</code> — o nível de educação do cliente.
<li><code>education_id</code> —  identificador da educação do cliente.
<li><code>family_status</code> — estado civil do cliente.
<li><code>family_status_id</code> — identificador do estado civil do cliente.
<li><code>gender</code> — o sexo do cliente.
<li><code>income_type</code> — o tipo de renda do cliente.
<li><code>debt</code> — se o cliente já deixou de pagar um empréstimo.
<li><code>total_income</code> — renda mensal.
<li><code>purpose</code> — motivo para fazer um empréstimo.
</ul>

<h3><b>Conclusões</b></h3>
Após análise dos dados chegamos as seguintes conclusões:
<ol>
<li>Não Existe uma correlação entre o nível de renda e o pagamento em dia, porém pessoas com renda entre 20.000 e 24.999 são os mais inadimplentes com uma taxa de 8,86%. A partir de 25.000, quanto maior for a renda menor será a taxa de inadimplência.
<li>Não existe uma correlação entre o status familiar e o pagamento em dia, mas solteiros e pessoas em união estável (civil partnership) tendem a ser mais inadimplentes em relação as outras com status familiar diferente desses.
<li>Não existe uma correlação entre a quantidade de crianças e o pagamento em dia, mas podemos observar que aqueles que não tem crianças tem menores taxas de inadimplência.
<li> As finalidades de crédito com maior taxa de inadimplência são aquelas ligadas à compra de automóveis e educação, enquanto aquelas ligada a casamento e a imóveis são as menores taxas, embora as solicitações de crédito para imóveis seja a mais recorrente.
<li>Existe uma correlação entre a educação e o pagamento em dia? Sim, quanto menor o grau de educação dos clientes maior a taxa de inadimplência.
</ol>
<br>

<font size=+3.5>
<h2><b>🛠 Tecnologias</b></h2></font>
<p>
As análises foram realizadas na linguagem Python, utilizando o Jupyter Notebook e a biblioteca pandas.