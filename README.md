# Arcabouço Zilvarin-Rincão V2.3

Derivação numérica das previsões da teoria do campo escalar X para testes clássicos da gravidade.

## Resultados

Este repositório calcula numericamente:

1. **Precessão do periélio de Mercúrio**: 42,98 arcseg/século
2. **Deflexão da luz pelo Sol**: 1,75 arcseg  
3. **Desvio pro vermelho gravitacional**: z = 0,999948

Todos reproduzem a Relatividade Geral no limite de campo fraco, derivados do tensor energia-momento de X.

## Teoria

Lagrangiana: L_X = ½ ∂_μ X ∂^μ X + g_XR X ψψ

Tensor energia-momento: T_μν = ∂_μ X ∂_ν X - g_μν [½ ∂_α X ∂^α X]

Acoplamento: g_XR = 2.0 × 10^-22

## Como rodar

```bash
pip install numpy scipy matplotlib
python Mercúrio_precesao.py



## Referência

Borges da Cunha, Délcio Henrique da Silva. (2026). Arcabouço Zilvarin-Rincão V2.3: Um Campo Escalar Sem Massa como Teoria Unificada Efetiva para Gravidade Quântica, Cosmologia, Modelo Padrão, Conservação de Carga Topológica e a Base Física da Consciência. Zenodo. DOI: [10.5281/zenodo.19598002](https://doi.org/10.5281/zenodo.19598002) 
