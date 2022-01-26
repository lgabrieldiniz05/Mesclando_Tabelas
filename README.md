# Mesclando_Tabelas
<h2>Tutorial para Mesclar tabelas usando <i>merge</i></h2>
<h4>primeiro começamos importando a biblioteca PANDAS para isso iremos utlizar a seguinte linha de código .</h4>
<h6><i>import pandas as pd</i></h6>
<h4>em seguinda atribuimos o nosso arquivo Vendas.xlsx a uma variável dentro do nosso código</h4>
<h6><i>tabela_vendas = pd.read_excel('Vendas.xlsx')</i></h6>
<h4>e atribuimos o nosso arquivo Gerentes.xlsx a outra variável</h4>
<h6><i>tabela_gerentes = pd.read_excel('Gerentes.xlsx')</i></h6>
<h4>Agora para juntar as duas tabelas é simples bastar atualizar a tabelas_vendas com um <i>merge</i> na tabela_gerentes</h4>
<h6><i>tabela_gerentes = pd.read_excel('Gerentes.xlsx')</i></h6>
<h4>e já podemos visualizar a nova tabela com o comando display</h4>
<h6><i>display(tabela_vendas)</i></h6>
<div align="center"><img src="https://user-images.githubusercontent.com/90981124/151084278-26512831-8760-4e3e-8c06-279700bfe545.png" width="900px" /></div>
