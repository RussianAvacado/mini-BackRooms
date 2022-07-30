
# My 3D_Maze
Прохождение 3D_Лабиринта от первого лица


![](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)
## Нажми на надпись и познай что такое Panda3D

[>>>>Panda3D<<<<](https://docs.panda3d.org/1.10/python/index)


## Фрагменты кода

Создание и запуск окна(show).
Для размещения в нём элементов.

```
from direct.showbase.ShowBase import ShowBase


class Game(ShowBase):
    def __init__(self):
        ShowBase.__init__(self)
        
game = Game()
game.run()
```

Создаём модель, добовляем на неё текстуру и цвет(rgba).

```
import pickle
class Mapmanager():
    def __init__(self):
        self.model = 'block'
        self.texture = 'block.png'          
        self.colors = [
            (0, 238, 255, 1),
            (255, 255, 255, 1)
        ]
```


## Документации на модули которые использовались в проекте

 - [Модуль pickle](https://docs.python.org/3/library/pickle.html)
 - [Модуль time](https://docs.python.org/3/library/time.html)


## Authors

- [GitHub:RussianAvacado](https://github.com/RussianAvacado)

