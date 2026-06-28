# Tipos primitvos

#### int | Inteiro

Um número inteiro é qualquer número que não possui parte fracionária ou decimal, englobando os números naturais positivos, seus opostos negativos e o zero.

``` Python 3.14
numero: int = 5
```

#### float | ponto flutuante

Um número float / ponto flutuante é um tipo de dado numérico usado na computação para representar números que possuem uma parte fracionária ou decimal, permitindo expressar valores reais de forma aproximada.

``` Python 3.14
numero: float = 1.45
```

#### bool | Boleano

Um booleano é um tipo de dado lógico que pode assumir apenas um de dois valores possíveis: verdadeiro (True) ou falso (False), sendo a base para a tomada de decisões e testes de condições na programação.

``` Python 3.14
switch: bool = False
switch: bool = True
```

#### str

Uma string é uma sequência ordenada de caracteres — que pode incluir letras, números, símbolos e espaços — tratada como texto e geralmente delimitada por aspas simples ou dupla.

``` Python 3.14
nome: str = 'Victor'
```

---

# F-strings

#### Python 2

``` Python 2.7.18
nome = "Ana"
idade = 30
print("Meu nome é %s e tenho %d anos" % (nome, idade))
```

#### Python 3

``` Python 3
nome = "Ana"
idade = 30
print("Meu nome é {} e tenho {} anos".format(nome, idade))
```

#### Python 3.6 em diante

``` Python ^3.6
nome = "Ana"
idade = 30
print(f"Meu nome é {nome} e tenho {idade} anos")
```