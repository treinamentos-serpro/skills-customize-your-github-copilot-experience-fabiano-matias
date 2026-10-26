# 📘 Assignment: Jogo da Forca

## 🎯 Objective

Pratique manipulação de strings, listas, loops, condicionais e entrada de dados em Python ao criar um jogo da Forca interativo.

## 📝 Tasks

### 🛠️ Preparar a palavra secreta e o estado do jogo

#### Descrição
Use a lista de palavras do código inicial para escolher uma palavra secreta aleatoriamente e prepare as variáveis necessárias para acompanhar o progresso da partida.

#### Requisitos
O programa concluído deve:

- Selecionar aleatoriamente uma palavra da lista `words`.
- Inicializar uma coleção para registrar as letras já tentadas.
- Definir e acompanhar um limite de palpites incorretos.
- Exibir a palavra oculta com um espaço reservado para cada letra, por exemplo: `_ _ _ _`.

### 🛠️ Implementar o ciclo de palpites

#### Descrição
Crie o loop principal para que o jogador tente adivinhar a palavra, recebendo retorno sobre o progresso até vencer ou esgotar as tentativas.

#### Requisitos
O programa concluído deve:

- Solicitar um palpite de letra e comparar a entrada sem diferenciar maiúsculas de minúsculas.
- Revelar todas as posições correspondentes quando a letra estiver na palavra.
- Contabilizar palpites incorretos e exibir quantas tentativas restam.
- Encerrar a partida quando a palavra for descoberta ou o limite de erros for atingido.
- Exibir uma mensagem clara de vitória ou derrota; em caso de derrota, revelar a palavra secreta.
