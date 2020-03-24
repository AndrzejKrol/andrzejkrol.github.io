---
layout: post
title:  "Welcome to Jekyll!"
date:   2020-03-24 14:32:06 -0500
categories: [blog, travel]
excerpt: "asdkoaskdoaskdsoa"
---
#### Pomoc
```
man ps
ps --help
help ps
```
#### Przechodzenie wstecz
```
cd -
```
#### Find
```
find . -name '*.log'
```
#### Wyswietlanie rozmiaru
```
find . -name '*.log' -exec du -h {} \;
```
#### Locate operuje na snapshocie komenda updatedb reindeksuje ją
```
locate docker
```
#### Który exec zostanie wykonany
```
which docker
```
#### Poprzednia komenda
```
!!
date
!!
sudo !!
```
#### Reverse search
```
ctrl+r
wiele wyników naciskac ctrl+r dalej
```
#### Opis pliku
```
file readme.me
```
#### Diff
```
diff README.md  GainCapital.ChasingReturns.TradesListener.sln  --side-by-side --color
```
#### telnet
```
telnet www.google.com 433
GET / /HTTP/1.1
```
#### kopowanie
```
cp co gdzie
```
#### tee zrzuca do pliku i na konsole
```
head/ tail -n 1 -f 
cat log.txt | grep  hello | cut -b 100
```
#### Grep szuka
```
 grep prometheus-example-service
 grep -v prometheus-example-service
```
#### awk edytor po kolumnach
#### pid
#### pidof
strace -p $(pidof vi) 
sudo netstat -pant

