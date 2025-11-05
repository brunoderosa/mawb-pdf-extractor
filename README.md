# AWB/MAWB PDF Extractor

Automação Python para extrair automaticamente o número do MAWB (Master Air Waybill) e a cotação USD/BRL de arquivos PDF de Conhecimento Aéreo.

## Descrição

Este projeto lê arquivos PDF de AWBs, identifica e extrai informações-chave como o número do MAWB (padrão IATA) e a cotação de câmbio USD/BRL, e salva os resultados em um arquivo Excel.

## Como usar

1. Instale as dependências:
pip install pandas PyPDF2

2. Defina as variáveis `pasta_pdfs` e `arquivo_excel` conforme seus caminhos locais.
3. Execute o script Python.

## Exemplo de uso

O script processa todos os arquivos PDF da pasta selecionada e gera um Excel com nome de arquivo, número MAWB e valor USD/BRL.

## Autor

Bruno Rosa - [LinkedIn](https://www.linkedin.com/in/brunoderosa/)
