# Инструкция по работе с удаленными репозиториями

**Удаленный (иногда говорят "внешний")** репозиторий – это версии вашего проекта, сохраненные на удаленном сервере. Доступ к репозиторию на таком сервере может осуществляться по интернету или по локальной сети.

*Удаленный репозиторий* – полноценный репозиторий, ничем не отличающийся от локального. У удаленного репозитория есть собственные ветки, собственный указатель **HEAD**, своя история коммитов и так далее.

Если мы подключим удаленный репозиторий к своему локальному, то у нас появятся копии всех ссылочных объектов удаленного репозитория. То есть, например, у удаленного репозитория есть ветка **main**, а у нас будет копия этой ветки – **origin/main**. Все такие ссылочные объекты (указатели, ветки и теги) удаленного репозитория хранятся почти там же, где и у локального – в директории **.git/refs/remotes/<имя_удаленного_репозитория>.**

*Таким образом*, чтобы стать полноценным пользователем Git, важно овладеть навыками работы с удаленным репозиторием. Среди них – создание новых и копирование к себе уже существующих удаленных репозиториев, загрузка на сервер локальных коммитов и скачивание изменения с сервера. Давайте изучим все это по порядку.
