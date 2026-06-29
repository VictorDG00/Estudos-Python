# Variáveis

## Rules
Variáveis só podem conter letras, números e _. Podem começar com letras ou _, mas não com números.

Existem palavras reservadas que não podem ser usadas como nome de variável, ex.: print.

### Simples
nome = tipo

### Listas
### Tuplas
### Conjunto | set
### Dicionário

# Tipos primitivos

### int | Inteiro

Um número inteiro é qualquer número que não possui parte fracionária ou decimal, englobando os números naturais positivos, seus opostos negativos e o zero.

```Python 3.14
numero: int = 5
```

### float | ponto flutuante

Um número float (ponto flutuante) é um tipo de dado numérico usado na computação para representar números que possuem uma parte fracionária ou decimal, permitindo expressar valores reais de forma aproximada.

```Python 3.14
numero: float = 1.45
```

### bool | Booleano

Um booleano é um tipo de dado lógico que pode assumir apenas um de dois valores possíveis: verdadeiro (True) ou falso (False), sendo a base para a tomada de decisões e testes de condições na programação.

```Python 3.14
switch: bool = False
switch: bool = True
```

### str

Uma string é uma sequência ordenada de caracteres — que pode incluir letras, números, símbolos e espaços — tratada como texto e geralmente delimitada por aspas simples ou duplas.

```Python 3.14
nome: str = 'Victor'
```

### Nulo

# Tipos Especiais

### Byte
### Range

---

# F-strings

### Python 2

```Python 2.7.18
nome = "Ana"
idade = 30
print("Meu nome é %s e tenho %d anos" % (nome, idade))
```

### Python 3

```Python 3
nome = "Ana"
idade = 30
print("Meu nome é {} e tenho {} anos".format(nome, idade))
```

### Python 3.6 em diante

```Python ^3.6
nome = "Ana"
idade = 30
print(f"Meu nome é {nome} e tenho {idade} anos")
```

---

# Operdores 


### Aritimeticos

| Operador | Significado | Exemplo | Resultado |
| ------------ | ------------- | ------------- | ------------- |
| ** | Expoente | 2 ** 2 | 4 |
| %  | Modulo / Resto | 14 % 4 | 2 |
| // | Divisao de inteiros / Quociente | 13 // 8 | 1 |
| /  | Divisao | 13 // 8 | 1.1625 |
| *  | Multiplicacao | 8 * 2 | 16 |
| -  | Subtracao | 7 - 1 | 6 |
| +  | Adicao | 2 + 2 | 4 |


### Comparacao
| Operador | Significado | Exemplo | Resultado |
| ------------- | ------------- | ------------- | ------------- |
| >  | Maior que | 100 > 10 | True |
| <  | Menor que | 100 < 10 | False |
| >= | Maior ou igual a | 2 >= 2 | True |
| <= | Menor ou igual a | 1 <= 4 | True |
| ++ | Igual | 6 == 9 | False |
| != | Diferente | 3 != 2 | True |

### Logico

| Operador | Significado | Exemplo | Resultado |
| ------------- | ------------- | ------------- | ------------- |
| and | e | True and False | True |
| or | ou | True or False | True |
| not | nao | not True | False |
---
# Pesquisar

Traceback do interpretador Python

Comandos com barra invertida: \n \t