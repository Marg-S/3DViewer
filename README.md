# 3DViewer
Разработана программа для визуализации каркасной модели в трехмерном пространстве.
## Описание
3DViewer - это программа, разработанная на языке Си стандарта C11, для визуализации каркасной модели в трехмерном пространстве. Программа поддерживает загрузку моделей из файлов формата obj, перемещение, поворот и масштабирование модели, а также настройку различных параметров отображения.
## Требования
Для компиляции и запуска программы требуется:
- Компилятор gcc
- Библиотеки: библиотека виджетов gtk4
## Установка
1. Склонируйте репозиторий:
```git clone ...```
2. Перейдите в папку с исходным кодом:
```cd 3DViewer```
3. Соберите программу с помощью Makefile:
```make all```
4. Запустите программу:
```~/3DViewer```
## Использование
После запуска программы откроется графический пользовательский интерфейс,
предоставляющий следующие возможности:
- Загрузка каркасной модели из файла формата obj.
- Перемещение, поворот и масштабирование модели.
- Настройка параметров отображения, таких как цвет ребер и вершин, толщина ребер и другие.
- Выбор цвета фона.
## Настройки
Настройки сохраняются между перезапусками программы, позволяя вам настроить параметры отображения по вашему вкусу.