# **MRedrock iOS Exam 2017** 
为了大家半期考试好好复习，考核推了一个周~突然有同学说买了演唱会的门票，我们又再推了一个周~这下躲不掉了噻
# **聚餐**
**周六（2017.05.20）晚上**，移动万年不变的传统，就像过年吃年夜饭一样，缓解一下大家考核的紧张气氛，增进一下部门友谊~ 请大家准守移动的传统哈，没有正当理由不许请假（部长说不来扣分,来了加分）

# **考核**
前年题目：图片查看器      
去年题目：音乐播放器      
今年题目：不用我说你们也该知道是啥了

* 考核题目: **一个使用 `百思不得姐` 接口的简易网络视频播放器**
* 考核时间：**5.19 21：00 - 5.21 21：00**
* 考核地点：随意，开心就好，飞机上也行
* 考核对象：iOS
* 提交方式：[GitHub](https://github.com/)  (发送仓库地址 ，不接受邮件压缩文件，嗯，我们懒)

# **注意事项**
* 兼容到 **iOS8.0**
* 可以使用第三方库和框架，但是最好先想想用原生的怎么写，了解原理。
* 请编写好 [GitHub](https://github.com/) 的**README**，最好有截图录屏什么的（我们都懒）
* 请在5.21 21：00 之前 `commit`，之后的 `commit`一律无效
* 导师不回答任何和代码关的问题，谈人生，请吃饭还是可以的
* 放心使用 [Google](https://www.google.com/)、[Bing](https://www.bing.com/)、 ~~[百度](https://www.baidu.com/)~~ 等搜索引擎
* 不要大面积复制网上的代码，被我们看出来就惨了
* **早睡早起，禁止熬夜，合理安排时间！！！**

# **API**
[百思不得姐查询接口](https://www.showapi.com/api/lookPoint/255)
> 文档写得很清楚，自己去注册一个获取下权限!做不到这个的望天吧，说不准老天会帮你。      
> 参数 `type` 写 `41`,我们只需要用它视频的接口，`title`不填返回所有

# **具体内容**

考核内容有**必做题**和**加分项** ( 会标注 ) ，所以请不要被题目吓到！
遇到难题就跳，不要恋战!必做题也不一定全要做出来，赶快前进!       
做不完是正常的，去年的题目也没人做完，不要紧张，尽力去做。      UI不限定，但是要做到自适应~开心噻


**禁止使用UIWebView，请使用`AVFoundation框架` 使用了 UIWebView 扣99.5，给0.5的卷面分（考核满分100）**


### **一、播放列表**
1. 把数据加载出来，用列表（用`tableView`）的形式展示，要求预加载

2. 每个cell需要显示视频的部分具体信息，如视频描述，作者名、**作者头像**等，下图仅作参考

3. **【加分项】** 截取视频第一帧显示在cell上~ 

4. **【加分项】** 在列表直接播放，当cell划出屏幕后停止

    ![example](example.PNG)

### **二、播放控制**
1. 进度条，时间轴，拖动改变视频进度
2. 开始、暂停，结束后重播
3. **【加分项】 重力感应，自动调整横竖屏，不要让我切换横竖屏之后视频从头开始放了**

### **三、播放记录**

1. 播放进度保存，再次播放视频跳转到上次播放的位置
2. 播放记录，按播放时间排序 滑动删除播放记录
3. **【加分项】视频缓存，点击记录加载缓存播放**

### **四、视频下载**

1. 视频下载到本地，**【加分项】下载列表显示下载进度**
2. **【加分项】下载到本地之后再次播放请使用本地数据**



### **五、拓展功能**

1. **【加分项】 视频缓冲，下面的进度条两种，当前播放到的进度，当前缓冲到的进度**
2. **【加分项】评论 点赞 分享功能** 



### **其他**
1. 交互逻辑正常点，不要让我们拿到不知道怎么用
2. 其他你想加的功能，但是不要搞些花里胡哨的界面但是功能啥都没实现
3. UI优美，代码逻辑清晰，有合理封装有加分

