# Проект "Kittygram"

[![Build Status](https://github.com/AdelKhakimov/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/AdelKhakimov/kittygram_final/actions)

Kittygram - социальная сеть для ваших котиков.

## Описание

Проект "Kittygram" представляет собой социальную сеть, созданную специально для любителей котиков. Здесь вы можете делиться фотографиями своих пушистых друзей, общаться с другими владельцами котов и находить новых друзей для ваших питомцев.

### Локальное развертывание

1. Клонируйте репозиторий:

    ```bash
    git clone https://github.com/AdelKhakimov/kittygram_final.git
    ```

2. Установите зависимости:

    ```bash
    # Пример для Python проекта с использованием pip
    pip install -r requirements.txt
    ```

3. Запустите приложение:

    ```bash
    # Пример для Django проекта
    python manage.py runserver
    ```

## Отличие между продуктивной и обычной версиями

Продуктивная версия предназначена для использования в боевых условиях и подключения к реальной базе данных, в то время как обычная версия может использоваться для разработки и тестирования с локальной базой данных.

## Настройка переменных окружения

Для корректной работы приложения рекомендуется создать файл `.env` в корне проекта и задать необходимые переменные окружения. Пример есть в файле .env.example.

## Ссылки

- **Развернутое приложение**: [Ссылка на развернутое приложение](https://kittygramadel.ddns.net/)
- **Workflow на GitHub**: [Статус Workflow](https://github.com/AdelKhakimov/kittygram_final/actions)

## Автор

- Адель Хакимов
- harso96@yandex.ru
- https://github.com/AdelKhakimov

## Используемые технологии

- Python
- Django
