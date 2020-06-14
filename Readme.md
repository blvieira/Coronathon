# Radar de Competências

Este projeto foi elaborado durante o Coronathon BR. O objetivo do projeto é facilitar o matching entre candidato e empregador. Através de um aplicativo e do emprego de text mining e natural language processing, o candidato pode verificar seu nível de qualificação para uma vaga de determinada ocupação, comparando-se com os demais candidatos e com as exigências dos empregadores.

Estas instruções orientam sobre como utilizar estes arquivos.


### Pré-requisitos

O que você precisa ter instalado para rodar o projeto:

```
Python 3.*

Jupyter Notebook (ou qualquer IDE que permite abrir notebooks, como o Visual Studio Code)

Todas as libraries mencionadas no arquivo Trabalhadores e Vagas.ipynb.
Em caso de necessidade, essas libraries podem ser instaladas através de:
!pip install <library>
!conda install <library>

Arquivos de stopwords e tokenizer obtidos através de:
nltk.download('stopwords')
nltk.download('punkt')
```

### Instalação

Além dos pré-requisitos, não é necessária instalação do projeto.

## Arquivos

SINE: pasta que contém as extrações de dados utilizados no projeto.
SINE/Trabalhadores: contém os arquivos com dados de candidatos a vagas de emprego
SINE/Vagas: contém os arquivos com dados de vagas publicadas no SINE
coronathon_db.sqlite: base de dados SQLite que contém os resultados do algoritmo de Trabalhadores e Vagas.ipynb
*.csv: os arquivos CSV são extrações de coronathon_db.sqlite, para referência apenas.
Trabalhadores e Vagas.ipynb: contém o tratamento de dados realizado nas extrações do SINE, gera os rankings de características e competências mais requisitados dos candidatos, divididos por ocupação. Gera atualizações das tabelas de coronathon_db.sqlite.

## Autores

* **Afonso Scliar** - Design - [LinkedIn] (https://www.linkedin.com/in/afonso-scliar/)
* **Anna Flávia Castro** - Front-end - [LinkedIn](https://www.linkedin.com/in/anna-fl%C3%A1via-castro-675264182/)
* **Bruno Vieira** - Data Science - [GitHub](https://github.com/blvieira/)
* **Hugo Mentzingen** - Data Science - [LinkedIn](https://www.linkedin.com/in/hugo-mentzingen/)
* **Leonardo Lannes** - Data Science - [LinkedIn](https://www.linkedin.com/in/leonardo-lannes-4528a631/)

## Licença

Este projeto está sob a licença Creative Commons CC BY-NC-ND - veja https://creativecommons.org/licenses/by-nc-nd/4.0/