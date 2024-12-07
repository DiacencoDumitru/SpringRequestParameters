## Параметры GET - запроса в Spring Framework

Параметры GET запроса можно получить двумя способами:

1. `HttpServletRequest` **тут мы просим все данные о HTTP запросе**
2. `@RequestMapping` **получаем конкретно только параметры запроса** (мы указываем какие параметры в виде ключей ждём в
   url, и в дальнейшем брать значение и обрабатывать его). Так-же когда указываем `required = false` если не передаются
   параметры, тогда будет стоять **null**
3. Для файла hello.html `<a href="/first/hello?name=Tom&surname=Jone">Request with parameters</a>` при нажатии происходит GET запрос и мы присвоим указанные значения от url параметров. 
