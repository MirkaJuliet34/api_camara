camara.leg: Ferramenta para Extrair Dados da API de Dados Abertos da
Câmara Legislativa
================

A API de dados abertos da camara legislativa possui várias informações
dos deputados, como por exemplo: nome, foto, email, votações, entre
outros. O pacote camara.leg foi desenvolvido para auxiliar os usuários a
acessar a API, baixar os dados e entregar em data frame. Para mais
informações de todo o conteúdo que você pode extrair, acesse a [página
oficial](https://dadosabertos.camara.leg.br/).

## Instalação

Para acessar e instalar a versão mais atual do camara.leg, use os
comandos abaixo e reinicie sua sessão R:

``` r
install.packages("devtools")
devtools::install_github("MirkaJuliet34/api_camara")
```

Carregue o pacote

``` r
library(api_camara)
```

## Baixando as informações da API

A API de dados abertos permite acessar as seguintes informações:

  - blocos
  - deputados
  - eventos
  - frentes
  - legislaturas
  - partidos
  - proposições
  - referências
  - votações
  - orgãos

Para acessar esses dados usando o pacote camara.leg basta chamar uma
função com o nome a da informação desejada (sem acentos). Veja os
exemplos a seguir.

``` r
deputados()
orgaos()
votacoes()
```

