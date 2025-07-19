# Projeto-Reprodutor-Automatizado-de-Musicas
Via YouTube API (Python)
Desenvolvi um sistema automatizado de busca e reprodução de músicas utilizando a API do YouTube em conjunto com técnicas de web scraping. A aplicação realiza:

Consulta à plataforma YouTube com base em uma categoria ou autor informados pelo usuário.

Coleta de links válidos por meio da biblioteca BeautifulSoup.

Navegação automatizada via Selenium com detecção de elementos para pular anúncios.

Extração da duração dos vídeos com Google API Client e isodate.

Conversão e reprodução dos áudios com pydub e urllib, evitando conteúdo ao vivo ou não musical.

Execução em modo headless, otimizando a performance e usabilidade em segundo plano.

O projeto foi construído com as seguintes tecnologias: Python, Selenium, BeautifulSoup, Google API Client, pydub, isodate, urllib, Chrome WebDriver.
