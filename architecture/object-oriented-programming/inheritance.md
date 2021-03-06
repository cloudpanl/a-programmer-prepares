# 继承

继承从代码复用的角度来说，特别好用，也特别容易被滥用和被错用。不恰当地使用继承导致的最大的一个特征就是高耦合。
在这里我要补充一点，耦合是一个特征，虽然大部分情况是缺陷的特征，但是当耦合成为需求的时候，耦合就不是缺陷了。耦合成为需求的例子在后面会提到。

## 总结
可见，代码复用也是分类别的，如果当初只是出于代码复用的目的而不区分类别和场景，就采用继承是不恰当的。我们应当考虑以上3点要素看是否符合，才能决定是否使用继承。就目前大多数的开发任务来看，继承出现的场景不多，主要还是代码复用的场景比较多，然而通过组合去进行代码复用显得要比继承麻烦一些，因为组合要求你有更强的抽象能力，继承则比较符合直觉。然而从未来可能产生的需求变化和维护成本来看，使用组合其实是很值得的。另外，当你发现你的继承超过2层的时候，你就要好好考虑是否这个继承的方案了，第三层继承正是滥用的开端。确定有必要之后，再进行更多层次的继承。

## 参考资料
- [跳出面向对象思想(一) 继承](http://casatwy.com/tiao-chu-mian-xiang-dui-xiang-si-xiang-yi-ji-cheng.html)