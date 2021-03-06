# Neo：Orm框架

Neo是一个基于JDBC开发的至简化框架。开发源头，源于几个原因，一个是之前几个公司采用的都是各自单独开发的Orm框架，这些框架不是开源，如果想自己使用，很多时候不方便，也不合适。另外一个主要是接触到的之前公司老大开发的那个框架思想很好，大道至简，对自己影响很大，该框架有很多思想借鉴之处。另一个是mybatis确实感觉不是很好用，把很多简单的东西设计的很复杂。最后是由于自己有很多想法，比如sql的规范落入到框架中、sql耗时统计和sql优化监控等等很多特性，且在之前接触的一些Orm框架中都没有。因此就有想法设计一个符合自己想法的Orm框架，下面的一些设计和各种特性有有借鉴之前接触到的一些优秀思想，也有在秉承着大道至简的原则进行的设计，框架刚起步，希望有兴趣的同学，一起添砖加瓦，共同成长。<br />下面介绍下框架的功能和一些用法。
<a name="SOWXF"></a>

目前已经发布到maven中央仓库，直接使用即可
```xml
<dependency>
  <groupId>com.github.simonalong</groupId>
  <artifactId>Neo</artifactId>
  <version>0.4.3</version>
</dependency>
```

源码：https://github.com/SimonAlong/Neo

---
文档方面找到更好的编写的位置因此后续文档不再更新，最新文档请见这里
https://www.yuque.com/simonalong/neo


