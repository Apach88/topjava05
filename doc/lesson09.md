# Занятие 9 онлайн проекта <a href="https://github.com/JavaWebinar/topjava05">Topjava</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFVWRGbEw1RjJrMjg">Материалы урока</a>

**Браузер кэширует javascript и css. Если изменения не работают, обновите приложение в браузере по Ctrl+F5**

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFb0JKbElkT000amM">HW8</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFd1J2YkU1cFhHU2c">1_ HW8.patch</a>**
> Поправка к видео: в гриде 12 колонок

- <a href="http://getbootstrap.com/css/#grid">Grid system</a>
- <a href="http://getbootstrap.com/css/#description">Bootstrap description</a>
- <a href="http://getbootstrap.com/css/#forms">Bootstrap forms</a>

> При удалении файлов не забывайте делать clean:
```mvn clean package```

###  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFV0VKY2FGbndGMTQ">HW8 Optional (enable/disable user)</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFSERtMmtYd2pWYWM">2_ HW8_ enable_ disable.patch</a>**

###  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFMFJGLV9SaFBpQVE">HW8 Optional (new API, remove duplicate ids)</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdUZPS2dEcGE1Zk0">3_ HW8_ newApi_ rowId.patch</a>**
-  <a href="https://datatables.net/upgrade/1.10-convert">Converting parameter names for 1.10</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYlRkc2NGRGVydk0">Spring Binding</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFOXZtNGJnM1hvQzQ">4_ binding.patch</a>**

>  Move `ru.javawebinar.topjava.util.UserMealsUtil.DEFAULT_CALORIES_PER_DAY` to `ru.javawebinar.topjava.util.UserUtil`

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFd2ZvcS1pSjdMQlU">Реализация update</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFWjI2bmNfR3ZUc00">5_ update.patch</a>**

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLXp5MTFDMEY5WFE">Spring Validation</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUDZJdHN1bjhTVjg">6_ validation.patch</a>**
-  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/validation.html#validation-beanvalidation">Spring Validation.</a>
-  <a href="http://beanvalidation.org/">Bean Validation</a>
-  <a href="https://spring.io/blog/2012/08/29/integrating-spring-mvc-with-jquery-for-validation-rules">Валидация формы по AJAX.</a>
-  <a href="http://stackoverflow.com/questions/14730329/jpa-2-0-exception-to-use-javax-validation-package-in-jpa-2-0#answer-17142416">JSR-303, 349</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcW1qeTVFdS1BdHM">Перевод DataTables на Ajax</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFZHcwNzc4NXg5bm8">7_ datatable_ via_ ajax.patch</a>**

>   Рефакторинг DataTable API в updateTableByData.

-  <a href="http://legacy.datatables.net/usage/options">DataTables Options</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUmhUTms1WnhTeHc">Форма логина / логаут.</a>
    Вопросы:
      Почему при логине как admin еда отдаются для user?
      Почему при логине как user не отображается список пользователей?
      Почему еда не редактируется и не удаляется?

-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFd3ZoV18xbld2elE">8_ min_ form_ login.patch</a>**
-  <a href="http://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/#ns-minimal">Минимальный form-login</a>
-  <a href="http://docs.spring.io/spring-security/site/migrate/current/3-to-4/html5/migrate-3-to-4-xml.html#m3to4-xmlnamespace-form-login">Migrating &lt;form-login&gt;</a>

-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFX3Rub01HUW9fRWs">9_ jsp_ form_ login.patch</a>**
-  <a href="http://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/#ns-form-and-basic">Собственный form-login</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYTA4aVN4bWxzbEU">Реализация собственного провайдера авторицазии.</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdW9Yb2M2dkNYZ1U">10_ auth_ via_ user_ service.patch</a>**
>  Изменения в проекте: вместо `LoggedUser implements UserDetails` сделал `LoggedUser extends org.springframework.security.core.userdetails.User`

-  <a href="http://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/#userdetailsservice-implementations">UserDetailsService Implementations</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFT2Qya2V4N0kzWWM">Принцип работы Spring Security. Проксирование.</a>
-  <a href="http://www.spring-source.ru/articles.php?type=manual&theme=articles&docs=article_07">Принцип работы Spring Security</a>
-  <a href="http://docs.spring.io/spring/docs/current/spring-framework-reference/html/aop.html#aop-proxying">Типы проксирования</a>
-  <a href="http://samolisov.blogspot.ru/2010/04/proxy-java.html">Dynamic Proxy API</a>
-  <a href="http://stackoverflow.com/questions/13977093/how-to-use-jparepositories-with-proxy-target-class-true/25543659#25543659">Конфликт проксирования Data Repository</a>
-  <a href="http://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/#filter-stack">Security фильтры</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFU3hMR0o4eGNoUmc">Spring Security Test</a>
-  **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFLXZrMDJBSE8wSnM">11 spring security test.patch</a>**
>   Поправил RootControllerTest.

-  <a href="http://docs.spring.io/spring-security/site/docs/4.0.x/reference/htmlsingle/#test">Spring Security Test</a></h3>
-  <a href="http://docs.spring.io/spring-security/site/docs/4.0.x/reference/htmlsingle/#test-mockmvc">Интеграция со Spring MVC Test</a>
-  <a href="http://docs.spring.io/spring-security/site/docs/4.0.x/reference/htmlsingle/#testing-http-basic-authentication">HttpBasic авторизация</a>
-  <a href="http://habrahabr.ru/post/171911/">Тестирование контроллеров с помощью MockMvc (без spring-security-test)</a>

##  <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUzNFanF6MGZGNHc">Cookie. Session.</a>
-  <a href="https://ru.wikipedia.org/wiki/HTTP_cookie">HTTP cookie</a></h3>
-  <a href="http://stackoverflow.com/questions/595872/under-what-conditions-is-a-jsessionid-created">Under what conditions is a JSESSIONID created?</a>
-  <a href="http://halyph.com/2014/08/how-to-disable-tomcat-session.html">Tomcat Session Serialization</a>

## Домашнее задание HW9

    Реализовать для meal Binding/ Update/ Validation.
    Перевести mealList.jsp на работу по ajax. Стиль записи таблицы сделать в зависимости от exceeded.
    Починить meals тесты

Optional

    Подключить datetime-picker

Ресурсы

- <a href="http://xdsoft.net/jqplugins/datetimepicker/">DateTimePicker jQuery plugin</a>

## Ваши вопросы:

> В UserMealRestControllerTest нам нужны калории обязательно для LoggedUser?

В тестах контроллера мы:
- заполняем правильно header креденшелами для базовой авторизации через userHttpBasic
- выполняем запрос
- поднятое тестами приложение авторизует юзера и заполняет LoggedUser
- выполняет запрос и возвращает ответ для залогиненного юзера
- авторизационный фильтр чистит свой контекст, LoggеdUser safeGet() возвратит null.

Поэтому в тестах getCaloriesPerDay берите у тестового юзера, которым авторизовалась.

## Подсказки по HW09

- Чтобы поле dateTime сбиндилось в UserMeal кроме аннотации нужно изменить в форме name="datetime" на "dateTime" 
- Если не работает `datepicker()` проверьте - подключен ли `jquery.dataTables.min.js` в mealList.jsp? Можно посмотреть из браузера по Ctrl+U и кликнуть ссылку на скрипт- должен открыться скрипт.
