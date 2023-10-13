**Problema: Verificar Idade para Entrada em uma Festa**

**Descrição:**
Você está escrevendo um programa para verificar se uma pessoa pode entrar em uma festa. A entrada na festa é permitida apenas para pessoas com 18 anos ou mais. Escreva um programa que pede a idade do usuário e informa se ele pode entrar na festa ou não.

**Código Resolvido (em Python):**

```python
# Pede a idade do usuário
idade = int(input("Digite sua idade: "))

# Verifica se o usuário tem 18 anos ou mais
if idade >= 18:
    print("Você pode entrar na festa!")
else:
    print("Desculpe, você não tem idade suficiente para entrar na festa.")
```

**Explicação:**
1. O programa pede a idade do usuário usando a função `input()`. A entrada é então convertida para um número inteiro usando `int()`.
2. O programa verifica se a idade é maior ou igual a 18 usando uma estrutura `if`.
3. Se a condição for verdadeira (idade maior ou igual a 18), o programa imprime "Você pode entrar na festa!".
4. Se a condição for falsa (idade menor que 18), o programa imprime "Desculpe, você não tem idade suficiente para entrar na festa.".

**Comentários:**
- `#` é usado para adicionar comentários no código. Comentários são úteis para explicar o que o código está fazendo.
- `input()` é usado para obter entrada do usuário.
- `int()` é usado para converter a entrada para um número inteiro.
- `if` verifica se a condição (idade >= 18) é verdadeira.
- `else` é usado para fornecer uma alternativa quando a condição do `if` é falsa.
- As mensagens impressas indicam se o usuário pode ou não entrar na festa com base em sua idade.

Este é um exemplo simples que usa uma estrutura condicional (`if-else`) para tomar uma decisão com base na entrada do usuário. Espero que isso ajude! Se você tiver mais perguntas ou precisar de mais exemplos, sinta-se à vontade para perguntar!