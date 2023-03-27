# WebCrawler
Solução com ferramentas utilizadas na raspagem de páginas web.

# Projetos

## WebCrawler.App
Projeto da aplicação que consumirá um serviço web crawler para realizar a raspagem de dados de uma página web.

Neste caso, a raspagem dos dados será realizada na páginas do [Top 250 Filmes IMDb](https://www.imdb.com/chart/top/).

## WebCrawler.Domain
Projeto da aplicação que contém as classes e interfaces que serão utilizadas pelo projeto `WebCrawler.App`.

## WebCrawler.Selenium
Projeto que contém o serviço web crawler que utiliza a ferramenta Selenium para coleta dos dados e ações na página.

Para a execução correta, é necessário manter o executável `chromedriver` do diretório `src/WebCrawler.Selenium/Drivers` atualizado conforme a versão do navegador Google Chrome.

**Observação importante:**
Neste projeto o chromedriver é referente ao sistema operacional `Linux`. Para utilização no sistema operacional `Windows` deverá ser feito o download do executável (site para download consta na seção de links úteis, ao final do documento).

# Links úteis
 - [Documentação oficial do Selenium](https://www.selenium.dev/documentation/)
 - [Download do Chromedriver](https://chromedriver.chromium.org/downloads)