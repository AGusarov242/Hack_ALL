Задание 1

Открываем задание, смотрим view details у любого наименования, нажимаем check stock перхватываем запрос с помощью Burp
Отправляем нужный запрос в Repeater и видим там следующее:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/0.png)

После вводим там следующее:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/1.png)

Задание 2

Открываем задание, смотрим view details у любого наименования, нажимаем check stock перхватываем запрос с помощью Burp
Отправляем нужный запрос в Repeater и видим там следующее:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/0.png)

После вводим там следующее:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/2.png)

Дальше к нашему ip прибавляем /latest и повтрояем отправку запроса пока не дойдем до adminи и получим:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/3.png)

Задание 3

Открываем задание, смотрим view details у любого наименования, нажимаем check stock перхватываем запрос с помощью Burp
Отправляем нужный запрос в Repeater и видим там следующее:

productId=2&storeId=1

После меняем 2 и на наш ввод и получаем следующее:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/4.png)

Задание 4

Открываем задание, смотрим view post у любого наименования, нажимаем post comment с любыми данными и  перхватываем запрос с помощью Burp
Отправляем нужный запрос в Repeater и видим там следующее:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/5.png)

После меняем application/ , а также добавляем имя файла с нужным расширение и вставляем наш код:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/6.png)

Потом переходим в наш пост, делаем view image нашей автарки:
![alt text](https://raw.githubusercontent.com/AGusarov242/Hack_ALL/master/XXE/7.png)

Теперь перепечатываем код в поле submit solution и профит
