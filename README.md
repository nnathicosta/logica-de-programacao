# 🧠 Variáveis em Python

## 📌 O que são variáveis?

Variáveis são **espaços na memória** usados para **guardar informações**.
Essas informações podem ser **texto, números, datas**, entre outras.

👉 Elas se chamam *variáveis* porque **podem mudar de valor conforme a situação**.

---

## ✍️ Atribuição de valor

Em Python, usamos o **operador =** para atribuir um valor a uma variável.

```python
velocidade_internet = 400
```

* `velocidade_internet` → nome da variável
* `=` → operador de atribuição
* `400` → valor armazenado

📎 **Boas práticas**:

* Não usar espaços no nome da variável
* Quando tiver mais de uma palavra, usar **underline (_)**

---

## 🖥️ Exibindo valores

Usamos a função `print()` para **exibir valores no terminal**.

```python
print(velocidade_internet)
```

➡️ Saída no terminal: `400`

---

## 🧩 Tipos de variáveis

Cada variável tem um **tipo**, que define **que tipo de informação** ela pode guardar.

### 🔢 Números inteiros (`int`)

```python
idade = 15
```

---

### 🔢 Números decimais (`float`)

(popularmente chamados de *números quebrados*)

```python
nota = 8.5
```

---

### 🔤 Texto (`string` / `str`)

Texto deve estar **entre aspas simples ou duplas**.

```python
nome_completo = 'Nathalia Costa Santos'
```

---

### ✅❌ Booleanos (`bool`)

Guardam apenas **dois valores**:

* `True` (verdadeiro)
* `False` (falso)

```python
pode_entrar = True
```

⚠️ **Importante**: o `T` e o `F` precisam ser **maiúsculos**.

---

## 🔍 Descobrindo o tipo de uma variável

Usamos a função `type()` para saber **qual é o tipo** armazenado em uma variável.

```python
print(type(idade))
```

Possíveis resultados:

* `int` → número inteiro
* `float` → número decimal
* `str` → texto
* `bool` → verdadeiro ou falso

---

## 🧠 Exercício prático – Valor por hora

**Problema:** calcular o valor da hora de um funcionário com base no salário mensal e nas horas trabalhadas.

### 📋 Método dos 5 Porquês (algoritmo)

1️⃣ **Dados de entrada**: salário mensal, horas trabalhadas

2️⃣ **O que fazer com os dados?**
Calcular o valor da hora

3️⃣ **Restrições**:

* Precisa ter salário
* Precisa ter horas trabalhadas

4️⃣ **Resultado esperado**:
Exibir o valor da hora

5️⃣ **Passos**:

* Receber salário
* Receber horas trabalhadas
* Dividir salário pelas horas
* Exibir o resultado

---

## ⌨️ Entrada de dados com `input()`

A função `input()` **sempre retorna texto (`str`)**.
Por isso, precisamos **converter o tipo** antes de calcular.

```python
salario_mensal = input('Qual é o seu salário mensal?: ')
horas_trabalhadas = input('Quantas horas trabalha por mês?: ')

valor_hora = float(salario_mensal) / int(horas_trabalhadas)
print(valor_hora)
```

📌 **Resumo importante**:

* `input()` → retorna `str`
* `float()` → converte para número decimal
* `int()` → converte para número inteiro

---

✨ **Conclusão**
Variáveis são a base da programação:

* Guardam informações
* Possuem tipos diferentes
* Ajudam o programa a tomar decisões
