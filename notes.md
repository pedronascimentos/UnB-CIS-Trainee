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
São dados numéricos, representados por números inteiros não negativos. Sua principal característica é a finitude, podem ser contados mas não podem ser mensurados (Ex: Número de bolas de futebol utilizadas ao longo de uma partida). Exemplo:
<p style="width: 100%; align-itens: center; text-align: center">Eu contei 35 bonés na loja</p>
#### **Quantitativo Contínuo**
São dados numéricos que podem assumir qualquer valor dentro de um intervalo, e podem ser divididos em partes, infinitamente, assumindo valores de -∞ até +∞. Não podem ser contados mas podem ser mensurados. São divididos em **Intervalares (Interval Data)** e **Razão (Ratio Data)** (Ex: Velocidade, Pressão, Distância)
<p style="width: 100%; align-itens: center; text-align: center">Eu tenho 1,80m de altura</p>
##### **Intervalares (Interval Data)**
Dados Intervalares são dados com ordem de unidades que possuem a mesma diferença (Ex: -10, -5, 0, 5, 10). Sua característica é que eles não possuem *zero absoluto ou zero verdadeiro*.
>**Importante:** Zero absoluto é a inexistência daquele valor, em valores proporcionais como a altura, a altura 0 significa que o objeto medido não existe. Entretanto, a temperatura pode ser 0ºC, não há nenhum valor que a temperatura pode assumir que implique na sua "inexistência"

##### Razão (Ratio Data)
Valores Razão também são dados com ordem de unidades que possuem a mesma diferença, a diferença é que eles **possuem zero absoluto**.

---
## Lidando com Dados Faltantes (Missing Values)

## Métodos Estatísticos de Visualização de Dados