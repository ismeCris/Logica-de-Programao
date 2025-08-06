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
