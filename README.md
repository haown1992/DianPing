# 大众点评数据分析

### 原文发表在知乎：https://zhuanlan.zhihu.com/p/29198391

仅针对本次数据，分析可以得出以下结论：

两极分化。大众点评上有52.1%商家没有得到过任何点评，这说明有大量商家无人问津，无法依靠大众点评为他们引流 ，带来人气。但同时热门商家点评非常火爆，会进一步带动人气。这将会使得二者之间的差距愈来愈大。
一线城市不管是餐厅数量还是菜系种类都领先于二三线城市，反应了一线城市的发展水平目前还是其他城市所无法比拟的，待在一线还是可以享受到很多便利的。
重点二线城市发展速度很快，从餐厅数量和菜系种类上愈来愈逼近一线城市，甚至于出现了像天津这样在菜系种类上已经超越一线的城市。如果要去二线城市发展的话，可以优先考虑如杭州、南京、成都、天津等这样的重点二线城市。
地区集中。大多数餐厅都集中在长三角、珠三角及环京地区，而西部地区则很少。反应了目前我国还是处在东南地区发达，西部地区欠发达的局面下。另外长三角、珠三角这两个超级城市群依然拥有很强的竞争力。
星级分布服从正态分布，从3.5星到4星是一个门槛，跨越难度很大，有73.8%的店面无法跨越，但过了之后前景也很好。
人均消费还是比较低的，大部分人都是工薪阶级，86.4%的人消费低于100元。但仍有部分土豪消费水平远超普通人，社会财富分布依然悬殊。
口味、环境、服务指标都服从正态分布。另外随着星级越来越高，各项指标也越发平衡，饭店如果想得到更高的星级必须均衡发展。
利用机器学习简单的对餐厅做好坏分类是可行的。


本次分析的数据由于不是全量数据，所以结论难免会与真实情况存在差异。而且本次分析的也比较简陋，很多情况都没有考虑到，结论也略显稚嫩，部分地方或许会有纯堆砌数据却无深入分析的情况存在。这是我以后要尽量避免，努力提高自己的地方。另外，机器学习的部分非常简陋，特征的选取应该有更好的方法，而且标签的定义也过于简单。本来是想做多分类任务的，从指标来预测星级，不过由于时间问题只好改成了二分类任务了。这点在以后的迭代中需要更加完善下。

