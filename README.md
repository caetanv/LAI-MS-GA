# Resumo
Este projeto tem como objetivo analisar e comparar os dados de pedidos de acesso à informação obtidos pelas Controladoria Geral da União (CGU) nos períodos entre o início do ano de 2018 e o fim de 2021. Esses dados foram processados no software Iramuteq e pelas análises de dados feitas pelas planilhas disponibilizadas pela CGU, que foi possível : obter informações geradas sobre o destaque de palavras-chaves; organizar os pedidos em nuvem de palavras; e realizar a verificação quantitativa dos dados.

# Introdução
A crise sanitária decorrente da pandemia de Covid-19 impactou profundamente os processos cotidianos da sociedade em escala global, alterando já em sua fase inicial - no Brasil, em março de 2020 - as modalidades de trabalho, de ensino básico e superior, mobilidade urbana e todas as atividades presencialmente ativas entre pessoas.
A brusca necessidade de alterações em atividades do cotidiano criou inevitavelmente ruídos de informação, evidenciando a posição da informação como recurso fundamental nos esforços do conjunto da sociedade rumo à proteção das vidas. Muitas das atividades tiveram que se adaptar e foram possíveis com o contexto virtual e tecnológico no qual vivemos atualmente. 
Dada a natureza sanitária da crise, todos os olhos se tornam ao Ministério da Saúde (MS), órgão federal que foi responsável pela centralização, contabilização e divulgação dos dados e informes sobre a pandemia, que hoje estão em todos os noticiários, como o número de infectados, óbitos por estado e município, dados sobre a semana epidemiológica, ocupação de hospitais etc. No entanto, esta situação se dá em um contexto em que havia um extenso esforço prévio de garantia de acesso a dados e informações. A partir da compreensão deste quadro pode se levantar a questão: houve alteração na prestação do serviço de informação por parte do Ministério da Saúde? 
Durante a pandemia, juntamente com a crise sanitária, o país também passou por uma crise de dados nos sistemas de informação. Em 10 de dezembro de 2021, as plataformas e-SUS Notifica, o Sistema de Informação do Programa Nacional de Imunização (SI-PNI), o ConecteSUS e funcionalidades como a emissão do Certificado Nacional de Vacinação Covid-19 e da Carteira Nacional de Vacinação Digital perderam suas funcionalidades. A falha nos sistemas comprometeu o acesso aos dados relacionados à saúde, inclusive os pandêmicos. A perda comprometeu não apenas a formulação e monitoramento de políticas emergenciais pelo poder público, mas impossibilitou o controle exercido pela sociedade civil das políticas de contingenciamento, parte imprescindível da participação social. Porém, além do ataque cibernético, a agência “Fique Sabendo” divulgou dados em abril de 2021 sobre a taxa de resposta do Ministério da Saúde em relação à pedidos de acesso à informação e foi observado que a pasta é a que mais ignora pedidos do governo federal, mesmo durante a crise sanitária. 
Tendo esta questão como mote, este trabalho propõe uma análise qualitativa da transparência passiva de modo a observar alterações no padrão de atendimento do MS em dois períodos distintos, sendo eles: janeiro de 2018 à dezembro de 2019 - como variável controle - e abril de 2020 à dezembro de 2021 - tomando como marco a Mensagem Presidencial nº23 que reconhece estado de calamidade pública no Brasil de acordo com recomendação da Organização Mundial da Saúde (OMS). As escolhas metodológicas utilizadas neste trabalho estão descritas na seção seguinte. 

