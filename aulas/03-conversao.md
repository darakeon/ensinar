A conversão entre tipos de dados, também conhecida como **type casting**, é um processo comum em programação, onde você altera o tipo de dado de uma variável para outro tipo. Aqui estão algumas conversões básicas que você pode encontrar como iniciante:

### 1. **De String para Inteiro (Inteiro Casting):**

Para converter uma string que representa um número inteiro em um inteiro, você pode usar a função `int()`:

```python
numero_em_string = "42"
numero_inteiro = int(numero_em_string)
print(numero_inteiro)  # Saída: 42
```

### 2. **De String para Ponto Flutuante (Float Casting):**

Para converter uma string que representa um número de ponto flutuante em um número de ponto flutuante, você pode usar a função `float()`:

```python
numero_em_string = "3.14"
numero_ponto_flutuante = float(numero_em_string)
print(numero_ponto_flutuante)  # Saída: 3.14
```

### 3. **De Inteiro para String:**

Para converter um inteiro em uma string, você pode usar a função `str()`:

```python
numero_inteiro = 42
numero_em_string = str(numero_inteiro)
print(numero_em_string)  # Saída: "42"
```

### 4. **De Ponto Flutuante para String:**

Para converter um número de ponto flutuante em uma string, você pode usar a função `str()` também:

```python
numero_ponto_flutuante = 3.14
numero_em_string = str(numero_ponto_flutuante)
print(numero_em_string)  # Saída: "3.14"
```

### 5. **De Inteiro para Ponto Flutuante:**

Para converter um inteiro em um número de ponto flutuante, você pode usar a função `float()`:

```python
numero_inteiro = 42
numero_ponto_flutuante = float(numero_inteiro)
print(numero_ponto_flutuante)  # Saída: 42.0
```

Porém, em Python, isso geralmente é feito automaticamente quando você realiza operações que envolvem números inteiros e de ponto flutuante. Por exemplo:

```python
numero_inteiro = 42
numero_ponto_flutuante = 2.5
numero_final = numero_inteiro * numero_ponto_flutuante
print(numero_final)  # Saída: 105.0
```

### 6. **De Ponto Flutuante para Inteiro (Arredondamento para Baixo):**

Para converter um número de ponto flutuante em um inteiro, você pode usar a função `int()`. Isso irá truncar o número, ou seja, removerá a parte decimal:

```python
numero_ponto_flutuante = 3.99
numero_inteiro = int(numero_ponto_flutuante)
print(numero_inteiro)  # Saída: 3
```
