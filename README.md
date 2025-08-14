# Sistema de Avaliação de Arbitragem Esportiva

Este projeto encontra-se na fase inicial de desenvolvimento, utilizando dados mockados — **as informações exibidas estão fixas no código por meio de listas, com o objetivo de testar e validar a interface**. A próxima etapa será a integração da aplicação com backend em FastAPI e banco de dados MongoDB.
O projeto é desenvolvido como Trabalho de Conclusão de Curso (TCC).

## Objetivos do Sistema
A aplicação será um sistema de análise esportiva focado na arbitragem, e permitirá que o usuário visualize:
1. Próximas partidas, e um perfil exclusivo sobre cada uma já finalizada.
2. Notícias gerais e análises especializadas sobre arbitragem.
3. Rankings gerais e semanais sobre os arbitros — completo e dividido por ligas.
4. Perfil excluviso para cada árbitro com informações do mesmo.
5. Perfil do jornalista, com acesso as análises e notícias escritas por ele.

## Status Atual
Atualmente, a página **`HomePege`** está sendo desenvolvida com diferentes componentes utilizando **dados hardcoded** para simular o funcionamento da listagem de notícias e de jogos. O último módulo implementado nesse estilo foi o **`ExpertArticles`**

## Funcionalidades atuais:
1. Listagem de notícias recentes, ordenadas por ID (maior para menor).
2. Listagem de notícias em destaque, ordenadas por quantidade de upvotes (maior para menor).
3. Listagem de análises e opiniões de especialistas, filtradas pela tag da notícia.

## Próximos Passos
1. Adicionar as páginas que faltam:
    - **Partida**: Jogadores destaques, estatísticas do jogo e do árbitro designado, e notícas relacionadas.
    - **Árbitro**: Dados pessoais relevantes do árbitro, estatísticas com filtros por temporada, notícias relacionadas e avaliações dos especialistas.
    - **Notícia**: Página com o corpo da notícia em sí com área para comentários e botão de upvote.
    - **Jornalista**: Últimas notícas publicadas pelo jornalista e suas análises.

## Observação
Este projeto faz parte do meu **Trabalho de Conclusão de Curso** e está em constante evolução. Atualmente, os dados são apenas exemplos para testes visuais e lógicos, não representando informações reais.