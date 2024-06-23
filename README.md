
<h2 align= "center"> Atividade ETL </h2>

Atividade proposta em aula do bootcamp da SoulCode de análise de dados onde em grupo deveríamos realizar o processo de ETL (Extract, Transform e Load) de um conjunto de dados públicos de uma empresa qualquer, neste caso especificamente era com o objetivo de avaliar as informações coletadas dos clientes e suas compras para poder analisar medidas de marketing futuramente. Após a realização da ETL se fosse possível, gerar alguns gráficos para analisar dados que pudessemos considerar importante. 

Antes de iniciar a ETL, armazenamos o conjunto de dados em formato CSV dentro do serviço de nuvem google cloud storage e habilitamos o acesso para todos os integrantes do grupo caso fosse necessário alguém ter o acesso dos dados. Após isso, usamos o Google Colab para fazer todo o processo utilizando a linguagem Python. Trouxemos os dados da Storage para o colab e para realizar o processo de ETL, utilizamos a biblioteca pandas do python. Nesse processo tivemos a extração e carregamento dos dados no colab, alteramos as colunas, traduzimos células e colunas, verificamos se existiam valores nulos, alteramos alguns tipos de dados como de float para int, verificamos colunas duplciadas, alteramos o tipo de data, verificamos se tinha consistências e utilizamos por fim, o pacote pandera para verificar a integridade do nosso processo de ETL. 

Depois disso, carreguei o conjunto de dados tratados primeiramente no google drive para poder salvar como segurança e em definitivo carregamos no google storage para armazenamento. 
Através do Matplotlib conseguimos exibir gráficos e assim visualizar algumas questões como a média de compras por categoria de produto através de um gráfico de barras, o total de compras de vinhos por Estado Civil também por um gráfico de barras e a quantidade de cliente nos anos 2012, 2013, 2014 através de um gráfico de pizza. 

Nesta atividade realizada, participei ativamente principalmente do processo de ETL do começo ao fim, realizando junto aos meus colegas de curso a atividade de maneira muito compromissada e satisfatória. 


