Посмотреть где я === pwd

Создать папку === mkdir folder_1

Зайти в папку === cd folder_1

Создать 3 папки === mkdir s_1 s_2 s_3

Зайти в любую папку === cd s_1

Создать 5 файлов (3 txt, 2 json) === touch {app_1.txt,app_2.txt,app_3.txt,map_1.json,map_2.json}

Создать 3 папки === mkdir fut_1 fut_2 fut_3

Вывести список содержимого папки === ls -la

Открыть любой txt файл === vim app_1.txt

Написать туда что-нибудь, любой текст === i

Сохранить и выйти === esc :wq

Выйти из папки на уровень выше === cd ..

Переместить любые 2 файла, которые вы создали, в любую другую папку === mv s_1/{map_2.json,app_2.txt} s_1/fut_2/

Скопировать любые 2 файла, которые вы создали, в любую другую папку === cp s_1/{app_3.txt,map_1.json} s_1/fut_3

Найти файл по имени === find app_1.txt

Просмотреть содержимое в реальном времени (команда grep) изучите как она работает === tail -f app_1.txt | grep файл

Вывести несколько первых строк из текстового файла === head -n 3 app_1.txt

Вывести несколько последних строк из текстового файла === tail -n 3 app_1.txt

Просмотреть содержимое длинного файла (команда less) изучите как она работает === less app_1.txt

Вывести дату и время === date

Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request === curl http://162.55.220.72:5005/terminal-hw-request === curl "http://162.55.220.72:5005/get_method?name=Olga&age=34"

Написать скрипт, который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13 ===
 #!/bin/bash                                                                                                                                                                                                       
 cd folder_1                                                                                                                                                                                                     
 mkdir s_1 s_2 s_3                                                                                                                                                                                           
 cd s_1                                                                                                                                                                                                             
 touch {app_1.txt,app_2.txt,app_3.txt,map_1.json,map_2.json}                                                                                                                     
 mkdir fut_1 fut_2 fut_3                                                                                                                                                                                   
 ls -la                                                                                                                                                                                                                 
 C:/QA/folder_1/s_1/{map_2.json,app_2.txt} C:/QA/folder_1/s_1/fut_2/ 
