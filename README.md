JSON
 1. Создать внешний репозиторий c названием JSON Создаем внешний репозиторий на сайте с названием "JSON"
 2. Клонировать репозиторий JSON на локальный компьютер. - git clone https://github.com/ViktorNikolaev88/JSON.git

 3. Внутри локального JSON создать файл “new.json”. - touch new.json 
 4. Добавить файл под гит git add new.json
 5. Закоммитить файл. git commit -m "new json file"
 6. Отправить файл на внешний GitHub репозиторий git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 $ cat > new.json
{
  "initials":[
    {

       "name":"Viktor",
       "Surname":"NIkolaev",
       "Patronymic":"Mihailovich"
    }
  ],
   "age":34,
   "pet_quantity": 2,
   "wanted_salary":500
} 
 8. Отправить изменения на внешний репозиторий. - git add new.json git commit -m "data" -git push
 9. Создать файл preferences.json - touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. 
 cat > preferences.json
{
  "favourite_film":"Terminator_2",
  "favourite_series":"LOST",
  "favourite_food":"potato",
  "favourite_season":"winter",
  "wanted_country_to_visit":"USA"
}
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 cat > skills.json
{
  "Skills": [
    {
      "first_skill": "Testing",
      "second_skill": "Bug_report",
      "third_skill": "Regression testing",
      "fourth_skill": "Black_box_testing",
      "fifth_skill": "Quality_control",
      "six_skill" : "Exploratory testing"
    }
  ]
}
 12. Отправить сразу 2 файла на внешний репозиторий.
 git add . git commit -m "commit two json files" git push
 13. На веб интерфейсе создать файл bug_report.json.  кнопка Add file затем нажать Create new file
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе. Вввести имя файла - сохранить изменения (нажать Commit canges)
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 {
  "Mobile_bug 13":[
    {

       "Environment":"Iphone 12 mini Safari 16.2",
       "Title":"При смене ориентации экрана с горизогнтальной на вертиальную и обртано едет верстка элемента [onetrust-banner-sdk]",
       "Steps":"1. Перейти на сайт https://capital.com 2. Сменить  положение утсройства с вертикального на гоаризонтальное",
       "Expected_result":"При смене ориентации экрана с горизогнтальной на вертиальную и обртано  верстка элемента [onetrust-banner-sdk] подстравается под ориентацию экрана",
       "Actual_result":"При смене ориентации экрана верстка элемента onetrust-banner-sdk едет, текст баннера заслоняет конпки"
    }
  ]
}
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. сохранить изменения (нажать Commit canges)
 17. Синхронизировать внешний и локальный репозиторий JSON - git pull
