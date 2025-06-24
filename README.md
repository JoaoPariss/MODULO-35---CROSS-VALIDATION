# MÓDULO 35 - Cross Validation

Nesta tarefa, trabalhei com uma base de dados contendo variáveis ambientais coletadas para a detecção de incêndios. O objetivo foi aplicar a técnica de **validação cruzada (cross-validation)** para avaliar a performance de um modelo de classificação na previsão da ocorrência de um *fire alarm*.

A validação cruzada é importante pois permite avaliar o desempenho do modelo de forma mais robusta, ajudando a garantir que ele generalize bem para dados não vistos.

---

## Etapas do Projeto

### 1. Carregamento e análise inicial dos dados
- A base de dados foi carregada e verifiquei os tipos de dados.
- Também foi feita uma checagem para identificar a presença de dados faltantes ou nulos.

### 2. Escolha do modelo
Para essa base, escolhi o modelo **Random Forest** para prever *fire alarm*. Ele costuma ter ótima performance em problemas de classificação, lida bem com variáveis que têm relações não lineares e é mais robusto contra ruídos e overfitting.

### 3. Separação da base
- Separei a base em variáveis independentes (X) e a variável alvo (Y).
- Em seguida, instanciei o modelo escolhido.

### 4. Definição dos Folds e aplicação da validação cruzada
- Defini o número de Folds = 5 para a validação cruzada.
- A validação cruzada foi executada utilizando o modelo já instanciado.

### 5. Avaliação do modelo
- Avaliei a pontuação obtida em cada uma das divisões dos dados.
- Ao final, calculei a média dos resultados para ter uma avaliação final da performance do modelo.

---

Este processo ajudou a garantir que o modelo tenha sido testado de maneira confiável e possa ser utilizado com mais segurança em novos dados.
