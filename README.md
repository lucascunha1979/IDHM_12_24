# Radar IDHM — Painel Interativo 2012–2024 | Versão 3 ajustada

Painel exploratório desenvolvido a partir do **Radar IDHM: evolução do IDHM e de seus componentes no período de 2012 a 2024**, produzido pelo PNUD, Fundação João Pinheiro e IBGE.

## Ajuste desta revisão

Esta revisão preserva os indicadores, filtros, cálculos e modos analíticos da versão 3. Foram alterados somente aspectos visuais do gráfico de ranking/comparação:

- altura dinâmica quando são exibidas duas barras por território, permitindo visualizar todas as 27 UFs;
- maior margem e escala horizontal para impedir cortes nos valores e barras das Regiões Metropolitanas/RIDE;
- abreviação visual de `RIDE Grande Teresina` no eixo do gráfico, sem modificar o conteúdo da base.

## Conteúdo do painel

- Panorama geral;
- Desigualdade por sexo — Homem × Mulher;
- Desigualdade por raça/cor — Branco × Negro;
- Desigualdade ajustada — IDHM × IDHMAD;
- mapa das UFs, séries históricas, ranking territorial, análise de diferenças e períodos de governo.

## Arquivos

- `index.html`: painel completo, pronto para GitHub Pages.
- `data/radar_idhm_dados_longos.csv`: base longa utilizada na aplicação.
- `data/dicionario_indicadores.csv`: definições dos indicadores.
- `data/br_ufs_simplificado.geojson`: malha simplificada das UFs.

## Notas metodológicas

- O IDHM sintetiza as dimensões Longevidade, Educação e Renda.
- O IDHMAD ajusta o IDHM às desigualdades internas e não é calculado por sexo ou raça/cor.
- Nas comparações por sexo, o painel respeita os indicadores ajustados à renda do trabalho apresentados pelo Radar.
- Na comparação por raça/cor, a categoria Negro segue a publicação e reúne pretos e pardos.
- Para índices, as diferenças são apresentadas em pontos do índice; para perdas percentuais, em pontos percentuais.
