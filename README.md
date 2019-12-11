# Ping Pong Game

Репозиторий с классической игрой на Python. Написан с целью изучить MVP и получить тестовый проект для разработки собственного дисплея. В данный момент имеет только один вариант отображения - QtVirtualDisplay, его удобнее всего использовать для разработки моделей. 

### Предполагается добавить:

- _GpioPwmDisplay_ - View для отображения на дисплее, где каждый элемент (светодиод, электродвигатель) висит на одном из пинов GPIO, а управляется с помощью ШИМа через транзистор. Необходим для проверки гипотез на железе, отработки плат и прочего.  

### Текущие задачи:

1. разработать LED дисплей с подключением к GPIO без интерфейсов
2. разработать вибродисплей. Копия дисплея из первого пункта, но светодиоды заменены на вибромоторы (___конечная цель___)
3. написать больше игр и других обучающих материалов для работы с вибродисплеями
4. проверить гипотезы и попытаться на вопросы, связанные с пунктом 2:
   - Может ли человек научиться работать с такими дисплеями?
   - Как быстро учиться? 
   - Насколько сложные образы воспринимаются?
   - Как быстро воспринимаются образы? Возможно распознавание изображения в реальном времени? 
   - Что лучше подходит для обучения?
   - Как строить интерфейсы для нового варианта отображения информации?
   - Как с ними взаимодествовать?
   - Может ли работа с ними стать интуитивной и постоянной, как любым другим органом чувств?
   - Он может дополнять зрительную информацию?
   - А что если попробовать передавать с помощью такого экрана звук? Текст? Закодированные сообщения?
   - Как будет ощущать мир человек, если использовать такой дисплей для вывода какой-либо информации о реальном мире? А после длительного использования, появления привычек и рефлексов, он все еще _человек_?

## Install

``` 
sudo apt install qt5-default
git clone https://github.com/mor1ins/ping_pong_game
cd ping_pong_game
pip install -r stable-req.txt
```

## Run

```
python3 PingPongGame.py
```

