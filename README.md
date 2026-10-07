# Rentabilidade de campanha de marketing

A campanha piloto (2.240 clientes aleatórios) deu **−3.046 MU**: cada contato custa 3 e cada venda rende 11, então só vale contatar quem tem **mais de 27,3%** de chance de comprar, e o piloto converteu 14,9%. Esta análise propõe como escolher quem impactar para que a próxima campanha dê lucro.

**[🧮 Simulador interativo: comece por aqui](https://picotti-matheus.github.io/rentabilidade-campanha/)**: mexa no corte, no custo e na margem e veja o lucro mudar.

**[▶ Abrir o notebook no Google Colab](https://colab.research.google.com/github/picotti-matheus/rentabilidade-campanha/blob/main/analise_campanha.ipynb)**: `Ambiente de execução → Executar tudo`. A base é lida direto deste repositório, sem upload.

## Conteúdo

| Arquivo | O que é |
|---|---|
| `analise_campanha.ipynb` | Análise técnica: tratamento, exploração, segmentação, modelo e estratégia |
| `docs/index.html` | Simulador interativo (publicado no GitHub Pages) |
| `data/base_campanha.csv` | Base do piloto (2.240 registros, 2.039 clientes únicos) |
| `outputs/lista_scores_piloto.csv` | Score e decisão por cliente do piloto (ilustrativo) |

## Rodar localmente

```bash
python -m venv .venv && source .venv/bin/activate
pip install pandas numpy scikit-learn statsmodels matplotlib jupyter
jupyter notebook analise_campanha.ipynb
```

---
Matheus Picotti
