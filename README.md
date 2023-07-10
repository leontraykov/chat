# README

ЧатЧат

Это приложение - чат, где пользователи могут создавать комнаты и обмениваться сообщениями в реальном времени. Это проект был разработан с использованием следующих технологий:

    Ruby on Rails 7.0.5.1, PostgreSQL, Hotwire Turbo & Stimulus, Rspec, Devise, Bootstrap 5

Функциональность

    - Создание и вход в комнаты для общения.
    - Обмен сообщениями в реальном времени.
    - Автоматическое обновление списка пользователей, чат-комнат и сообщений при появлении новых.
    - Очистка поля ввода после отправки сообщения.

Установка и Запуск

Сначала клонируйте репозиторий:

    git clone https://github.com/leontraykov/chat.git
    cd chat

Установите зависимости:

    bundle install
    yarn install

Сборка стилей:
    yarn build:css
    yarn build:js

Создайте базу данных и выполните миграции:

    rails db:create
    rails db:migrate

Запустите сервер:

    rails s

Теперь вы можете открыть приложение в браузере по адресу http://localhost:3000.
