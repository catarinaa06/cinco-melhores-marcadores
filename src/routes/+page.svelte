<script>
	import FlourishScroller from '../components/FlourishScroller.svelte';
	import NewsArticle from './NewsArticle.svelte';
	let steps = [
		'Este gráfico apresenta os cinco melhores marcadores da Liga portuguesa ao longo das últimas dez temporadas, contendo o período de 2013/2014 a 2022/2023. O gráfico revela a quantidade de golos marcados e a classificação da liga dos seus clubes.',
		'Na época 2013/2014, Derley, que na altura jogava no Marítimo foi considerado o segundo melhor marcador naquela época, sendo que a equipa encontrava-se em décimo lugar.Derley jogou uma média de 89 minutos por jogo. ' ,
		'No mesmo ano Rafael Martins, classificou-se como o terceiro melhor marcador, tendo marcado 15 golos, naquela época jogava no Vitória SC que ficou em nono lugar na classificação da liga. ' , 
		'Em último o quinto melhor marcador, a jogar no Sporting, Fredy Montero, que precisava de 156 minutos para marcar um golo. O Sporting nesse ano encontrou-se em sétimo lugar.',
		'Em 2014/2015 há um jogador que está no meio dos grandes clubes, Marco Matias, nesta época jogava no Nacional e o clube encontrava-se em sétimo lugar.',
		'Leo Bonatini, jogador no Estoril Praia (oitavo lugar) e fez 33 jogos pelo clube, na época 2015/2016.' ,
		'Na mesma época, Rafael Martins, marcou 16 golos, 4 deles em penaltis, na altura jogava no Moreirense (décimo lugar). ',
		'Seguindo para a época 2017/2018, Fabrício ficou em quinto lugar, a jogar no Portimonense que se classificou em décimo lugar. ',
		'Em segundo lugar, com 18 golos, Mehdi Taremi é o segundo melhor marcador, na época 2019/2020, jogava no Rio Ave (quinto lugar).',
		'Em quinto lugar Fábio Abreu a jogar no Moreirense (oitavo lugar), fez 33 jogos nessa época e goleou 13 vezes. ',
		'Na época 2020/2021, Mario González a jogar no CD Tondela, onde a equipa se classificou em décimo segundo lugar. ',
		'Fran Navarro nas duas últimas épocas ficou em quarto lugar como melhor marcador, a jogar no Gil Vicente. O clube na época 2021/2022 ficou em quinto lugar e nesta última época em décimo terceiro lugar.',
		
	];
</script>

<NewsArticle />

<FlourishScroller flourish_id="1946114" {steps} />


<div class="max-w-2xl py-20 mx-auto font-serif">
	<p class="mt-2">Ao analisar os dados apresentados neste gráfico, podemos concluir que ao longo das últimas dez temporadas da Liga Portuguesa (2013/2014 - 2022/2023), houve um grupo seleto de jogadores que se destacaram como os melhores marcadores.<p>
	<p class="mt-2">Estes jogadores foram essenciais para as suas equipas a nível de vitórias e títulos.</p>
	<p class="mt-2">É importante destacar que o sucesso destes jogadores não está restrito apenas aos números de golos marcados, mas também à sua influência nos jogos e ao impacto que tiveram no desempenho ao longo de cada época.</p>
		
</div>

