# Web Scraping de Placas de Vídeo VGA - Kabum

## Descrição

Este projeto consiste em um script de web scraping desenvolvido em Python para extrair informações sobre placas de vídeo VGA do site da Kabum (https://www.kabum.com.br/). O objetivo é obter de forma automatizada dados como nome do produto, preços e links dos produtos.

## Funcionalidades

- O script realiza a raspagem de todas as páginas da categoria de placas de vídeo VGA do site da Kabum.
- Para cada placa de vídeo encontrada, são obtidas informações como nome do produto, preço com PIX, preço a prazo, preço original e link do produto.
- Os dados extraídos são armazenados em uma lista de dicionários, facilitando sua manipulação e análise posterior.

## Pré-requisitos

Antes de executar o script, verifique se você possui os seguintes requisitos:

- Python 3.x instalado no seu sistema.
- As bibliotecas `requests`, `beautifulsoup4`, `csv`, `pandas`, `re` e `math` instaladas. Caso não tenha, você pode instalar executando o seguinte comando:

```shell
pip install requests beautifulsoup4 pandas
```

## Utilização

1. Defina a URL da categoria de placas de vídeo VGA que deseja extrair no arquivo `main.py` no campo `url`. Por exemplo:

```python
url = "https://www.kabum.com.br/hardware/placa-de-video-vga"
```

2. Execute o script `main.py`. Os dados extraídos serão armazenados na lista `lista_produtos`.

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades neste projeto. Basta seguir as etapas abaixo:

1. Faça um fork do repositório.
2. Crie um novo branch com as suas modificações: `git checkout -b minha-feature`
3. Commit suas modificações: `git commit -m 'Adicionando nova feature'`
4. Faça um push para o branch: `git push origin minha-feature`
5. Envie um Pull Request

## Aviso Legal

Este projeto é fornecido como está e destina-se apenas a fins educacionais. Respeite os termos de serviço do site da Kabum e utilize o script com responsabilidade.
