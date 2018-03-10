![](https://raw.githubusercontent.com/pzhlkj6612/ZhihuPost-23656301/master/pic_zhimg_com/v2-12a27bbf5d319c1f3180729a4992786c.jpg)

转载请注明来源。

<br/>

本文章内容已做极大修改，但未偏离原意；

部分原内容已于 00:02 2017/8/16 转移至新文章，新文章包含了更多可能遇到的问题：

[https://github.com/pzhlkj6612/ZhihuPost-28488426](https://github.com/pzhlkj6612/ZhihuPost-28488426)

<br/>

本文章也存在于GitHub仓库：

[https://github.com/pzhlkj6612/ZhihuPost-23656301](https://github.com/pzhlkj6612/ZhihuPost-23656301)

<br/>

注意：

* 本文并不会持续更新；
* 本文仅适用于Windows用户。

<br/>

# 现象

在新安装的Windows 7 SP1虚拟机上安装Cinema4D R18时出错：

> MAXON-Inst.exe – 无法找到入口    
> (X) 无法定位程序输入点 RemoveDllDirectory于动态链接库KERNEL32.dll上。

![](https://raw.githubusercontent.com/pzhlkj6612/ZhihuPost-23656301/master/pic_zhimg_com/v2-8ebd181febc4464cbfb9a37ceafc3fd2.jpg)

# 解决方法

打上对应操作系统版本的KB2533623：[https://support.microsoft.com/zh-cn/help/2533623](https://support.microsoft.com/zh-cn/help/2533623)

补丁安装结束后建议立即保存所有打开的工作，重新启动计算机以使补丁生效。

<br/>

# 来源

> ...    
> Windows 7, Windows Server 2008 R2, Windows Vista and Windows Server 2008: To call this function in an application, use the GetProcAddress function to retrieve its address from Kernel32.dll. KB2533623 must be installed on the target platform.

[https://msdn.microsoft.com/zh-cn/library/hh310514](https://msdn.microsoft.com/zh-cn/library/hh310514)

<br/>

# 其他

* 来自于IHDT公众号的推送：[http://mp.weixin.qq.com/s/bSdzm71yC6pGeyOdIioqsw](http://mp.weixin.qq.com/s/bSdzm71yC6pGeyOdIioqsw)
* 本文早期版本内容（作者主动投稿）：[http://www.c4d.cn/news-73-1.html](http://www.c4d.cn/news-73-1.html)
* 本文内容的探究过程：[http://tieba.baidu.com/p/4860468715](http://tieba.baidu.com/p/4860468715)
* 被转载的本文内容的探究过程（作者主动投稿）：[http://www.c4d.cn/news-72-1.html](http://www.c4d.cn/news-72-1.html)

<br/>

**强烈建议你使用当前最新版本的CINEMA 4D以及最新版本的正式版操作系统；**

**不懂再问。**

----

[@颜格](http://www.zhihu.com/people/60fb02669c8153429c6f7a8aab70b98e) 提示；

[@司卿](http://www.zhihu.com/people/cd3b49b1a20b771ac5f7d2b2f4a58baa) 指正；

贴吧用户[@cgcgbei](http://tieba.baidu.com/home/main?un=cgcgbei)的回复提示。

<br/>

[@墨子 2200MHz](http://www.zhihu.com/people/faf758840a7dfc528c4f620cdddf1460) 整理。

<br/>

修改于：22:39 2018/01/11

转载请注明来源。