# ДОМАШНЯЯ РАБОТАПО КОНФИГУРАЦИОННОМУ УПРАЛВЛЕНИЮ №1 ЧУМАКОВ С.Ю. ИКБО-43-23 #

# SHELL EMULATOR #

Вариант №30: Разработать эмулятор для языка оболочки ОС. Необходимо сделать
работу эмулятора как можно более похожей на сеанс shell в UNIX-подобной ОС.
Эмулятор должен запускаться из реальной командной строки, а файл с
виртуальной файловой системой не нужно распаковывать у пользователя.
Эмулятор принимает образ виртуальной файловой системы в виде файла формата
tar. Эмулятор должен работать в режиме CLI.

**1. ОБЩЕЕ ОПИСАНИЕ.**
Этот проект представляет собой эмулятор командной строки, реализованный на
Python, который позволяет пользователю выполнять базовые команды файловой
системы, такие как ls, cd, du, и find. Эмулятор работает с виртуальной файловой
системой, распакованной из архива .tar, и сохраняет журнал действий в формате
JSON. Также включены тесты для проверки правильности работы функций
эмулятора.

