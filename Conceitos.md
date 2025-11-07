## Bill Inmon

[x] Apresentar os dados de forma contextualizada, respeitando as dimensões de tempo, produto, cliente, entre outras.

> Todas as informações fazem parte do contexto da reserva, respeitando a dimensão do tempo (ordnação dos mais recentes na grid e temporal no gráfico de linhas)

[x] Permitir análise comparativa, mostrando variações, tendências e correlações.

> Gráfico de linhas permite comparar o número de reservas por dia, permitindo enxergar a variação no tempo. Já o grafico de rosca permite verificar a prefeência/tendência por determinado tipo de quarto.

[ ] Garantir confiabilidade, refletindo fielmente os dados do armazém (DW).

> 

[x] Ser padronizados e consistentes, permitindo que diferentes áreas usem os mesmos indicadores.

> A paleta de cores com predominancia do azul é mantida desde o cabeçalho ao elementos dos gráficos. 

[x] Apoiar decisões táticas e estratégicas, mais do que apenas operacionais.

> Análises de reservas por dia pode apoiar decisões sobre a quantidade de prestadores de serviço necessários, organização de escalas de trabalho, quantidade de alimento produzido preparado para os hóspedes... Enquanto a análise sobre a preferência do tipo de quarto pode servir para decidir por novas expansões.

[ ] Servir como interface de consulta corporativa, normalmente a partir de ferramentas OLAP e de reporting institucional.

> 

## Ralph Kimball

[x] Os relatórios devem ser baseados em modelos dimensionais (fato e dimensão), permitindo navegação intuitiva.

> Os dados estão organizados através do modelo dimensional, contendo a tabela fato Reserva apoiada pelas dimensões Cliente e Data

[x] O design visual precisa ser orientado ao negócio — os usuários devem entender os relatórios sem depender de suporte técnico.

> Os nomes das colunas foram tratados para melhor legibilidade, Legendas e marcações foram adicionadas aos gráficos.

[x] O BI deve permitir autonomia analítica, favorecendo o self-service BI.

> O usuário pode filtrar o relatório pelo tipo de quarto, de forma a entender os dados de forma segmentada.

## Thomas Davenport

[ ] São instrumentos de aprendizado organizacional, promovendo decisões baseadas em evidências.

> 

[x] Devem ser construídos com propósito, orientados a perguntas-chave do negócio.

> O relatório proposto segue o propósito de listar as reservas conforme objetivo solicitado, além de apoiar a pergunta-chave implicita no contexto de analisar as reservas ao longo do tempo através dos gráficos.

[ ] Devem incorporar narrativas e storytelling com dados, conectando análise e contexto.

> 

## Stephen Few

[x] Evitar sobrecarga visual: eliminar elementos que não contribuem para a compreensão.

> O relatório apresenta somente conteúdos relacionados as reservas, com design limpo.

[ ] Priorizar legibilidade e hierarquia visual, destacando o que é mais relevante.

>

[x] Utilizar gráficos adequados a cada tipo de análise, como séries temporais para tendências e colunas para comparações.

> Utilizado o gráfico de linhas para entender a ocupação ao longo do tempo. E utilizado o gráfico de rosca para observar a distribuição das reservas por tipo de quartos.

[ ] Manter consistência de layout e cores entre relatórios e dashboards.

> 