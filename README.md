# Reconhecimento de Texto em Imagens com Azure

Este projeto utiliza os serviços de Visão de IA do **Azure** para realizar o reconhecimento de texto em imagens. As imagens são analisadas e o texto presente nelas é extraído e salvo em arquivos de resultados.

## Objetivo

O objetivo deste projeto é demonstrar como utilizar a ferramenta de reconhecimento óptico de caracteres (OCR) da plataforma de **Visão de IA do Azure** para extrair texto de imagens e armazenar os resultados em um formato de fácil leitura.

## Tecnologias Utilizadas

- **Azure Cognitive Services**: Usado para implementar o reconhecimento de texto nas imagens.
- **GitHub**: Para versionamento do código e armazenamento dos resultados.

## Estrutura do Projeto

O repositório contém as seguintes pastas e arquivos:

- **inputs**: Contém as imagens utilizadas para o reconhecimento de texto.
- **output**: Contém os arquivos de resultados do OCR, com o texto extraído das imagens.
- **README.md**: Documento de descrição do projeto, com detalhes sobre o processo e insights adquiridos.

## Passo a Passo

### 1. Criação do Repositório
Primeiramente, criei um repositório no GitHub chamado `image-text-recognition` para armazenar o código e os resultados do projeto.

### 2. Preparação das Imagens
As imagens que foram utilizadas para o reconhecimento de texto foram salvas na pasta `inputs`. Essas imagens contêm textos variados, como documentos impressos e imagens com texto em diferentes formatos e fontes.

### 3. Processamento das Imagens
Utilizei a funcionalidade de **Reconhecimento Óptico de Caracteres (OCR)** da **Visão de IA do Azure** para extrair o texto das imagens. A API do Azure foi configurada para acessar o serviço de OCR, processar as imagens da pasta `inputs`, e gerar os arquivos de texto com os resultados. Esses resultados foram salvos na pasta `output`.

### 4. Resultados
Após o processamento, os resultados de cada imagem estão salvos na pasta `output` em arquivos de texto (`.txt`). Os arquivos contêm o texto extraído das imagens, permitindo fácil acesso e análise posterior.

## Insights Adquiridos

Durante o processo, algumas observações importantes foram feitas:

- O OCR funciona melhor com imagens nítidas e bem iluminadas, com contraste claro entre o texto e o fundo.
- Algumas imagens de baixa qualidade ou com fontes manuscritas geraram resultados imprecisos, o que demonstra a importância de usar imagens de boa qualidade para garantir a precisão do OCR.
- É possível combinar o reconhecimento de texto com outras ferramentas para automatizar tarefas como a digitalização de documentos ou extração de dados de formulários.

## Possibilidades Futuras

Este projeto pode ser expandido para:

- **Automatização de digitalização de documentos**: Usando o OCR para processar grandes volumes de imagens e gerar documentos de texto automaticamente.
- **Leitura de placas de veículos**: Aplicando o OCR em imagens de placas de veículos para criar sistemas de reconhecimento de veículos.
- **Tradução automática**: Integrar com serviços de tradução para traduzir o texto extraído de imagens em diferentes idiomas.

## Conclusão

Este projeto demonstra como utilizar os recursos de Visão de IA do Azure para realizar o reconhecimento de texto em imagens de forma eficiente. O Azure OCR é uma ferramenta poderosa que pode ser aplicada em diversas áreas, desde a digitalização de documentos até sistemas automatizados de leitura.
