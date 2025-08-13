# Projeções Multidimensionais

Repositório com os dados de projeções multidimensionais para o Brasil e UFs.
Dados organizados por sexo, idade e nível educacional, para o período 2022-2062.

## Informações gerais
Os dados estão organizados para cada quinquênio, entre 2022 e 2062.
Os níveis educacionais utilizados seguem as definições de Speringer et al. (2019), e são:
E1 - Sem instrução;
E2 - Primário incompleto;
E3 - Primário completo;
E4 - Ensino fundamental completo;
E5 - Ensino médio completo;
E6 -  Ensino superior.

SPERINGER, M. et al. Global Reconstruction of Educational Attainment, 1950 to 2015: Methodology and Assessment. VID Working Paper, 02/2019, Vienna, Austria: VID/OÄAW, 2019.

A metodologia completa para a realização do trabalho e os códigos podem ser solicitados ao pesquisador.
Abaixo seguem os resultados para o Brasil, considerando as mudanças na estrutura etária por sexo, idade e nível educacional.

## Métodos e dados
A base incluída contém 3 cenários futuros da dinâmica demográfica e socioeducacional, baseados nas shared socioeconomic pathways - SSPs (RIAHI et al., 2017, KC;LUTZ, 2017) e segue pressupostos que combinam as projeções oficiais do Brasil (IBGE, 2024) com as utilizadas nas SSPs (WCDE, 2024).
Cenários:
1. SSP1 – Sustentabilidade. Há uma transição gradual para um desenvolvimento inclusivo, respeitando limites ambientais. Os avanços na gestão de bens comuns globais e investimentos em educação e saúde aceleram a transição demográfica, com diminuição da fecundidade e aumento da expectativa de vida. Governos e sociedades aumentam o foco no bem-estar, na redução da desigualdade e há menor uso de recursos naturais e energéticos.
2. SSP2 - Meio do caminho. Há desafios intermediários à mitigação e adaptação. A desigualdade persiste, e o progresso para os Objetivos do Desenvolvimento Sustentável – ODSs, é lento. A degradação ambiental persiste, mas o uso de recursos naturais e energético apresenta diminuição. O crescimento populacional se estabiliza na segunda metade do século XXI, com tendência de mudança inercial da migração, fecundidade e mortalidade. Há persistentes desafios à redução da vulnerabilidade.
3. SSP3 - Rivalidade regional. O nacionalismo é ascendente, e os conflitos regionais levam os países a priorizarem questões domésticas, com foco em segurança energética e alimentar. O desenvolvimento é lento, investimentos em educação e tecnologia diminuem, e o consumo de recursos é elevado. Desigualdades aumentam e a degradação ambiental é intensa em algumas regiões, especialmente nas menos desenvolvidas. Há estabilização dos níveis da mortalidade, fecundidade e migração.


- Base de dados: pop_idade_sexo_edu.csv. 
Variáveis: 
1. region = Código da UF (IBGE);
2. area = Sigla da UF;
3. Time = ano projetado;
4. sex = sexo do grupo (f = mulheres; m = homens);
5. edu = grupo educacional;
6. agest = grupo etário quinquenal (o valor se refere ao início do grupo etário; último grupo etário de 80 anos e mais);
7. scenario = cenário SSP;
8. pop = tamanho da população.


- IBGE. Projeções da População: Brasil e Unidades da Federação. Estimativas e Projeções: Revisão 2024, Notas metodológicas 01/2024. IBGE, Rio de Janeiro, 2024.
- RIAHI, K. et al. The Shared Socioeconomic Pathways and their energy, land use, and greenhouse gas emissions implications: An overview. Global Environmental Change, v. 42, pp. 153-168, 2017.
- KC, S.; LUTZ, W. The human core of the shared socioeconomic pathways: Population scenarios by age, sex and level of education for all countries to 2100. Global Environmental Change, v. 42, pp 181-192, 2017.
- WITTGENSTEIN CENTRE FOR DEMOGRAPHY AND GLOBAL HUMAN CAPITAL. Human Capital Data Explorer Version 3.0. 2024. Disponível em http://dataexplorer.wittgensteincentre.org/wcde-v3/

## Resultados gerais
O arquivo Estruturas_Etarias.R traz o exemplo das estruturas etárias para o Brasil, utilizando a base de dados com os resultados.

## Licença
Creative Commons 4.0 (CC by 4.0).

## Contato
Cesar Marques — (cesar.m.silva@ibge.gov.br)
Escola Nacional de Ciências Estatísticas - ENCE/IBGE