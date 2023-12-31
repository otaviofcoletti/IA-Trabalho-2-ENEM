# Projeto: Mineração, Análise e Classificação de Concorrentes no ENEM 

Link para o repositório [aqui](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM).

**Grupo**:

| Nome  | nUSP |
|------------------------------------|----------|
| Otávio Ferracioli Coletti - Lider  | 11767796 |
| Victor Rodrigues da Silva - Vice   | 12566140 |
| Kenzo Yves Yamashita Nobre         | 5028772  |
| Fernando César Lopes Barbosa Filho | 10260559 |
| Adalton de Sena Almeida Filho      | 12542435 |
| Rafael Zimmer                      | 12542612 |



## Descrição do Projeto

![ENEM](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/Resultado-ENEM-termo-cresce_Credito-guia-do-estudante.jpg) 

Este projeto tem como objetivo realizar uma mineração de dados nos [Microdados do ENEM](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados). A proposta é analisar e compreender as áreas em que as notas são mais elevadas e mais baixas, buscando identificar as possíveis dificuldades de estudo enfrentadas pelos participantes do ENEM. Iremos compactar e transformar os dados em CSV, de modo a remover linhas com valores inválidos, colunas com valores insignificantes (código de institutos, ruas, vetores de respostas dos participantes e de gabarito. Devemos também colocar os dados em formato de máquina, transformando para uma codificação aceitável para o formato CSV e que não tenha caratéres inválidos.

Isso será feito de modo a permitir que realizemos um pré-processamento dos dados no futuro, em formato de dataset. Isso permitirá que implementemos modelos e algoritmos mais complexos que nos permitam formar insights e criar associações entre as features, identificando possibilidades de melhora no sistema de educação e investimento em regiões precárias.
Em resumo, iremos **classificar** as regiões do Brasil com a maior quantidade de alunos carentes nas diversas habilidades do ENEM.

## Problema

O problema que iremos resolver é o de identificar em que regiões do Brasil há uma carência de habilidades dos alunos no que é exigido no Exame Nacional do Ensino Médio, verificando quais matérias são as que os alunos tem mais dificuldades. Para essa classificação iremos também explorar a relação de atributos como a renda, escolaridade, cor, genêro, localização, faixa etária entre outros atributos dos participantes. 

### Como Funciona

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

   Para ver os resultados da análise inicial, acesso o notebook [Análise_Exploratório.ipynb](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/An%C3%A1lise_Explorat%C3%B3ria.ipynb)
   
## Licença

Nosso projeto no GitHub está licenciado sob a [Licença MIT](https://opensource.org/license/mit/).


## Membros da equipe

| Otávio Ferracioli Coletti | Victor Rodrigues da Silva | Kenzo Yves Yamashita Nobre | Fernando César Lopes Barbosa Filho | Adalton de Sena Almeida Filho | Rafael Zimmer |
| -------------------------- | ------------------------- | --------------------------- | ---------------------------------- | ------------------------------- | ------------- |
| ![Otávio Ferracioli Coletti](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/otavio.jpg) | ![Victor Rodrigues da Silva](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/vigdor_rodigis.jpg) | ![Kenzo Yves Yamashita Nobre](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/genzo.jpg) | ![Fernando César Lopes Barbosa Filho](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/garde.jpg) | ![Adalton de Sena Almeida Filho](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/adarton.jpg) | ![Rafael Zimmer](https://github.com/otaviofcoletti/IA-Trabalho-2-ENEM/blob/main/fotos/sinmber.jpg) |

