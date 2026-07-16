Створіть в своєму середовищі новий каталог з назвою "new-project".
Перейдіть до каталогу "new-project".
Ініціалізуйте новий публічний Git-репозиторій всередині каталогу "new-project".
Створіть новий файл з назвою "README.md" і додайте до нього початковий текст.
Підготуйте файл "README.md" до коміту.
Закомітьте зміни у репозиторій з коміт повідомленням “init”.
Створіть нову гілку з назвою "development" і перейдіть до неї.
Додайте інструкцію до файлу "README.md" і підготуйте їх до коміту.
Закомітьте зміни у гілці "development" з повідомленням у форматі Smart Commit (див. інструкцію https://support.atlassian.com/jira-software-cloud/docs/process-issues-with-smart-commits/#Smart-Commit-commands) .
Об'єднайте зміни з гілки "development" у гілку "main".
Перевірте статус, переконайтеся, що все актуально.
Закомітьте зміни

1.  mkdir new-project && cd new-project
2.  git init
3.  touch README.md
4.  git remote add origin https://github.com/ogoncharenko32/new-project.git
    git branch -M main
5.  git add README.md
6.  git commit -am "init"
7.  git push -u origin main
8.  git branch development
9.  git checkout development

10. Edit README.md file and commit with message: "PROM-42164 #comment step-by-step instructions is added"
