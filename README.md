# pw-lei-projeto_Gon-aloFerreira_230001170

- Tema e Ideia do Projeto
O projeto FocusBoard é um painel de produtividade pessoal (dashboard) desenhado para ajudar os utilizadores a organizarem o seu dia. A aplicação numa única página (Single Page Application) vai permitir ao utilizador visualizar a meteorologia atual para a sua cidade, ler uma citação inspiradora diária para manter o foco, e gerir uma lista de tarefas (To-Do List).

A interface será altamente interativa, reagindo a eventos e cliques do utilizador , e atualizando o conteúdo e o estilo (HTML/CSS) dinamicamente através da manipulação do DOM. A aplicação fará pedidos assíncronos (HTTP) para obter dados externos e internos para alimentar o dashboard.

- APIs a Usar
Para enriquecer a aplicação e demonstrar a integração de diferentes Web APIs, vou fazer pedidos HTTP às seguintes APIs públicas:  

API do IPMA: Será utilizada para obter dados e previsões meteorológicas fidedignas para as cidades portuguesas, consumindo os dados em formato JSON disponibilizados pelo serviço público.

Quotable API: Será utilizada para carregar dinamicamente citações inspiradoras e motivacionais sempre que o utilizador inicia a página ou clica num botão para "nova citação".

- APIs a Desenvolver 
Para cumprir os requisitos de mais-valia, nomeadamente o desenvolvimento de APIs do lado do servidor e a capacidade de criar, atualizar e eliminar dados:

FocusBoard Tasks API: Será desenvolvida uma API RESTful simples focada na gestão da lista de tarefas. Esta API terá os seguintes endpoints:

GET /tasks: Para obter as tarefas guardadas.

POST /tasks: Para criar uma nova tarefa.

PUT /tasks/:id: Para atualizar o estado da tarefa (ex: de pendente para concluída).

DELETE /tasks/:id: Para eliminar uma tarefa da lista.
Os dados serão geridos e armazenados em formato JSON no servidor.
