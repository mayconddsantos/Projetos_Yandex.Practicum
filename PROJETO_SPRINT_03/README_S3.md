<h4>Bootcamp em Análse de dados | Practicum by Yandex</h4>

<h1><b>Sprint 3 - Análise Exploratória de Dados (EDA) </b></h1>
<p>
No terceiro <i>sprint</i> do <i>boocamp</i>, aprendemos a verificar a qualidade dos dados, a avaliar e modificar a estrutura dos dados, a analisar dados categóricos e a procurar relações e padrões, criamos gráficos básicos e elaboramos as primeiras hipóteses. Abaixo os tópicos abordados nesse sprint:
<ul>
<li> Primeiros gráficos e conclusões.
<li> Fatias de Dados.
<li> Trabalhando com Várias Fontes de Dados. 
<li> Distribuição Conjunta. 
<li> Validação de Resultados.

</ul>
<br/>
<font size=+3.5>
<h2><b>Sobre o Projeto</b></h2></font>
<p>
O projeto desse <i>sprint</i> foi estudar os dados coletados nos últimos anos pelo site "Lista de Eixo de Manivela" e determinar quais fatores influenciaram o preço de um veículo, esse site veícula centenas de propagandas gratuitas de veículos que possuem caracteristicas dos veículos como: cor, modelo, quilometragem, etc.

<br/>
<p>
<h3><b>Objetivo</b></h3>
O objetivo desse projeto foi determinar quais são os tipos de automóveis mais populares e quais os fatores que exercem maior influência sobre o preço desses automóveis.
<p>
<br/>

<h3><b>Dados</b></h3>
Os dados analisados foram disponibilizados pela Practicum e estão armazenados no arquivo <code>vehicles_us.csv</code>. Abaixo a descrição das colunas:
<ul>
<li><code>price</code> — Preço do veículo.
<li><code>model_year</code> — Ano do modelo.
<li><code>model</code> — Modelo.
<li><code>condition</code> — Condições de conservação.
<li><code>cylinders</code> —  Quantidade de cilindros.
<li><code>fuel</code> — Tipo do combustível.
<li><code>odometer</code> — Quilometragem do veículo quando a propaganda foi publicada.
<li><code>transmission</code> — Tipo da transmissão.
<li><code>paint_color</code> — Cor predominante do veículo.
<li><code>is_4wd</code> — Se o veículo é 4 por 4.
<li><code>date_posted</code> — Data que a propaganda foi publicada.
<li><code>days_listed</code> — Dias desde a publicação até a retirada.
</ul>

<h3><b>Conclusões</b></h3>
Após análise dos dados chegamos as seguintes conclusões:
<ol>
<li>O parâmetro que tem maior impacto sobre o preço é a idade do veículo.
<li>O segundo parâmetro que tem maior impacto sobre o preço é a quilometragem .
<li>O terceiro parâmetro com maior impacto sobre o preço foi a condiçãode conservação do veículo.
<li> Os parâmetros cor da pintura e transmissão não demonstra tanta influência sobre o preço.
<li>O tipo de automóveis mais populares são os  Sedans, seguidos pelos as SUV's.
<li>Em média os SUV's possuem preços mais altos que os sedans.
</ol>
<br>

<font size=+3.5>
<h2><b>🛠 Tecnologias</b></h2></font>
<p>
As análises foram realizadas na linguagem Python, utilizando o Jupyter Notebook e as seguintes bibliotecas: Pandas, Numpy, Seaborn e Matplotlib.