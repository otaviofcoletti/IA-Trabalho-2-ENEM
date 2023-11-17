# Projeto: Mineração, Análise e Classificação de Concorrentes no ENEM

## Descrição do Projeto

Este projeto tem como objetivo realizar uma mineração de dados nos Microdados do ENEM. A proposta é analisar e compreender as áreas em que as notas são mais elevadas e mais baixas, buscando identificar as possíveis dificuldades de estudo enfrentadas pelos participantes do ENEM.

## Como Funciona

O projeto utiliza os Microdados do ENEM como fonte de dados. As análises são conduzidas em um ambiente Python, fazendo uso das bibliotecas pandas, Dask, e gdown para manipulação e análise eficiente dos dados. A mineração de dados destaca padrões e tendências nas notas dos participantes, oferecendo insights sobre as áreas que demandam mais atenção. Para ver a descrição de todos os dados, acesse o [Dicionário dos Microdados](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/Dicion%C3%A1rio_Microdados_Enem_2021.xlsx).

![Dicionário](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/Dicionario.png)
- Imagem 1. Exemplo de colunas dos dados minerados e processados



## Pré-requisitos

Para rodar a primeira etapa (baixar e carregar os dados), usamos a biblioteca Dask como gerenciador de dataframes, e Gdown para baixar os arquivos do Google Drive.
Antes de começar, certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install pandas dask gdown
```

## Como Rodar Localmentne

1. **Clone o Repositório:**

   ```bash
   git clone https://github.com/seu-usuario/mineracao-dados-enem.git
   ```

2. **Acesse os Dados:**

   ```bash
   cd mineracao-dados-enem
   ```

3. **Análise Exploratória:**

   Fizemos uma pequena análise exploratória, assim como compactamos os dados em um .zip a partir dos dados iniciais, de modo a facilitar uma análise inicial e baixar a partir do repositório no GitHub.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).
