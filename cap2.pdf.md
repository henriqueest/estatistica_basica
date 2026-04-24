---
title: "Análise Exploratória"
author: "Henrique José de Paula Alves"
format:
  html:
    include-before-body:
      text: |
        <div style="float: right; margin-top: 35px; margin-right: 10px; margin-bottom: 10px; z-index: 999; position: relative;">
          <img src="images/fig2.png" style="width: 300px; height: 178px; opacity: 1 !important; filter: none !important; -webkit-filter: none !important;">
        </div>
---







## Introdução

Em linhas gerais, a análise exploratória de dados tem ligação direta com a organização e descrição dos dados, reunindo uma quantidade razoável de ferramentas e recursos que auxiliam na interpretação dos valores observados ou amostrados. Exemplificando sua utilidade, a avaliação de como as observações se distribuem, bem como onde estão posicionadas e, ainda, como se apresentam em termos de dispersão e associação.

Neste capítulo, será introduzido conceitos e métodos de exploração de dados, um passo fundamental para análises estatísticas completas e avançadas.

### Variáveis

Em linhas gerais, trata-se de uma característica medida na população ou na amostra. Como exemplos, apresentam-se a altura de um indivíduo, o peso, a temperatura, a cor dos olhos, o número de filhos, a cor das folhas de uma planta, entre outros. São representadas por letras maiúsculas do nosso alfabeto: X, Y, A, B, W.

A Figura 2 apresenta um esquema de classificação das variáveis.

![Figura 2: Esquema de classificação de variáveis.](images/fig3.png){fig-align="center" width="549"}

#### Variável Qualitativa Nominal

As variáveis qualitativas nominais apresentam o menor grau de informação dentre os quatro tipos apresentados. É possível apenas a avaliação de frequências e ordenações arbitrárias. O sexo, a religião, a raça, a cor preferida, são exemplos desse tipo de variável

:::: exemplo
Exemplo: Sexo de uma pessoa

::: exemplo-title
Suponha uma pesquisa com aplicação de um questionário on-line, onde o sexo dos entrevistados é perguntado. Suponha ainda que a variável *Sexo de uma pessoa* seja representada por X, as observações podem ser:

X:{Masculino, Masculino, Feminino, Masculino, Feminino, Feminino, ..., Feminino}
:::
::::
