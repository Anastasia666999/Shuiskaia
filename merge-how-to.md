Инструкция по слиянию веток...
Перейти в основную ветку (main):
bash

git checkout main
Обновить основную ветку с сервера:
bash

git pull origin main
Создать или переключиться на ветку друга (surname):
bash

git checkout -b surname origin/surname
# или
git checkout surname
Вернуться в основную ветку:
bash

git checkout main
Объединить ветку друга в main:
bash

git merge surname
Отправить изменения на сервер:
bash

git push origin main