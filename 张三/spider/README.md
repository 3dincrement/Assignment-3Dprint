#### emmm, 差不多算完成了
#### 开头的变量可以自己设置，每个标签爬多少页，每隔多少页跳一下，还有爬完一页和爬完一个标签所休息的时间，之前我的是小标签休息5分钟，每页休息一分钟，你们可以尝试一下更快的速度。
# 1. 然后就是现在有的几个问题了，一个是作者的国籍，在豆瓣里作者的国籍是由中括号包裹的，然后中国作者没有国籍，在数据处理上可能会遇到一些问题，还没想好怎么解决。
# 2. 还有就是热度爬下来后会有冗余的信息需要再拿excel再处理一下，还有作者出版社什么的由“\”隔开也可以直接拿excel处理。
# 3. emm，又发现一个问题，当外国小说有译者的时候会出现问题，在转换成json格式的时候可能会有问题，还在想。
# 3. 又发现一个问题，就是在爬下来书的细节部分，例如作者出版社时间价钱等，如果出现多个作者转换是就会出现问提，后来我使用翻转list的方法可以保证作者之后和作者之前的准确性，emmm看样子是解决了。
