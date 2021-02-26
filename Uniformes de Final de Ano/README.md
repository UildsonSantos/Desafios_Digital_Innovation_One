<h1>Desafio</h1>
O professor Girafales organizou a confecção de um uniforme para as turmas da escola para comemorar o final do ano. Após algumas conversas, ficou decidido com os alunos que eles poderiam escolher a cor do uniforme entre branco ou vermelho. Assim sendo, Girafales precisa de sua ajuda para organizar as listas de quem quer o uniforme em cada uma das turmas, relacionando estas camisetas pela cor, tamanho (P, M ou G) e por último pelo nome.

<h2>Entrada</h2>
Cada caso de teste inicia com um valor <strong>N</strong>, (1 ≤ <strong>N</strong> ≤ 60) inteiro e positivo, que indica a quantidade de uniformes a serem feitas para aquela turma. As próximas <strong>N</strong>*2 linhas contém informações de cada um dos uniformes (serão duas linhas de informação para cada uniforme). A primeira linha irá conter o nome do estudante e a segunda linha irá conter a cor do uniforme ("branco" ou "vermelho") seguido por um espaço e pelo tamanho do uniforme "P" "M" ou "G". A entrada termina quando o valor de <strong>N</strong> for igual a zero (0) e esta valor não deverá ser processado.

<h2>Saída</h2>
Para cada caso de entrada deverão ser impressas as informações ordenadas pela cor em ordem ascendente, seguido pelos tamanhos em ordem descendente e por último por ordem ascendente de nome, conforme o exemplo abaixo.

<table>
	<thead>
		<tr>
			<td>Exemplo de Entrada</td>
			<td>Exemplo de Saída</td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
			<p>9<br>
			Maria Jose<br>
			branco P<br>
			Mangojata Mancuda<br>
			vermelho P<br>
			Cezar Torres Mo<br>
			branco P<br>
			Baka Lhau<br>
			vermelho P<br>
			JuJu Mentina<br>
			branco M<br>
			Amaro Dinha<br>
			vermelho P<br>
			Adabi Finho<br>
			branco G<br>
			Severina Rigudinha<br>
			branco G<br>
			Carlos Chade Losna<br>
			vermelho P<br>
			0</p>
			</td>
			<td>
			<p>branco P Cezar Torres Mo<br>
			branco P Maria Jose<br>
			branco M JuJu Mentina<br>
			branco G Adabi Finho<br>
			branco G Severina Rigudinha<br>
			vermelho P Amaro Dinha<br>
			vermelho P Baka Lhau<br>
			vermelho P Carlos Chade Losna<br>
			vermelho P Mangojata Mancuda</p>
			</td>
		</tr>
	</tbody>
</table>