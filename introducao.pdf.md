---
title: "Conceitos básicos"
author: "Henrique José de Paula Alves"
format:
  html:
    include-before-body:
      text: |
        <div style="float: right; margin-top: 10px; margin-right: 10px; margin-bottom: 10px; z-index: 999; position: relative;">
          <img src="images/fig1.png" style="width: 300px; height: 178px; opacity: 1 !important; filter: none !important; -webkit-filter: none !important;">
        </div>
---







## Introdução {#sec-intro}

Neste capítulo inicial, estabeleceremos as bases fundamentais da estatística, diferenciando a análise puramente descritiva da inferência, e definindo os tipos de dados com os quais trabalharemos ao longo deste livro.

### O que é Estatística?

A Estatística pode ser definida como a ciência que utiliza a probabilidade para lidar com a incerteza. Em um mundo inundado por dados, ela fornece as ferramentas para transformar observações brutas em conhecimento científico e suporte à decisão.

Podemos dividir a estatística em três grandes pilares:

1.  **Descritiva:** Resume e organiza os dados históricos para descrever o que aconteceu, sem tirar conclusões externas

2.  **Inferencial:** Usa amostras para tirar conclusões e generalizar propriedades sobre uma população inteira sob incerteza.

3.  **Preditiva**: utiliza algoritmos estatísticos e técnicas de machine learning para definir a probabilidade de eventos futuros com base em padrões encontrados em dados do passado.

De modo geral, a Estatística engloba ferramentas teóricas e práticas visando entender ou analisar o comportamento de informações quantitativas e/ou qualitativas, medindo incertezas e, dessa forma, auxiliando na tomada de decisão.

### Conceitos Fundamentais

Antes de avançarmos para os cálculos, precisamos definir os objetos de estudo:

-   **População:** O conjunto total de elementos que compartilham pelo menos uma característica comum (ex: todos os domicílios do Brasil).

-   **Parâmetro:** Uma medida numérica que descreve uma característica da população (geralmente desconhecida e representada por letras gregas como $\mu$, $\sigma$).

-   **Amostra:** Um subconjunto representativo da população ($\bar{X}$, $S$)

-   **Estimativa (ou Estatística):** Uma medida numérica calculada a partir de dados amostrais para estimar um parâmetro.

![Figura 1: O Fluxo da Inferência Estatística entre População e Amostra.](images/clipboard-3880653047.png){fig-align="center" width="549"}

Alguns conceitos e definições matemáticas bem como suas propriedades são de extrema importância para um bom entendimento das técnicas de análise estatística. Entretanto, não será apresentado um capítulo a parte sobre esses conceitos e definições. Ao longo do livro, à medida que for sendo necessário, estes serão apresentados da forma mais simples possível, sem o rigor matemático. No próximo capítulo, vamos tratar da análise exploratória de dados.
