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

### 第八天: 2018年10月20日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-8。

**思考：** 早读主要是介绍了如何写一个开源js库。JavaScript30-8实现了一个浏览器上的画板，主要是使用canvas的绘图功能，监听鼠标动作，进行画线，可以设置画线的样式。

**工作成果链接：** [JavaScript30-8](https://github.com/sj279811799/JavaScript30/blob/master/08%20-%20Fun%20with%20HTML5%20Canvas/index-START.html)


# 100 Days Of Code - 日志

### 第九天: 2018年10月21日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-9。

**思考：** 早读前端发展，没什么技术方面的内容。JavaScript30-9介绍了浏览器的console输出，主要有log,error,warn,info,assert,dir,group,groupCollapsed,groupEnd,table,count,time,timeEnd。

**工作成果链接：** [JavaScript30-9](https://github.com/sj279811799/JavaScript30/blob/master/09%20-%20Dev%20Tools%20Domination/index-START.html)


# 100 Days Of Code - 日志

### 第十天: 2018年10月22日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-10。

**思考：** 前端早读主要介绍了Proxy的优缺点及用途，优点是支持数组和对象的监听，缺点是兼容性和多层嵌套不支持（可以递归Proxy实现支持）。用途可以用来响应式，数据验证，多继承，隐藏私有变量等。JavaScript30-10主要实现shift多选，两种方法，一种是初始check为false，遇到本次点击或上次点击列，则翻转，实现两次点击列间的选中/取消。第二种是利用数组slice方法，使用indexOf获取两次点击下标，然后截取得到要操作的项。

**工作成果链接：** [JavaScript30-10](https://github.com/sj279811799/JavaScript30/blob/master/10%20-%20Hold%20Shift%20and%20Check%20Checkboxes/index-START.html)


# 100 Days Of Code - 日志

### 第十一天: 2018年10月23日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-11。

**思考：** 前端早读主要介绍了原生html组件，主要由四大组件标准组成，html template、shadow dom、custom elements、html import(废弃，被es6 import替代)组成。shadow dom是dom树上一个隔离的子树，可以继承父级的一些属性，利用其隔离性就可以实现html组件了，比如原生组件video，input等（Chrome可以设置显示shadow dom）。shadow root是shadow dom下的根。当组件内部复杂，就可以使用html template了，使用js将其插入到shadow dom中。利用html impot可以将template定义在其他html文件中，然后倒入进来。通过上面三个已经将组件结构定义好了，然后就可以使用custom elements创建组件了，它提供了一系列生命函数，实现组件的交互事件。JavaScript30-11主要实现了对video标签的操作，包括播放暂停，快进快退，声音，速度，进度条等监听及调整。

**工作成果链接：** [JavaScript30-11](https://github.com/sj279811799/JavaScript30/blob/master/11%20-%20Custom%20Video%20Player/scripts.js)


# 100 Days Of Code - 日志

### 第十二天: 2018年10月24日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-12。

**思考：** 前端早读主要介绍了如何鉴别一个js库是否稳定可用。JavaScript30-12介绍了如何引入js文件，以及键盘监听，splice函数使用，从第一个参数开始，删除第二个参数制定个数元素，并插入第三个元素。

**工作成果链接：** [JavaScript30-12](https://github.com/sj279811799/JavaScript30/blob/master/12%20-%20Key%20Sequence%20Detection/index-START.html)


# 100 Days Of Code - 日志

### 第十三天: 2018年10月25日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-13。

**思考：** 前端早读主要介绍了如何优化前端页面，因为之前没看过相关内容，不是很懂，有时间系统学习一下，优化一下项目代码。JavaScript30-13介绍了文章中图片滑入滑出，主要利用滚动位置计算图片相对当前窗口的位置，然后利用opacity和translateX属性实现滑入。

**工作成果链接：** [JavaScript30-13](https://github.com/sj279811799/JavaScript30/blob/master/13%20-%20Slide%20in%20on%20Scroll/index-START.html)


# 100 Days Of Code - 日志

### 第十四天: 2018年10月26日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-14。

**思考：** 前端早读主要介绍了使用Redux处理数据的几个建议，虽然不用redux，但其中的几个思想还是值得参考的比如保存源数据，数据与界面状态分离，多个页面公共数据共用。JavaScript30-14主要介绍了数组和对象拷贝，如果直接赋值，只是对象引用，而不是新建一个对象。

**工作成果链接：** [JavaScript30-14](https://github.com/sj279811799/JavaScript30/blob/master/14%20-%20JavaScript%20References%20VS%20Copying/index-START.html)


# 100 Days Of Code - 日志

### 第十五天: 2018年10月27日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-15。

**思考：** 前端早读主要介绍了React16.7中的Hooks，在纯组件PureComponent是无法使用state和周期函数的。新提供的useState和useEffect允许在纯函数中使用。JavaScript30-15主要讲了localStorage的使用。

**工作成果链接：** [JavaScript30-15](https://github.com/sj279811799/JavaScript30/blob/master/15%20-%20LocalStorage/index-START.html)


# 100 Days Of Code - 日志

### 第十六天: 2018年10月28日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-16。

**思考：** 前端早读主要介绍了js中this的指代。JavaScript30-16实现了一个随鼠标变化的多个彩色文字的移动，实现原理是首先使用contenteditable使标签可编辑，然后获取鼠标位置，让后对标签设置四个方向不同颜色的textShadow。

**工作成果链接：** [JavaScript30-16](https://github.com/sj279811799/JavaScript30/blob/master/16%20-%20Mouse%20Move%20Shadow/index-start.html)


# 100 Days Of Code - 日志

### 第十七天: 2018年10月29日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-17。

**思考：** 前端早读主要介绍了前端面试，主讲了关于react的面试内容，意识到还有很多要学的，目前知道的还比较浅显。JavaScript30-17主要讲了对数组的排序，sort是对数组本身的操作，不会生成新的对象。

**工作成果链接：** [JavaScript30-17](https://github.com/sj279811799/JavaScript30/blob/master/17%20-%20Sort%20Without%20Articles/index-start.html)