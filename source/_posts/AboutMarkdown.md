title: "Markdown初探"
date: 
categories: Markdown笔记
tags: [Markdown,语法]
description: 这是我的第一篇用Mardown写的文章，我向来是不太喜欢写东西的，就算连上课的笔记都懒得记，因为我对我的记忆力深信不疑，不过每到学期期末的时候只好抱佛脚找同学借笔记，所以这算是我亲自动手在自己搭建的博客上写的第一篇软文吧，希望可以将自己的想法和思考分享给这个世界。
---
**摘要**：*这篇文章包括：（1）完全没有逻辑的一个蛇精病的胡言乱语（2）写博客的起源（3）带你进入Markdown的大坑*
<!--more-->
这是我的第一篇用Mardown写的文章，我向来是不太喜欢写东西的，就算连上课的笔记都懒得记，因为我对我的记忆力深信不疑，不过每到学期期末的时候只好抱佛脚找同学借笔记，所以这算是我亲自动手在自己搭建的博客上写的第一篇软文吧，希望可以将自己的想法和思考分享给这个世界。

嗯，这是一个不错的开始不是吗，我已经有了自己的第一个博客，敲下了第一行代码，写下了第一篇文章，所有的想法都不仅仅只存在我的脑海之中，我对这个世界不再是只有INPUT了，这些INPUT的东西在我脑海里发酵发酵，变成了香喷喷的面包，再继续发酵发酵着，最终终于身成功就圆满的完成它们的使命——变成了一坨屎，被我给排泄出去，甚至还引发了一阵恶臭，我按下抽水马桶的按钮，忘记了那坨屎和它本来的面貌。

无数个想法在我脑海中激荡，无数个日日夜夜难以入眠，无数次的上课神游，无数次心理并在生理的高潮，无数次如此的接近人生的高峰，但是我却过着一如既往的生活，就好像我从乘坐宇宙飞船游飞跃了太阳系，将土星的光圈戴在我的手指上，将那牛郎织女的银河化作斗篷披在我的身上，但是我又必须回到我起飞的地方，没有人为我鼓掌，没有人为我欢呼，甚至连个人影都没有，第二天，我又早起迎接太阳神阿波罗的恩赐——扫我的大马路去了，但是那失重的快感将永远存在我的世界里，我用力一挥扫帚，又是一个宇宙。

好吧，想象力又开始乱挥了，这篇文章就算是给我一个巴掌吧，响亮的巴掌，伴着阵阵回音……

##关于博客
最早是12年的时候在 [36氪](36kr.com "36氪") 看到一篇关于外国创业公司   [Medium](medium.com "medium") 的报道，由于是Twitter的两位创始人Josh Miller 与 Evan Williams创建的，所以格外关注，但是Medium本身还是深深感动了我，在一个繁华浮躁的网络上居然有一片能够让人们分享内心所思所想的一片净土，极致简介的设计，去除繁杂的功能，就是为了让作者更加专注写作，读者着专注于阅读，每一篇文章都精美像一篇时尚杂志，沉浸式的体验让人们从阅读写作中获得快感，不过由于我的英文水平实在不怎么样，没有坚持下去，果断放弃。

后来无意了解到国内了本土创业公司 [简书](jianshu.io "简书")，主要是在V2EX论坛看关于DNS的文章时被带到一个hexo搭建的博客，由于界面精美所以们生了用hexo托管在github上搭建博客的想法，这就是这个博客的由来，由于找资料的时候不小失足掉入简书这个大坑，互联网简直就是一个黑洞啊，它能够把你从一粒灰尘吸入另一个世界，各个世界的由连接这个东西联系成一个整体，只要你不断的加速翻转跳跃，总能找到你的那一张床，然后你躺上去，晚安。

简书里面的很多文章虽然不能和一些作家相提并论，但是都可以看出大家都是认真在写作，一些文章还是深深触动了我，比如东湖老师的 [你不是书读得少，你是经典读得少](http://jianshu.io/p/53d918a3fe52)，可能人类就是这样吧，对自己亲生经历过的事总是历历在目，每一次他们总能从一些微尘中看到自己，或爱，或恨，或恐惧，或伤心，所以我们有时能看到那些对着屎或笑，或哭，或作娇嗔状，或咬牙切齿的人，没有人知道为什么，因为谁也没有尝过，也重来没有人问过，就算是问了，也不会有人回答你，因为没有人会告诉你他吃过屎。

但是，在我们的生活中却能看到那些吃了屎，手舞足蹈在马路上奔走相告的人，在这个时代这种无私的人类还真是少见啊，于是大家就形成了一个党派，目的是让更多的人能够吃到屎，于是全人类都吃上了屎，你吃我的屎，我吃你的屎，过上了幸福快乐的生活。

好吧，好像再次离题了，或者根本就没有点到题……

##关于Medium
这篇文章就是用Medium写的，虽然软之又软且毫无养分，但是我献身证明了
>*这种狗血的写作方式是能够让一个呆子瞬间化身成胡言乱语流着唾液到处乱咬人的疯子的。*

Medium专为写作而生，和HTML的标签说拜拜，只需要用一些简单的字符就可以完成文章的排版工作。
下面是一个栗子：
    
	#hello world --> <h1>hello world</h1> #使用一号标题
	**这是粗体markdown** --> <b>这是粗体html</b> #使用粗体
	*这是斜体markdown* --> <i>这是斜体html</i> #使用斜体
果然动起笔来爽到爆啊，可以省去好多`< ></ >`,根本停不下来。




