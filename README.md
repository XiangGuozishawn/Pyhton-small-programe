# Pyhton-small_programe
一些杂七杂八的python小项目

## 康威生命游戏
游戏规则：
任何四周邻居存活数少于两个的存活网格将死亡，因为人口稀少。
任何四周邻居存活数多于三个的存活网格将死亡，因为过度拥挤。
任何四周邻居存活数等于两个或三个的存活网格将在下一代中继续存活。
任何已经死亡的网格，如果周围邻居存活数为3个，将重新复活。

使用方法:
```python Conway_game_of_life.py```
***
## 兽语译者
由吾爱破解论坛大佬制作
使用方法:
先实例化一个对象
```demo=HowlingAnimalsTranslator()```
加密:
```demo.convert()```
解密:
```demo.deConvert```
