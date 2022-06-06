# TXT

1. Создать внешний репозиторий c названием TXT.

![Screenshot_10](https://user-images.githubusercontent.com/91422609/172233026-e497eaec-516d-4768-a553-47a734f050c6.png)

![Screenshot_11](https://user-images.githubusercontent.com/91422609/172233067-00e4c8aa-ced0-4ecd-a4cf-7a300ddd1d3d.png)

 2. Клонировать репозиторий TXT на локальный компьютер.
 
 ```
 git clone https://github.com/OlesyaMashuk/TXT
 ```
 
 3. Внутри локального TXT создать файл “new.txt”.
  
 ```
 cd TXT
 touch new.txt 
 ```

 4. Добавить файл под гит.
 
 ``` git add . ```
 
 5. Закоммитить файл.
 
 ```
 git commit -m "commiting TXT file to our rep"
 ```
 
 6. Отправить файл на внешний GitHub репозиторий.
 
 ``` git push ```
 
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе 
 (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT..
 ```
vim new.txt
i
name Olesya
surname Mashukova
age 40
pets 1
salary 1500

esc :wg enter 
```

8. Отправить изменения на внешний репозиторий
```
git push
```
9. Создать файл preferences.txt
```
touch preferences.txt
```
10. В файл preferences.txt добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
```
vim preferences.txt
i
fav_movie Terminator
fav_TV_series 12 moments of sprin
fav_food Salad
fav_season Summer
countfy Iceland

esc :wq enter
```
11.  Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
``` 
vim skills.txt
i
skill_1 Terminal
skill_2 GitBash
skill_3 GitHub
skill_4 Postman
skill_5 API
skill_6 Test case
skill_7 Charles
skill_8 DevTools
skill_9 SQL	

esc :wq enter
```
 12. Сделать коммит в одну строку.
```
git add -A && git commit -m "Коммит в одну строку"

```
 13. Отправить сразу 2 файла на внешний репозиторий.
 ```
 git push
 ```
 14. На веб интерфейсе создать файл bug_report.txt.
 ```
 В репозитории TXT >> клик Add file >> клик Creat new file >> в Name your file пишу bug_report.txt
 ```
 ![Screenshot_12](https://user-images.githubusercontent.com/91422609/172238995-df884abf-9fff-4d49-83e3-6984bb0c4324.png)

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 после ввода названия файла внизу >> клик Commit new file
 ```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

 В репозитории TXT выбираем файл bug_report.txt >> клик на иконку карандаш

 
 ![Screenshot_5](https://user-images.githubusercontent.com/91422609/172230889-00cd2a2d-f554-4064-8a52-01684080c142.png)

 
 ```
 ID BR_1
 Title В поле 'Номер заказа' можно вводить любое количество цифр
 Steps
        Step_1 Зайти на главную страницу сайта
	Step_2 В поле 'Номер заказа' ввести слишком длинную строку 12345678901234567890465484512151212121212121218989
 Actual_result В поле можно вводить слишком длинные строки
 Expected_result В поле нельзя ввести слишком длинную строку, есть ограничение по количеству цифр
 ```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 внизу клик Commit changes
 ```
 18.  Синхронизировать внешний и локальный репозиторий TXT
 ```
 git pull
 ```
 
