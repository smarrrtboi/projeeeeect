# Ход работы
1. Проанализровал данный файл, составил для хранения его данных класс **Building**
2. Распарсил CSV, используя CSVReader, создал массив из Buildng. Пустые строки, строки "малоэтажный" и "многоэтажный" в поле количества этажей были заменены на нулевые.
3. Создал БД в SQLite с таблицами Buildings и Prefixes, соответствующую 3НФ, подключил её драйверами из Maven.
4. Создал класс DB для выполнения запросов в БД, с его помощью заполнил БД данными из парсера.
**Чтобы ещё раз заполнить БД, вызовите метод DB.fillDB() (Процесс заполнения ОЧЕНЬ долгий!)**
5. Создал класс Task для выполнения задач посредством класса DB.


**ЗАДАНИЕ 1**

![image](https://user-images.githubusercontent.com/72685173/146520228-ff0b723b-5626-4919-b177-05496ffe805b.png)




**ЗАДАНИЕ 2**


![image](https://user-images.githubusercontent.com/72685173/146520535-c888d120-fa45-4739-b237-e3a766ed6576.png)





![image](https://user-images.githubusercontent.com/72685173/146520358-25d7d9c4-53a4-44f7-908f-6f4708e7ba7f.png)



**ЗАДАНИЕ 3**

![image](https://user-images.githubusercontent.com/72685173/146520718-e404222e-6245-406a-a2da-f101aa9d857c.png)

