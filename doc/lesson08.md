# Занятие 8 онлайн проекта <a href="https://github.com/JavaWebinar/topjava05">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFfkpMd2UyWjBsc2JsSE4tRDFkU3BvMktFQkhUN1J6VExxSUUzOHlSR0RhNm8">Материалы урока</a>

**Браузер кэширует javascript и css. Если изменения не работают, обновите приложение в браузере по Ctrl+F5**

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdWdxdGpfV2J0VDA">HW7</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFbExRbTRzSWN1cDQ">1_ HW7_ jdbc_ transaction.patch</a>**
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFaFB2SjFoMVdTeEE">2_ HW7_ controller_ test.patch</a>**
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFeU1wd1U2TG44aHM">3_ HW7_ rest_ controller.patch</a>**

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLXZ3OHdac18yZlk">HW7_ Optional</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVUNwWUMxYTc2RHM">4_ HW7_ formatters.patch</a>**
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFSnk2WC12MGZNbTA">5_ HW7_ soapui.patch</a>**
-  <a href="http://rus-linux.net/lib.php?name=/MyLDP/internet/curlrus.html">HTTP-запросы через Curl</a>
```
curl http://localhost:8080/topjava/rest/profile/meals
curl -X POST --data '{"dateTime": "2015-06-01T10:05","description": "New breakfast","calories": 777}' -H 'Content-Type: application/json' http://localhost:8080/topjava/rest/profile/meals
```
- <a href="http://www.getpostman.com/">Postman</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUmVsM3V6djMzYmc">WebJars. jQuery and JavaScript frameworks</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcHRFZHRkcTRFTEU">6_ webjars.patch</a>**

        УБРАЛ из проекта http://dandelion.github.io обертку к datatables. Причины:
          не встречал нигде, кроме Spring Pet Clinic;
          привязан к старому (legacy) API datatables;
          поддержка работы с datatables через Dandelion оказалось гораздо более трудоемкое, 
          чем работа с плагином напрямую. 
   
-  Подключение веб ресурсов. <a href="http://www.webjars.org/">WebJars</a>.
-  <a href="http://www.jamesward.com/2012/04/25/introducing-webjars-web-libraries-as-managed-dependencies">Introducing WebJars</a>
-  <a href="https://ru.wikipedia.org/wiki/Document_Object_Model">Document Object Model (DOM)</a>
-  <a href="https://css-tricks.com/dom/">What is the DOM?</a>
-  <a href="https://ru.wikipedia.org/wiki/JQuery">jQuery</a>
-  <a href="http://stackoverflow.com/questions/7062775/is-jquery-a-javascript-library-or-framework">Is jquery a javascript library or framework</a>
-  <a href="https://www.datatables.net/">DataTables</a>
-  <a href="http://www.sitepoint.com/working-jquery-datatables/">Working with jQuery DataTables</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFNXJmeTZBbmduaU0">Bootstrap</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdG5TdWc2V3NCX2s">7_ bootstrap.patch</a>**
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFTVduaXhPWnl5T0U">icon-meal.png</a>**
> В патч картинки не берутся, положить вручную icon-meal.png в \src\main\webapp\resources\images\icon-meal.png

-  <a href="http://getbootstrap.com/getting-started/">Подключаем Bootstrap</a>. Форматируем JSP.
-  <a href="http://www.tutorialrepublic.com/twitter-bootstrap-tutorial/">Twitter Bootstrap Tutorial</a>
-  <a href="http://www.w3schools.com/bootstrap/">Bootstrap 3 Tutorial</a>
-  <a href="https://www.youtube.com/playlist?list=PLypd1VrGv7FPokhw3f5pwBQTHsU9T2mBq">Видео: уроки по Bootstrap 3</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYjhIVDNkallsTTQ">AJAX. Datatables. jQuery</a>
>  JSP полезны, если надо с сервера отдать статический html с серверной логикой (условия, циклы), сформированный на основе модели. 
Для динамической отрисовки таблицы мы будем использовать REST и JSON на 9м уроке (работа с datatables через Ajax).

-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYUhZdlZkTURTNE0">8_ ajax_ datatables.patch</a>**
-  <a href="https://ru.wikipedia.org/wiki/AJAX">AJAX</a>. 
-  Событие $(document).ready. Запросы ajax. Обратный вызов (Callback).
-  <a href="http://anton.shevchuk.name/jquery/">jQuery для всех</a>.
-  <a href="http://anton.shevchuk.name/javascript/jquery-for-beginners-ajax/">jQuery для начинающих. AJAX</a>.
-  <a href="http://anton.shevchuk.name/javascript/jquery-for-beginners-selectors/">jQuery для начинающих. Селекторы</a>.
-  <a href="http://api.jquery.com/">jQuery API</a>
-  Редактирование таблицы на основе <a href="http://getbootstrap.com/javascript/#modals">модального окна Bootstrap</a>. 
-  <a href="http://bootstrap-ru.com/203/javascript.php">Javascript плагины для Bootstrap</a>
-  <a href="http://datatables.net/reference/api/">DataTables API</a>


