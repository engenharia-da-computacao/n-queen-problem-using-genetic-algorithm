# Problema das N-Rainhas usando Algoritmo Genético
Resolvendo o Problema das N-Rainha usando Algoritmo Genético

O objetivo do problema das N-Rainhas é colocar N rainhas em um tabuleiro de xadrez N x N, de modo que nenhuma rainha esteja em conflito com as outras.

## Terminologia
- Gene: um indivíduo é caracterizado por um conjunto de variáveis
- Cromossomo: os genes são unidos em uma string para formar um cromossomo (solução). Um cromossomo é um conjunto de parâmetros que definem uma solução proposta para o problema que o algoritmo genético está tentando resolver
- População: o conjunto de todas as soluções
- Função de Fitness: Pares de rainhas não atacantes (digamos, para N = 6, Fmax = 6C2 = 6 * 5/2 = 15)
- Crossover: Também chamado de recombinação, é um operador genético usado para combinar a informação genética de dois pais para gerar novos descendentes.
- Mutação: altera um ou mais valores genéticos em um cromossomo de seu estado inicial

### Como o algoritmo genético resolve o problema das n-rainhas?
- Etapa 1: um cromossomo aleatório é gerado
- Etapa 2: o valor de adequação do cromossomo é calculado
- Etapa 3: Se o fitness não for igual a Fmax
- Passo 4: Reproduzir um novo cromossomo (cruzado) de dois melhores cromossomos selecionados aleatoriamente
- Etapa 5: A mutação pode ocorrer
- Passo 6: Novo cromossomo adicionado à população
- Repita os passos 2 a 6 até que um cromossomo (solução) com valor de Fitness = Fmax seja encontrado

### Nota
Como a maior parte do processo é aleatória, nem sempre leva o mesmo tempo para convergir para uma solução. Se você quiser saber mais, assista [this] (https://www.youtube.com/watch?v=qt85_CinKwo&t=4s).


(Original)
# N-Queen problem using Genetic Algorithm
Solving N-Queen problem using Genetic Algorithm

The aim of N-Queens Problem is to place N queens on an N x N chessboard, in a way so that no queen is in conflict with the others.

## Terminology
- Gene:  An individual is characterized by a set of variables
- Chromosome: Genes are joined into a string to form a Chromosome (solution). A chromosome is a set of parameters which define a proposed solution to the problem that the genetic algorithm is trying to solve
- Population: The set of all solutions
- Fitness Function: Pairs of non-attacking queens (say for N=6, Fmax= 6C2 = 6*5/2 = 15)
- Crossover: Also called recombination, is a genetic operator used to combine the genetic information of two parents to generate new offspring
- Mutation: It alters one or more gene values in a chromosome from its initial state

### How the genetic algorithm solves the n-queen problem?
- Step 1: A random chromosome is generated
- Step 2: Fitness value of the chromosome is calculated
- Step 3: If fitness is not equal to Fmax
- Step 4: Reproduce (crossover) new chromosome from 2 randomly selected best chromosomes
- Step 5: Mutation may take place
- Step 6: New chromosome added to population
- Repeat Step 2 to 6 until a chromosome (solution) with Fitness value = Fmax is found

### Note
Since most of the process is random, it doesn't always take the same time to converge to a solution. If you want to dig deep, watch [this](https://www.youtube.com/watch?v=qt85_CinKwo&t=4s).
