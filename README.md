## **Описание Yatube API:**
1) Получение списка всех публикаций.

2) Получение публикации по id.

3) Создание новой публикации.

4) Обновление публикации по id.

5) Частичное обновление публикации. 

6) Удаление публикации по id. 

7) Получение комментариев к публикации.

8) Добавление комментария к публикации.

9) Получение комментария к публикации по id.

10) Обновление комментария к публикации по id. 

11) Частичное обновление комментария к публикации по id. 

12) Удаление комментария к публикации по id. 

13) Получение списка доступных сообществ.

14) Получение информации о сообществе по id.

15) Получение всех подписок пользователя, сделавшего запрос. 

16) Подписка пользователя, от имени которого сделан запрос на пользователя переданного в теле запроса. 

17) Получение JWT-токена.

18) Обновление JWT-токена.

19) Проверка JWT-токена.

# Как запустить проект:
1) Клонировать репозиторий и перейти в него в командной строке:
git clone https://github.com/AnnSonrisa/api_final_yatube.git

2) Cоздать и активировать виртуальное окружение:
python -m venv venv

source venv/Scripts/activate

3) Установить зависимости из файла requirements.txt:
python -m pip install --upgrade pip

pip install -r requirements.txt

4) Выполнить миграции:
python3 manage.py migrate
