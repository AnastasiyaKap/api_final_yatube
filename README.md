**Описание проекта:**

Проект api_yatube - это API социальной сети Yatube, в которой можно создавать, удалять и комментировать посты. Подписываться на других авторах.

С помощью api_yatube можно запрашивать данные о постах, группах, комментариях в социальной сети Yatube, а также создавать новые.

**Как запустить проект:**
Клонировать репозиторий и перейти в него в командной строке:
git clone git@github.com:4kolesov/api_final_yatube.git

Cоздать и активировать виртуальное окружение:
python -m venv env
source env/Scripts/activate

Установить зависимости из файла requirements.txt:
python -m pip install --upgrade pip
pip install -r requirements.txt

В директории с файлом manage.py выполнить миграции:
python manage.py migrate

В директории с файлом manage.py запустить проект
python manage.py runserver
