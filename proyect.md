para obtener todos los titulos de los libros en la pagina books.toscrape.com podemos usar
$x('//article[@class="product_pod"]/h3/a/@title').map(x => x.value) En la consola del navegador chrome.

para poder obtener los precios podemos tambien usar
$x('//article[@class="product_pod"]/div[@class="product_price"]/p[@class="price_color"]/text()').map(x => x.wholeText)

para poder obtener las categorias =>
$x('//ul[@class="nav nav-list"]/li/ul/li/a/text()').map(x => x.wholeText)
nos restaria realizar un strip en python para poder quitar los espacios.

para obtener el stock disponible de un libro entramos al libro y
$x('//p[2]/text()').map(x=> x.wholeText)[1].replace(/[\s\n]/g, '')

para obtener losd etalles del libro entramos al libro y
$x('//article[@class="product_page"]/p/text()').map(x => x.wholeText)
