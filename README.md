# Deep-Learning-Neural-Networks_Lab2

Используя пример запуска нейронной сети глубокого обучения SSD я выполнил ее качественный анализ работы. Для этого использовал снимки, полученные из набора данных VisDrone2019-DET-train. Оценку работы данной сети я бы поставил неудовлетворительную. Так как встречаются такие снимки на которых сеть не выделяет ничего хотя объекты можно визуально отделить и определить (пример фотография номер 6 или 7). Также встречаются снимки на которых сеть ошибочно определила объекты (чаще всего встречается ошибка машина = телефон). 
Выявленные ошибки сети я могу объяснить тем что у используемого набора данных встречаются фотографии с плохой контрастность и ракурс съемки не подходит для данной нейронной сети. 


![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/1.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/2.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/3.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/4.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/5.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/6.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/7.JPG)
![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/8.JPG)

Средняя точность детектирования объектов, количество пропущенных объектов, количество ложных тревог для порогов IoU = 0.5, 0.75, 0.9

![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/DataAnalysis.JPG)

Средняя точность детектирования объектов, количество пропущенных объектов, количество ложных тревог для каждого класса для порогов IoU = 0.5, 0.75, 0.9

![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/IoU05%20(1).jpg)

![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/IoU075%20(1).jpg)

![](https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks_Lab2/blob/master/detected/IoU09%20(1).jpg)
