# Redes Neurais com Scikit-Learn

Este projeto explora o uso de redes neurais utilizando a biblioteca `sklearn`, abordando tanto classificação quanto regressão. O projeto inclui a implementação de modelos de `MLPClassifier` e `MLPRegressor` para diferentes conjuntos de dados.

## Requisitos

Antes de executar o projeto, certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install pandas seaborn scikit-learn matplotlib
```

## Estrutura do Projeto

O notebook `NeuralNetwork.ipynb` está dividido nas seguintes seções:

### 1. **Importação das Bibliotecas**

- Importação de pacotes essenciais para manipulação de dados (`pandas`, `seaborn`), normalização (`StandardScaler`), separação dos dados (`train_test_split`) e modelos (`MLPClassifier`, `MLPRegressor`).

### 2. **Classificação com o dataset Iris**

- Carregamento do dataset Iris.
- Separação dos dados em treino e teste.
- Padronização dos dados com `StandardScaler`.
- Treinamento de um `MLPClassifier`.
- Avaliação do modelo utilizando `accuracy_score` e matriz de confusão.

### 3. **Regressão com Redes Neurais**

- Definição de um problema de regressão (dataset a ser determinado).
- Pré-processamento dos dados.
- Treinamento de um `MLPRegressor`.
- Avaliação utilizando `mean_squared_error` e `mean_absolute_error`.

## Como Executar o Projeto

1. **Clone ou baixe o repositório**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
   ```
2. **Instale os requisitos**
   ```bash
   pip install -r requirements.txt
   ```
3. **Execute o Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
4. \*\*Abra e execute o notebook \*\*\`\`

## Resultados Esperados

Após a execução, você verá métricas de desempenho para a classificação (acurácia e matriz de confusão) e para a regressão (erro médio quadrático e absoluto), permitindo avaliar a eficácia dos modelos utilizados.

## Contribuições

Se desejar contribuir, sinta-se à vontade para abrir uma issue ou um pull request!

## Licença

Este projeto é disponibilizado sob a licença MIT.

