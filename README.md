# myvshell
____
## Эмулятор командной строки
____
*Разработать эмулятор командной строки vshell. В качестве аргумента vshell принимает образ файловой системы известного формата (tar, zip).*

*Обратите внимание: программа должна запускаться прямо из командной строки, а файл с виртуальной файловой системой не нужно распаковывать у пользователя. В vshell должны поддерживаться команды pwd, ls, cd и cat. Ваша задача сделать работу vshell как можно более похожей на сеанс bash в Linux. Реализовать vshell можно на Python или других ЯП, но кроссплатформенным образом.*
____
### Список комманд:
* **pwd** - выводит путь, где мы сейчас находимся
* **cat** + {аргумент} - выводит содержимое файла (аргумента)
* **cd** + {аргумент} - переходит в указанную директиву
* **ls** - выводит список файлов и папок в текущей директиве
