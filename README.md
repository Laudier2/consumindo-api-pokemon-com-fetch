# consuming-api-pokemon-with-fetch
![Exemplo de como fuciona](https://github.com/Laudier2/consumindo-api-pokemon-com-fetch/blob/master/img/gitgif.gif)

The Fetch API provides an interface for fetching resources (including from the network). It will look familiar to anyone who has used XMLHttpRequest, but the new API offers a more powerful and flexible feature set.

## Concepts and usage
 
Fetch provides a generic definition of Requeste Responseobjects (and other things involved with network requests). This will allow them to be used wherever they are needed in the future, be it for service workers, cache APIs and the like that handle or modify requests and responses, or any type of use case that may require you to generate your responses programmatically (that is, the use of a computer program or personal programming instructions).

It also defines related concepts, such as CORS and the HTTP Origin header semantics, replacing its separate definitions elsewhere.

To make a request and fetch a resource, use the WindowOrWorkerGlobalScope.fetch () method. It is implemented on several interfaces, specifically Windowe WorkerGlobalScope. This makes it available in almost any context in which you want to look for resources.

The fetch () method has a mandatory argument, the path to the resource you want to fetch. It returns a Promiseque resolves for Response to that request, whether it is successful or not. You can also optionally pass an initobject of options as the second argument (see Request).

After a Response is recovered, there are several methods available to define what the body's content is and how it should be treated (see Body Resources).
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
