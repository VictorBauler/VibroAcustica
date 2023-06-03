# VibroAcustica
Repositório com os trabalhos da disciplina EMC410104 (Vibroacústica Computacional)

## Setup

Instale o [Poetry](https://python-poetry.org/docs/#installation) e execute o comando abaixo para instalar as dependências do projeto:

```bash
poetry install
```

## Arquivos

Dentro da pasta `notebooks` estão os arquivos `.ipynb` com os códigos utilizados para a resolução dos trabalhos.

Para gerar os pdfs dos notebooks foi usado:
```bash
jupyter-nbconvert --to webpdf --allow-chromium-download nome_do_arquivo.ipynb
```
