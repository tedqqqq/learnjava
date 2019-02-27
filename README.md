# learnjava

在Object提供的消息通知机制应该遵循如下这些条件：

1.永远在while循环中对条件进行判断而不是if语句中进行wait条件的判断；
2.使用NotifyAll而不是使用notify。
