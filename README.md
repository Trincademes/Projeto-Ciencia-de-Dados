#  Projeto Final: Ciência de Dados com Python

##  Objetivo
Este projeto tem como objetivo aplicar, de forma prática, os conceitos estudados na disciplina de Ciência de Dados com Python. Foi realizada uma análise exploratória e descritiva com base em dados simulados, utilizando bibliotecas estatísticas e gráficas da linguagem Python. O tema escolhido foi o **desempenho de alunos simulados**, adaptando o dataset `tips` da biblioteca Seaborn.

## Integrantes do Grupo

- João Victor Machado Pinto
- Pedro Vieira Cavalciuk
- Vitor Henrique da Silva Fogaça

##  Tecnologias e Bibliotecas Utilizadas
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scipy

##  Estrutura do Projeto
```
projeto_ds_colab.ipynb     # Notebook principal com toda a análise
README.md                  # Este arquivo
CienDeDadosDocument.pdf    # Documentação do projeto         
```

##  Base de Dados
Utilizou-se o dataset `tips` do Seaborn, que foi interpretado como se representasse dados de alunos (notas, número de disciplinas, sexo, etc.). Ele é carregado diretamente da biblioteca com:
```python
df = sns.load_dataset('tips')
```

##  Tópicos Estatísticos Aplicados
- **Escalas de Medição:** Classificação de variáveis como nominal e razão.
- **Medidas de Tendência Central:** Cálculo da média, mediana e moda.
- **Medidas de Dispersão:** Amplitude, desvio padrão e variância.
- **Visualizações:** Histogramas, boxplots, scatterplots.
- **Testes de Normalidade:** Teste de Shapiro-Wilk.
- **Correlação entre Variáveis:** Correlação de Pearson entre número de disciplinas e nota final.

##  Visualizações
Foram gerados diversos gráficos explicativos como:
- Histogramas de distribuição
- Boxplots para comparar grupos
- Gráficos de dispersão com correlação

##  Conclusão
O dataset simulado permitiu uma análise estatística completa com aplicação dos principais conceitos da disciplina. Concluímos que:
- As notas simuladas não seguem uma distribuição normal.
- Existe uma correlação positiva entre o número de disciplinas cursadas e a nota final.

## Projeto Pronto para a Vizualização
[Acessar o documento](./projeto_ds_colab.ipynb)

##  Relatório Técnico
O relatório em PDF foi desenvolvido conforme as normas da ABNT e encontra-se disponível no repositório (ou será enviado separadamente).
[Acessar o documento](./CienDeDadosDocument.pdf)

##  Como Executar
1. Clone o repositório ou baixe os arquivos.
2. Execute o notebook `projeto_ds_colab.ipynb` em um ambiente como Google Colab, Visual Studio Code (Necessita do Python instalado no computador) ou Jupyter Notebook.
3. Certifique-se de ter as bibliotecas instaladas:
```bash
pip install pandas numpy matplotlib seaborn scipy
```
