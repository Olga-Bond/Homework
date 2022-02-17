TXT
 1. Создать внешний репозиторий c названием TXT === link new
 2. Клонировать репозиторий TXT на локальный компьютер === git clone ссылка
 3. Внутри локального TXT создать файл "new.txt"  === touch new.txt
 4. Добавить файл под гит === git add new.txt
 5. Закоммитить файл === git commit -m "текст"
 6. Отправить файл на внешний GitHub репозиторий === git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT === vim new.txt

Bondar Olga Gennadievna
34 years old
I have one cat and two dogs
The desired salary is 50,000 rubles

 8. Отправить изменения на внешний репозиторий === git add . === git commit -m "текст" === git push
 9. Создать файл preferences.txt === touch preferences.txt
 10. В файл preferences.txt  добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT === vim preferences.txt

My favorite movie is "Titanic"
Favorite TV series "Deceive me"
Favorite food : Ice Cream
Favorite time of the year : Spring
I want to visit  USA

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT === cat > skills.txt
 12. Сделать коммит в одну строку === git add . ===  git commit -m "текст" 
 13. Отправить сразу 2 файла на внешний репозиторий === git push
 14. На веб интерфейсе создать файл bug_report.txt === link add file === link create new file
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе === link commit new file
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT === link edit this file

Heading
Summary: error 500
Project: Yandex.ru
Component: Email registration page
Version: 22.1.4.627 beta
Severity: Blocker
Priority: High
Steps to Reproduce
Actual Result : page lock
Expected Result: opening a page
Additional Information
Attachments

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе ===  link Commit changes
 18. Синхронизировать внешний и локальный репозиторий TXT === git pull


JSON
 1. Создать внешний репозиторий c названием JSON === link new
 2. Клонировать репозиторий JSON на локальный компьютер ===  git clone ссылка
 3. Внутри локального JSON создать файл "new.json" === touch new.json
 4. Добавить файл под гит ===  git add new.json
 5. Закоммитить файл ===  git commit -m "текст"
 6. Отправить файл на внешний GitHub репозиторий === git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON === vim new.json
{
  "last_name":"Olga",
  "first_name":"Bondar",
   "age":34,
   "number_of_pets":3,
   "future_desired_salary":50000
}
 
 8. Отправить изменения на внешний репозиторий === git add . === git commit -m "текст" === git push
 9. Создать файл preferences.json === touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна,  которую хотели бы посетить) в формате JSON === vim preferences.json
{
  "favorite_movie":"Titaniс",
  "favorite_TV_series":"Deceive_me",
  "favorite_food":"Ice_cream",
  "favorite_time_of_the_year":"Spring",
  "country":"USA"
}

 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON === vim skills.json
{
     "skill1":"Postman",
     "skill2":"Charles",
     "skill3":"Fiddler",
     "skill4":"Dev_Tools",
     "skill5":"Android Studio",
     "skill6":"Git Bash",
     "skill7":"Github",
     "skill8":"SQL",
     "skill9":"Postgres",
     "skill10":"Redis",
     "skill11":"Jmeter",
     "skill12":"Python",
     "skill13":"Json",
     "skill14":"Xml"
}

 12. Отправить сразу 2 файла на внешний репозиторий === git add . === git commit -m "текст" === git push
 13. На веб интерфейсе создать файл bug_report.json === link add file === link create new file
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе === link commit new file
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON === link edit this file

{   
      "Summary":"error_500",
      "Project":"Yandex_ru",
      "Component":"Email_registration_page",
      "Version":"22_1_4_627_beta",
      "Severity":"Blocker",
      "Priority":"High",
      "Steps_to_Reproduce":"Steps",
      "Actual_Result":"Page_lock",
      "Expected_Result":"Opening_a_page",
      "Additional_Information":"Other",
      "Attachments":"Other"
}

 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе === link Commit changes
 17. Синхронизировать внешний и локальный репозиторий JSON === git pull


XML
 1. Создать внешний репозиторий c названием XML. === link new
 2. Клонировать репозиторий XML на локальный компьютер. ===  git clone ссылка
 3. Внутри локального XML создать файл “new.xml”. ===  touch new.xml
 4. Добавить файл под гит. === git add new.xml
 5. Закоммитить файл. ===  git commit -m "текст"
 6. Отправить файл на внешний GitHub репозиторий. === git push
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. === nano new.xml

<?xml version ="1.0"?>
   <user>
    <first_name>Olga</first_name>
    <last_name>Bondar</last_name>
    <age>34</age>
    <pets>3</pets>
    <salary>50000</salary>
   </user>
 
 8. Отправить изменения на внешний репозиторий. === git add . === git commit -m "текст" === git push
 9. Создать файл preferences.xml === touch preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна, которую хотели бы посетить) в формате XML. === nano preferences.xml

<?xml version ="1.0"?>
  <preferences>
   <favorite_movie>Titaniс</favorite_movie>
   <favorite_TV_series>Deceive me</favorite_TV_series>
   <favorite_food>Ice cream</favorite_food>
   <favorite_time_of_the_year>Spring</favorite_time_of_the_year>
   <country>USA</country>
  </preferences>

 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML === nano skills.xml

<?xml version ="1.0"?>
  <skills>
     <skill1>Postman</skill1>
     <skill2>Charles</skill2>
     <skill3>Fiddler</skill3>
     <skill4>Dev Tools</skill4>
     <skill5>Android Studio</skill5>
     <skill6>Git Bash</skill6>
     <skill7>Github</skill7>
     <skill8>SQL</skill8>
     <skill9>Postgres</skill9>
     <skill10>Redis</skill10>
     <skill11>Jmeter</skill11>
     <skill12>Python</skill12>
     <skill13>Json</skill13>
     <skill14>Xml</skill14>
  </skills>

 12. Сделать коммит в одну строку. === git add . === git commit -m "текст"
 13. Отправить сразу 2 файла на внешний репозиторий. === git push 
 14. На веб интерфейсе создать файл bug_report.xml. === link add file === link create new file
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. === link Commit new file
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. === link edit this file

<?xml version ="1.0"?>
   <bug_report>
      <Summary>error 500</Summary>
      <Project>Yandex.ru</Project>
      <Component>Email registration page</Component>
      <Version>22.1.4.627 beta</Version>
      <Severity>Blocker</Severity>
      <Priority>High</Priority>
      <Steps_to_Reproduce>Steps</Steps_to_Reproduce>
      <Actual_Result>Page lock</Actual_Result>
      <Expected_Result>Opening a page</Expected_Result>
      <Additional_Information>Other</Additional_Information>
      <Attachments>Other</Attachments>
   </bug_report>

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. === link Commit changes
 18. Синхронизировать внешний и локальный репозиторий XML === git pull
