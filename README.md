
# Projeto de Previsão com Python

Este repositório contém um projeto de previsão utilizando técnicas de análise de dados e machine learning. O código foi desenvolvido em Python dentro de um ambiente Jupyter Notebook.

## Estrutura do Projeto

- **Notebook Principal:** `ModeloPrevisao.ipynb`
- **Células de Código:** 19 células com etapas de importação de bibliotecas, análise exploratória de dados e modelagem preditiva.
- **Células de Markdown:** 3 células explicando os passos da análise e metodologia aplicada.

## Pré-requisitos

Certifique-se de que as seguintes bibliotecas estão instaladas no seu ambiente:
- `prophet`
- `pandas-profiling`
- `pygwalker`

Para instalar, execute os comandos abaixo:

```bash
pip install prophet
pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip
pip install pygwalker --upgrade
```

## Etapas do Projeto

1. **Análise Exploratória de Dados (AED):**
   - Entender o contexto dos dados.
   - Limpar valores duplicados e inconsistentes.
   - Tratar valores ausentes de forma apropriada.
   - Realizar análises descritivas.

2. **Preparação dos Dados:**
   - Normalização e transformação de atributos.
   - Separação em conjuntos de treino e teste.

3. **Modelagem Preditiva:**
   - Treinamento de modelos utilizando `prophet` e outras bibliotecas.
   - Avaliação de desempenho e ajuste de hiperparâmetros.

4. **Visualização de Resultados:**
   - Utilização do `pygwalker` para criar visualizações interativas.
   - Relatórios automáticos com `pandas-profiling`.

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale os requisitos:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook para reproduzir os resultados.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
