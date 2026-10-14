# Fontes e bases de dados utilizadas nas pesquisas do Scanner do Tempo

Este índice acompanha os estudos de Cuité e os materiais complementares do livro *A Cápsula e o Scanner do Tempo: novas sementes para a historiografia de Cuité*. Reúne **bases efetivamente recebidas ou extraídas**, produtos derivados da pesquisa e **fontes identificadas cuja série ainda não foi obtida**. O índice não é um catálogo oficial de estações nem representa uma série única, contínua e homogênea.

**Convenção:** *recebida* = arquivo fornecido por instituição; *extraída* = recorte produzido por consulta/plataforma; *transcrita* = dados copiados e conferidos de publicação; *derivada* = organização ou cálculo feito sobre outras bases; *inventariada* = localização documental sem obtenção integral da série.

## 1. Observações pluviométricas e publicações históricas

| Base/fonte e recorte local | Tipo / estado do material da pesquisa | Arquivos de referência no acervo de trabalho | Acesso à fonte institucional |
|---|---|---|---|
| **ANA/HidroWeb — Cuité, posto 00636035**, julho/1962–dezembro/1983 | Série pluviométrica diária e mensal **recebida da ANA** em setembro/2026; auditoria da entrega bruta (254 meses existentes, quatro meses inteiros ausentes) | `ANA_HIDRO_CUITE_00636035_DIARIO_BRUTO_v0.1.csv`; `ANA_HIDRO_CUITE_00636035_MENSAL_BRUTO_v0.1.csv`; relatório de auditoria | [Portal HidroWeb/SNIRH](https://www.snirh.gov.br/hidroweb/) |
| **SUDENE — Cuité, publicação de 1971**, recorte histórico 1963–1971 | Fonte oficial histórica **consultada e transcrita em parte**, com conferência de edições; não constitui observação independente da linhagem pluviométrica | `SUDENE_1971_CUITE_PAGINA_28.png`; `SUDENE_CUITE_COMPARACAO_EDICOES_1971_1990_1963_1971.csv` | [Biblioteca/catálogo da SUDENE](https://www.gov.br/sudene/pt-br/centrais-de-conteudo/biblioteca-catalogo-de-publicacoes-sudene-para-doacao-2017-1-pdf) |
| **SUDENE — Série Pluviometria, Paraíba (1990)**, valores documentais usados até 1985 | Publicação institucional histórica **consultada/transcrita e cotejada** com ANA/HidroWeb; não somar como uma estação adicional | `SUDENE_1990_CUITE_PAGINA_24.png`; tabelas de comparação e revisão | [Biblioteca/catálogo da SUDENE](https://www.gov.br/sudene/pt-br/centrais-de-conteudo/biblioteca-catalogo-de-publicacoes-sudene-para-doacao-2017-1-pdf) |
| **SEIRA/SUDENE — Cuité, identificador 3827973**, 1984–1993 | Exportação diária e mensal **recebida/recuperada e auditada**; 1.778 de 3.653 dias calendários, 48,67% de cobertura; faltam anos completos | `dados_sudene_01-01-1984_a_31-12-1993.csv`; `SEIRA_SUDENE_CUITE_3827973_DIARIO_1984_1993_v0.1.csv`; exportação mensal auditada | [AESA — instituição estadual e acesso a sistemas](https://www.aesa.pb.gov.br/) |
| **AESA — Cuité, posto 3827973**, janeiro/1994–dezembro/2018 | Planilha diária pluviométrica **recebida da AESA** em setembro/2026; auditoria de 300 meses; sem flags individualizadas por valor | `Dados pluviométricos 01_01_1994 a 31_12_2018.xlsx`; `AESA_CUITE_3827973_DIARIO_1994_2018_v0.1.csv`; arquivos mensal/anual | [AESA](https://www.aesa.pb.gov.br/) |
| **Rede pluviométrica histórica do entorno (SUDENE)**, comparação 1968–1985 | **Transcrições e base derivada**, incluindo Cuité, Sossego, Picuí, Barra de Santa Rosa, Pedra Lavrada, Seridó e Olivedos; uso para controles espaciais | `BASE_OBSERVACIONAL_REDE_SUDENE_CUITE_ENTORNO_1968_1985_v0.3.csv`; `SUDENE_REDE_7_POSTOS_INTERCOMPARACAO_MENSAL_1968_1985.csv` | [Biblioteca/catálogo da SUDENE](https://www.gov.br/sudene/pt-br/centrais-de-conteudo/biblioteca-catalogo-de-publicacoes-sudene-para-doacao-2017-1-pdf) |

**Cautela:** proximidade entre códigos ou coordenadas de postos históricos não demonstra continuidade do mesmo instrumento/sítio ou homogeneidade da série ao longo de décadas. Ausência de registro não é precipitação igual a zero.

## 2. Produtos climáticos gradeados e reanálise

| Produto | Recortes efetivamente trabalhados | Tipo / estado | Fonte científica |
|---|---|---|---|
| **TerraClimate** | Cuité, 1968–2018, com 51 valores anuais e 612 mensais auditados; outros exercícios para 1981–2024 e mesorregiões paraibanas | Produto climático espacial, **extraído e analisado**, não estação meteorológica | [Earth Engine: TerraClimate](https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_TERRACLIMATE) |
| **ERA5-Land** | Cuité, 1968–2018, com 51 valores anuais e 612 mensais auditados; exercícios 1981–2024 e mesorregiões paraibanas | **Reanálise**, extraída e analisada; não observação direta local | [Earth Engine: ERA5-Land mensal](https://developers.google.com/earth-engine/datasets/catalog/ECMWF_ERA5_LAND_MONTHLY_AGGR) |
| **CHIRPS** | Cuité, 1981–2018: 38 valores anuais e 456 mensais auditados; exercícios 1981–2024 e mesorregiões paraibanas | Produto de precipitação que combina informação satelital e de estações, **extraído e analisado** | [Earth Engine: CHIRPS diário](https://developers.google.com/earth-engine/datasets/catalog/UCSB-CHG_CHIRPS_DAILY) |
| **BR-DWGD** | Piloto Cuité 2020–2022; rede regional 1968–2025, sete variáveis, 31 referências territoriais correspondentes a 28 células; recorte do dossiê 1968–2018 | Produto meteorológico brasileiro **gradeado diário**, extração regional e auditoria documentadas | [Portal do produtor: BR-DWGD](https://sites.google.com/site/alexandrecandidoxavierufes/brazilian-daily-weather-gridded-data) |

Os recortes temporais listados descrevem **a pesquisa realizada**, não a extensão total disponível nos produtos globais ou nacionais. **CHIRPS não foi estendido artificialmente a 1968–1980.** A comparação entre produtos não valida, sozinha, os registros de uma estação.

## 3. Geografia, relevo, cadastro e bases derivadas

| Base/camada | Estado e uso na pesquisa | Registro correspondente | Fonte |
|---|---|---|---|
| **NASADEM** | Modelo de elevação **consultado via Earth Engine**; descritores topográficos derivados para 31 pontos (altitude, posição topográfica relativa, relevo local etc.) | `SUDENE_REDE_7_POSTOS_TOPOGRAFIA_NASADEM_NORMALIZADA_v0.2.csv`; notas e mapas | [Earth Engine: NASADEM 30 m](https://developers.google.com/earth-engine/datasets/catalog/NASA_NASADEM_HGT_001) |
| **Cadastro geoespacial AESA de postos** | Shapefile institucional usado na pré-triagem; relatório registra 270 linhas, 269 pontos válidos e 81 em até 100 km de Cuité | Análise `MET-EXP-005` e mapas de rede | [AESA](https://www.aesa.pb.gov.br/) |
| **Inventário das estações de Cuité e entorno** | **Base derivada** de localização, códigos e atributos; não é série de precipitação | `ESTACOES_OBSERVACIONAIS_CUITE_ENTORNO_v0.1.csv` / `.geojson` | [ANA/HidroWeb](https://www.snirh.gov.br/hidroweb/), [AESA](https://www.aesa.pb.gov.br/) e demais fontes identificadas |
| **Base comparativa de precipitação municipal** | **Base derivada** reunindo TerraClimate (1968–2018), ERA5-Land (1968–2018) e CHIRPS somente em 1981–2018; mantém as diferenças metodológicas | `CUITE_PRECIPITACAO_RETROSPECTIVA_1968_2018_BASE_COMPARATIVA.csv`; séries e quadros auxiliares | Fontes específicas da seção 2 |
| **Comparação BR-DWGD × ERA5-Land (2020–2023)** | Conjunto analítico de 1.461 pares diários por variável no trabalho acadêmico; avaliação e proveniência específica ainda sujeitas à conferência docente | Relatório `MET-EXP-005` / trabalho associado ao CBMET | BR-DWGD e ERA5-Land, conforme seção 2 |
| **Análises de mesorregiões paraibanas (1981–2024)** | **Bases derivadas** de CHIRPS, TerraClimate e ERA5-Land nas atividades de Instrumentos Meteorológicos | `CHIRPS_PB_MESORREGIOES_1981_2024`; `TERRACLIMATE_PB_MESORREGIOES_1981_2024`; `ERA5LAND_PB_MESORREGIOES_1981_2024` | Respectivos produtos da seção 2 |

## 4. Fontes identificadas, mas que não equivalem a séries obtidas

- **AESA-C019 — Cuité:** estação automática/agroclimatológica identificada, **sem ficha técnica e histórico observacional completos recuperados** no levantamento consultado. Não integra a série pluviométrica 3827973 por simples associação de nome.
- **INMET — rede convencional e automática:** catálogos e estações regionais **consultados/inventariados**, mas não foi demonstrada a aquisição de uma série observacional da estação chamada Cuité. [INMET](https://portal.inmet.gov.br/).
- **Dados de sensores futuros do Scanner:** nenhuma estação, câmera de acompanhamento contínuo ou observatório local do Scanner está declarado como já instalado. A série visual de ponto fixo até 2068 permanece uma intenção de pesquisa/instrumentação.

## Como acessar os dados

Esta página dá acesso **às fontes oficiais e ao inventário dos produtos que a pesquisa efetivamente manipulou**, mas **não distribui aqui automaticamente os arquivos recebidos de instituições, transcrições de livros, dados privados do Drive ou bases derivadas ainda não liberadas para divulgação**. Os arquivos brutos, planilhas, códigos, verificações, registros de integridade e solicitações institucionais permanecem identificados no acervo de trabalho da pesquisa; a disponibilização pública de conjuntos derivados poderá ocorrer após auditoria de licenças, qualidade, metadados e privacidade.

Para uso acadêmico, a citação deve identificar não apenas o produtor, mas também **produto, versão, período efetivo, método de extração, geografia, variáveis e data de acesso** quando aplicável.

Voltar ao [portal do leitor](../LEITOR_DO_LIVRO.md) · [recursos complementares do livro](../LIVRO/INDICE_DE_RECURSOS.md).

**Situação:** catálogo de fontes e produtos da pesquisa em desenvolvimento, não arquivo de dados oficiais administrado pelo Museu ou pela UFCG.
