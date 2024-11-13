# Visão Computacional - Dataset Processing

Este repositório contém o código para processamento e análise de imagens para o projeto de visão computacional. O código está disponível no Google Colab e pode ser executado diretamente a partir do link fornecido abaixo. O código foi desenvolvido para carregar imagens, extrair metadados e salvar o resultado final como um arquivo CSV.

## Links Úteis

1. Github: https://github.com/MarceloBxD/visao-computacional-dataset

2. Dados: https://drive.google.com/drive/folders/1resSJF7sZVL3wDmyt_GC0FEU6FN4gsgO?usp=sharing


## Como Executar

1. Clique no link abaixo para abrir o código diretamente no Google Colab:
   [*Abrir no Google Colab*](https://colab.research.google.com/drive/13-XYxHmW-Z5xzIwJZ_pOE3H0yUPRGgyJ?usp=sharing)

2. No Google Colab, você poderá ver o código que já foi desenvolvido. Para executá-lo, siga estes passos:

   - Monte o Google Drive para acessar os arquivos.
   - Execute o código célula por célula.
   - O código irá percorrer as pastas de imagens, extrair os metadados e gerar um arquivo CSV com os detalhes das imagens.

3. Certifique-se de ter acesso ao *Google Cloud Console* para permitir que o Google Colab tenha permissões de leitura e escrita no Google Drive, caso necessário.

## Estrutura do Projeto

O projeto está estruturado para:

- Carregar imagens de um dataset organizado por pastas e subpastas (ex: dia_dentro, dia_fora, noite_dentro, etc.).
- Extrair metadados diretamente dos nomes dos arquivos (classe, número do objeto, fundo, iluminação, textura).
- Salvar um arquivo CSV contendo todos os metadados extraídos.

## Exemplo de Execução

Aqui estão exemplos de como o código funciona, exibindo as tabelas sumárias dos dados e a exportação correta dos metadados:

### Tabela Sumária dos Dados:

O código gera uma tabela sumária contendo informações como:

- Número de classes
- Número total de imagens
- Tamanho total do dataset em MB

### Arquivo CSV:

O arquivo CSV gerado contém colunas com os seguintes metadados:

- Nome do arquivo
- Classe do objeto
- Número do objeto
- Fundo (dentro, fora)
- Iluminação (dia, noite)
- Textura
- Caminho completo da imagem
