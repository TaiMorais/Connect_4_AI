# 🕹️ Agente de Inteligência Artificial para o Jogo Conecta-4

Este projeto implementa um **agente de Inteligência Artificial (IA)** para o jogo **Conecta-4**, utilizando o algoritmo **Minimax** com otimização pela técnica de **poda alfa-beta**. O agente é capaz de tomar decisões estratégicas em tempo real, considerando o estado atual do tabuleiro e realizando movimentos otimizados para maximizar suas chances de vitória.

## 🚀 Objetivo

O objetivo deste trabalho é aprimorar o entendimento sobre **busca competitiva em jogos de adversários** por meio da implementação de um agente de IA para o jogo **Conecta-4**. A IA utiliza uma **função de avaliação heurística** para tomar decisões estratégicas em tabuleiros de diferentes tamanhos, considerando as restrições computacionais.

## 📑 Metodologia

- **Algoritmo Minimax**: Utilizado para gerar uma árvore de jogo, onde cada nó representa um estado do jogo e cada aresta corresponde a um movimento possível.
- **Poda Alfa-Beta**: Otimiza a busca na árvore de jogo, reduzindo o número de nós visitados e permitindo que o agente explore mais profundamente em menos tempo.
- **Função Heurística**: Avalia o tabuleiro em tempo real com base nas peças do jogador, peças do oponente e espaços vazios, atribuindo pontuações que guiam o algoritmo Minimax.

## ⚙️ Implementação

A IA foi implementada utilizando o algoritmo Minimax com poda alfa-beta, além de uma **heurística personalizada** baseada em jogos de soma-zero. A heurística considera o número de peças alinhadas e espaços vazios no tabuleiro, atribuindo pontuações que orientam a estratégia da IA. 

### Principais Funcionalidades:
- **Decisões otimizadas** em tempo real.
- **Redução de nós visitados** com a poda alfa-beta.
- Avaliação baseada em **estratégias de soma-zero**.

## 🧠 Análise de Resultados

Testamos a IA em diferentes tamanhos de tabuleiro, como 6x7, 10x11 e 15x16, avaliando o desempenho com diferentes profundidades de busca. Observamos que, com a poda alfa-beta, o número de nós visitados foi significativamente reduzido, resultando em uma melhora no desempenho computacional.

## 👩‍💻 Autores

- **Tainara  Morais**
- **Tatiane Vitória**
