### Contando Números Pares em uma Lista

```python
# Contando números pares em uma lista usando um loop for
numeros = [1, 2, 3, 4, 5]
contador_pares = 0

for numero in numeros:
    if numero % 2 == 0:
        contador_pares = contador_pares + 1

print("Número de pares na lista:", contador_pares)
```

Neste exemplo, o loop `for` verifica se cada número na lista `numeros` é par (divisível por 2) e incrementa o contador `contador_pares` se for par.
