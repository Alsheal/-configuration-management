**Pract 1**

"Вывести отсортированный в алфавитном порядке список имен пользователей в файле passwd (вам понадобится grep)."

grep -o '^[^:]*' /etc/passwd | sort
grep -o - вывести только совпавшую часть строки
'^[^:]*' - регулярное выражение; все символы кроме двоеточия
sort - сортировка по алфавиту

Вывод:
_apt
_chrony
alyona
backup
bin
daemon
dhcpcd
games
irc
landscape
list
lp
mail
man
messagebus
news
nobody
polkitd
proxy
root
sync
sys
syslog
systemd-network
systemd-resolve
uucp
www-data


**Задача 2**
Вывести данные /etc/protocols в отформатированном и отсортированном порядке для 5 наибольших портов, как показано в примере ниже:

[root@localhost etc]# cat /etc/protocols ...
142 rohc
141 wesp
140 shim6
139 hip
138 manet"

grep -v '^#' /etc/protocols | awk 
'{print $2, $1}' | sort -rn | head -5
grep -v '^#' - убирает строки-комментарии
awk '{print $2, $1}' - смена порядка полей: сначала имя, затем номер протокола
sort -rn - сортировка по числу (-n)  в обратном порядке (-r)
head -5 - первые 5 строк

Вывод: 
262 mptcp
143 ethernet
142 rohc
141 wesp
140 shim6