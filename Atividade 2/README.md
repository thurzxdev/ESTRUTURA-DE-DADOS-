# Atividade Avaliativa – Estruturas de Dados

## 📚 Arrays, Matrizes, Algoritmos de Ordenação e Busca

**Valor:** 1,0 ponto

---

## 🎯 Objetivo

Investigar experimentalmente o comportamento de estruturas de dados e algoritmos fundamentais, relacionando conceitos de:

* Arrays
* Matrizes
* Algoritmos de Ordenação
* Algoritmos de Busca
* Índices
* Loops
* Complexidade Computacional

Além da implementação dos programas, o objetivo é analisar, medir e interpretar a quantidade de operações realizadas pelos algoritmos, comparando os resultados obtidos com as complexidades teóricas estudadas em sala de aula.

---

## 📋 Conteúdo Desenvolvido

### Parte 1 – Conceitos Fundamentais

Estudo dos conceitos básicos relacionados a:

* Arrays e vetores
* Matrizes bidimensionais
* Índices e posicionamento de dados
* Estruturas de repetição
* Complexidade de algoritmos

---

### Parte 2 – Experimento de Ordenação

Comparação experimental entre os algoritmos:

* Bubble Sort
* Quick Sort

Testes realizados com:

* 10 elementos
* 20 elementos
* 1.000 elementos

Aspectos analisados:

* Quantidade de operações
* Crescimento do custo computacional
* Relação entre resultados experimentais e complexidade teórica

---

### Parte 3 – Investigação de Busca em Matrizes

Implementação de busca sequencial utilizando loops aninhados.

Experimentos realizados em matrizes:

* 2 × 2
* 10 × 10
* 100 × 100

Análises realizadas:

* Busca no início
* Busca no final
* Valor inexistente

Aspectos observados:

* Quantidade de comparações
* Melhor caso
* Pior caso
* Complexidade O(m × n)

---

### Parte 4 – Hands On 1: Investigação do Array

Desenvolvimento de um sistema para análise de temperaturas utilizando um array de 10 posições.

Operações realizadas:

* Leitura dos valores
* Exibição dos dados
* Cálculo da média
* Identificação do maior valor
* Identificação do menor valor
* Localização dos índices
* Contagem de valores acima da média

Complexidade identificada:

```text
O(n)
```

---

### Parte 5 – Hands On 2: Matriz Aplicada – Monitoramento de Sensores

Simulação de um sistema de monitoramento composto por:

* 5 sensores de temperatura
* 24 medições por sensor

Estrutura utilizada:

```cpp
float sensores[5][24];
```

Análises realizadas:

* Média por sensor
* Média geral
* Maior temperatura registrada
* Sensor responsável
* Horário da ocorrência
* Contagem de leituras acima de um limite informado

Complexidade identificada:

```text
O(m × n)
```

---

## 📊 Principais Resultados

Os experimentos demonstraram que:

* Algoritmos possuem comportamentos distintos conforme o tamanho da entrada.
* O Bubble Sort apresenta crescimento quadrático (**O(n²)**).
* O Quick Sort apresenta crescimento médio de **O(n log n)**.
* A busca sequencial depende diretamente da posição do elemento procurado.
* Arrays apresentam percursos lineares (**O(n)**).
* Matrizes exigem loops aninhados e possuem custo proporcional ao número total de elementos (**O(m × n)**).

---

## 🧠 Conhecimentos Aplicados

Durante a realização da atividade foram aplicados conceitos de:

* Estruturas de Dados
* Programação em C++
* Vetores e Matrizes
* Algoritmos de Busca
* Algoritmos de Ordenação
* Análise de Desempenho
* Complexidade Computacional
* Lógica de Programação

---

## ✅ Conclusão

A atividade permitiu observar na prática como diferentes estruturas e algoritmos se comportam conforme o volume de dados aumenta. Os resultados experimentais confirmaram as complexidades teóricas estudadas e reforçaram a importância da escolha adequada de algoritmos para garantir eficiência e desempenho em aplicações reais.

---

## 👨‍💻 Tecnologias Utilizadas

* Python
* C
* Estruturas de Dados
* Algoritmos de Busca
* Algoritmos de Ordenação
* Análise de Complexidade Computacional
