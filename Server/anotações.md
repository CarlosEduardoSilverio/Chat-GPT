
src = source (ou código fonte) 

dentro da src -> Seu código fonte
fora da src -> Arquivos de configuração

Server que sustenta uma aplicação

Conceitos de arquitetura N-layer

camadas: 
- Controllers: controlar quem acessa e controlar as respostas de devolução (request e responses).

- Rotas: Quem vai o apontamento de endereços para os nossos controllers.

- Model: é a forma de entreda/saida de dados no seu servidor.

- Config: server para colocar configurações de outras aplicações (aplicações de terceiros) e dados não sensiveis.

- Configurações não embarcadas (.env):
server para isolar dados sensiveis.