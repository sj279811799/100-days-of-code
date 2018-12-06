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


# 100 Days Of Code - 日志

### 第十八天: 2018年10月30日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-18。

**思考：** 前端早读主要介绍了浏览器工作原理，太长还没看。JavaScript30-18就是对map,split,reduce三个函数的使用。

**工作成果链接：** [JavaScript30-18](https://github.com/sj279811799/JavaScript30/blob/master/18%20-%20AddingUpTimesWithReduce/index-start.html)


# 100 Days Of Code - 日志

### 第十九天: 2018年10月31日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-19。

**思考：** 前端早读主要介绍了网易小程序的设计，JavaScript30-19主要介绍了网页端摄像头调用以及canvas的使用，都没细看，留到周末细读。


# 100 Days Of Code - 日志

### 第二十天: 2018年11月01日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-20。

**思考：** 前端早读主要介绍了css实现一个加载动画。JavaScript30-20介绍了浏览器端语音识别，看不到底层实现，而且只有谷歌浏览器支持，权当了解。


# 100 Days Of Code - 日志

### 第二十一天: 2018年11月02日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-21。

**思考：** 前端早读主要介绍了Rxjs的使用。JavaScript30-21介绍了浏览器端使用navigator.geolocation获取地理位置信息和速度方向等信息，但笔记本不支持。


# 100 Days Of Code - 日志

### 第二十二天: 2018年11月03日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-22。

**思考：** 前端早读主要介绍了网页左右布局，主要考虑到一些国家的阅读方式是RTL，利用transform可以实现整个页面左右翻转。JavaScript30-22介绍了实现对鼠标移入的文字添加白色背景，主要是利用getBoundingClientRect获取区块宽高和位置，然后调整背景块的位置。


# 100 Days Of Code - 日志

### 第二十三天: 2018年11月04日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-23。

**思考：** 前端早读主要介绍了通过IntersectionObserver实现异步懒加载，我们通过判断图片位置来控制图片加载，但这会scroll频繁触发，增加浏览器负担，IntersectionObserver会异步监听元素位置变化不会占用主线程。JavaScript30-23介绍了实现浏览器端的语音合成，即识别文字并语音播放，主要使用SpeechSynthesisUtterance获取语言，SpeechSynthesis获取语音识别播放实例。


# 100 Days Of Code - 日志

### 第二十四天: 2018年11月05日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-24。

**思考：** 前端早读主要介绍了深拷贝的相关知识，主要介绍了四种深拷贝的方法，主要不同是处理了递归导致内存溢出和循环引用。JavaScript30-24主要介绍了滚动页面自动调整导航，就是通过判断滚动高度，然后调整样式，transition可以定义css变化用时，使变换看起来更像动画。


# 100 Days Of Code - 日志

### 第二十五天: 2018年11月06日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-25。

**思考：** 前端早读主要介绍了前端页面在数据未加载时，使用骨架屏替代加载图标和白屏。JavaScript30-25主要介绍了js中的点击事件，函数接收三个参数，第三个参数为配置项，once为控制是否多次触发，为true时只触发一次。capture控制触发顺序，当为true时，由外向内。


# 100 Days Of Code - 日志

### 第二十六天: 2018年11月07日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-26。

**思考：** 前端早读主要介绍了React项目的目录结构和文件命名，目录按模块拆分，UI组件单独存放，文件名根据模块-功能决定。JavaScript30-26主要实现了一个导航栏，鼠标放在导航上显示下拉。主要实现原理是监听鼠标移入，然后设置下拉的display和opacity，显示文字。背景板位置通过getBoundingClientRect获取下拉元素的位置及宽高设置。


# 100 Days Of Code - 日志

### 第二十七天: 2018年11月08日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-27。

**思考：** 前端早读主要介绍了css中阴影的使用技巧，有待深入研究。JavaScript30-27主要实现了鼠标点击滑动的效果，厉害的还是其中的css，可以用perspective实现子元素的透视效果。


# 100 Days Of Code - 日志

### 第二十八天: 2018年11月09日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-28。

**思考：** 前端早读主要介绍了使用Lighthouse对网站进行分析优化，并在实践中给出了很多网站的优化建议。JavaScript30-28主要实现了一个控制视频播放速度的进度条，主要是点击事件获取相对顶部的偏移，然后相对高度算出百分比，设置进度样式和视频速度。


# 100 Days Of Code - 日志

### 第二十九天: 2018年11月10日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-29。

**思考：** 前端早读主要介绍了小程序的相关知识，暂时不看。JTimeavaScript30-29主要实现了一个倒计时的功能，显示剩余秒数和截止时间。主要知识点就是时间转换。利用setTimeout倒计时。


# 100 Days Of Code - 日志

### 第三十天: 2018年11月11日

**今天的进展：** 阅读了早读文章，学习了JavaScript30-30。

**思考：** 前端早读主要介绍了React的SSR即服务端渲染，使用在前后端间增加一个node层，做服务端渲染，减轻浏览器压力，减少TTFP（Time To First Page).主要请求过程是客户端请求，node路由分析并请求API然后渲染返回客户端，客户端拿到html像node请求js文件然后客户端渲染，js文件中向node请求数据，node代理到后端接口，返回数据，客户端完成渲染。整个过程前后端要各做一次路由解析和渲染。（JavaScript30结束了，但其中的css还有待学习）


