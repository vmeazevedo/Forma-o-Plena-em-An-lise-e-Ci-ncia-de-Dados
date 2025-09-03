# Probabilidade I

A Probabilidade é a área da matemática que estuda as chances de um evento ocorrer em um **experimento aleatório**.

## Fenômenos

Fenômenos são quaisquer acontecimentos naturais e podem ser classificados em dois tipos:

- **Determinísticos**: Quando repetidos sob as mesmas condições iniciais, produzem sempre o mesmo resultado.
- **Aleatórios**: Quando repetidos sob as mesmas condições iniciais, podem produzir diferentes resultados.

**Nota**: Embora, teoricamente, as repetições ocorram sob as mesmas condições iniciais, na prática isso é difícil de garantir.

## Experimentos - Características

Os experimentos possuem duas características principais:

- **Repetitividade**: Um fenômeno pode ser repetido quantas vezes desejarmos.
- **Regularidade**: Refere-se à possibilidade de ocorrência dos resultados do fenômeno. A avaliação numérica dessas possibilidades dá origem às probabilidades.

## Espaço Amostral (S)

O espaço amostral é o conjunto de todos os resultados possíveis de um experimento.

### Exemplos
1. **Lançamento de uma moeda**:
   ```
   S = {cara, coroa}
   ```

2. **Lançamento de um dado de 6 faces**:
   ```
   S = {1, 2, 3, 4, 5, 6}
   ```

### Representação
- O espaço amostral pode ser representado por um **diagrama de árvore** para visualização dos resultados possíveis.

## Evento

Um evento é qualquer subconjunto do espaço amostral de um experimento.

### Exemplos (Lançamento de um dado, S = {1, 2, 3, 4, 5, 6})
- **Evento A**: {1, 2} (obter 1 ou 2).
- **Evento B**: {3, 4, 5} (obter 3, 4 ou 5).
- **Evento C**: {} (conjunto vazio, chamado de **evento impossível**, pois nunca ocorrerá).
- **Evento S**: O espaço amostral completo, chamado de **evento certo**.
- **Evento complementar**: O evento que ocorre quando um evento específico não ocorre.
- **Exemplo adicional**: Obter um número par ao lançar um dado:
  ```
  E = {2, 4, 6}
  ```

## Operações com Eventos

### Definições
- **União**: Ocorre quando pelo menos um dos eventos acontece.
- **Interseção**: Ocorre quando ambos os eventos acontecem simultaneamente.
- **Complementar**: O evento que ocorre quando um evento específico **A** não ocorre.
- **Inclusão**: Se **A ⊆ B** (A está contido em B), então **A implica B**. Se **A ⊆ B** e **B ⊆ A**, então **A = B**.

## Axiomas de Probabilidade

1. **Axioma 1**:
   ```
   0 ≤ P(E) ≤ 1
   ```
   A probabilidade de um evento **E** está sempre entre 0 e 1.

2. **Axioma 2**:
   ```
   P(S) = 1
   ```
   A probabilidade do espaço amostral é igual a 1.

## Proposições de Probabilidade

1. **Proposição 4.1**:
   A probabilidade do evento complementar (**Eᶜ**, tudo que não é **E**) é dada por:
   ```
   P(Eᶜ) = 1 - P(E)
   ```

2. **Proposição 4.2**:
   Se **E ⊆ F** (E está contido em F), então:
   ```
   P(E) ≤ P(F)
   ```

3. **Proposição 4.3**:
   A probabilidade da união de dois eventos **E** e **F** é dada por:
   ```
   P(E ∪ F) = P(E) + P(F) - P(E ∩ F)
   ```
   Onde **P(E ∩ F)** é a probabilidade de **E** e **F** ocorrerem simultaneamente.