***Pract 1***

**Задача 1**

<img width="583" height="482" alt="image" src="https://github.com/user-attachments/assets/f12d9111-932d-4465-9acb-8480fbf0661b" />

Основное решение и вывод:
<img width="614" height="463" alt="image" src="https://github.com/user-attachments/assets/c13e552c-a6ed-46c8-b901-e57bddffde7f" />


**Задача 2**
"Вывести данные /etc/protocols в отформатированном и отсортированном порядке для 5 наибольших портов, как показано в примере ниже:

[root@localhost etc]# cat /etc/protocols ...

grep -v '^#' /etc/protocols | awk '{print $2, $1}' | sort -rn | head -5
grep -v '^#' - убирает строки-комментарии
awk '{print $2, $1}' - смена порядка полей: сначала имя, затем номер протокола
sort -rn - сортировка по числу (-n)  в обратном порядке (-r)
head -5 - первые 5 строк

Вывод: 


**Задача 3**
"Написать программу banner средствами bash для вывода текстов, как в следующем примере (размер баннера должен меняться!):

[root@localhost ~]# ./banner "Hello from RTU MIREA!"
+-----------------------+
| Hello from RTU MIREA! |
+-----------------------+
Перед отправкой решения проверьте его в ShellCheck на предупреждения."


#1/bin/bash
if [$# -eq 0 ]; then
    echo "Использование: $0 ‹текст>" >82
    exit 1
fi text="$1" length-${#text}
line-"+"
for ( (i = 0; i ‹ length + 2; i++)); do
    line+="_"
done line+="+"
printf "%s\n' "$line"
printf "| %s | \n' "$text" 
printf "%s\n' "$line"
