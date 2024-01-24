Данилов Я.И КНМО-101
# Указания к папке RLE:
```
rle.js - основной файл с кодом
input.txt - файл, из которого берётся исходный материал для кодирования
code.txt - файл, в который записывается закодированная строка
decode.txt - файл, в который записывается декодированная строка
```
## Исполнительные команды:
Запуск кодирования через терминал
```
node .\rle.js code .\input.txt .\code.txt 
```
Запуск декодирования через терминал
```
node .\rle.js decode .\code.txt decode.txt
```
# Указание к папе Entropy:
Код выводит Энтропию Шенона для заданной строки.
## Запуск алгоритма через терминал:
```
node .\Education_JS\Entropy\entropy.js abrakadabra
```
В примере abrakadabra - заданная строка.
# Указание к папе Huffman:

# Указание к папе Hemming:
Программа представляет собой одностраничный сайт, в который встроен алгоритм Хемминга. Можно ввести какое-то сообщение из 4-х бит(состоящее из 1 и 0) и получить его в закодированном формате.
Также можно проверить какое-то сообщение на верность. Если в сообщении есть ошибки, то алгоритм выведет верный вариант сообщения и укажет, где была ошибка.
# Указание к папке Dijkstra_Algorithm:
В алгоритме реализована правая ассоциативность степеней - то есть, если во входной строке будет: "2 ^ 3 ^ 2" - Ответ будет равен 512
## Запуск алгоритма через терминал:
1. Для корректного выполнения алгоритма необходимо прописывать все символы через пробел(как в примере)
2. Выражение нужно обязательно помещать в ковычки(как в примере)
### Пример команды:
```
node .\Education_JS\Dijkstra_Algorithm\Dextra.js "1 + 2 * ( 4 / 2 ) ^ 2 ^ 3 - 1"
```
