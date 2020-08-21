
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
usethis::create_package("caminho_ate_o_projeto/nome_do_projeto")

# Exemplo: usethis::create_package("~/Documents/curso-r/MeuCursoDeR")
# Isso criará o projeto MeuCursoDeR dentro da pasta curso-r/.
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

| slide             | link                                                                |
| :---------------- | :------------------------------------------------------------------ |
| slides/index.html | <https://curso-r.github.io/main-regressao-linear/slides/index.html> |

## Scripts usados em aula

| script | link |
| :----- | :--- |
