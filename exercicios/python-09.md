### Contagem de Vogais

```python
# Contando o número de vogais em uma palavra usando um loop for
palavra = "python"
contador_vogais = 0

for letra in palavra:
    if letra.lower() in "aeiou":
        contador_vogais += 1

print("Número de vogais na palavra:", contador_vogais)
```

Neste exemplo, o loop `for` conta o número de vogais na palavra "python".
