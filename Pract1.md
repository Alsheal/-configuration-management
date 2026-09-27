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

Код для решения задачи на языке Bash:
<img width="584" height="69" alt="{A531A1EC-D9CD-404F-BA7B-9D44FB9D9CAE}" src="https://github.com/user-attachments/assets/200cb8dc-955c-4799-af6d-1c6a63e2f4a8" />

Пример работы программы при случае, когда нет дубликатов
<img width="358" height="49" alt="{1AD12658-7D5A-40EF-BEED-67E8732DD4A8}" src="https://github.com/user-attachments/assets/4be7b2d8-6a23-44ae-a20c-d145ce2d97c2" />

Код для "тестировки" работы программы, "cоздаем дубликаты"
<img width="243" height="72" alt="{7CC1421A-CAEC-41F5-9425-42B72FDA0616}" src="https://github.com/user-attachments/assets/5e94d070-8556-4a91-bbe5-e59f8b9eb9c0" />

Пример работы программы при случае, когда есть дубликаты
<img width="439" height="39" alt="{08F9F780-3B0E-41F5-8E3A-EF84DAB62B41}" src="https://github.com/user-attachments/assets/b257b6cc-f922-4bae-a9c8-7b8a62ec4239" />


**Задача 8**
Написать программу, которая находит все файлы в данном каталоге с расширением, указанным в качестве аргумента и архивирует все эти файлы в архив tar.

Код для решения задачи на языке Bash:
<img width="416" height="184" alt="{CC412985-D8BF-48EE-953C-FAEAE69F6681}" src="https://github.com/user-attachments/assets/a5ff5c16-4ed3-41e9-975d-42eed2096f19" />

Пример работы программы
<img width="191" height="24" alt="{442A5E84-C750-4145-8CC6-33D9761DBE19}" src="https://github.com/user-attachments/assets/1d8064d9-9b6e-49e4-92f8-5505c059d77a" />
<img width="226" height="24" alt="{021B3A9A-99A1-4770-B95D-9649EC5B52E0}" src="https://github.com/user-attachments/assets/29e19f63-0bef-409b-87f6-5e7a1589ab17" />

Код для просмотра содержимого архива tar
<img width="240" height="40" alt="{11BDDB00-87C4-452B-9001-72C8DE9DD819}" src="https://github.com/user-attachments/assets/dd20b639-3ded-4d91-a016-f380e3fac963" />

**Задача 9**
Написать программу, которая заменяет в файле последовательности из 4 пробелов на символ табуляции. Входной и выходной файлы задаются аргументами.

Код для решения задачи на языке Bash:
<img width="277" height="69" alt="{470CA042-4C3D-4908-AFAC-627061695F80}" src="https://github.com/user-attachments/assets/18e65767-ec5f-40ce-b106-78c126629336" />

Пример работы программы
<img width="412" height="121" alt="{196BF801-C3FE-41BE-A0E8-863612716B94}" src="https://github.com/user-attachments/assets/74f486e7-d50b-41e1-b086-43a26798bf85" />


**Задача 10**
Написать программу, которая выводит названия всех пустых текстовых файлов в указанной директории. Директория передается в программу параметром.

Код для решения задачи на языке Bash:
<img width="236" height="61" alt="{A5D334C3-CADF-4453-A8F8-2F10E238469C}" src="https://github.com/user-attachments/assets/bca15937-c622-492a-9d73-b04b1582b28a" />

Создаём тестовые файлы:
<img width="467" height="54" alt="{E93565FA-1A3C-4CA9-84B5-0C63FA6FF7E4}" src="https://github.com/user-attachments/assets/64550cb9-6148-4716-b4f4-a390903bf5bd" />

Пример работы программы
<img width="304" height="56" alt="{E544B579-0000-447A-9E35-233B7FB387F4}" src="https://github.com/user-attachments/assets/6292e216-7561-4fff-be92-e36e9c68a9c2" />
