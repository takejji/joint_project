Добавление проекта

git remote add origin https://github.com/takejji/joint_project.git
git branch -M main
git push -u origin main


установка и запуск вирутального окружения (venv):

pip -m venv venv


затем 

venv/Scripts/activate


--установка пакетов питона из файла--
pip install -r requirements.txt


--обновление баз данных--
python manage.py make migrations - создать миграции (всех БД)
python manage.py migrate - добавить все таблицы проекта


--запуск сервера--
python manage.py createsuperuser - создать админа
-- username - admin
-- email - скип
-- password - admin
ввод "y" для продолжения

python manage.py runserver - запуск сервера