##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFMTVWaXdWRUZsUEE"> Notifications</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFV0tobldvY2hKdkU">9_ notification.patch</a>**
-  Обработка ajaxError. <a href="http://ned.im/noty/">jQuery notification</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFRVkzcFMwc0hrYmM">Добавление Spring Security</a>  
>  Правка к видео: путь в intercept-url должен быть полный - pattern="/rest/admin/**"

>  В Spring Security 4.x по умолчанию включен csrf. Будем его проходить на 10м занятии.  

-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFOURIYld2WWNvUUk">10_ add_ security.patch</a>**

-  <a href="http://projects.spring.io/spring-security/">Spring Security</a>

-  <a href="https://ru.wikipedia.org/wiki/Протокол_AAA">Протокол AAA</a>
-  <a href="https://ru.wikipedia.org/wiki/Аутентификация_в_Интернете">Методы аутентификации</a>.
-  <a href="https://en.wikipedia.org/wiki/Basic_access_authentication">Basic access authentication</a>

-  <a href="http://articles.javatalks.ru/articles/17">Использование ThreadLocal</a>

-  Добавляем в проект spring-security и security filter
-  Конфигурируем security context для ресурсов и REST
-  Тестируем Security REST через SoapUI/ curl/ Postman
```
curl -H 'Authorization: Basic dXNlckB5YW5kZXgucnU6cGFzc3dvcmQ=' http://localhost:8080/topjava/rest/profile/meals
```

## Домашнее задание HW08
    Перевести mealList на datatables (mealList.jsp, UserMealAjaxController).

    Реализовать добавление записи еды через модальное окно Bootstrap и удаление/добавление еды по ajax
    (без редактирования).
    
    При вставке данных по AJAX пропадает все JSP форматирование, 
                                        чинить перерисовку НЕ надо: отрисовываем таблицу через jsp.
    Следующий урок- будем делать datatable по AJAX и форматирование на стороне клиента.

Optional.

    Реализовать enable/disable User через checkbox в userList.jsp с сохранением в DB
    
    Перевести работы фильтра на AJAX (при обновлении данных таблицы учитывать поля формы фильтрации).
    Попробуйте после модификации таблицы (например добавлении записи) обновлять ее также с учетом фильтра.
       
    Перейти на новый dataTables API (https://www.datatables.net/reference/api/)
    
    Избавиться от дублирования id="${user.id}" в строках таблиц users и meals (переместить id в строку tr)
             (id должно быть уникальным: http://pyramidin.narod.ru/html401/global.html#h-7.5.2)

Ресурсы

- <a href="http://stackoverflow.com/questions/25207147/datatable-vs-datatable-why-is-there-a-difference-and-how-do-i-make-them-w">dataTable() vs. DataTable()</a>
- <a href="https://www.datatables.net/reference/api/">dataTables API</a>

## Ваши вопросы
> Что делает код?
```
$('.delete').click(function () {
        deleteRow($(this).attr("id"));
    });
```

На все элементы DOM с классом delete вешается обработчик события click который вызывает функцию deleteRow. Классы в html разделяются через пробел.

> тянет ли bootstrap за собой jQuery?

Bootstrap зависит от jQuery: http://stackoverflow.com/questions/14608681/can-i-use-twitter-bootstrap-without-jquery#answer-14608772

> А где реально этот путь "classpath:/META-INF/resources/webjars? Т.е. начиная от положения пакета, выходит?

Внутри подключаемых webjars ресурсы лежат по пути /META-INF/resources/webjars/... Не поленитесь посмотреть на них через Ctrl+Shift+N.
Все подключаемые jar попадают в classpath и ресурсы доступны по этому пути.

> У меня она лежит внутри ".m2\repository\org\webjars\". С чем это может быть связано?

Maven скачивает все депенденси в local repository, который по умолчанию находится в ~/.m2.
Каталог по умолчанию можно переопределить в APACHE-MAVEN-HOME\conf\settings.xml, элемент localRepository.

> WEBJARS лежат вообще в другом месте WEB-INF\lib*. Биндим mapping="/webjars/*" например на реальное положение jar в ware, откуда spring знает где искать наш jquery ?

В war в `WEB-INF/lib/*` лежат все jar, которые попадают к classpath. Spring при обращении по url `/webjars/` ищет по пути биндинга `<mvc:resources mapping="/webjars/ " location="classpath:/META-INF/resources/webjars/"/>`
по всему classpath (то же самое как распаковать все jar в один каталог) в META-INF/resources/webjars/. В этом месте во всех jar, которые мы подключили из webjars лежат наши ресурсы.

> Как можно в браузере сбросить введенный пароль базовой авторизации?

Проже всего делать новый запрос в новой анонимной вкладке (Ctrl+Shift+N в Chrome)
