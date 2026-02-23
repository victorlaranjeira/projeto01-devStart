# 🏅 Projeto Notas Atletas

Aplicação desenvolvida em JavaScript para calcular a média válida das notas de atletas em uma competição de ginástica artística.

## 📌 Sobre o Projeto

Em uma competição com cinco jurados, cada atleta recebe cinco notas.  
A regra de cálculo determina que:

- Cada jurado atribui uma nota entre 1 e 10
- A maior e a menor nota devem ser descartadas
- A média é calculada utilizando apenas as três notas intermediárias

Esta aplicação automatiza esse processo.

---

## 🚀 Tecnologias Utilizadas

- JavaScript (ES6)

---

## 🧠 Lógica Aplicada

1. Ordenação numérica das notas utilizando `.sort((a, b) => a - b)`
2. Remoção da maior e menor nota com `.slice(1, 4)`
3. Soma das notas válidas com `.forEach()`
4. Cálculo da média com base no tamanho do array filtrado
