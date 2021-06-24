# Shell trics

## edit shell input
```
export EDITOR=vim
```
CTRL-x-e откроет в **vim** то, что вводится в консоли 

## CTRL-r
поиск в истории команд

## CTRL-k
стереть до конца строки

## CTRL-u
стереть до начала строки

## CTRL-y
вернуть стёртое

## CTRL-w
стереть всё до пробела налево

## !!
вся предыдущая команда

## ALT-.
вставить последний аругмент

## reset
всё исправить, когда с переносами строки какая-то шляпа

## script
команда запускает логгер работы в консоли  
```
script -s myscript -t mytiming
```
Можно воспроизвести (показать), что происходило  
```
scriptreplay -s myscript -t mytiming
```