# Introdução a Análise de Dados e Machine Learning


## Classificação Teórica dos Tipos de Dados

##### Entender os tipos de dados é essencial para **limpeza**, **análise exploratória**, **visualização**, **modelagem**, e **interpretação dos resultados**.

##### Os dados podem ser classificados quanto a sua **Natureza (Qualitativo e Quantitativo)**


### **Tipos de dados quanto a sua Natureza**

| Tipo                              | Definição                                                                           | Subtipos                     | Exemplo                                      |
| --------------------------------- | ----------------------------------------------------------------------------------- | ---------------------------- | -------------------------------------------- |
| **Qualitativos** (ou Categóricos) | Representam qualidades, categorias ou atributos. Não têm valor numérico mensurável. | Nominais, Ordinais e Binário | Cor dos olhos, gênero, nível de escolaridade |
| **Quantitativos** (ou númericos)  | Representam quantidades numéricas. Podem ser mensuradas e operadas matematicamente. | Discretos e Contínuos        | Idade, altura, número de filhos              |
> **Importante:** Às vezes, dados qualitativos são codificados como números (ex: 1 = masculino, 2 = feminino), mas **não se tornam quantitativos**.

#### **Qualitativo Nominal**
Variáveis Categorizáveis que não obedecem a determinada ordenação (Ex: Gênero, Tipo Sanguíneo).
#### **Qualitativo Ordinal** 
 Varıáveis categorizáveis cuja a ordem é de suma relevância (Ex: Nível Educacional).
#### **Qualitativo Binário**
Varıáveis categorizáveis que tendem a seguir a lógica booleana, ou seja, assumem apenas um valor (Ex: Falso/Verdadeiro, Estado de vida).


#### **Quantitativo Discreto**
São dados numéricos, representados por números inteiros não negativos. Sua principal característica é a finitude, podem ser contados mas não podem ser mensurados (Ex: Número de bolas de futebol utilizadas ao longo de uma partida). 
#### **Quantitativo Contínuo**
São dados numéricos que podem assumir qualquer valor dentro de um intervalo, e podem ser divididos em partes, infinitamente, assumindo valores de -∞ até +∞. Não podem ser contados mas podem ser mensurados. São divididos em **Intervalares (Interval Data)** e **Razão (Ratio Data)** (Ex: Velocidade, Pressão, Distância)
##### **Intervalares (Interval Data)**
Dados Intervalares são dados com ordem de unidades que possuem a mesma diferença (Ex: -10, -5, 0, 5, 10). Sua característica é que eles não possuem *zero absoluto ou zero verdadeiro*.
>**Importante:** Zero absoluto é a inexistência daquele valor, em valores proporcionais como a altura, a altura 0 significa que o objeto medido não existe. Entretanto, a temperatura pode ser 0ºC, não há nenhum valor que a temperatura pode assumir que implique na sua "inexistência"
##### Razão (Ratio Data)
Valores Razão também são dados com ordem de unidades que possuem a mesma diferença, a diferença é que eles **possuem zero absoluto**.

---
## Métodos Estatísticos de Visualização de Dados
## Lidando com Dados Faltantes (Missing Values)


## Pontos importantes em Python

### **Aritmética**

Caso a versão do Python utilizada faça a divisão de inteiros por padrão (5/2 = 2) comece os seus arquivos com:

```Python
from __future__ import division
```

após essa importação as divisões passam a ser: 5/2 = 2.5 . Caso você deseje fazer a divisão de inteiros é só fazer: 5//2 .


### **Funções**

As funções em Python são de *primeira classe*, o que significa que podemos atribuí-las a variáveis e passá-las para as funções como quaisquer outros argumentos:

```Python
def double(x):
    return x * 2

def apply_to_one(f):
	return f(1)

my_double = double           # refere-se à função definida anteriormente
x = apply_to_one(my_double)  # é igual a 2
```

As funções anônimas, ou *lambdas*, podem ser definidas dentro de outra função e atribuídas a variáveis, apesar de não ser uma boa prática:

```Python
y = apply_to_one(lambda x: x + 4) # igual a 5
another_double = lambda x: 2 * x  # não faça isso
def another_double(x): return 2 * x  # faça isso
```

Os parâmetros de função também podem receber argumentos padrões, que só precisam ser especificados quando o valor desejado for diferente do valor padrão
> Em Java, para realizar essa ação seria necessário realizar uma sobrecarga com *@Override*na função

```Python
def my_print(message = "mensagem padrão"):
	print message

my_print("hello") # exibe 'hello'
my_print()        # exibe 'mensagem padrão'
```

Muitas funções será necessário especificar os argumentos pelo nome, por facilidade:

```Python
def subtract(a=0, b=0):
	return a - b

subtract(10, 5) # retorna 5
subtract(0, 5)  # retorna -5
subtract(b=5)   # retorna -5 (mesmo que a anterior)
```



### **Strings**

A criação de strings múltiplas se faz utilizando aspas triplas, da seguinte forma:

```Python
multi_line_string = """esta é a primeira linha.
esta é a segunda
esta é a terceira"""
```



### **Exceções**

Enquanto no Java e no Javascript você tem o `try` `catch` `finally`. Em Python você pode manipular exceções com `try` e `except`:

```Python
try: 
	print 0/0
except ZeroDivisionError:
	print "cannot divide by zero"
```
