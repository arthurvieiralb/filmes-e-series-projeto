1. Introdução
O objetivo deste projeto é implementar um sistema simples de biblioteca de filmes e séries usando a estrutura de dados pilha. O sistema simula a funcionalidade de adicionar filmes e séries à lista de conteúdos a serem assistidos, assistir ao conteúdo mais recente, exibir o próximo conteúdo a ser assistido e limpar o histórico de conteúdos assistidos.
Esse tipo de sistema utiliza a pilha (LIFO - Last In, First Out), onde o conteúdo mais recente adicionado à pilha é o primeiro a ser assistido.
2. Documentação das Funcionalidades
O que o sistema faz?
O sistema tem um menu com as seguintes funcionalidades:
1- Adicionar filme ou série: O usuário pode adicionar um filme ou série à pilha, informando o título e se é uma série ou um filme.
2- Assistir ao próximo filme ou série: O usuário pode remover o filme ou série do topo da pilha (assistir ao conteúdo mais recente).
3- Exibir o próximo filme ou série para assistir: Exibe o conteúdo que está no topo da pilha.
4- Exibir histórico de filmes e séries: Exibe todos os filmes e séries adicionados à pilha até o momento.
5- Limpar histórico: Remove todos os filmes e séries da pilha, apagando o histórico.
De que forma?
A estrutura de dados utilizada é a pilha, onde cada filme ou série é empurrado para o topo da pilha.
Função push: Adiciona um filme ou série à pilha.
Função pop: Remove o filme ou série do topo da pilha (assistir ao próximo conteúdo).
Função viewCurrent: Exibe o filme ou série no topo da pilha (próximo a ser assistido).
Função displayHistory: Exibe todos os filmes e séries armazenados na pilha.
Função clearHistory: Remove todos os filmes e séries da pilha, apagando o histórico.
3. Conclusão
Este sistema simples demonstrou o uso da estrutura de pilha para gerenciar um histórico de filmes e séries. A implementação cobre funcionalidades básicas de adicionar conteúdos à pilha, assistir ao conteúdo mais recente, visualizar o próximo conteúdo a ser assistido e limpar o histórico.
Melhorias futuras:
Persistência de dados: Implementar uma funcionalidade para salvar o histórico de filmes e séries em um arquivo para garantir que os dados não sejam perdidos quando o programa for fechado.
Limitação de tamanho do histórico: Adicionar uma funcionalidade que limita o número de filmes e séries no histórico, removendo os mais antigos quando o limite for atingido.
Interface gráfica: Implementar uma interface gráfica para tornar a interação mais intuitiva e agradável.
Buscas por filmes e séries: Implementar a busca por título para verificar se um filme ou série já foi adicionado à pilha.
