# AcessosTelefoniaMovel-GeoPandas
 Mini Projeto desenvolvido como prática durante a minha jornada de aprendizagem em Data Science.
 
  Nesse projeto foi analisada a quantidade média de acessos relativos aos principais serviços de telecomunicações (Serviço Móvel Pessoal – SMP) no estado do Maranhão no período de Jan./2022 à Fev./2022.

A análise exploratória dos dados, levou em consideração a geolocalização de cada município do Estado e quantidade de acessos de Telefonia Móvel, por tipo de tipo de cobrança (Pós-pago e Pré-pago) e o tipo de pessoa (pessoa física e pessoa jurídica). Após as devidas conclusões, os dados foram dispostos sobre o mapa.

Mapas e seus insights:

1.Mapa de clusters: Nesse mapa, é mostrada a quantidade de acessos de cada município do Estado. A medida que é dado o zoom, os clusters irão se dispersando no mapa levando em consideração a localização de cada município;

2. Mapa de Calor (heatmap): Nesse mapa, é mostrado onde se concentra a maior parte dos dados. Quanto mais vermelha for a área, maior é a concentração dos dados. Nesse mapa, está destacado (figura com contorno preto) a geometria (dimensões) geoespacial que forma a ilha de São Luís;

3. Mapa de geolocalização: Nesse mapa, mostra a posição de cada município dentro do Estado e ao clicar em cada município, é gerado um popup que mostra o nome do município e a quantidade média dos acessos daquele estado.

Os dados analisados, são as quantidades de acessos das quatro maiores empresas de Telecomunicações do País (TIM Brasil, Vivo (Telefônica Brasil), Claro Brasil e Oi). 

Ferramentas utilizadas:

Linguagem de programação Python;
JupyterLab;

Comentários: 

1.Devido às bases de dados serem muito grandes (na casa dos gigabytes) e o meu computador ser fraco para esse tipo de processo, fiz várias manipulações de dados (slices) utilizando a biblioteca Pandas do Python.