# 100 Days Of Code - 日志

### 第三十一天: 2018年11月12日

**今天的进展：** 阅读了早读文章，学习了前端性能优化0。

**思考：** 前端早读主要介绍了React的hooks,之前看了一篇文档，但还是很模糊，今天看了这篇后才知道之前理解的有点偏差，hooks使用的函数式组件指的不是纯组件，而是一个返回dom结构的函数。hooks可以让我们可以在该函数中使用state和周期函数。前端性能优化今天看了开篇，之后一个月大致会没两天看一篇，刚好一个月看完。


# 100 Days Of Code - 日志

### 第三十二天: 2018年11月13日

**今天的进展：** 阅读了早读文章，学习了前端性能优化1-1。

**思考：** 前端早读主要介绍了对css进行重命名来避免相互影响，主要是在css名称后加一串随机码。前端性能优化1-1主要是对是代码的打包时间和大小的优化。主要是避免node_modules的babel转义，将第三方依赖单独打包一个文件缓存，只有改变时才重新编译。开启多进程处理。体积压缩主要是删除冗余代码和按需加载。


# 100 Days Of Code - 日志

### 第三十三天: 2018年11月14日

**今天的进展：** 阅读了早读文章，学习了前端性能优化1-2。

**思考：** 前端早读主要介绍了微前端（类似微服务）的实现方式，并给了demo，抽空看看。前端性能优化1-2主要讲了Gzip压缩的原理，就是对文件中的重复内容进行临时替换，减小文件大小，减小传输时间。


# 100 Days Of Code - 日志

### 第三十四天: 2018年11月15日

**今天的进展：** 阅读了早读文章，学习了前端性能优化2-1。

**思考：** 前端早读主要介绍了如何构建夜间模式。前端优化主要介绍了几种图片格式的优缺点和使用场景。


# 100 Days Of Code - 日志

### 第三十五天: 2018年11月16日

**今天的进展：** 阅读了早读文章，学习了前端性能优化2-2。

**思考：** 前端早读主要介绍了React高阶组件的使用。前端优化主要介绍了几种图片格式的优缺点和使用场景。


# 100 Days Of Code - 日志

### 第三十六天: 2018年11月17日

**今天的进展：** 阅读了早读文章，学习了前端性能优化3-1。

**思考：** 前端早读主要介绍了WebAssembly，具体使用还有很远，简单了解。性能优化主要介绍了http缓存的机制，主要分为强缓存和协议缓存两种，强缓存主要是返回资源时携带一个时间戳或者资源有效期，浏览器会判断资源是否过期来决定是否读取缓存。协议缓存是每次都会向服务器询问资源是否改变，未修改则会重定向本地缓存（304）。


# 100 Days Of Code - 日志

### 第三十七天: 2018年11月18日

**今天的进展：** 阅读了早读文章，学习了前端性能优化3-2。

**思考：** 前端早读主要介绍了页面链接的打开方式，即在当前页面打开还是新页面打开。性能优化主要介绍了其他几种缓存，包括MemoryCache、Service Worker Cache、Push Cache。


# 100 Days Of Code - 日志

### 第三十八天: 2018年11月19日

**今天的进展：** 阅读了早读文章，学习了前端性能优化4-1。

**思考：** 前端早读主要介绍了JS和WebAssembly相互调用。性能优化主要介绍了浏览器端的存储，包括cookie，local storage，session storage。


# 100 Days Of Code - 日志

### 第三十九天: 2018年11月20日

**今天的进展：** 阅读了早读文章，学习了前端性能优化4-2。

**思考：** 前端早读主要介绍了谷歌photo的实现，主要是点是根据所有图片计算出大体的框架结构，并按列别分块。然后根据算法计算出每行显示图片的最佳数量，保持最佳的图片比例。当用户滑动窗口，按分类显示/隐藏图片，实现懒加载。最后当用户点击放大，先放大缩略图，同时加载原图。性能优化主要介绍了浏览器端的数据库indexDB。


# 100 Days Of Code - 日志

### 第四十天: 2018年11月21日

**今天的进展：** 阅读了早读文章，学习了前端性能优化5-1。

**思考：** 前端早读主要介绍了js函数的柯里化，即将多个参数的函数，转换成多个嵌套的单参数函数。常用于某个参数不常改变的情况。前端优化主要介绍了使用CDN的优点。


# 100 Days Of Code - 日志

### 第四十一天: 2018年11月22日

**今天的进展：** 阅读了早读文章，学习了前端性能优化5-2。

**思考：** 前端早读主要介绍了js的箭头函数，其优点是不需要绑定this,写法简单。前端优化主要看了CDN的原理，主要是智能DNS，通过请求的地址，动态寻找最近的服务器。


# 100 Days Of Code - 日志

### 第四十二天: 2018年11月23日

**今天的进展：** 阅读了早读文章，学习了前端性能优化6-1。

