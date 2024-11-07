# 小红书关键词帖子文章检索和收集爬虫程序 个人修改版

## 程序介绍
本程序使用了https://github.com/xiaohe112233/redbook-keywords  的代码
- 使用介绍点进大佬的项目
- 以下新功能都是用AI加入的，都是我自己需要的功能，陆陆续续的跟AI说了一堆话总结的功能

## 主要有以下几个新功能:
- 增加了关键词排除功能: 用户可以输入需要排除的关键词,那些包含这些关键词的帖子将不会被爬取。
- 增加了排序方式的选择: 用户可以选择按"综合"、"最新"或"最热"的顺序进行排序。
- 增加了随机延迟功能: 爬取数据后会随机等待5-15秒再进行下一个帖子的爬取,以减少对网站的请求压力。
- 优化了页面滚动加载的方式: 当已经爬取了部分数据后,会尝试多次滚动页面,以确保能加载更多的帖子数据。
- 增加了更详细的日志记录: 记录了更多的日志信息,包括每个步骤的进度和一些错误信息。
- 增加了异常处理: 对一些预期内的异常进行了更好的处理,能在出现问题时继续尝试爬取其他数据。
