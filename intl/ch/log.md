# 100 Days Of Code - 日志

### 第一天: 2018年10月13日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-1。

**思考：** react中函数如果写在Dom中，会每次都创建新的函数对象，导致重新渲染，所以尽量写在render外面。对于数组遍历出的节点上的函数，可以用一个数组缓存每个函数，根据key去索引。JavaScript30-1中介绍了声音播放和css变换，比较简单。

**工作成果链接：** [JavaScript30-1](https://github.com/sj279811799/JavaScript30/blob/master/01%20-%20JavaScript%20Drum%20Kit/index-START.html)


# 100 Days Of Code - 日志

### 第二天: 2018年10月14日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-2。

**思考：** js中当有if-else时，尽量先考虑特殊情况先return，减少代码的复杂度。判断数组中可以使用some或every函数，简化代码。JavaScript30-2实现了个简单的时钟，主要原理是将根据时间调整角度。

**工作成果链接：** [JavaScript30-2](https://github.com/sj279811799/JavaScript30/blob/master/02%20-%20JS%20%2B%20CSS%20Clock/index-START.html)


# 100 Days Of Code - 日志

### 第三天: 2018年10月15日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-3。

**思考：** 早读主要是介绍居中的知识，看到一个比较有趣的实现是利用writing-mode可以将水平方向的css变成垂直方向，这样text-align就变为垂直居中了，但此时文字也垂直排列了，需要在文字上设置一下writing-mode。JavaScript30-3实现了对图片的放大，模糊，颜色的调整，学到了使用--定义css变量，原生input也可以实现滑动条和颜色选择器。

**工作成果链接：** [JavaScript30-3](https://github.com/sj279811799/JavaScript30/blob/master/03%20-%20CSS%20Variables/index-START.html)


# 100 Days Of Code - 日志

### 第四天: 2018年10月16日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-4。

**思考：** 早读主要是介绍react,vue将虚拟dom渲染成真实节点的过程，还有点看不懂。JavaScript30-4主要是对数组的排序统计等操作，主要是reduce，这个之前没怎么用过，接收2个值，一个函数，一个初始值。函数有两个参数，第一个是上一次计算的结果，第二个是本次的循环到的值。

**工作成果链接：** [JavaScript30-4](https://github.com/sj279811799/JavaScript30/blob/master/04%20-%20Array%20Cardio%20Day%201/index-START.html)


# 100 Days Of Code - 日志

### 第五天: 2018年10月17日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-5。

**思考：** 早读主要是介绍了react、vue等框架的响应式，即一个值发生变化，依赖这个值的其他值也会跟着改变。其实现原理大致是给每个变量定义set、get方法，当变量被引用时，get被调用，用数组存下调用的计算函数，函数相当于该变量的订阅者。当变量被改变，set被调用，遍历调用数组中的订阅函数。JavaScript30-5主要介绍了flex的使用以及简单的css的动画变换。

**工作成果链接：** [JavaScript30-5](https://github.com/sj279811799/JavaScript30/blob/master/05%20-%20Flex%20Panel%20Gallery/index-START.html)


# 100 Days Of Code - 日志

### 第六天: 2018年10月18日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-6。

**思考：** 早读主要是介绍了js中几种计时器，大部分之前都没用过，抽空仔细了解下。JavaScript30-6主要介绍的是数据的请求和过滤展示，请求使用的fetch函数，过滤使用的正则。

**工作成果链接：** [JavaScript30-6](https://github.com/sj279811799/JavaScript30/blob/master/06%20-%20Type%20Ahead/index-START.html)


# 100 Days Of Code - 日志

### 第七天: 2018年10月19日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-7。

**思考：** 早读主要是介绍了响应式框架新的实现方式，使用Proxy替代了Object.defineProperty，拦截set、get、deleteProperty方法。JavaScript30-7主要是对数组操作，很简单，今后要常用some、every做判断，findIndex获取下标，slice截取数组，splice插入删除替换元素。

**工作成果链接：** [JavaScript30-7](https://github.com/sj279811799/JavaScript30/blob/master/07%20-%20Array%20Cardio%20Day%202/index-START.html)


# 100 Days Of Code - 日志

### 第八天: 2018年10月19日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-8。

**思考：** 早读主要是介绍了如何写一个开源js库。JavaScript30-8实现了一个浏览器上的画板，主要是使用canvas的绘图功能，监听鼠标动作，进行画线，可以设置画线的样式。

**工作成果链接：** [JavaScript30-8](https://github.com/sj279811799/JavaScript30/tree/master/08%20-%20Fun%20with%20HTML5%20Canvas)