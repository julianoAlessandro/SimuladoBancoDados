# SimuladoBancoDados
Atividade que será usada como meio de estudo para a prova do dia 19/06
 <h2>Tabelas a serem consideradas na Questão:📝📂</h2>

    <b>Estrada:</b>Tabela com as estradas na base de dados.<br>
<b>Trecho:</b>Tabela com os trechos de estrada, indicando localidade de início e de fim e comprimento em km do trecho -
Sequencia dá a ordem relativa dos trechos começando em um para cada estrada.<br>
<b>Localidade:</b> Tabela das localidades - CodLocAbrang indica a localidade que contém (se houver) a localidade em
questão. Por exemplo: A SP 340 (estrada) passa pela Localidade “Recanto do Sol Nascente” e esta fica na localidade
“Mogi Mirim”. UF: tabela com as unidades da federação.<br>
<b>Construtora:</b> Nome das construtoras que construíram os trechos das rodovias.<br>
<hr>
<h3>ENUNCIADO DAS QUESTOES 🧾</h3>
2 – Faça uma Subconsulta que mostre o nome da construtora e a quantidade total de estradas que cada empresa
construiu. Mostre ordenado, do maior para menor, pela total construído (soma do comprimento).<br><br>
3 – Faça uma subconsulta para mostrar o nome das localidades e a quantidade de trechos que passam por cada uma
dessas localidades.<br><br>
4 – Faça uma Stored Procedure que receba com parâmetro o nome da unidade de federação Inicial e da unidade de
federação final. Com estas informações, mostre os nomes de todas estradas que têm pelo menos um trecho que
começa na unidade da federação informada no parâmetro “federação inicial” e que termina na unidade da
federação informada no último parâmetro. Exemplo: A procedure é executada passando os parâmetros ‘RJ’ e ‘MG’,
em seguida é retornado o nome de todas as estradas que começam em ‘RJ’ e terminam em ‘MG’.<br><br>
5 – Faça uma Stored Procedure para exibir os nomes das estradas que têm trechos construídos por uma construtora
informada no parâmetro desta função. Observar que a coluna Trecho. Nome Construtora é opcional.<br><br>
