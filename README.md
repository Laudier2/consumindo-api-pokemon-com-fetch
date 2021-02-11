# consumindo-api-pokemon-com-fetch

![Exemplo de como fuciona](https://github.com/Laudier2/consumindo-api-pokemon-com-fetch/blob/master/img/gitgif.gif)

A API Fetch fornece uma interface para buscar recursos (inclusive na rede). Parecerá familiar para quem já usou XMLHttpRequest, mas a nova API oferece um conjunto de recursos mais poderoso e flexível.

##Conceitos e uso  
 
Fetch fornece uma definição genérica de Requeste Responseobjetos (e outras coisas envolvidas com pedidos de rede). Isso permitirá que sejam usados ​​onde quer que sejam necessários no futuro, seja para service workers, API de cache e outras coisas semelhantes que tratam ou modificam solicitações e respostas, ou qualquer tipo de caso de uso que pode exigir que você gere suas respostas programaticamente (ou seja, o uso de um programa de computador ou instruções de programação pessoal).

Ele também define conceitos relacionados, como CORS e a semântica do cabeçalho HTTP Origin, substituindo suas definições separadas em outros lugares.

Para fazer uma solicitação e buscar um recurso, use o WindowOrWorkerGlobalScope.fetch()método. É implementado em várias interfaces, especificamente Windowe WorkerGlobalScope. Isso o torna disponível em praticamente qualquer contexto em que você queira buscar recursos.

O  fetch() método tem um argumento obrigatório, o caminho para o recurso que você deseja buscar. Ele retorna um Promiseque resolve para Responseessa solicitação, seja ela bem-sucedida ou não. Você também pode opcionalmente passar um initobjeto de opções como o segundo argumento (consulte Request).

Depois que um Responseé recuperado, há vários métodos disponíveis para definir o que é o conteúdo do corpo e como ele deve ser tratado (consulte Recursos Body).
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
