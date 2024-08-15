# Problema de K-Centros

O problema de K-Centros é comum na área de aprendizado de máquina, com aplicações práticas em biologia computacional, agrupamento de documentos, detecção de anomalias, segmentação de clientes, entre outros.

## Definição do Problema

Dado um conjunto de pontos P = {p1, p2, ..., pn} em um espaço vetorial (X, d) e um parâmetro k, o objetivo é encontrar k centros C = {c1, c2, ..., ck} que minimizem a distância máxima r de qualquer ponto pi em P ao centro mais próximo cj em C.

## Complexidade Computacional

Este é um problema NP-Completo, o que significa que não existe um algoritmo capaz de resolvê-lo em uma máquina de Turing determinística em tempo polinomial para todas as instâncias.. Portanto, soluções exatas são impraticáveis para conjuntos de dados muito grandes.

## Algoritmos Aproximativos

Este projeto implementa e análisa dois algoritmos 2-aproximados para resolver o problema de K-Centros:

- **Abordagem Gulosa:** Seleciona centros iterativamente, buscando minimizar a distância máxima em cada iteração.
- **Refinamento de Intervalos:** Ajusta intervalos de possíveis soluções para aproximar a solução ótima.

Esses algoritmos garantem que o raio mínimo encontrado é, no máximo, duas vezes pior que o ótimo. A análise eh feita em diversos cenários diferentes.

