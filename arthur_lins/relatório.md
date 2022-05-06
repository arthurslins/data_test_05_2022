<h1 align="center"> Relatório Bolsista de Data Science</h1>
Diante do problema apresentado, primeiramente realizei uma análise exploratória dos dados procurando algum tipo de irregularidade e após realizei testes para entender melhor do que se tratava.

A partir de entender os dados, realizei uma análise do dadaset por completo. Verificando que, os horários B e C tem maior quantidade de dados e capacidade de produção energético. Diante das usinas, foi verificado que a Usina Y possui maior capacidade de produção de energia que a X.

Procurei utilizar um método de clusterização para verificar se o mesmo conseguiria separar os dados por horário de forma eficaz, pois poderia ser útil para algum insight futuro.

Após isso, foquei em realizar uma analise por horário, já que os mesmos tinham valores bem diferentes entre si. Verifiquei que as duas usinas possuem relação positiva entre elas, apesar da quantidade de produção não ser a mesma.A partir do boxplot gerado para os horário B e C percebi que existiam muitos valores de outliers, sendo eles extremamente altos.
Pensei em duas hipóteses:

- A) São valores de extremo calor
- B) São valores do período de verão

Para tentar separar os dados em forma de estações do ano ou em temperaturas altas,médias,baixas, utilizei novamento o método do pca, forçando existir 4 clusters.

A partir disso conseguimos observar a divisão, tendo a primeira valores muito baixos o que resultaria em dados de inverno/temperaturas baixas, valores medianos para os clusters 2 e 3 o que resultaria em dados de outono,primavera/temperaturas médias e o último cluster com valores altos o que resultaria em dados de verão/altas temperaturas.
