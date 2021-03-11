# Rk01## Рубежный контроль №1 Шумилишский Богдан ИУ8-22

#Часть 1

##Задание 1
 `cd.. `</br> 
`cd /home/user`</br>
`cd ~/`
##Задание 2
` grep -v "<substring>"`
##Задание 3
```
mkdir /home/user/workspace
cd /home/user/workspace
nano test.txt
```
##Задание 4
`tar --create test.tar /home/user/workspace/test`
## 5
`grep -rl "aaa" | grep -l "bbb"`
##Задание 6
`find . maxdepth 1 -type d | wc`
##Задание 7
`sudo du -Sh / | sort -rh | head -10`

#Часть 2

## Задание 1
```
git init
git clone
```
## Задание 2
Закомитится версия, добавленная через git add
## Задание 3
Вливает patch1 в master:
```
git checkout master
git merge patch1
```
Вливает master в patch1:
```
git checkout patch1
git rebase mster
```
## Задание 4
Если два человека одновременно делают пуш, то один запушит, а другой получит ошибку

## Вопрос про cmake
Файл CMakeLists.txt
