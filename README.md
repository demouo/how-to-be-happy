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

# 如何知道一家美食店好不好吃

先到店

```java
mx.goTo("美食店");
```

打开手机便签，输入“这家店好吃吗？”，配上表情包

```java
NoteWriteStream nws = mx.open(Device.PHONE,App.NOTE,"w");
nws.write("这家店好吃吗？*emoji-question*");
```

礼貌地敲店面橱窗，把手机给里面吃饭的人看，寻求回复

```java
mx.knock(Store.WINDOW,AskMode.POLITE);
mx.showPhoneAndWait();
/*
 ** After getting reply, we should thank strangers we ask.
*/
```

# 如何快速完成作业

打开chatgpt网页

```java
mx.open(Device.COMPUTER,Web.CHATGPT);
```

输入作业问题

```java
mx.keyInput(Device.COMPUTER,Question.HOMEWORK);
```

获取g哥的解析然后cv

```java
mx.cvWith(Web.CHATGPT,Reply.TEXT);
```

# 如何在教室吃早餐

先把早餐包（看你喜欢，麦麦早餐也可以的）拿到教室

```java
mx.goTo("classroom",Breakfast.BREAD);
```

打开电脑

```java
mx.open(Device.COMPUTER);
```

一边开电脑一边吃东西

```java
mx.eat(Breakfast.BREAD);
```

# 如何为大家提供有意义的信息

首先确保自己是乐于助人的

```java
mx.setHelping(true);
```

来到班群、年级群

```java
mx.goTo(Qq.GROUP);
```

发送有意义的信息

```java
mx.sendMessage(Message.MEANING);
```

# 如何快速登录校园统一登录

首先打开电脑统一登录网页

```java
mx.open(Device.COMPUTER,Web.SCUT);
```

调取Google记住的密码

```java
mx.fetchInput(Device.COMPUTER,Brower.GOOGLE);
```

oh no本来是为了方便才调用一键登录的，没想到还要调取企业微信验证码呢！安全性真好

```java
mx.goTo("微信");
String captcha=mx.getWXCaptcha();
mx.keyInput(Device.COMPUTER,captcha);
```
# 如何快速的备课

先找到b站视频链接

```java
mx.find(Device.COMPUTER,Web.BILIBILI,Teaching.MATH)
```

打开视频并作帧记录

```java
mx.open(Web.VIDEO)
mx.record(Video.TIME,Comment.NOTE)
```

使用python将所作的记录自动化生成word

```java
mx.py_call(Function.recordToWord,Record.CURRENT)
```

# 如何吃夜宵不胖

晚下课先回到宿舍，不要着急

```java
mx.goTo(Place.DORMITORY,Time.NIGHT);
```

回到宿舍先打开牛奶

```java
mx.open(Food.MILK);
```

然后喝牛奶，这样不会胖胖哦

```java
mx.drink(Food.MILK);
```
