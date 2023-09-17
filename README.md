# 如何保持快乐

先把自己*new*出来

```java
Person mx = new Person();
```

然后给自己设置快乐属性为真

```java
mx.setHappy(true);
```

然后使得自己保持

```java
mx.keepHappy();
```

# 如何获得满足感

先把自己的小成就*new*出来

```java
List<String> having= new ArrayList<>();
having.add("国家励志奖学金");
having.add("先进个人"); 
having.add("你是我见过最有耐心的老师！"); 
//...... 
Gain gain = new Gain(having);
```

把成就装到自己身上

```java
mx.setGain(gain);
```

用成就不断激励自己前行

```java
mx.moveOnGain();
```

# 如何不熬夜

先设置自己的睡眠时间为11点休息

```java
mx.setSleepTime("23:00:00");
```

如果当前时间超过晚上十一点早于凌晨七点，则强制睡眠

```java
Calendar cal=Calendar.getInstance();
int	hour=cal.get(Calendar.HOUR_OF_DAY);
if(hour>23||hour<7) mx.forceSleep(); 
```

如果睡不着，则开启冥想模式；如果睡着了，已成功休息，请勿打扰，谢谢。

```java
while(true){
    if (!mx.sleeping)mx.converseToSleepingMode("冥想");
    else {
    mx.converseToSleepingMode("睡着");
    break;
}
}
//end of day...
```

# 如何不翘二郎腿

先设置自己的腿部摆放为“双腿平放，自然打开“

```java
mx.setLegsMode("双腿平放，自然打开");
```

如果想翘二郎腿，那么把腿稍稍再打开(约15°，因人而异)，直到一个舒服的姿势

```java
mx.openLegsWith(15,Math.ANGLE);
```

如果还在翘二郎腿，那就用拳头把高起来的腿一拳打下去吧！

```java
mx.hitHigherLegWith(Person.FIST);
/*
** 当然我们还有别的办法可以把腿打下去
*/
// mx.hitHigherLegWith(Tool.STICK);
// mx.hitHigherLegWith(SportsEquipment.BASKETBALL);
// and so on...
```

# 如何高效地学习

先设置自己为学习模式

```java
mx.setDailyMode(Daily.STUDY);
```

再设置学习模式为高效学习模式

```java
mx.setStudyMode(Study.EFFICIENT);
```

最后摈弃外界一切干扰

```java
mx.abandonInterference(Interference.ALL);
/* But high mode will consume more energy of mx, so mx should relax after
   doing some works
*/
// mx.relax();

```
