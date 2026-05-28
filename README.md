# Radar IDHM — Painel Interativo 2012–2024 | Versão 3

Painel exploratório desenvolvido a partir do **Radar IDHM: evolução do IDHM e de seus componentes no período de 2012 a 2024**, produzido pelo PNUD, Fundação João Pinheiro e IBGE.

## Novidades da versão 3

- quatro modos de análise: **Panorama geral**, **Desigualdade por sexo**, **Desigualdade por raça/cor** e **Desigualdade ajustada — IDHM × IDHMAD**;
- visualização conjunta de **Mulher × Homem** e **Branco × Negro** nas séries temporais e barras territoriais;
- mapa de diferenças entre grupos sociais para as Unidades da Federação;
- mapa da perda pela desigualdade no modo **IDHM × IDHMAD**;
- linhas comparativas com faixa visual entre os resultados;
- gráfico específico da diferença entre grupos ao longo do tempo;
- comparação das perdas pela desigualdade por dimensão no modo IDHM × IDHMAD;
- cards comparativos com valores dos dois grupos, distância atual, diferença relativa e mudança da distância no período;
- tabela comparativa com valores dos dois grupos e a desigualdade observada no ano selecionado;
- períodos de governo destacados nas séries e consolidados em gráficos descritivos.

## Conteúdo analítico

- Brasil, Unidades da Federação e Regiões Metropolitanas/RIDE;
- IDHM, IDHM Educação, IDHM Longevidade e IDHM Renda;
- IDHM ajustado por sexo e IDHM Renda ajustado por sexo;
- IDHMAD e perdas pela desigualdade;
- comparação territorial e temporal das desigualdades por sexo e raça/cor;
- análise por intervalo de anos e por períodos presidenciais.

## Arquivos

- `index.html`: painel completo, com dados e mapa incorporados; pode ser publicado sozinho no GitHub Pages.
- `data/radar_idhm_dados_longos.csv`: base longa utilizada na aplicação.
- `data/dicionario_indicadores.csv`: definições dos indicadores.
- `data/br_ufs_simplificado.geojson`: malha simplificada das UFs.

## Notas metodológicas

- O **IDHM** varia de 0 a 1 e sintetiza as dimensões Longevidade, Educação e Renda.
- O **IDHMAD** ajusta o IDHM às desigualdades internas: quando não há desigualdade, ele é igual ao IDHM; com maior desigualdade, seu valor é menor.
- O IDHMAD não é calculado de forma desagregada por sexo ou raça/cor.
- Na comparação por sexo, a publicação utiliza o **IDHM ajustado** e o **IDHM Renda ajustado** aos rendimentos do trabalho quando cabível.
- Na comparação por raça/cor, a categoria **Negro** segue a publicação e reúne pretos e pardos.
- Para índices, diferenças absolutas são mostradas em **pontos do índice**; para perdas percentuais, em **pontos percentuais (p.p.)**.
- A comparação por períodos presidenciais é descritiva e não estabelece causalidade; o ano de 2016 é tratado separadamente como transição.
