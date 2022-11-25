<h4>Bootcamp em Análse de dados | Practicum by Yandex</h4>

<h1><b>Sprint 1 - Python Básico</b></h1>
<p>
No primeiro <i>sprint</i> do <i>boocamp</i>, foram abordados os conceitos fundamentais e sintaxe básica de Pyhton e conhecemos também a biblioteca pandas para análises de dados. Ao final do conteúdo realizamos o primeiro estudo de caso e em seguida desenvolvemos o primeiro projeto. Segue abaixo os tópicos abordados nesse sprint:

<ul>
<li> Variáveis, exibição, tipos de dados, e operações aritméticas.
<li> <i>Strings</i>.
<li> Listas. 
<li> Laços de repetição <code>for</code>. 
<li> Listas aninhadas.
<li> Condições e laços de repetição <code>while</code>.
<li> Criando funções.
<li> Dicionários.
<li> Biblioteca pandas para análise de dados. 
<li> Pré-processamento de dados.
<li> Analisando dados e apresentando resultados.
<li> Conhecendo o jupyter notebook.
</ul>
<br/>

<font size=+2>
<h2><b>Sobre o Projeto</b></h2></font>
<p>
Neste projeto, comparamos as preferências musicais dos habitantes de Springfild e Shelbyville. Examinamos os dados reais do Y.Music para análisar 3 hipóteses e comparar os comportamentos dos usuários dessas duas cidades.


<h3><b>Hipóteses</b></h3>
<ol>
<li>A atividade dos usuários é diferente dependendo do dia da semana e da cidade.
<li>Durante as manhãs de segunda-feira, os moradores de Springfield e Shelbyville escutam diferentes gêneros. Isso também é verdadeiro para noites de sexta-feira.
<li>Os ouvintes de Springfield e Shelbyville têm diferentes preferências. Em Springfield, as pessoas preferem Pop, enquanto Shelbyville tem mais fãs de Rap.
</ol>
<h3><b>Dados</b></h3>
Os dados analisados foram disponibilizados pela Practicum e estão armazenados no arquivo <code>music_project_en.csv</code>, eles possuiam algumas inconsistências quanto ao nome das colunas e presença de dados com valores ausentes e duplicados que foram tratados na fase de pré-processamento de dados. Abaixo a descrição das colunas:
<ul>
<li><code>userID</code> — identificador do usuário.
<li><code>Track</code> — título da faixa.
<li><code>artist</code> — nome do artista.
<li><code>genre</code> — gênero de música.
<li><code>City</code> — cidade do usuário.
<li><code>time</code> — o tempo exato que a faixa foi reproduzida.
<li><code>Day</code> — dia da semana.
</ul>
<h3><b>Conclusões</b></h3>
Após analisar os dados chegamos as seguintes conclusões referentes às hipóteses acima cidatas:
<ol>
<li>As atividades dos usuários em Springfield e Shelbyville dependem do dia da semana, embora as cidades variam de formas diferentes, por esse motivo consideramos a primeira hipótese verdadeira.
<li>As preferências musicais não variam significativamente ao decorrer da semana tanto em Springfield como em Shelbyville. Em Springfield e Shelbyville, as pessoas escutam mais música Pop. Os resultado poderiam ter sido diferentes se não houvessem valores ausentes. Por esses motivos também consideramos a segunda hipótese verdadeira.
<li>As preferências musicais dos usuários de Springfield e Shelbyville são muito parecidas. A terceira hipótese foi rejeitada, pois parentemente as preferências  são iguais.
</ol>
<br>

<font size=+2>
<h3><b>🛠 Tecnologias</b></h3></font>
<p>
As análises foram realizadas na linguagem Python, utilizando o Jupyter Notebook e a biblioteca pandas.