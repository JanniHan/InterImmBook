# 火星历法

为了火星上的生活方便，火星上的计时与历法都与地球有所不同。

## 火星计时

火星沿用了地球上秒、分钟以及小时，但是由于火星上一个太阳日的时间要比地球上的太阳日要长，因此火星上一天除了二十四个小时，还有一段的扩展时间，长度为39分35.24409秒。

文字记录方法在每天的二十四小时内与地球的记录方法相同，超出二十四小时的部分采用“+时间”来记录，例如二十四小时后十三分钟二十六秒记作：+13:26.


## 火星历法

火星历法采用了大流士火星历，只是由于火星本地人的习惯的不同，对历法中的月份有不同的称呼，比较流行的是每年二十四个月分别采用了地球上古中国的二十四节气的称呼。火星历中，每个火星回归年定为一火星年，每年起始点为春分，是太阳直射火星赤道的时间。而火星元年开始，对应的是地球上的公元一九七零年四月二十八日，因此，人类第一个降落在火星的探测器，就是在火星元年到达的。

火星历将每年分为二十四个火星月，按照每六个火星月一组分为四组，每组的前五个月有二十八个火星日，第六个月只有二十七个火星日，每年最后一个月在闰年会多包含闰日，即在闰年会有二十八天。一个典型的火星年应该是这样的。

|        春季        |       夏季       |       秋季       |        冬季        |
|:------------------:|:----------------:|:----------------:|:------------------:|
| 立春月（二十二月） |  立夏月（四月）  |  立秋月（十月）  |  立冬月（十六月）  |
| 雨水月（二十三月） |  小满月（五月）  | 处暑月（十一月） |  小雪月（十七月）  |
| 惊蛰月（二十四月） |  芒种月（六月）  | 白露月（十二月） |  大雪月（十八月）  |
|   春分月（一月）   |  夏至月（七月）  | 秋分月（十三月） |  冬至月（十九月）  |
|   清明月（二月）   |  小暑月（八月）  | 寒露月（十四月） |  小寒月（二十月）  |
|   谷雨月（三月）   |  大暑月（九月）  | 霜降月（十五月） | 大寒月（二十一月） |

如表格所示，按照每六个月一个季节，分为四季。


每个火星月共有四个星期，与地球不同的是，不管之前一个火星月最后一天是星期几，当每个火星月新开始的时候，星期总是从第一天开始计算。因此一个典型的火星月是这样的：

| 星期日 | 星期一 | 星期二 | 星期三 | 星期四 | 星期五 | 星期六 |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|    1   |    2   |    3   |    4   |    5   |    6   |    7   |
|    8   |    9   |   10   |   11   |   12   |   13   |   14   |
|   15   |   16   |   17   |   18   |   19   |   20   |   21   |
|   22   |   23   |   24   |   25   |   26   |   27   |   28   |

最后一天是否存在与月份以及是否闰年有关。

火星年的置闰问题，算法与地球类似，即大流士火星历的置闰方法：

> 一火星日比一地球日长39分钟35.244秒，而一火星年的长度则为668.5907火星日，因此基本的置闰公式就是每十个火星年均由6个669火星日的火星年及4个668火星日的火星年所组成。前者（虽然比平年更常出现，可是仍然是被称作闰年）为奇数年份及能被10整除的年份。惟能被100整除的年份规定为平年；能被1000整除的年份为闰年；能被3000整除的年份为平年。


## 一些重要的日期


作为历法的校准，火星元年一年中四个重要的日期与地球历法的对应为：

|      春分      |      夏至      |      秋分     |      冬至     |
|:--------------:|:--------------:|:-------------:|:-------------:|
| 1970年4月28日  | 1970年11月12日 | 1971年5月15日 | 1971年10月8日 |


火星上一些具有重要天文意义的节日：

| 火星历日期  |    节日    |
|:----------: |:----------:|
| 春分月1日   |  火星春分  |
| 芒种月12日  | 火星远日点 |
| 夏至月27日  |  火星夏至  |
| 寒露月11日  |  火星秋分  |
| 大雪月12日  | 火星近地点 |
| 冬至月14日  |  火星冬至  |

## 火星时区

由于火星上一天的时间并不是24小时，这给时期的划分造成了一定的麻烦。

为了时间换算的方便，火星上相邻两个时区之间时差均为1个小时，这样的话，一个时区的所跨的精度就不再是15°，而是14.5987°。

火星上的本初子午线为穿过艾里-0陨石坑的经线，并且火星上的经度均以东经表示，从东经0°-东经360°，并没有西经，因此，火星上的时区也是以本初子午线为起点，向东每隔14.5987°为一个时区。这样一来，火星上最先进入一天的时区为24区，即靠近0区左侧的时区。火星上时区划分列表如下：

| 时区 | 起始经度 | 终止经度 | 与0区时差
| :--: | :--: | :--: | :--: |
| 0区 | 0° | 14.5987° | 0 |
| 1区| 14.5987° |  29.1974° | +1 |
| 2区 | 29.1974° | 43.7961° | +2 |
| 3区 | 43.7961° | 58.3948° | +3 |
| 4区 | 58.3948° | 72.9935° | +4 |
| 5区 | 72.9935° | 87.5922° | +5 |
| 6区 | 87.5922° | 102.1909° | +6 |
| 7区 | 102.1909° | 116.7896° | +7 |
| 8区 | 116.7896° | 131.3883° | +8 |
| 9区 | 131.3883° | 145.9870° | +9 |
| 10区 | 145.9870° | 160.5858° | +10 |
| 11区 | 160.5858° | 175.1845° | +11 |
| 12区 | 175.1845° | 189.7832° | +12 |
| 13区 | 189.7832° | 204.3819° | +13 |
| 14区 | 204.3819° | 218.9806° | +14 |
| 15区 | 218.9806° | 233.5793° | +15 |
| 16区 | 233.5793° | 248.1780° | +16 |
| 17区 | 248.1780° | 262.7767° | +17 |
| 18区 | 262.7767° | 277.3754° | +18 |
| 19区 | 277.3754° | 291.9741° | +19 |
| 20区 | 291.9741° | 306.5728° | +20 |
| 21区 | 306.5728° | 321.1715° | +21 |
| 22区 | 321.1715° | 335.7702° | +22 |
| 23区 | 335.7702° | 350.3689° | +23 |
| 24区 | 350.3689° | 360° | +24 |

必须注意的是，24区所横跨的经度并不是14.5987°，而是9.6311°。