# Análise Estatística com Pandas
Após a criação da tabela Estatística de acordo com valores da coluna Preço, Fui capaz de indentificar que:

## Principais análises
A moda sendo menor que a mediana e a mediana sendo menor que a média é um sinal de assimetria Positiva,
ou seja, a maiorias dos preços dos produtos está em valores menores, mas existem alguns preços MUITO altos
puxando a média la para cima.

Já em questão ao Desvio Padrão, fui capaz de observar que o valor está relativamente alto em comparação a média.

Isso indica alta dispersão dos preços, os valores não estam concentrados próximos da média.

Provavelmente:
-Existem produtos baratos ou com preço médio
- e alguns extremamentes caros

O valor minimo e o valor máximo tem uma grande diferença, isso mostra:
- Grande Variação nos preços
- Possível presença de Outliers
Consequentemente a Amplitude tem um valor muito alto onde deixa claro que os dados estão bastante espalhados e que a extremos importante no dataset

Skew sendo Positiva e Kurtosis estando bem acima de 0 reforça a forte assimetria Positiva e a Alta Kurtosis
Interpretação Visivelmente clara:
- muitos produtos têm preços baixos/médios
- poucos produtos têm preços muito altos
- esses valores altos “puxam” a distribuição para a direita
- existem outliers relevantes
- alguns valores extremos aparecem com frequência maior que numa distribuição normal

# Conclusão 
A análise estatística mostrou que os preços possuem alta dispersão e forte assimetria positiva, indicando que a maioria dos produtos possui preços baixos ou médios, enquanto poucos produtos muito caros puxam a média para cima. Além disso, os valores de skewness e kurtosis reforçam a presença de outliers e de valores extremos no dataset.




