# 诗歌生成器

[View full project on microbit\.org](https://microbit.org/zh-cn/projects/make-it-code-it/poetry-generator)

To code this project yourself, right click on the background of the workspace and choose ‘delete all blocks’, then follow the coding video below. You can find the `forever` and `on start` blocks in the `Basic` section.

### 它是什么？

这个诗歌生成器项目生成随机短语，可用于诗歌、密码或开始一个故事。 与朋友们分享特别有诗意或有趣的短语是很不错的。   

这两个视频介绍了你将制作什么以及如何编程：

https://www.youtube.com/watch?v=D5DNTn0cna8

https://www.youtube.com/watch?v=Ovq3dJiQQlM

### 您将学到

您将学习**数组**，这种特殊的变量。 **数组**是将数据像清单一样逐个存储的好用方式。

### 工作原理

* 当您晃动BBC micro:bit，会生成一个由形容词、名词、动词和副词构成的随机短语，例如，“beautiful bird eats swiftly”。
* 您可以自己写短语来开始一首诗，或者与其他由这个程序生成的短语一起，写一整首诗。
* 这个程序使用四个**数组**，分别叫做adjectives,（形容词）、nouns,（名词） verbs（动词）和adverbs（副词）。
* 每个数组各存储一个单词列表。 数组中的每个项目（在这里是单词），被称为这个数组的一个**元素**。 数组里的元素用**索引**来进行编号。 举个例子，数组nouns包含三个元素，分别是0号元素bird，1号元素butterfly和2号元素dragonfly。 因为计算机从0开始计数，所以索引从0开始编号。
* 您晃动micro:bit的时候，每个数组会随机选择一个0到2之间的数字。 这些数字索引对应的元素会显示在micro:bit的LED显示屏上。

Visit the [projects page on microbit\.org](https://microbit.org/zh-cn/projects/make-it-code-it/) for a full description of this and other projects.