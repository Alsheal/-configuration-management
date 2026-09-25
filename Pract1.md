***Pract 1***

**Задача 1**

<img width="583" height="482" alt="image" src="https://github.com/user-attachments/assets/f12d9111-932d-4465-9acb-8480fbf0661b" />

Основное решение и вывод:
<img width="614" height="463" alt="image" src="https://github.com/user-attachments/assets/c13e552c-a6ed-46c8-b901-e57bddffde7f" />


**Задача 2**
"Вывести данные /etc/protocols в отформатированном и отсортированном порядке для 5 наибольших портов, как показано в примере ниже:

[root@localhost etc]# cat /etc/protocols ...

Основное решение и вывод:
<img width="800" height="135" alt="image" src="https://github.com/user-attachments/assets/62e21c61-e6be-473f-9e6f-5824f0411d10" />


**Задача 3**
"Написать программу banner средствами bash для вывода текстов, как в следующем примере (размер баннера должен меняться!):

[root@localhost ~]# ./banner "Hello from RTU MIREA!"
+-----------------------+
| Hello from RTU MIREA! |
+-----------------------+
Перед отправкой решения проверьте его в ShellCheck на предупреждения."

Код программы для решения задачи.
<img width="502" height="366" alt="image" src="https://github.com/user-attachments/assets/24fde157-4718-4618-9f2d-3670ca0413d9" />


**Задача 4**
"Написать программу для вывода всех идентификаторов (по правилам C/C++ или Java) в файле (без повторений)."

Пример для hello.c:
h hello include int main n printf return stdio void world

Код для решения задачи на языке Bash:
<img width="657" height="242" alt="image" src="https://github.com/user-attachments/assets/41cdf3a9-668a-4c35-bd06-e277b3f94c43" />


Код на языке С, для проверки работы кода на Bash
<img width="356" height="139" alt="image" src="https://github.com/user-attachments/assets/402baee5-1dd3-4d6b-8d95-20c1e6ee3c63" />


Результат вывода строки на терминал с помощью команды ./hello hello.c
<img width="603" height="95" alt="image" src="https://github.com/user-attachments/assets/88ca5373-cd39-4acf-a521-63758c0746c6" />


**Задача 5**
Написать программу для регистрации пользовательской команды (правильные права доступа и копирование в /usr/local/bin).

Например, пусть программа называется reg:
./reg banner
В результате для banner задаются правильные права доступа и сам banner копируется в /usr/local/bin.

Код файла reg для решения задачи
<img width="302" height="132" alt="image" src="https://github.com/user-attachments/assets/9fd6e6b5-6218-44ce-aa9e-96efec03e015" />

Код файла banner для решения задачи
<img width="311" height="100" alt="image" src="https://github.com/user-attachments/assets/04b53303-c96a-4ce1-bce3-e7347605a36d" />

Результат работы программы с проверкой на месторасположение команды
<img width="810" height="144" alt="image" src="https://github.com/user-attachments/assets/85d86247-d7ab-4642-b493-12c27a4f45eb" />


**Задача 6** 
Написать программу для проверки наличия комментария в первой строке файлов с расширением c, js и py.

Код для решения задачи на языке Bash:
<img width="586" height="276" alt="image" src="https://github.com/user-attachments/assets/88a56c6a-939b-436b-a4a1-113b5e14c29b" />

Код на С для проверки работы программы
<img width="269" height="72" alt="image" src="https://github.com/user-attachments/assets/2573541c-3dff-4cb5-bd22-a60ecc9d2cde" />

Результат проверки работы программы ( для С )
<img width="318" height="50" alt="image" src="https://github.com/user-attachments/assets/44493756-f26c-4d4e-aa5b-a5c49780e5a0" />

Код на Python для проверки работы программы
<img width="167" height="63" alt="image" src="https://github.com/user-attachments/assets/7e081d46-c152-48d9-ac1c-a4a5df9d932f" />

Результат проверки работы программы ( для Python )
<img width="322" height="50" alt="image" src="https://github.com/user-attachments/assets/44b0ce2a-b3f4-4e24-b30c-721f9cd6f4b7" />


**Задача 7**
Написать программу для нахождения файлов-дубликатов (имеющих 1 или более копий содержимого) по заданному пути (и подкаталогам).
