
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Configuração inicial

#### Passo 1: Instalar pacotes

``` r
install.packages("remotes")

# instalar pacote da Curso-R
remotes::install_github("curso-r/CursoR")

# instalar pacotes que vamos usar durante o curso
CursoR::instalar_dependencias()
```

#### Passo 2: Criar um projeto do RStudio

Faça um projeto do RStudio para usar durante todo o curso e em seguida
abra-o.

``` r
install.packages("usethis")
usethis::create_project("caminho_ate_o_projeto/nome_do_projeto")
```

#### Passo 3: Baixar o material

Certifique que você está dentro do projeto criado no passo 2 e rode o
código abaixo.

**Observação**: Assim que rodar o código abaixo, o programa vai pedir
uma escolha de opções. Escolha o número correspondente ao curso de
Regressão Linear\!

``` r
# Baixar ou atualizar material do curso
CursoR::atualizar_material()
```

## Slides

| slide                              | link                                                                                 |
| :--------------------------------- | :----------------------------------------------------------------------------------- |
| slides/01-introducao-ao-curso.html | <https://curso-r.github.io/main-regressao-linear/slides/01-introducao-ao-curso.html> |
| slides/02-regressao-linear.html    | <https://curso-r.github.io/main-regressao-linear/slides/02-regressao-linear.html>    |

## Scripts usados em aula

| script                            | link                                                                                                         |
| :-------------------------------- | :----------------------------------------------------------------------------------------------------------- |
| 01-exercicios-durante-a-aula1.Rmd | <https://curso-r.github.io/202008-regressao-linear/scripts_feitos_em_aula/01-exercicios-durante-a-aula1.Rmd> |
| 01-exercicios-durante-a-aula2.Rmd | <https://curso-r.github.io/202008-regressao-linear/scripts_feitos_em_aula/01-exercicios-durante-a-aula2.Rmd> |
| 03-interacoes.R                   | <https://curso-r.github.io/202008-regressao-linear/scripts_feitos_em_aula/03-interacoes.R>                   |

## Referências

#### Programação em R

  - [Livro da Curso-R (Curso-R)](https://livro.curso-r.com/)
  - [Tidyverse (Wickham H)](https://www.tidyverse.org/)
  - [R for Data Science (Wickham H)](https://r4ds.had.co.nz/)
  - [Advanced R (Wickham H)](https://adv-r.hadley.nz/)

#### Regressão Linear

  - [Introduction to Statistical Learning (Hastie, et
    al)](http://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf)
  - [Elements of Statistical Learning (Hastie, et
    al)](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
  - [Computer Age Statistical Inference (Hastie,
    Efron)](https://web.stanford.edu/~hastie/CASI_files/PDF/casi.pdf)
  - [Tidymodels (Kuhn, et al)](https://www.tidymodels.org/)
  - [Feature Engineering and Selection: A Practical Approach for
    Predictive Models (Kuhn, Kjell)](http://www.feat.engineering/)
  - [Kaggle](https://www.kaggle.com/)
  - [Livro do Gilberto
    Paula](https://www.ime.usp.br/~giapaula/texto_2013.pdf)
  - Estatística básica 7a edição - BUSSAB e MORETTIN
  - [Tese sobre Regressão Linear da Sandra
    Rodrigues](https://ubibliorum.ubi.pt/bitstream/10400.6/1869/1/Tese%20Sandra%20Rodrigues.pdf)
  - [Aplicação de Regressão Linear
    Simples](https://www.ime.usp.br/~giapaula/slides_exemplo_cfoguete.pdf)
  - [Introduction to Econometrics with
    R](https://www.econometrics-with-r.org/6-5-the-distribution-of-the-ols-estimators-in-multiple-regression.html)
