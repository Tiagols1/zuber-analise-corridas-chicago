# Zuber: análise de corridas de táxi em Chicago

Projeto de análise de dados com SQL e Python para a Zuber, empresa de compartilhamento de caronas que está sendo lançada em Chicago.

## O que foi feito
- Web scraping dos dados de clima de novembro de 2017
- Consultas SQL (JOIN, CASE, GROUP BY) sobre empresas de táxi
- Análise exploratória e gráficos com pandas, matplotlib e seaborn
- Teste de hipótese (teste t) sobre o efeito da chuva na duração das corridas do Loop ao aeroporto O'Hare

## Principais resultados
- A Flash Cab lidera em número de corridas
- Loop, River North e Streeterville estão entre os principais destinos
- Corridas em sábados chuvosos são mais longas: cerca de 33 min contra 40 min (p = 6,52 × 10⁻¹²)

## Ferramentas
Python, pandas, matplotlib, seaborn, scipy, BeautifulSoup, SQL

## Observação
O notebook lê arquivos de `/datasets/`, que existem apenas na plataforma do curso. No GitHub, os resultados já aparecem salvos nas células.
