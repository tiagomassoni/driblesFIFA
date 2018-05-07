HTML5 removes the need for <div> elements from the outlining algorithm by introducing a new element, <section>, the HTML Section Element.


The <!DOCTYPE html> declaration defines this document to be HTML5

No primeiro caso (Can��o), sua página em ISO-8859-1 está obtendo a palavra Canção armazenada em UTF-8 da origem, seja ela do banco de dados ou de um XML, txt etc.
Já o segundo caso (CanÃ§Ã£o) é a sua página em UTF-8 exibindo a palavra Canção armazenada em ISO-8859-1 da origem.
Solução: <meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">

Empty elements can be "closed" in the opening tag like this: <br />.
HTML5 does not require empty elements to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.

