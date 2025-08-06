
# Introdução aos Algoritmos

Um **algoritmo** é um conjunto finito e ordenado de instruções definidas para resolver um problema ou realizar uma tarefa. Pense nele como a **receita de um bolo**: você segue um passo a passo com instruções claras até alcançar um resultado.

> 💡 A beleza dos algoritmos é que eles são **independentes de linguagem de programação**. A lógica que você cria pode ser aplicada em Python, C++, Java ou qualquer outra linguagem.

---

## 📌 Componentes de um Algoritmo

Todo algoritmo bem construído possui três partes essenciais:

### 🟢 Entrada
É o **dado inicial** que será processado. Pode ser:
- Um número digitado pelo usuário
- Um valor vindo de um arquivo
- Um dado de um banco de dados

**Exemplo:** As quatro notas de um aluno.

---

### 🔄 Processamento
É onde a mágica acontece: os dados são **transformados**. Aqui usamos:
- Variáveis
- Condicionais (`if`, `else`)
- Laços de repetição (`for`, `while`)
- Operações matemáticas

**Exemplo:** Calcular a média das quatro notas recebidas.

---

### 🟣 Saída
É o **resultado final** após o processamento. Pode ser:
- Um texto exibido na tela
- Um arquivo gerado
- Um relatório ou gráfico

**Exemplo:** "Aluno aprovado com média 7.5".

---

## 🧭 Representações de Algoritmos

Antes de escrever código, é importante pensar na lógica. Para isso, usamos três formas principais de representação:

### 1. 🧾 Pseudocódigo
É uma **linguagem intermediária**, entre o português e a programação. Ajuda a estruturar o raciocínio lógico sem se preocupar com a sintaxe de uma linguagem específica.

**Exemplo:**

```plaintext
1. Leia o valor de nota1
2. Leia o valor de nota2
3. Calcule media ← (nota1 + nota2) / 2
4. Se media ≥ 7 então
     Escreva "Aprovado"
   Senão
     Escreva "Reprovado"
```

---

### 2. 📊 Fluxograma
É uma representação **visual** do algoritmo, usando símbolos gráficos:
- 🔷 Início/Fim
- 🔽 Entrada/Saída
- ⬛ Processamento
- 🔺 Decisão

Ideal para **visualizar o fluxo** de uma solução.

---

### 3. 📄 Descrição Narrativa
É a explicação do algoritmo em **texto corrido**, detalhando cada etapa de forma descritiva. É útil para documentação, mas menos prática para iniciantes.

---

## 💻 Desafios de Algoritmo para Praticar

A melhor forma de aprender algoritmos é **praticando**! Aqui estão alguns desafios clássicos para você treinar:

---

### 1. 📘 Cálculo de Média

**Objetivo:** Calcular a média de 4 notas de um aluno e informar se foi aprovado (média ≥ 6) ou reprovado.

**Pseudocódigo:**
```plaintext
1. Leia nota1, nota2, nota3, nota4
2. Calcule media ← (nota1 + nota2 + nota3 + nota4) / 4
3. Se media ≥ 6 então
     Escreva "Aprovado"
   Senão
     Escreva "Reprovado"
```

---

### 2. 🔢 Verificação de Par ou Ímpar

**Objetivo:** Informar se um número digitado é par ou ímpar.

**Pseudocódigo:**
```plaintext
1. Leia numero
2. Se numero % 2 = 0 então
     Escreva "Par"
   Senão
     Escreva "Ímpar"
```

---

### 3. 🔺 Maior de Três Números

**Objetivo:** Ler três números diferentes e informar qual é o maior.

**Pseudocódigo:**
```plaintext
1. Leia num1, num2, num3
2. Se num1 > num2 e num1 > num3 então
     Escreva "Maior é num1"
   Senão se num2 > num3 então
     Escreva "Maior é num2"
   Senão
     Escreva "Maior é num3"
```

---

### 4. 📈 Tabuada de um Número

**Objetivo:** Imprimir a tabuada de um número informado pelo usuário (1 a 10).

**Pseudocódigo:**
```plaintext
1. Leia numero
2. Para i de 1 até 10 faça
     resultado ← numero * i
     Escreva numero + " x " + i + " = " + resultado
```

**Exemplo de saída (número = 7):**
```
7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
...
7 x 10 = 70
```

---

## 🚀 Conclusão

Algoritmos são o **fundamento da programação**. Eles ajudam você a organizar o raciocínio e solucionar problemas de forma lógica. Com prática e dedicação, você será capaz de criar soluções eficientes e elegantes para os mais diversos desafios!

> **Próximo passo:** Pegue papel e lápis ou um editor de texto e comece a praticar os exemplos!

---

**© 2025 - Cris | Estudo de Algoritmos**
