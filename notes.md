* HTML5 removes the need for <div> elements from the outlining algorithm by introducing a new element, <section>, the HTML Section Element.

* The <!DOCTYPE html> declaration defines this document to be HTML5

* No primeiro caso (Can��o), sua página em ISO-8859-1 está obtendo a palavra Canção armazenada em UTF-8 da origem, seja ela do banco de dados ou de um XML, txt etc.
Já o segundo caso (CanÃ§Ã£o) é a sua página em UTF-8 exibindo a palavra Canção armazenada em ISO-8859-1 da origem.
Solução: <meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">

* Empty elements can be "closed" in the opening tag like this: <br />.
HTML5 does not require empty elements to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.

* Here, a title attribute is added to the <p> element. The value of the title attribute will be displayed as a tooltip when you mouse over the paragraph:

* Inspecionar os elementos no browser: ótima ferramenta quando a exibição está incorreta.

* <tagname style="property:value;">, onde property é o nome da propriedade do CSS, e value é o valor da propriedade

* The width, height, and style attributes are valid in HTML5. However, we suggest using the style attribute. It prevents styles sheets from changing the size of images:

* A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can). The <div> element is a block-level element.

* span is a container for some text, with id, style and class. div is a container for some other HTML elements, also with id, style and class.


* Difference Between Class and ID. An HTML element can only have one unique id that belongs to that single element, while a class name can be used by multiple elements

* It is a best practice to use relative file paths (if possible). When using relative file paths, your web pages will not be bound to your current base URL. All links will work on your own computer (localhost) as well as on your current public domain and your future public domains. 

* HTML5 offers new semantic elements that define the different parts of a web page: header, nav, section, article, aside, footer, details, summary

* If you want to create your layout fast, you can use a framework, like W3.CSS or Bootstrap.

* Responsive Web Design is about using HTML and CSS to resize, hide, shrink, enlarge, or move the content to make it look good on any screen:

* meta name="viewport", um jeito de deixar sua página responsiva, novo no HTML5, se adequa ao tamanho do device.
 
* The HTML picture element allows you to define different images for different browser window sizes.

* UTF-8 is unicode. It is the dafault encoding for HTML5

* form method: when GET is used, the submitted form data will be visible in the page address field, useful for submissions whose results may be bookmarked. 

* HTML5 added several new input types:
  color, date, datetime-local, email, month, number, range, search, tel, time, url, week
  
  