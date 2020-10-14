# challenge-bsconsult
Teste BS Consult


Construa um microsite responsivo em SPA (_single-page application_) para mostrar a previsão do tempo nas localidades informadas na caixa de texto branca (na imagem de [exemplo](./exemplo_teste.png) é o local aonde aparece "Rio de Janeiro, Rio de Janeiro"). Essa caixa de texto, deve ser um `input`, aonde o usuário possa trocar a localidade. Com a mudança da localidade, deve ser carregada as informações de previsão do tempo referentes a nova localidade.

Logo que a página seja aberta deve ser coletada as coordenadas geográficas do usuário pela API do navegador para então ser descobrir o nome da cidade via _reverse geocode_.

Como fundo de tela deve ser usado a imagem de destaque do Bing. Devem ser mostradas as previsões para: hoje, amanhã e depois de amanhã.

Note que existe um degradê sobreposto na imagem original, na verdade essa cor reflete a temperatura atual do lugar buscado para as três datas. Para temperaturas abaixo de 15ºC deve ser usado tons de azul, para temperaturas acima de 35ºC deve ser usado tons de vermelho e use tons de amarelo para as demais temperaturas. Quando não houver nenhuma localidade escolhida deve ser usado tons de cinza como base para o degradê. Se o usuário clicar em qualquer temperatura, as temperaturas devem ser alteradas de Celcius para Fahrenheit ou de Fahrenheit para Celcius.

A URL da imagem de fundo deve ser extraida da API do [Bing](https://www.bing.com/HPImageArchive.aspx?format=js&idx=0&n=1&mkt=pt-BR)

Para consultar a previsão do tempo, utilize a API do [Yahoo Weather] (https://developer.yahoo.com/weather/) informando o nome da localidade (Cidade e Estado). Crie as credenciais para sua conta.

Para converter latitude e longitude use a Api do Google Maps.

Os ícones podem ser encontrados em http://www.alessioatzeni.com/meteocons/

## Requisitos

-   Preferencialmente faça em JQuery ou React.js, mas você pode usar também JavaScript puro (Vanilla JS). Se for usar jQuery, não use plugins de jQuery, queremos ver o seu trabalho.
-   Para a folha de estilo, você pode usar o que preferir (CSS, SASS, LESS, CSS Modules, CSS-in-JS, etc).
-   Forkar esse desafio e criar o seu projeto (ou workspace) usando a sua versão desse repositório, tão logo acabe o desafio, submeta um _pull request_.
-   Caso tenha problemas em criar seu fork, pode criar seu próprio repositório público, ou nos enviar em arquivo zipado via e-mail para diogo@bsconsult.com.br
-   Para executar seu código, deve ser preciso apenas rodar os seguintes comandos:
    -   git clone \$seu-fork
    -   cd \$seu-fork
    -   comando para instalar dependências
    -   comando para executar a aplicação

## Critério de avaliação

-   **Organização do código**: Separação de módulos, view e model, back-end e front-end
-   **Clareza**: O README explica de forma resumida qual é o problema e como pode rodar a aplicação?
-   **Assertividade**: A aplicação está fazendo o que é esperado? Se tem algo faltando, o README explica o porquê?
-   **Legibilidade do código** (incluindo comentários)
-   **Segurança**: Existe alguma vulnerabilidade clara?
-   **Cobertura de testes** (Não esperamos cobertura completa)
-   **Histórico de commits** (estrutura e qualidade)
-   **UX**: A interface é de fácil uso e auto-explicativa
-   **Escolhas técnicas**: A escolha das bibliotecas, banco de dados, arquitetura, etc, é a melhor escolha para a aplicação?

## Dúvidas
Envie um e-mail para diogo@bsconsult.com.br

Boa sorte! ;)


