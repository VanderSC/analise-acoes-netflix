![image](https://github.com/VanderSC/analise-acoes-netflix/assets/95940138/415938ce-f30b-4cb6-af0a-0473d5c9c98d)

Este conjunto de dados fornece um registro abrangente das mudanças de preço das ações da Netflix ao longo do tempo. Ele inclui colunas essenciais, como data, preço de abertura, maior preço do dia, menor preço do dia, preço de fechamento, preço de fechamento ajustado e volume de negociação.

Fazer esse tipo de análises dos dados, pode proporcionar uma série de benefícios e insights importantes para investidores, analistas financeiros e gestores de portfólio, entre outros.

Esta tabela fornece estatísticas descritivas para os diferentes atributos (colunas).

count: O número total de observações (linhas) para cada atributo.

mean: A média dos valores para cada atributo.

std: O desvio padrão dos valores para cada atributo, que é uma medida de dispersão em torno da média.

min: O valor mínimo para cada atributo.

25%: O primeiro quartil (Q1), que é o valor abaixo do qual 25% dos dados se encontram.

50%: O segundo quartil (Q2), também conhecido como mediana, que é o valor abaixo do qual 50% dos dados se encontram.

75%: O terceiro quartil (Q3), que é o valor abaixo do qual 75% dos dados se encontram.

max: O valor máximo para cada atributo.

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Open</th>
      <th>High</th>
      <th>Low</th>
      <th>Close</th>
      <th>Adj Close</th>
      <th>Volume</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>5540.000000</td>
      <td>5540.000000</td>
      <td>5540.000000</td>
      <td>5540.000000</td>
      <td>5540.000000</td>
      <td>5.540000e+03</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>140.532640</td>
      <td>142.672456</td>
      <td>138.337011</td>
      <td>140.561354</td>
      <td>140.561354</td>
      <td>1.569438e+07</td>
    </tr>
    <tr>
      <th>std</th>
      <td>182.387899</td>
      <td>184.938036</td>
      <td>179.723418</td>
      <td>182.376297</td>
      <td>182.376297</td>
      <td>1.862414e+07</td>
    </tr>
    <tr>
      <th>min</th>
      <td>0.377857</td>
      <td>0.410714</td>
      <td>0.346429</td>
      <td>0.372857</td>
      <td>0.372857</td>
      <td>2.856000e+05</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>4.165893</td>
      <td>4.245714</td>
      <td>4.080000</td>
      <td>4.163036</td>
      <td>4.163036</td>
      <td>5.751000e+06</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>35.942858</td>
      <td>36.778572</td>
      <td>35.346429</td>
      <td>36.154285</td>
      <td>36.154285</td>
      <td>9.830450e+06</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>282.360008</td>
      <td>287.464989</td>
      <td>275.742500</td>
      <td>282.892502</td>
      <td>282.892502</td>
      <td>1.859220e+07</td>
    </tr>
    <tr>
      <th>max</th>
      <td>692.349976</td>
      <td>700.989990</td>
      <td>686.090027</td>
      <td>691.690002</td>
      <td>691.690002</td>
      <td>3.234140e+08</td>
    </tr>
  </tbody>
</table>
</div>

Um gráfico de candlestick é interessante porque fornece uma representação visual do preço das ações da Netflix ao longo do tempo. Ele é amplamente utilizado na análise técnica do mercado financeiro porque permite observar facilmente os padrões de preço, tendências e volatilidade de um ativo.

![Captura de tela 2024-06-03 152330](https://github.com/VanderSC/analise-acoes-netflix/assets/95940138/cfea6a8f-c3b8-4b80-80e7-876cf79cc412)

Utilizando um gráfico de boxplot para comparar o fechamento das ações da Netflix nos anos de 2002 até 2024.

O boxplot é uma ferramenta poderosa para visualizar a distribuição dos dados e identificar medidas resumidas, como mediana, quartis e possíveis outliers. Ao comparar o fechamento das ações em diferentes anos, os investidores podem entender como o preço se comportou ao longo do tempo e se houve mudanças significativas na distribuição.

![image](https://github.com/VanderSC/analise-acoes-netflix/assets/95940138/8dbbc8eb-e2e2-440b-9ad6-6bb2dff0d095)

A estabilidade nos anos anteriores a 2010 pode ser atribuída ao estágio inicial da empresa e à sua posição no mercado de streaming de vídeo, que ainda estava em desenvolvimento.

O grande aumento a partir de 2010 pode refletir o crescimento exponencial da Netflix como uma plataforma líder de streaming de vídeo, à medida que ela expandiu seu catálogo de conteúdo, aumentou sua base de assinantes e expandiu sua presença global. A partir de então, vários fatores, como lançamento de conteúdo original, parcerias estratégicas e avanços tecnológicos, podem ter contribuído para esse crescimento contínuo.

Durante os anos de 2020 e 2021 apesar da pandemia, é interessante. Durante esse período, muitas pessoas em todo o mundo passaram mais tempo em casa devido a medidas de distanciamento social, o que levou a um aumento na demanda por entretenimento em casa, incluindo serviços de streaming como a Netflix. Além disso, a Netflix conseguiu continuar produzindo conteúdo original e adaptar sua estratégia de negócios para atender às novas demandas do mercado, o que pode ter contribuído para seu sucesso durante a pandemia.

O gráfico de volume de negociação de ações da Netflix fornece uma visão geral da atividade de compra e venda de ações da empresa ao longo dos anos.

![image](https://github.com/VanderSC/analise-acoes-netflix/assets/95940138/92d89f7a-58e6-47fe-bc91-3af5dcb2616f)

É interessante observar esses picos no volume de negociação das ações da Netflix nos anos de 2011 e 2012, podem ter sido impulsionados pelo aumento da popularidade da Netflix como plataforma de streaming de vídeo.

Embora estejamos apenas na metade de 2024, o volume de negociação das ações da Netflix não chega nem perto do registrado em 2023. Essa diferença substancial pode ser resultado de diversos fatores, incluindo as expectativas dos investidores, condições menos favoráveis do mercado e mudanças nos preços de assinatura
