# 1. GIT
## Task:
<ol>
  <li>
    Создать сервер на nodejs, который будет возвращать простой html. Снаписанным кодом произвести pull request в свой репозиторий.
  </li>
  <li>
    Заполнить табличку “Фамилии-Репозитории".
  </li>
  <li>
    Создать рандомную issue к чужому репозиторию.
  </li>
</ol>

### Task №1
<p>
        Pull request - это запрос на интеграцию изменений из одной ветки в другую. Пул-реквесты позволяют разработчикам делиться внесенными в код изменениями с другими участниками одной системы. Это запрос на принятие изменений.
</p>
<ol>
        <li>
            <code>nvim server.js</code>. Туда прописываем код сервера.
        </li>
        <li>
            <code>git branch pulltest</code>. Создаем еще одну ветку.
        </li>
        <li>
            <code>git checkout pulltest</code>. Переключаемся на новую ветку.
        </li>
        <li>
            <code>git add .</code>. Добавляем файлы.
        </li>
        <li>
            <code>git commit -m "Simple Server"</code>. Коммитим
        </li>
        <li>
            <code>git push</code>. Но вылетит ошибка, потому что такой ветки еще нет на сервере. Поэтому пропишем <code>git push --set-upstream origin pulltest</code>.
        </li>
        <li>
            В Github переходим на нашу ветку и создаем там Pull request. Там кликаем Pull request.
        </li>
        <li>
            <code>git checkout main</code>. Переходим на нашу главную ветку.
        </li>
        <li>
            <code>git pull</code>. Сливаем все изменения.
        </li>
        <li>
            <code>git branch --delete pulltest</code>. Удаляем ветку со своего локального репозитория.
        </li>
</ol>
