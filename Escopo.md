## Escopo do Projeto: Análise de Tendências de Crimes nos EUA com Base nos Dados do FBI

1. Objetivo:

Realizar uma análise detalhada dos dados de crimes fornecidos pelo FBI, identificando tendências e explorando correlações entre diferentes tipos de crimes e fatores socioeconômicos.

2. Fontes de Dados:

Dados de Crimes:

FBI Crime Data: https://ucr.fbi.gov/crime-in-the-u.s

Dados Socioeconômicos:

Renda média por estado: https://www.census.gov/
Taxa de desemprego por estado: https://www.bls.gov/
Nível educacional por estado: https://nces.ed.gov/
Taxa de pobreza por estado: https://www.census.gov/topics/income-poverty/poverty.html

3. Indicadores Principais:

Total de crimes por ano e por estado.
Taxa de crimes violentos (por 100.000 habitantes).
Taxa de crimes contra propriedade (por 100.000 habitantes).
Taxa de homicídios (por 100.000 habitantes).
Taxa de crimes relacionados a drogas (por 100.000 habitantes).

4. Transformações e Cálculos com dbt:

a. Base de Crimes por Estado e Ano:

Agrupe os dados por estado e ano.
Calcule o total de cada tipo de crime.

b. Taxas de Crimes (por 100.000 habitantes):

Utilize a população de cada estado (obtida do U.S. Census Bureau).
Calcule a taxa para cada tipo de crime usando a fórmula: (Número de crimes / População) * 100,000.

c. Integração de Dados Socioeconômicos:

Integre os dados de renda média, taxa de desemprego, nível educacional e taxa de pobreza por estado e ano.
Realize transformações necessárias para alinhar esses dados com os dados de crimes.

d. Correlações:

Utilize funções de correlação para explorar as relações entre os indicadores de crimes e os fatores socioeconômicos.

5. Relações e Correlações a Explorar:

Correlação entre renda média e taxa de crimes.
Correlação entre taxa de desemprego e taxa de crimes.
Correlação entre nível educacional e taxa de crimes.
Correlação entre taxa de pobreza e taxa de crimes.

6. Visualização e Relatórios:

Mapa de calor dos EUA mostrando a taxa de crimes por estado.
Gráficos de linha mostrando tendências de crimes ao longo dos anos.
Gráficos de dispersão explorando as correlações entre crimes e fatores socioeconômicos.
Tabelas detalhadas com taxas de crimes e indicadores socioeconômicos por estado e ano.

7. Considerações Finais:

Garanta que todos os dados estejam limpos e consistentes antes de realizar análises.
Utilize testes no dbt para validar a qualidade dos dados.
Documente todas as transformações e cálculos realizados.
Ao interpretar correlações, lembre-se de que correlação não implica causalidade.