**思考：** 前端早读主要介绍了浏览器页面新一代的生命周期。性能优化介绍了SSR，即服务端渲染。


# 100 Days Of Code - 日志

### 第四十三天: 2018年11月24日

**今天的进展：** 阅读了早读文章，学习了前端性能优化6-2。

**思考：** 前端早读主要介绍了新版api在异步方面的优化，推荐使用async/await。


# 100 Days Of Code - 日志

### 第四十四天: 2018年11月25日

**今天的进展：** 阅读了早读文章，学习了前端性能优化7-1。

**思考：** 前端早读主要介绍了css在网络加载方面的优化，一般就是优先加载必须的，懒加载其它的，减少使用@import，将不被js依赖的css放在就是后面等。前端优化主要介绍了浏览器的渲染过程，包括解析html生成DOM，解析css生成CSSDOM,合并生成RenderDOM，计算大小和位置，渲染页面。


# 100 Days Of Code - 日志

### 第四十五天: 2018年11月26日

**今天的进展：** 阅读了早读文章，学习了前端性能优化7-2。

**思考：** 前端早读主要介绍了ELE组件库的结构和构建过程，现在主要用antd，有空可以仔细研究一下。前端优化上半篇主要介绍了浏览器的渲染过程，下半篇主要介绍了css和js解析加载方面的优化。主要是css选择器书写的注意事项，css应尽早加载，js应合理加载。


# 100 Days Of Code - 日志

### 第四十六天: 2018年11月27日

**今天的进展：** 阅读了早读文章，学习了前端性能优化8-1。

**思考：** 前端早读主要介绍了return,await,return await三种调用一个异步函数的区别，return异步不会执行，await会有异步执行但得不到异步函数结果，return await 会有异步执行，且能得到结果。前端优化主要讲了JS操作DOM慢的原因，调用过程有消耗，改变了尺寸，会重新计算尺寸，然后重绘。


# 100 Days Of Code - 日志

### 第四十七天: 2018年11月28日

**今天的进展：** 阅读了早读文章，学习了前端性能优化8-2。

**思考：** 前端早读主要介绍了babel对class的转义过程。前端优化主要是对DOM操作的优化，首先就是减少DOM查询，将查询的节点放到变量缓存下来，每次操作变量。其次是减少对DOM的改变次数，可以利用DocumentFragments生成一段DOM片段，直接操作这个片段，最后将片段插入DOM树中。


# 100 Days Of Code - 日志

### 第四十八天: 2018年11月29日

**今天的进展：** 阅读了早读文章，学习了前端性能优化9-1。

**思考：** 前端早读主要介绍了抽象语法树AST，生成过程主要是首先词法分析，对代码处理放入一个tockens列表。然后语法分析将数组转换成树形表达式，也就是AST。前端优化主要介绍了异步任务包含宏任务和微任务，Event Loop执行过程是宏任务，微任务，渲染，web worker。


# 100 Days Of Code - 日志

### 第四十九天: 2018年11月30日

**今天的进展：** 阅读了早读文章，学习了前端性能优化9-2。

**思考：** 前端早读主要介绍了ES2018的新特性，最感兴趣的是Promise的finally。前端优化主要是讲解了React和Vue是如何处理更新操作的，主要就是将操作放到数组中批量执行，较少对DOM的操作次数。


# 100 Days Of Code - 日志

### 第五十天: 2018年12月01日

**今天的进展：** 阅读了早读文章，学习了前端性能优化10-1。

**思考：** 前端早读主要介绍了Service Worker的使用。前端优化主要介绍了哪些操作会引发回流和重绘。


# 100 Days Of Code - 日志

### 第五十一天: 2018年12月02日

**今天的进展：** 阅读了早读文章，学习了前端性能优化10-2。

**思考：** 前端早读主要介绍了babel 7的使用。前端优化主要介绍了如何修改DOM来减少触发回流和重绘。


# 100 Days Of Code - 日志

### 第五十二天: 2018年12月03日

**今天的进展：** 阅读了早读文章，学习了前端性能优化11-1。

**思考：** 前端早读主要介绍了什么是内存管理，比较了js和C在内存管理方面的区别。前端优化主要介绍了懒加载。


# 100 Days Of Code - 日志

### 第五十三天: 2018年12月04日

**今天的进展：** 阅读了早读文章，学习了前端性能优化11-2。

**思考：** 前端早读主要介绍了ArrayBuffers 和 SharedArrayBuffers。前端优化主要介绍了懒加载的实现。

# 100 Days Of Code - 日志

### 第五十四天: 2018年12月05日

**今天的进展：** 阅读了早读文章，学习了前端性能优化12-1。

**思考：** 前端早读主要介绍了新的小程序框架。前端优化主要介绍了防抖和节流的原理和实现。


# 100 Days Of Code - 日志

### 第五十五天: 2018年12月06日

**今天的进展：** 阅读了早读文章，学习了前端性能优化12-2。

**思考：** 前端早读主要介绍了如何用JS写一个JS解释器。前端优化主要介绍了利用节流来优化防抖。
