# windows-file-duplicates-mover

Очень простой скрипт на Powershell, который находит дубликаты файлов в папке и удаляет их.
Нужно поместить скрипт в папку с файлами и в контекстном меню выбрать "Выполнить с помощью PowerShell".

Скрипт проверит все файлы, сравнит их размеры и, при равенстве размеров, сравнит md5-суммы. Если и размер, и контрольная сумма совпадают, то останется файл с наименьшей длиной названия, а все его дубликаты будут перемещены в корзину.

