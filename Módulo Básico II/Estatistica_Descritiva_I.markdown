# Estatística Descritiva I

A Estatística Descritiva tem como objetivo **organizar, descrever e sumarizar dados**, diferentemente da estatística inferencial, que busca usar os dados para aprender sobre a população. Suas principais técnicas incluem:

- **Tabelas de Frequência** (simples ou em classes)
- **Gráficos**
- **Métodos Acessórios**:
  - Medidas de Posição
  - Medidas de Dispersão
  - Medidas de Distribuição dos Dados (assimetria, curtose, boxplot)
  - Estatísticas de Resumo
  - Estatísticas de Tendência

## Tabelas de Frequência

As tabelas de frequência são uma das formas mais utilizadas para sumarizar conjuntos de dados. Elas representam os dados de forma tabular ou gráfica, com base nas frequências com que os valores aparecem, permitindo observar tendências básicas e possíveis caminhos iniciais de análise. O tipo de tabela depende diretamente do tipo de variável em estudo:

### Tipos de Variáveis
- **Quantitativas**:
  - **Discretas**: Utilizam tabelas de frequência simples.
  - **Contínuas**: Utilizam tabelas de classes de frequência.
- **Qualitativas**:
  - **Nominais**: Utilizam tabelas de frequência simples.
  - **Ordinais**: Geralmente não se aplicam tabelas de frequência para visualização.

### Exemplo de Tabela de Frequência Simples (Variável Discreta)
Para uma variável discreta, consideramos:
- **xi**: Valor da variável na posição *i*.
- **fi**: Frequência absoluta do valor *xi*.

**Exemplo**:
```
xi | fi
---|---
 0 |  8
 1 |  5
 2 |  5
 3 |  2
```

### Exemplo de Tabela de Classes de Frequência (Variável Contínua)
Para variáveis contínuas, os dados são agrupados em classes:
```
Classe | Intervalo de Classe | fi
-------|---------------------|---
   1   | 2–4                 |  4
   2   | 4–6                 | 12
   3   | 6–8                 | 10
   4   | 8–10                |  4
```

### Tamanho e Variedade Amostral
- Se o tamanho da amostra (**n**) for maior que 30, geralmente utiliza-se a **tabela de classes de frequência** para variáveis contínuas.

## Construção de uma Tabela de Frequência Simples

Uma tabela de frequência simples contém as seguintes colunas:
- **xi**: Valores individuais observados no conjunto de dados.
- **fi**: Frequência absoluta de cada valor.
- **Fi**: Frequência absoluta acumulada (soma das frequências até o valor atual).
- **fri**: Frequência relativa ao total (fi/n).
- **Fri**: Frequência relativa acumulada (soma das frequências relativas até o valor atual).

### Exemplo Prático
Imagine que você coletou as notas de 10 alunos: **0, 8, 10, 6, 10, 4, 0, 10, 2, 8**. Vamos construir a tabela de frequência simples.

#### Passo a Passo
1. **Identificar os valores individuais**:
   ```
   x = {0, 2, 4, 6, 8, 10}
   ```

2. **Contar a frequência absoluta (fi)**:
   ```
   x = {0, 2, 4, 6, 8, 10}
   fi = {2, 1, 1, 1, 2, 3}
   Total = 10
   ```

3. **Construir a tabela completa**:

| xi | fi | fri       | Fi | Fri       |
|----|----|-----------|----|-----------|
| 0  | 2  | 2/10 = 0,2| 2  | 0,2       |
| 2  | 1  | 1/10 = 0,1| 3  | 0,3       |
| 4  | 1  | 1/10 = 0,1| 4  | 0,4       |
| 6  | 1  | 1/10 = 0,1| 5  | 0,5       |
| 8  | 2  | 2/10 = 0,2| 7  | 0,7       |
| 10 | 3  | 3/10 = 0,3| 10 | 1,0       |
| **Total** | **10** | **1,0** | - | - |

#### Definições
- **xi**: Cada valor discreto do conjunto.
- **fi**: Frequência absoluta (quantas vezes cada valor aparece).
- **fri**: Frequência relativa (percentual que o valor representa no total, ex.: 0,2 = 20%).
- **Fi**: Frequência absoluta acumulada (soma progressiva das frequências).
- **Fri**: Frequência relativa acumulada (soma progressiva das frequências relativas).

4. **Criar um gráfico simples e interpretar os resultados**:
   - Um histograma ou gráfico de barras pode ser usado para visualizar as frequências.
   - A análise pode indicar, por exemplo, que a nota 10 é a mais frequente (30% dos alunos), enquanto as notas 2, 4 e 6 aparecem menos frequentemente.