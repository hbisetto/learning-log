# Learninglog
O Learninglog é um site de registro de aprendizagem. Através dele, um usuário registra os tópicos referentes a assuntos que está aprendendo. Nesses tópicos é possível adicionar entradas, que são anotaçõe sobre os tópicos.
Cada usuário vê somente os seus tópicos e suas entradas.

O projeto Learninglog foi feito em Python(Django) com base nas lições do livro Python Crash Course de Eric Matthes.
Algumas adaptações foram necessárias, como, por exemplo, o deploy. O livro recomenta o site https://plattaform.sh, que não existe mais. Então, eu fiz o deploy no site render (https://render.com/).

O Learninglog é um projeto de estudo. É um projeto simples, porém foi feito passo a passo, com análise e reflexão em cada processo. A ideia aqui é trabalhar os fundamentos do Python/Django em um projeto real, ainda que simples. Por fim, é um ponto de partida para adicionar outras features como estudo.
## Features adicionadas
Como estudo, adicionei algumas features extras:
- Correção na página inicial: a página mostrava a opção de Register mesmo quando o usuário já estava logado. Agora, é feita uma verificação anterior e se o usuário estiver logado, encaminha-se para a sessão dos tópicos.
