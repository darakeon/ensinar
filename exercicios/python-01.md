Este exercício envolve a criação de um programa Python que calcula a média de três números digitados pelo usuário:

```python
# Solicita ao usuário para inserir três números
input1 = input("Digite o primeiro número: ")
input2 = input("Digite o segundo número: ")
input3 = input("Digite o terceiro número: ")

# Transforma os inputs em números 
numero1 = float(input1)
numero2 = float(input2)
numero3 = float(input3)

# Calcula a média dos três números
media = (numero1 + numero2 + numero3) / 3

# Exibe a média
print("A média dos números é:", media)
```

Neste exercício:

1. **`input()`** é usado para obter entrada do usuário. O que o usuário digita é armazenado nas variáveis `numero1`, `numero2` e `numero3`.

2. **`float()`** é usado para converter a entrada do usuário em números decimais, pois `input()` retorna uma string.

3. Os números são somados e divididos por 3 para calcular a média.

4. A média é então exibida usando a função **`print()`**.

Para executar este código, você pode usar um ambiente de desenvolvimento Python (como IDLE ou PyCharm) ou até mesmo um editor de código online.

Este é um exemplo simples, mas eficaz, para ajudar iniciantes a entenderem como receber entrada do usuário, realizar operações matemáticas básicas e exibir resultados. À medida que os iniciantes ganham confiança, eles podem começar a explorar problemas mais complexos e desafiantes.
