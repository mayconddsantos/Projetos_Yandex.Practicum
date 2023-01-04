<h4>Bootcamp em Análse de dados | Practicum by Yandex</h4>

<h1><b>Projeto Integrado - 01 </b></h1>
<p>
Após os quatros primeiros <i>sprints</i> desenvolvemos o primeiro projeto integrado utilizando os conhecimentos adiquiridos até então, nesse projeto utilizamos os dados de uma loja online de video games para tentar identificar padrões que pudessem determinam se um jogo tem sucesso ou não. Abaixo os detalhes sobre o projeto.

</ul>
<br/>
<font size=+3.5>
<h2><b>Sobre o Projeto</b></h2></font>
<p>

Nesse projeto iremos trabalhar com a loja online Ice, que vende videogames no mundo todo. As avaliações de usuários e especialistas, gêneros, plataformas (por exemplo, Xbox ou PlayStation) e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. Precisaremos identificar padrões que determinam se um jogo tem sucesso ou não. Isso permitirá identificar potenciais grandes vencedores e planejar campanhas publicitárias.
Nossos dados remontam a 2016. Vamos imaginar que estamos em dezembro de 2016 e estamos planejando uma campanha para 2017.
O conjunto de dados contém a abreviatura ESRB. O Entertainment Software Rating Board avalia o conteúdo de um jogo e atribui uma classificação etária, como Adolescente ou Maduro.

<br/>
<p>
<h3><b>Orientações para realização de projeto</b></h3>

<p><ul>
<li>Prepare os dados.</li>   
<ul><li>Converta os dados para os tipos necessários.</li>
    <li>Encontre e elimine erros nos dados.</li>
    <li>Decida como tratar os valores ausentes.</li>
    <li>Preste atenção à abreviação TBD (a ser determinada).</li></ul>

<p>    
<li>Analise os dados.</li>   
<ul><li>Veja quantos jogos foram lançados em anos diferentes.</li>
    <li>Veja como as vendas variaram de plataforma para plataforma.</li>
    <li>Quanto tempo leva para as novas plataformas aparecerem e as antigas desaparecerem?</li>
    <li>Quais plataformas estão liderando em vendas?</li>
    <li>Quais estão crescendo ou diminuindo?</li>
    <li>Veja como as avaliações de usuários e profissionais afetam as vendas de uma plataforma popular.</li>
    </ul>
<p>
<li>Criar um perfil de usuário para cada região.</li>
<ul><li>Para cada região (AN, UE, JP), determine:</li>
    <ul><li>As cinco plataformas principais.</li>
    <li>Os cinco principais gêneros. </li>
    <li>As classificações do ESRB afetam as vendas em regiões individuais?</li>
    </ul></ul>
<p>    
<li>Teste as hipóteses
<ul><li>As classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.</li>
    <li>As classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes.</li></ul>
<p>
    <li>Escreva uma conclusão geral</li></p>   
<p></ul>
<br/>

<h3><b>Dados</b></h3>


Os dados da loja online de vídeo games foram disponibilizados pela Practicum e estão armazenados no arquivo <code>games.csv</code>, segue abaixo a descrição de cada coluna encontrada nesse arquivo:</p>
    <p>
    <ul>
    <li><b>Name</b> — Nome do jogo.</li>
    <li><b>Platform</b> — Plataforma.</li>
    <li><b>Year_of_Release</b> — Ano de lançamento.</li>
    <li><b>Genre</b> — Gênero.</li>
    <li><b>NA_sales</b> — Vendas norte-americanas em milhões de USD.</li> 
    <li><b>EU_sales</b> — Vendas na Europa em milhões de USD.</li> 
    <li><b>JP_sales</b> — Vendas no Japão em milhões de USD.</li> 
    <li><b>Other_sales</b> — Vendas em outros países em em milhões de USD.</li>   <li><b>Critic_Score</b> —  Pontuação atríbuida pela crítica (máximo de 100).</li> 
    <li><b>User_Score</b> — Pontuação atríbuida pelos usuários (máximo de 10).</li> 
    <li><b>Rating</b> — Classificação ESRB.</li> 
        </ul></p>

    
<p>

<h3><b>Conclusões</b></h3>
Analisamos os dados afim de encontrar padrões para jogos de sucesso em diferentes regiões. As princípais informações que obtivemos foram as seguintes:
<ol>
<li>As plataformas ficam em torno de 10 anos disponíveis no mercado.
<li>O gênero de Ação é o mais vendido em todo o mundo.
<li>Jogos com grandes valores em vendas também costumam ter bons scores por parte da crítica.
<li> O JP é o mercado mais diferente entre JP, NA e EU.
<li> Sobre nossas hipóteses iniciais, os resultados foram:
<ol><li>Sim, as classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.
    <li>Sim, as classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes, 6.8 e 5.2 respectivamente.

</ol>
<br>

<font size=+3.5>
<h2><b>🛠 Tecnologias</b></h2></font>
<p>
As análises foram realizadas na linguagem Python, utilizando o Jupyter Notebook e as seguintes bibliotecas: Pandas, NumPy, SciPy, Seaborn e Matplotlib.