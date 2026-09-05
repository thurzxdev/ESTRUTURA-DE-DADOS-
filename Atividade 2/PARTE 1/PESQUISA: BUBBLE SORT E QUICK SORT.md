# Pesquisa: Bubble Sort e Quick Sort

## 📚 Objetivo

Estudar e comparar os algoritmos de ordenação **Bubble Sort** e **Quick Sort**, analisando seu funcionamento, complexidade computacional, vantagens, limitações e aplicações.

---

# Bubble Sort

## Como o algoritmo funciona

O Bubble Sort percorre a lista repetidamente, comparando elementos adjacentes e realizando trocas sempre que estiverem na ordem incorreta.

O processo continua até que nenhuma troca seja necessária, indicando que a lista está ordenada.

### Exemplo

Lista inicial:

```text
5 3 8 2
```

Após as trocas:

```text
3 5 2 8
```

Depois:

```text
3 2 5 8
```

Finalmente:

```text
2 3 5 8
```

## Lógica de ordenação

* Compara elementos vizinhos;
* Troca quando necessário;
* Repete o processo até a lista estar ordenada.

## Complexidade

| Caso        | Complexidade |
| ----------- | ------------ |
| Melhor caso | O(n)         |
| Caso médio  | O(n²)        |
| Pior caso   | O(n²)        |

## Vantagens

* Fácil de entender;
* Fácil de implementar;
* Utiliza pouca memória;
* Adequado para fins educacionais.

## Limitações

* Muito lento para grandes volumes de dados;
* Realiza muitas comparações e trocas;
* Baixa eficiência em aplicações reais.

## Situações adequadas

* Ensino de algoritmos;
* Listas pequenas;
* Dados quase ordenados.

## Situações não recomendadas

* Grandes conjuntos de dados;
* Sistemas que exigem alto desempenho.

---

# Quick Sort

## Como o algoritmo funciona

O Quick Sort utiliza a estratégia **Dividir para Conquistar**.

O algoritmo:

1. Escolhe um pivô;
2. Divide os elementos em duas partes:

   * menores que o pivô;
   * maiores que o pivô;
3. Aplica o mesmo processo recursivamente em cada parte.

## Lógica de ordenação

* Seleção de pivô;
* Particionamento;
* Ordenação recursiva dos subconjuntos.

## Complexidade

| Caso        | Complexidade |
| ----------- | ------------ |
| Melhor caso | O(n log n)   |
| Caso médio  | O(n log n)   |
| Pior caso   | O(n²)        |

## Vantagens

* Muito eficiente;
* Excelente desempenho em grandes volumes de dados;
* Amplamente utilizado em sistemas reais;
* Bom aproveitamento de memória.

## Limitações

* Implementação mais complexa;
* Pode atingir O(n²) quando o pivô é mal escolhido;
* Não é estável por padrão.

## Situações adequadas

* Grandes conjuntos de dados;
* Aplicações de produção;
* Sistemas que exigem alta performance.

## Situações não recomendadas

* Quando a estabilidade da ordenação é obrigatória;
* Quando há risco elevado de escolhas ruins de pivô sem otimizações.

---

# 📊 Tabela Comparativa

| Característica             | Bubble Sort                                                               | Quick Sort                                                                             |
| -------------------------- | ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Princípio de funcionamento | Compara e troca pares adjacentes repetidamente até a lista estar ordenada | Divide para conquistar: particiona a lista em torno de um pivô e ordena recursivamente |
| Melhor caso                | O(n)                                                                      | O(n log n)                                                                             |
| Caso médio                 | O(n²)                                                                     | O(n log n)                                                                             |
| Pior caso                  | O(n²)                                                                     | O(n²)                                                                                  |
| Uso de memória             | O(1) – in-place                                                           | O(log n) – pilha de recursão                                                           |
| Vantagem principal         | Simplicidade de implementação e entendimento                              | Alta eficiência em grandes volumes de dados                                            |
| Limitação principal        | Ineficiente para listas grandes                                           | Pode atingir O(n²) com má escolha de pivô                                              |
| Aplicação recomendada      | Fins didáticos e listas pequenas                                          | Sistemas em produção e grandes conjuntos de dados                                      |

---

# 📈 Comparação das Complexidades

O gráfico de complexidade mostra por que o Quick Sort tende a ser muito mais eficiente que o Bubble Sort conforme a quantidade de elementos aumenta.

---

# ✅ Conclusão

O Bubble Sort é um algoritmo simples e excelente para fins educacionais, porém apresenta baixa eficiência para grandes conjuntos de dados devido à sua complexidade O(n²).

O Quick Sort, por sua vez, utiliza a estratégia de dividir para conquistar e apresenta desempenho médio O(n log n), tornando-se uma das soluções mais utilizadas para ordenação em aplicações reais.

Assim, para listas pequenas e aprendizado, o Bubble Sort pode ser suficiente. Já para aplicações práticas e grandes volumes de dados, o Quick Sort é geralmente a melhor escolha.
