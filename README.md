# Практическое занятие 1
# Шишков Алексей Дмитриевич ЭФМО-02-21

## Цель
Развернуть рабочее окружение Go на Windows, создать минимальный HTTP-сервис на net/http, подключить и использовать внешнюю зависимость, собрать и проверить приложение.

## Задание
- Установить Go и Git, проверить версии.
- Инициализировать модуль Go в новом проекте.
- Реализовать HTTP-сервер с маршрутами /hello (текст) и /user (JSON).
- Подключить внешнюю библиотеку (генерация UUID) и использовать её в /user.
- Запустить и проверить ответы curl/браузером.
- Собрать бинарник .exe и подготовить README и отчёт.

## Проверка версий git и go
<img width="419" height="33" alt="изображение" src="https://github.com/user-attachments/assets/f8e282bd-e840-4ff0-ae68-3d25de3a3929" />
<img width="477" height="31" alt="изображение" src="https://github.com/user-attachments/assets/4a504a61-9f94-4da5-b6e6-fb15eb085480" />

## Запуск
### 1. Клонировать репозиторий
git clone https://github.com/Alex171228/helloapi.git  
cd helloapi  
### 2. Установить зависимости
go get github.com/google/uuid@latest  
go mod tidy  

### 3. Запустить сервер
Зайти в папку /helloapi и выполнить go run ./cmd/server
# Структура проекта:
<img width="302" height="225" alt="изображение" src="https://github.com/user-attachments/assets/675b4578-9b6f-46bd-8991-c9345fdf01a2" />

# Доступные запросы и результат их выполнения:

<img width="1187" height="299" alt="изображение" src="https://github.com/user-attachments/assets/98695f9e-2ea5-4c3b-84c2-0f892cb039da" />

<img width="1262" height="324" alt="изображение" src="https://github.com/user-attachments/assets/bb856bfa-d0c7-4d0d-8215-182885bf9f76" />
<img width="1375" height="389" alt="изображение" src="https://github.com/user-attachments/assets/f8ab6b5f-96bb-46e8-8182-9e9b4e9a5c07" />




