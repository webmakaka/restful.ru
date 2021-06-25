---
layout: page
title: RESTful
permalink: /
---

# RESTful

Собственно, почти все что нужно знать.

<br/>

![Restful](/img/pic1.png 'Restful'){: .center-image }

<br/>

![Restful](/img/pic2.png 'Restful'){: .center-image }

<br/>

![Restful](/img/pic3.png 'Restful'){: .center-image }

<br/>

### Примеры RESTful реализации на:

<h3>
    <a href="/golang/">Golang</a> ||
    <a href="/python/">Python</a> ||
    <a href="/js/">Java Script (Node.js, Angular, etc.)</a> ||
    <a href="http://ws.javadev.ru">Java</a>
</h3>

<br/>
<br/>

### Работающие RESTFul сервисы для тестов:

<a href="https://restcountries.eu/rest/v2/all" rel="nofollow">REST Countries</a>

<a href="https://jsonplaceholder.typicode.com/" rel="nofollow">jsonplaceholder</a>

<br/>

### Получить человекочитаемый вывод от RESTFul сервисов

![Restful Python](/img/curl-python.png 'Restful Python'){: .center-image }

<br/>

```shell
$ curl \
    --data '{
        "firstCategory": 0
    }' \
    --header "Content-Type: application/json" \
    --request POST https://courses-top.ru/api/top-page/find \
    | jq
```

<br/>

jq в ubuntu можно доставить командой apt install.

<br/>

```shell
$ curl \
    --data '{
        "firstCategory": 0
    }' \
    --header "Content-Type: application/json" \
    --request POST https://courses-top.ru/api/top-page/find \
    | python -m json.tool
```

<br/>

json.tool - не понимает, кодировки русского языка и вроде как нет параметра, которым можно было бы это все легко поправить.

<br/>

### Лекция по Restfull на русском

<div align="center">
    <iframe width="853" height="480" src="https://www.youtube.com/embed/_EmcOWmstko" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br/>

**Буду признателен, за ссылки на проекты с реализацией RESTFul на разных языках.**

<br/>

**Marley** <br/>

![Marley](/img/a3333333mail.gif 'Marley')
