Первое задание:

1. открываем в браузере первое задание на root-me 
![alt text](https://github.com/AGusarov242/Hack_ALL/blob/master/Screenshot%20from%202019-11-18%2017-08-58.png)
2. с помощью Burp перехватываем запрос и во вкладке Intrcept ищем запрос и применяем Do intercept, далее жмем Forward пока не найдем html нашего запроса
![alt text](https://github.com/AGusarov242/Hack_ALL/blob/master/Screenshot%20from%202019-11-18%2017-09-53.png)
3. удаляем ключевые слова disabled в разделе input, чтобы открыть доступ
![alt text](https://github.com/AGusarov242/Hack_ALL/blob/master/Screenshot%20from%202019-11-18%2017-10-19.png)
4. теперь вводим любое слово и получаем флаг
![alt text](https://github.com/AGusarov242/Hack_ALL/blob/master/Screenshot%20from%202019-11-18%2017-10-42.png)

Второе задание:

1. открываем в браузере второе задание на root-me и вводим любые данные в поля
2. с помощью Burp перехватываем запрос и во вкладке Intrcept ищем запрос и применяем Do intercept, далее жмем Forward пока не найдем html нашего запроса
3. отправляем запрос в Repeater и жмем GO, теперь мы можем посмотреть на код и увидеть правильные логин и пароль
