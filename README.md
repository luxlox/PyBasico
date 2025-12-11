# PyBásico - Conceitos Básicos de Python e NumPy

Este repositório contém exemplos básicos de programação em Python, incluindo operações matemáticas, manipulação de listas, funções, condicionais, loops, e operações com **NumPy**.

É ideal para iniciantes que desejam aprender conceitos fundamentais da linguagem e começar a trabalhar com arrays e operações matemáticas usando NumPy.

---

## 🔗 Abrir no Google Colab

Você pode abrir este notebook diretamente no Google Colab clicando no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luxlox/PyBasico/blob/main/Basico_Py.ipynb)

---

## 📚 Conteúdo

### 1. Operações Básicas
- Soma de dois números
- Verificação de idade (maior ou menor)
- Contagem de caracteres em uma string
- Soma de uma lista sem usar `sum()`
- Maior número de uma lista
- Contagem de elementos específicos em uma lista
- Filtrar números pares

### 2. Média e Aprovação
- Cálculo da média de notas
- Verificação de aprovação ou reprovação

### 3. Funções
- Função que soma elementos de uma lista
- Função que verifica se uma palavra é palíndromo

### 4. Problemas Clássicos
- Simulação de caixa eletrônico (notas 100, 50, 10 e 1)
- Jogo de adivinhar o número
- Lista de pessoas (nome + idade)

### 5. NumPy
- Criação de arrays e matrizes
- Slicing e indexação
- Operações matemáticas básicas com arrays
- Estatísticas (média, mediana, desvio padrão, variância)
- Operações por linha e coluna em matrizes
- Broadcasting
- Reshape de arrays

---

## ⚡ Exemplos

```python
# Soma de uma lista sem SUM
lista = [1, 5, 7, 2]
soma = 0
for num in lista:
    soma += num
print("Soma:", soma)  # Saída: 15