# Metodologia
De forma a analisar as diferenças nos tratamentos dos pedidos de informações antes e durante a pandemia do novo coronavírus, foram averiguados todos estes para a pasta do Ministério da Saúde (MS) de acordo com o seguinte recorte temporal: 2018 - 2021. Se obteve os dados desses pedidos a partir das planilhas disponibilizadas pela Controladoria Geral da União (CGU), que possibilitaram a contagem dos pedidos submetidos, os atendidos e os não atendidos a cada ano.
A partir dessa observação, foram combinados os modelos qualitativo e quantitativo do período pandêmico, para que se possa, primeiramente, mapear os pedidos que não foram respondidos, e, posteriormente, avaliar tais pedidos a fim de estabelecer se há algum padrão de solicitações não respondidas.
A base de dados utilizada foi as planilhas disponibilizadas pelo portal eletrônico governamental FalaBr. Nestes dados, foram utilizadas filtragens sobre os dados respondidos pelo Ministério da Saúde a partir do software Iramuteq. Em seguida, foram selecionadas as categorias relacionadas a pandemia da Covid-19. A análise quantitativa dos dados de transparência passiva possibilita obter uma dimensão referente aos pedidos concedidos e não concedidos.
Para trabalhar a análise de dados o software livre Iramuteq nos serve como ferramenta de manipulação de palavras as quais foi possível detectar e quantificar as referências de palavras-chaves existentes no corpo dos pedidos.
# Desenvolvimento
Foram extraídos os dados sobre os pedidos da LAI a respeito dos anos de 2018, 2019, 2020  e 2021. Esses pedidos foram retirados através da plataforma de Busca de Pedidos e Respostas, do site da Controladoria Geral da União. Os dados obtidos continham as informações de cabeçalhos da seguinte maneira :
![image](https://user-images.githubusercontent.com/7980761/180070329-9e0c0a51-ba64-4810-975d-20be99713e57.png)

Após a extração dos dados - que nestes haviam todos os pedidos de Acesso à Informação de todos os órgãos federais -, posteriormente foram agrupados e postos em gráfico da seguinte maneira:

![image](https://user-images.githubusercontent.com/7980761/180070392-b6868705-bdb2-4141-a83b-a61a5c9fba25.png)

![image](https://user-images.githubusercontent.com/7980761/180070435-cc92b476-07bf-4728-b049-649e4fc14d55.png)

É possível verificar que há um crescimento gradual de aproximadamente 16% nos pedidos de informação direcionados ao Ministério da Saúde entre 2018 a 2020. Contudo, mesmo com a decretação de estado de emergência e o reconhecimento do Covid-19 pelas autoridades do país do início da pandemia, aparentemente, não se refletiram em aumento significativo na demanda por informações por parte do Ministério da Saúde.
A partir do software e das planilhas, serão feitas comparações quantitativas dos pedidos e suas categorizações para que se possa observar a existência de padrões. A próxima seção, de Resultados, apresentará de forma específica as descrições do que foi observado nas análises dos números e porcentagens geradas no  processamento via software.

# Resultados Obtidos
Nesta seção serão descritos os resultados obtidos a partir da metodologia utilizada para a realização do desenvolvimento das análises de planilhas fornecidas pela CGU. Foram utilizadas para as observações as seguintes classificações: nuvem de palavras, categorização dos assuntos e status dos pedidos.
As informações resultantes permitirão relacionar a variação dos dados de pedidos de informação com o contexto da pandemia.

## Limpeza dos Pedidos e Cloud Of Words (“nuvem de palavras”)
Delimitando apenas os pedidos enviados ao Ministério da Saúde, uma filtragem foi realizada para remoção das denominadas “stopwords” (que significa “palavras de parada”), que são os conectivos em português (por exemplo: de, para, por, etc), dos textos dos pedidos que estavam na coluna “DetalhamentoSolicitacao”. Também foram eliminados verbos e alguns substantivos genéricos e frequentes, como por exemplo “saúde” e “ministério”, etc. A justificativa para a exclusão destes termos em específico é a frequência em que aparecem nas introduções dos pedidos, como “solicito ao ministério da saúde”. Em seguida, o texto final tratado foi exportado para um arquivo em formato .txt, que, então, foi aberto dentro do software  Iramuteq.
Uma vez no Iramuteq, os dados importados foram processados de acordo com os anos listados, nos quais foram gerados as seguintes nuvens de palavras:

### 2018
![image](https://user-images.githubusercontent.com/7980761/180070594-ce07f146-fdbd-4fd1-9239-c49b39f0145c.png)

Em 2018 é possível observar uma nuvem de palavras espaçada e composta por menos elementos, em relação aos anos posteriores. Em relação ao teor dos pedidos, são observadas ocorrências significativas de solicitações de dados orçamentários, processuais, informações de compra e medicamentos. Em relação aos níveis da federação, as palavras “município”, “Brasil”, “federal” e “nacional” foram citadas mais vezes que a palavra “estados”. 

### 2019
![image](https://user-images.githubusercontent.com/7980761/180070658-be7153fd-c03a-4169-9ba0-add6e6d1df86.png)

Em 2019 é possível,  a nuvem de palavras se torna mais densa. Porém, o teor dos pedidos é muito semelhante ao do ano anterior. 

### 2020
![image](https://user-images.githubusercontent.com/7980761/180070784-588be231-776a-4997-a45e-33da4ef7ed9e.png)

Em 2020, primeiro ano da pandemia do Covid-19, os pedidos passam a ter palavras correspondentes a temáticas diferentes entre as mais citadas. Além do próprio termo Covid-19, também foram solicitadas informações referentes à vacina e testes. 

### 2021
![image](https://user-images.githubusercontent.com/7980761/180070856-8cead4b8-f954-42c7-a288-1fe96159d08a.png)

No ano de 2021,em relação ao ano anterior, são adicionadas ocorrências referentes às doses vacinais, explicadas pela introdução da vacinação contra o vírus no Brasil . 

## Resultados das Análises dos Assuntos Pedidos

Da mesma forma, foi feito um relatório utilizando a biblioteca de nome “pandas_profiling”, uma biblioteca disponível na internet para se utilizar na programação com a linguagem Python. O arquivo da planilha foi trabalhado no ambiente de desenvolvimento colaborativo virtual e online, Jupyter Notebook. Desta forma foi possível realizar a análise das outras colunas dos pedidos. Serão apresentadas posteriormente as categorizações dos pedidos (coluna “AssuntoPedido”), incrementadas e melhor detalhadas nos anos de 2020 e 2021:

## Categorização dos Pedidos 

![image](https://user-images.githubusercontent.com/7980761/180070962-fd39bdd8-b2f5-478c-bf51-0e4fc235505d.png)
Nestas comparações entre as categorias dos assuntos dos pedidos foi observado que, nos anos de 2018 e 2019, a plataforma que recebia os pedidos ao Ministério da Saúde agrupava em 4 categorias referente ao assunto do pedido. No período seguinte, houve um aumento nas categorizações, passando a existir um total de 78 categorias já no ano de 2020. 

Neste ano de 2020 também marca o início da pandemia no país, onde o governo decreta o país sob estado de emergência, normas e regulamentações são adotados para a prevenção e o tratamento da infecção do COVID-19 (BRASIL, 2020). Os governos federal, estaduais e municipais começam a dirigir políticas públicas para conter e combater a pandemia. Os assuntos relacionados ao COVID-19 e tudo que o cerca começam a ter grande destaque e são centrais nos pedidos de informações ao Ministério da Saúde. Analisando sistematicamente, observa-se que a categorização  “Outros”, que antes era a maioria dos assuntos, teve uma redução no número total de pedidos.

No ano de 2021 houveram 107 categorias para classificação dos pedidos e, dessa vez, a categoria mais relevante foi o de “Acesso à informação”. Já o número de pedidos em relação ao COVID teve uma queda, mas ainda  obteve destaque quando se analisa de maneira geral.
Não se observa vantagens quanto à enorme categorização de tipos de pedidos, pois muitos pedidos não são classificados com categorias no âmbito específico da saúde, e podem até de certa forma serem desconsiderados para se fazer um levantamento da análise de dados, pois não trazem resultados significativos para os gráficos.

## Resultado das Análises Feitas Sobre os Acessos Concedidos

A partir dos dados separados nas tabelas, também foi calculado a porcentagem de pedidos que receberam respostas positivas quanto  a solicitação de dados e outros documentos, que podiam já estar disponíveis na plataforma ou não. Utilizando os valores “Acesso Concedido” na coluna "Decisão" é possível ilustrar a quantidade de pedidos que tiveram o acesso à informação concedido.

![image](https://user-images.githubusercontent.com/7980761/180071052-02fd2cac-6837-4284-a1a6-f8a8955389e5.png)

Podemos observar a partir da análise dos dados que houve queda sensível da taxa de resposta concedida pelo Ministério da Saúde ao longo do período analisado. Realizando-se a média da taxa de resposta, temos uma queda média de 4,45% por ano no período e de 13,36% em relação ao ano base.  
Existem também outras categorias de acesso dispostas nas planilhas, além de “Acesso Concedido”. São elas “Acesso Negado”, “Acesso Parcialmente Concedido”, “Pergunta Duplicada/Repetida”, “Informação Inexistente”; “Órgão não tem competência para responder sobre o assunto” e “Não se trata de solicitação de informação”. A relação temporal entre as categorias pode ser observada no gráfico a seguir:

![image](https://user-images.githubusercontent.com/7980761/180071096-faad4bbb-38af-4a8e-87d1-994d724687a7.png)

Por outro lado, pode-se observar também significativo aumento na taxa de pedidos de informação classificados como “Acesso Negado”. O gráfico seguinte ilustra a afirmação, removendo apenas a categoria “Acesso Concedido" para melhor visualização das informações:

![image](https://user-images.githubusercontent.com/7980761/180071147-9345c342-0b8d-4ed3-8aa4-6ab8bc11f260.png)

No que diz respeito aos acessos negados, o ano de 2018 registrou 4,08% dos pedidos com a negativa de acesso. Nos anos seguintes, essa porcentagem cresceu substancialmente e a categoria passou a representar uma porcentagem mais expressiva do total de respostas, com aproximadamente 5% e 7,5%, em 2019 e 2020 respectivamente, representando aumento maior de 2,65% entre os dois anos. Já em 2021, 9% dos pedidos estavam com o status de pedido negado, aumento de 1,45% em relação ao ano anterior e de 4,92% ao ano base.
Além disso, é possível observar uma relevante mudança “Acesso Parcialmente Concedido”, caindo aproximadamente 1% entre 2018 e 2019, porém crescendo pouco mais de 2% até 2021. Outro indicador que cresceu ao longo do período analisado é o “Informação Inexistente”, principalmente em 2021, ano em que passou de representar 1,72% para 3,51% do total. 

Este aumento do número de pedidos negados, parcialmente concedidos e de informação inexistente se deu independentemente do crescimento da demanda de pedidos de pedidos de acesso à informação, pois em 2021 os encaminhados ao Ministério da Saúde foram identificados em menor número que no ano anterior.
![image](https://user-images.githubusercontent.com/7980761/180071195-cebeb775-d1b2-4dee-ab19-790d94b0423f.png)

O número de pedidos concedidos teve queda em porcentagem com o período da pandemia, mesmo com a diminuição do número de pedidos pela população, revelando o impacto que houve no sistema de pedidos de informação. E ainda assim o COVID-19 se mostrou a terceira categoria mais requisitada nos pedidos. Houve uma quantificação semelhante nos pedidos de 2020 e 2021 em relação com as categorias “acesso à informação” e “outros em saúde” que pode indicar a importância dada pelo órgão em adaptar melhor o uso das categorias durante as mudanças que ocorreram neste período de adaptação na quantidade de categorias.

Também foi feita a análise da “Decisão do Pedido” considerando as Top 4 categorias mais frequentes de cada ano.

![image](https://user-images.githubusercontent.com/7980761/180071241-80894b0e-5ffc-41d4-9cd0-07035b2d09e5.png)

Pudemos observar que a divisão do assunto não varia muito em relação ao Total, ou seja, não existe nas top 4 categorias mais frequentes, uma categoria que atrapalhe ou tenha um índice de resposta significativamente menor.
		Mas pudemos perceber que a categoria “Medicamentos e Aparelhos” esteve sempre acima da média Total na decisão de “assuntos respondidos”, o que pode significar alguma influência do contexto pandêmico. 

# Conclusões

A crise sanitária fez com que todos os setores envolvidos passassem a operar, muitas vezes, centralmente para execução de novas políticas públicas e entre outras formas de adaptações. O Ministério da Saúde, junto aos três poderes da União e a própria sociedade civil passaram a ter a prevenção e o combate ao novo coronavírus como a principal forma de ação. 
Notavelmente, durante a pandemia em 2020 , observou-se que o número de pedidos ao Ministério da Saúde se manteve relativamente estável, nas quais plataformas governamentais puderam funcionar de forma regular, de forma geral. No entanto, foi possível reparar algumas mudanças nas temáticas e palavras-chaves dentro dessas solicitações.
Foi necessário  a eliminação de alguns termos e itens nos pedidos para que se pudesse obter um diagnóstico mais compreensível  e objetivo, enquanto dentro da Cloud of Words foi possível ter um reconhecimento geral das expressões mais utilizadas nos pedidos. Apesar de nem sempre a análise de forma isolada de algumas palavras-chaves e termos não significarem a centralidade do pedido, é apropriado afirmar que não houveram grandes alterações no padrão do uso destes nos pedidos ao longo desses anos analisados, mas apenas algumas particularidades a partir do  ano de 2020, marco inicial da pandemia no país. 
Da mesma forma, a partir de 2020  pudemos perceber que houve uma pulverização de categorias nos assuntos dos pedidos, essas que eram muito genéricas e abrangentes em 2018 e 2019, mas se tornaram um pouco mais específicas no ano de 2020 e continuaram a crescer no ano de 2021. Usualmente, essas categorizações atribuídas não são atribuídas de forma muito rigorosa nem específica, o que pode ajudar para se obter uma pesquisa mais objetiva, porém carrega também alguns aspectos negativos, tais quais a falta de detalhamento dos pedidos e a identificação das especificidades e diferenças entre estes. 
Como limitação, o estudo não pretendeu verificar de forma específica e individual o conteúdo de cada pedido, mas somente apontar alguns padrões gerais e tendências dentro de uma perspectiva macro. Da mesma forma, o trabalho foi realizado a partir dos dados primários, sem muitos respaldos e tratamentos. O diagnóstico serviu para indicar alguns aspectos que foram verificados com frequência,  ponderando que tais pautas sejam discutidas e sejam revistas,  buscando a melhor integração entre população, plataformas digitais e o governo federal. Como sugestão para trabalho futuros, recomenda-se o aprofundamento na análise dos pedidos, como o  status que estes se encontram - acesso concedido, acesso parcialmente concedido e acesso negado - principalmente este último, que pode ser ser explicado por diversos fatores, tais quais pedidos inválidos, dados que já se encontram no portal, dados sigilosos, negligências, entre outros.

# Bibliografia

ROCHA, Lucas; MOREIRA, Rudá. Apagão de dados do Ministério da Saúde deixa monitoramento da pandemia à deriva. Indicadores como os números de casos e de óbitos, dados de hospitalização e o percentual da população vacinada ajudam a compor cenário epidemiológico da Covid-19 no país. Disponível em: https://www.cnnbrasil.com.br/saude/apagao-de-dados-do-ministerio-da-saude-deixa-
monitoramento-da-pandemia-a-deriva/ Data de Publicação: 07/01/2022. Data de Acesso em 05/06/2022

Brasil de Fato. Ministério da Saúde é a pasta que mais ignora pedidos de acesso a informação pública. Dados foram sistematizados e divulgados pela agência Fiquem Sabendo, especializada na Lei de Acesso à Informação (LAI) Disponível em: https://www.brasildefato.com.br/2021/04/26/ministe
rio-da-saude-e-a-pasta-que-mais-ignora-pedidos-de-acesso-a-informacao-publica Data de Publicação: 26/04/2022. Data de Acesso: 05/06/2022

GOV.BR. Busca de Pedidos e Respostas Disponível em: https://www.gov.br/acessoainformacao/pt-br/assuntos/busca-de-pedidos-e-respostas/busca-de-pedidos-e-respostas Data de Acesso: 10/05/2022

CGU, Consulta ao E-SIC pela ferramenta da de pesquisa de consultas da CGU Disponível em: http://www.consultaesic.cgu.gov.br/busca/SitePages/principal.aspx Data de Acesso: 10/05/2022

GOV.BR. Avaliação QualiLAI Disponível em: https://www.gov.br/acessoainformacao/pt-br/lai-para-sic
/politica-monitoramento/avaliacao-do-atendimento-a-lai Data de Acesso: 10/05/2022

CGU, FALA BR Plataforma Integrada de Ouvidoria e Acesso à Informação https://falabr.cgu.gov.br/publico/Manifestacao/SelecionarTipoManifestacao.aspx?ReturnUrl=%2f Data de Acesso: 10/05/2022

CGU, Paineis da CGU. Disponível em: http://paineis.cgu.gov.br/resolveu/index.htm e http://paineis.cgu.gov.br/lai/index.htm Data de Acesso: 10/05/2022

BRASIL. Lei nº 13.979, DE 06 DE FEVEREIRO DE 2020. Dispõe sobre as medidas para enfrentamento da emergência de saúde pública de importância internacional decorrente do coronavírus responsável pelo surto de 2019.Diário Oficial da União: seção 1, Brasília, DF, ano 139, n. 8, p. 1-74, 11 jan. 2002.








