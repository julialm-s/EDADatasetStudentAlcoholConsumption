Analisar as variáveis nominais tendo o desejo de ensino superior como um sintoma das notas baixas, porque há uma diferença gritante entre as notas do grupo que deseja faculdade do que não deseja.

A ideia é utilizar as outras variáveis nominais como contexto, para explicar as notas baixas e o desejo de faculdade.

RELAÇÃO DAS VARIÁVEIS:

região ↔ trabalho da mãe e do pai
escola ↔ região
desejo de ensino superior ↔ região, escola e sexo

Para cada par de variáveis nominais, calculamos o V de Cramér, um número de 0 a 1 que diz quanto uma variável “acompanha” a outra:

Perto de 0: conhecer uma não ajuda a adivinhar a outra.
Perto de 1: conhecer uma quase entrega a outra.

Com 10 variáveis são 45 pares, e o mapa de calor mostra todos de uma vez, com a cor mais escura nos pares mais ligados. Na prática vamos ver valores baixos, e como regra geral: abaixo de 0,1 é praticamente nenhuma relação, de 0,1 a 0,2 é fraca, e de 0,2 a 0,4 é moderada.

Conclusões:

Português:
Quanto ao desejo de ensino superior nas escolas, concluí-se que, em todas as escolas, quem deseja a faculdade, tem notas muito maiores, variando entre 2 a quase 4 pontos de diferença.

Matemática:
Na matéria de matemática, a escola GP permanece com o padrão de quem deseja faculdade possuir notas maiores.
Na escola MS, essa ideia não se traduz, pois só possui 3 alunos que não desejam a faculdade.

Na matéria de matemática, não conseguimos dizer se a diferença das notas entre os sexos provém da escola com precisão, porque apenas 46 alunos da escola MS cursam a matéria, contra 349 da escola GP.

Conseguimos observar, de maneira geral, que em matemática, os homens tiram notas melhores que as mulheres.
Em matemática, na escola GP, os homens tiram notas maiores. Na escola MS, as mulheres tiram notas maiores.
Enquanto que em português, as mulheres tiram notas maiores em ambas as escolas.

Na matéria de português, em ambas as escolas as mulheres são melhores que os homens. (cf. relacao_escola...)


Algo que quero te dizer é que não vamos mais analisar o arquivo dos alunos de matemática, vamos apenas retirá-lo.
Sobre como vamos definir o Q1 e Q4 dentro de cada escola.
Inicialmente eu tinha pensado em algo que fosse como a opção A, que pega os valores gerais e plota um gráfico disso. Mas diante do que você falou, acho melhor fazer os cortes dentro da própria escola, apesar dos meus colegas de projeto terem feito de forma geral, porque eles nao consideraram a escola como uma coluna durante a análise deles. 
Outra coisa que quero que tratemos é a seguinte: o meu desejo com isso é tirar dados mais conclusivos sobre os grupos e poder concluir que x grupo ocupa uma maior porcentagem no quarto quartil que em relação ao grupo y. Isso vai ser possível de identificar?
Quero que o código seja semelhante ao do boxplot por lente, para que eu possa alterar as variáveis que estão sendo plotadas facilmente.
Antes de implementar, apenas confira tudo antes. Informe sempre o tamanho do grupo, como no boxplot por lente e use media_notas.



Não coloque taxa de 25%. Eu gostaria de fosse feito um gráfico de barra, com as porcentagens, assim como vc fez o outro.
Eu pensei exclusivamente no gŕafico plotado mostrando a diferença, como é mostrado nesse, por exemplo:

O que quero no gráfico é apenas as porcentagens em cima das barras para que assim eu possa colocá-los na apresentação e explicar mais facilmente.
