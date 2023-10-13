Estruturas de controle em programação são comandos que permitem que você controle o fluxo de execução de um programa. Elas determinam a ordem em que as instruções são executadas com base em certas condições ou repetem um bloco de código várias vezes. As estruturas de controle são essenciais para escrever programas que tomam decisões, repetem tarefas e respondem dinamicamente às entradas do usuário.

Existem três tipos principais de estruturas de controle:

### 1. **Estruturas de Controle de Sequência:**
   - As instruções são executadas sequencialmente, uma após a outra, na ordem em que são escritas no código. Não há desvios ou repetições neste tipo de estrutura.

   **Exemplo:**
   ```python
   print("Passo 1")
   print("Passo 2")
   print("Passo 3")
   ```

### 2. **Estruturas de Controle de Decisão (Condicionais):**
   - Permitem que o programa tome decisões com base em condições. Se uma condição é verdadeira, um bloco de código é executado; caso contrário, outro bloco de código pode ser executado.

   **Exemplo (em Python usando `if`, `else`):**
   ```python
   idade = 18

   if idade >= 18:
       print("Você é maior de idade.")
   else:
       print("Você é menor de idade.")
   ```

### 3. **Estruturas de Controle de Repetição (Loops):**
   - Permitem que um bloco de código seja executado várias vezes. Existem dois tipos principais de loops: `for` (para um número específico de iterações) e `while` (enquanto uma condição é verdadeira).

   **Exemplo (em Python usando `for`):**
   ```python
   for i in range(5):
       print("Iteração", i)
   ```

   **Exemplo (em Python usando `while`):**
   ```python
   contador = 0
   while contador < 5:
       print("Iteração", contador)
       contador += 1
   ```

Aprender essas estruturas de controle é fundamental para se capacitar a criar programas que possam tomar decisões com base em dados, repetir tarefas automaticamente e criar lógica dinâmica em seus códigos. É especialmente importante ao aprender programação para arte, pois muitas vezes você precisará de lógica condicional para criar padrões complexos ou interações específicas com o usuário em projetos artísticos.

## Loop com for

O loop `for` em Python é uma estrutura de controle que permite executar um bloco de código várias vezes. Vamos explorar as formas básicas do `for` em Python com explicações simples e exemplos:

### 1. **Iterando sobre uma Lista ou Sequência:**

A forma mais comum de usar o `for` é iterar sobre uma lista ou qualquer outra sequência. Aqui está um exemplo:

```python
lista = [1, 2, 3, 4, 5]
for elemento in lista:
    print(elemento)
```

Nesse exemplo, o `for` percorre cada elemento na lista `lista` e executa o bloco de código para cada elemento. A variável `elemento` contém o valor atual da lista a cada iteração.

### 2. **Usando a Função `range()` para Gerar uma Sequência Numérica:**

A função `range()` gera uma sequência de números, o que é útil para criar loops. Aqui está um exemplo:

```python
for i in range(1, 6):  # Gera números de 1 a 5
    print(i)
```

Nesse caso, `range(1, 6)` cria uma sequência de números de 1 a 5. O loop `for` itera sobre esses números e imprime cada um.
