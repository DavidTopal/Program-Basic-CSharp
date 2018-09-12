### Пример: принтиране на триъгълник

Да се създаде метод, който принтира триъгълник, както е показано в примерите.

#### Примерен вход и изход

|Вход|Изход|Вход|Изход|
|---|---|---|---|
|3|1<br>1 2<br>1 2 3<br>1 2<br>1|4|1<br>1 2<br>1 2 3<br>1 2 3 4 <br>1 2 3<br>1 2<br>1|

#### Насоки и подсказки

Преди да създадем метод за принтиране на един ред с дадени начало и край, прочитаме входното число от конзолата. След това избираме смислено име за метода, което описва целта му, например **`PrintLine`**, и го имплементираме.

![](/assets/chapter-10-images/08.Print-triangle-01.png)

От задачите за рисуване на конзолата си спомняме, че е добра практика **да разделяме фигурата на няколко части**. За наше улеснение ще разделим триъгълника на три части - горна, средна линия и долна.

Следващата ни стъпка е с цикъл да разпечатаме **горната половина** от триъгълника:

![](/assets/chapter-10-images/08.Print-triangle-02.png)

След това разпечатваме **средната линия**:

![](/assets/chapter-10-images/08.Print-triangle-03.png)

Накрая разпечатваме **долната част** от триъгълника, като този път стъпката на цикъла намалява.

![](/assets/chapter-10-images/08.Print-triangle-04.png)

#### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.bg/Contests/Practice/Index/594#2](https://judge.softuni.bg/Contests/Practice/Index/594#2).