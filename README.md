XML

 21. Создать внешний репозиторий c названием XML.
Git_XML

 22. Клонировать репозиторий XML на локальный компьютер.
git clone https://github.com/Amithehost/Git_XML.git

 23. Внутри локального XML создать файл “new.xml”.
cd Git_XML
touch new.xml

 24. Добавить файл под гит.
git add new.xml

 25. Закоммитить файл.
git commit -m "add first file"

 26. Отправить файл на внешний GitHub репозиторий.
git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
cat >> new.xml
<?xml version-"1.0"?>
<new>	
<Full name>Глот Ксения Васильевна</Full name> 
<Age>27</Age>
<Number of pets>1</Number of pets> 
<Future desired slary>1000</Future desired slary> 
</new>
CTRL+D

 28. Отправить изменения на внешний репозиторий.
git commit -am "changes xml file"

 29. Создать файл preferences.xml
touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

<?xml version-"1.0"?>
<preferences>
<favourite_movie>Black Knight</favourite_movie>
<Favourite_TV_show>Big Bang Theory</Favourite_TV_show>
<Favourite_food>Pasta</Favourite_food>
<Fouvorite_season>Summer</Fouvorite_season>
<Favourite_country>Ireland</Favourite_country>
</preferences>
CTRL+D

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
<?xml version-"1.0"?>
<skills>
<QA>Linux, Bash, Git, GitHub, API, HTTP/HTTPS, Web Testing, Mobile Testing, Proxy, VPN, SQL, JMeter</QA>
</skills>
CTRL+D

 32. Сделать коммит в одну строку.
git add . ; git commit -m "add skills and preferences"

 33. Отправить сразу 2 файла на внешний репозиторий.
git push

 34. На веб интерфейсе создать файл bug_report.xml.
Создать файл в GitHub

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Файл bug_report.xml закоммитить в GitHub

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

<?xml version-"1.0"?>
<bug_report>
<ID>aith-2727</ID>
<Title>Кнопка входа неактивна</Title>
<Preconditions>Открыть страницу https://ith.com , перейти в раздел входа в систему</Preconditions>
<STR>Заполнить валидными данными поля входа в систему и нажать кнопку вход</STR>
<ER>Вход успешно выполнен</ER>
<AR>Кнопка входа неактивна после выполнения всех необходимых полей входа в систему</AR>
<Attachments>screenshot.png</Attachments>
</bug_report>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сделать коммит файла bug_report.xml в GitHub

 38. Синхронизировать внешний и локальный репозиторий XML
git fetch
git pull
