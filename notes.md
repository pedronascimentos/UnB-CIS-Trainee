# Introdução a Análise de Dados

## Classificação Teórica dos Tipos de Dados

##### Entender os tipos de dados é essencial para **limpeza**, **análise exploratória**, **visualização**, **modelagem**, e **interpretação dos resultados**.

##### Os dados podem ser classificados quanto a sua **Natureza (Qualitativo e Quantitativo)**

### **Tipos de dados quanto a sua Natureza**

| Tipo                              | Definição                                                                           | Subtipos                     | Exemplo                                      |
| --------------------------------- | ----------------------------------------------------------------------------------- | ---------------------------- | -------------------------------------------- |
| **Qualitativos** (ou Categóricos) | Representam qualidades, categorias ou atributos. Não têm valor numérico mensurável. | Nominais, Ordinais e Binário | Cor dos olhos, gênero, nível de escolaridade |
| **Quantitativos** (ou númericos)  | Representam quantidades numéricas. Podem ser mensuradas e operadas matematicamente. | Discretos e Contínuos        | Idade, altura, número de filhos              |
> **Importante**: Às vezes, dados qualitativos são codificados como números (ex: 1 = masculino, 2 = feminino), mas **não se tornam quantitativos**.

#### **Qualitativo Nominal**
>Variáveis Categorizáveis que não obedecem a determinada ordenação (Ex: Gênero, Tipo Sanguíneo).
#### **Qualitativo Ordinal** 
#### **Qualitativo Binário**
#### **Quantitativo Discreto**
#### **Quantitativo Contínuo**

---

## 🧠 5. Considerações Práticas em Data Science

- **Pré-processamento**: Dados categóricos precisam ser convertidos para representação numérica antes de entrar em algoritmos de machine learning.
    
- **Visualização**:
    
    - Dados categóricos: gráficos de barras, pizza.
        
    - Dados numéricos: histogramas, boxplots.
        
- **Modelagem**:
    
    - Modelos como **árvores de decisão** lidam bem com dados mistos.
        
    - Modelos lineares requerem que os dados sejam numéricos e, muitas vezes, normalizados.
        
