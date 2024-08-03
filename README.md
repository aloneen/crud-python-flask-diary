# Mini Diary

Mini Diary is a Python Flask application for managing personal diary entries. This application includes features such as adding entries, deleting entries, and editing entries, all backed by a database.

## Features

- **Add Entry**: Users can add new diary entries.
- **Delete Entry**: Users can delete existing diary entries.
- **Edit Entry**: Users can edit existing diary entries.

## Requirements

- Python 3.7 or higher
- Flask
- Flask-SQLAlchemy
- Flask-Scss
- SQLite (or any other preferred database)

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/aloneen/crud-python-flask-diary.git
    cd crud-python-flask-diary
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Initialize the database**:
    ```sh
    flask db init
    flask db migrate
    flask db upgrade
    ```

5. **Run the application**:
    ```sh
    flask run
    ```

## Usage

1. Open your browser and go to `http://localhost:5000`.
2. Use the interface to add, delete, and edit diary entries.

## Contributing

Feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.





# Mini Diary

Mini Diary - это приложение на Python Flask для управления личными дневниковыми записями. Это приложение включает в себя функции добавления записей, удаления записей и редактирования записей, поддерживаемые базой данных.

## Функции

- **Добавление записи**: Пользователи могут добавлять новые дневниковые записи.
- **Удаление записи**: Пользователи могут удалять существующие записи.
- **Редактирование записи**: Пользователи могут редактировать существующие записи.

## Требования

- Python 3.7 или выше
- Flask
- Flask-SQLAlchemy
- Flask-Scss
- SQLite (или любая другая предпочтительная база данных)

## Установка

1. **Клонируйте репозиторий**:
    ```sh
    git clone https://github.com/aloneen/crud-python-flask-diary.git
    cd crud-python-flask-diary
    ```

2. **Создайте виртуальное окружение**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # На Windows используйте `venv\Scripts\activate`
    ```

3. **Установите зависимости**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Инициализируйте базу данных**:
    ```sh
    flask db init
    flask db migrate
    flask db upgrade
    ```

5. **Запустите приложение**:
    ```sh
    flask run
    ```

## Использование

1. Откройте браузер и перейдите по адресу `http://localhost:5000`.
2. Используйте интерфейс для добавления, удаления и редактирования дневниковых записей.

## Вклад

Не стесняйтесь отправлять вопросы и запросы на добавление изменений. Для крупных изменений, пожалуйста, сначала откройте вопрос для обсуждения того, что вы хотите изменить.

