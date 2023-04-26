# Інструкція для розробників
1. Створюємо в своєму середовищі новий каталог з назвою "new-project" та переходимо до нього:
  `mkdir new-project && cd new-project`
2. Ініціалізуєм новий публічний Git-репозиторій всередині каталогу "new-project":
  `git init`
3. Створюємо новий файл з назвою "README.md" і додаємо до нього початковий текст:
  `echo '# Інструкція для розробників' > README.md`
4. Готуємо файл "README.md" до коміту:
  `git add README.md`
5. Закомітемо зміни у репозиторій з повідомленням 'init':
  `git commit -s -m 'init'`
6. Створюємо нову гілку з назвою "development" і переходимо до неї:
  `git checkout -b development`
Додаємо інструкцію до файлу "README.md".
7. Готуємо файл "README.md" до коміту:
  `git add README.md`
8. Закомітемо зміни у гілці "development" з повідомленням про коміт 'Додали інстукцію у файл "README.md"':
  `git commit -s -m 'Додали інстукцію у файл "README.md"'`
9. Об'єднуємо зміни з гілки "development" у гілку "main":
  `git checkout main && git merge development`
10. Перевіяємо статус, щоб переконатися, що все актуально:
  `git status`
11. Закомітемо зміни:
  `git commit --allow-empty -s -m 'Об'\''єднали гілки "development" та "main"'`
12. Надсилаємо зміни до GitHub:
  `git push origin main`

# Developer Guide
1. Create a new directory in our environment called "new-project" and go to it:
  `mkdir new-project && cd new-project`
2. Initialize a new public Git repository inside the "new-project" directory:
  `git init`
3. Create a new file called "README.md" and add the initial text to it:
  `echo '# Інструкція для розробників' > README.md`
4. Prepare the "README.md" file for the commit:
  `git add README.md`
5. Let's commit changes to the repository with the message 'init':
  `git commit -s -m 'init'`
6. Create a new branch called "development" and go to it:
  `git checkout -b development`
Add instructions to the "README.md" file.
7. Prepare the "README.md" file for the commit:
  `git add README.md`
8. Let's commit the changes in the "development" branch with the commit message 'Додали інстукцію у файл "README.md"':
  `git commit -s -m 'Додали інстукцію у файл "README.md"'`
9. Merge changes from the "development" branch into the "main" branch:
  `git checkout main && git merge development`
10. Review the status to make sure that everything is up to date:
  `git status`
11. Let's notice the changes:
  `git commit --allow-empty -s -m 'Об'\''єднали гілки "development" та "main"'`
12. Send changes to GitHub:
  `git push origin main`
