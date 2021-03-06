# Автоматическая подборка картинок и размещение в Instagram

## Как установить

Python3 должен быть уже установлен.
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

## Как работает скрипт

Репозиторий содержит три скрипта, работающих независимо друг от друга:
- fetch_spacex.py - скрипт скачивает фотографии последнего запуска SpaceX в директорию images/
- fetch_hubble.py - скрипт скачивает картинки из коллекции 'spacecraft' с сайта телескопа Хаббл в директорию images/
- space_as_space.py - скрипт закачивает картинку в аккаунт Space_as_space инстаграмм

Каждый скрипт запускается из командной строки:
```
python fetch_spacex.py
python fetch_hubble.py
python space_as_space.py
```

## Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
