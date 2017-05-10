---
layout: post
title:  前端开源框架
date:   2017-5-10 13:31:01 +0800
categories: document
tags: html
---

* content
{:toc}


转自http://www.cnblogs.com/huangyin1213/p/5750113.html
10大html5前端框架
---
Bootstrap
---

首先说 Bootstrap，估计你也猜到会先说或者一定会有这个( 呵呵了 )，这是说明它的强大之处，拥有框架一壁江山的势气。自己刚入道的时候本着代码任何一个字母都得自己敲出来挡我者废的决心，来让自己成长。结果受到周围各 种基友的引诱开始了 Bootstrap 旅程。本人虽然是个设计+前端的万里有一的人才，但是老天只让我会用 PS 和各种设计工具却不给我跟设计妹子一样的审美，所以这也是我最初选择 Bootstrap 的原因之一，它让我做出来的东西好歹能在妹子面前装个逼，不过时间长了难免觉得 Bootstrap 美的让人烦躁， 但好在它的每个版本都会有很大的改变，不会让人觉得自己做的网站会跟很多网站撞脸。Bootstrap 的用法及其简单( 这也可能就是 Bootstrap 作者阅攻城士无数，了解他们痛的结果 )，以至于是个小前端都可以快速上手，几乎没什么学习成本。

官网：http://getbootstrap.com/

Github：https://github.com/twbs/bootstrap/

作者：Mark Otto 和Jacob Thornton Star：93,112

总结：Bootstrap 最大的优势就是它非常流行，流行就代表你有问题就有很多人帮你解决问题，就代表装逼它就是利器，还有就是界面比较和谐，容易上手，关注它的童鞋应该发现最 新 V4 版也开始支持 FlexBox 布局，这是非常好的升级体验。 劣势是 class 命名不够语义化，并且各种缩写，以至于我离了文档就是个菜，最近开始整混合 APP，选框架的时候首选就是它，但之前搞 PC 一直没注意，后来搞混合右键属性看它的时候，瞬间一阵凉风袭来，Bootstrap 好小，小到我只好选择别的框架。

---
AUI
---

第二个是最近刚起来的AUI，虽然作者声称是专为APICloud开发者设计的一套UI框架，但实际它还是解决了很多移动前端开发的普遍问题，是主 要面向混合开发的 CSS 框架。看起来作者比较猖狂，各种高级 CSS3 遍地使用，这让我也不得不去查查这些个 CSS3 的兼容性。不负众望果然选的都是兼容不错的属性，哈哈了一顿激动从前辈手上大胆认识了几个好东西，并且框架还提供了聊天界面、计数列表等组件，解决了很多 复杂的让我骂娘的布局，现在可以直接拿走就用。

Github：https://github.com/liulangnan/aui

官网：http://www.auicss.com/

作者：流浪男 Star：92

总结：这个框架对我来说有个优点就是纯 CSS 框架，自己以前也就用过 Pure，自己有点 JS 能力，如果不是复杂的效果，找个纯 CSS 框架自己随便改改就可以，而现在 CSS3 也已经能够做到动画，效率、质量、高效全兼顾，所以还是选择了这种 CSS 框架。有一点觉得不满的是这框架的文档真的好那什么，说好的高大上呢。

---
Amaze UI
---
第三个介绍的是妹子UI，最初使用它是因为本尊遇到了一个爱纠结细节设计士，有一次她跟我的字体较上真了，结果一句顶万句的 BOOS 夸了她，我只好根据她的想法去解决，结果最后找到了Amaze UI 框架( 我不介意你叫我懒淫 )，按照官方的话说就是 "基于社区开源项目构建的一个跨屏前端框架，以移动优先，从小屏到大屏，最终实现所有屏幕适配，适应移动互联潮流" 。但其实我就是看中它能解决国内浏览器存在的跨屏适配和兼容性问题。

官网：http://amazeui.org/

Github：https://github.com/amazeui/amazeui

所属公司：云适配 Star：6710

总结：Amaze UI 总的来说就是加入更多符合中国市场特性的元素，框架对跨屏、适配都做了的比较好的处理并且准备一了一系列的常用的网页组 件，为减少搞兼容、适配各种敲键盘的加班狗们的工作时间做了不小的贡献。，框架还对中文排版优化，兼容中国本土主流浏览器、轻量化，不仅适用于桌面端，还 更更适合移动端、包含一些封装好的Widgets。不过自也就我感觉 Amaze UI 文档是否有点太那什么了，比如 “人们不会在乎jQuery的那 点流量。”，说实的在这真没啥，不过我从来不会说出来( 哈哈 )，代码和设计上感觉没太多突出的点。

---
Frozen UI
---

有段时间看到 QQ 瞬间高大上了，后来四处打听，原来 QQ 客服端也用了 混合开发，其中QQ会员前端用的是 Frozen UI，并且这套框架开源，欣喜若狂耐不住心里的寂寞直接上手试了一遍，初体验感觉基础样式效果简单色调清爽，有个比较活跃的社区所以组件什么的也比较丰 富。

Github：https://github.com/frozenui/frozenui

官网：http://frozenui.github.io/

作者： QQVIP FD Team Star：1,067

总结：如果拿 Frozen UI 配合一些如 APICloud 用来做混合 APP 感觉就太酷了，或者原生的火鸡们拿去嵌套在应用中做前端开发，这个框架对 android 2.3 +、ios 4.0 + 做了兼容，或者拿来做 Web App 也是极好的选择，劣势的话从 UI 层面就可以看到了，谁让它是出生在QQ会员前端的呢。

---
WeUIi
---

第五个是WeUI和同 FrozenUI都属于 差不多的 WeUi了，也是一个比较专一的框架，WeUI应该说比FrozenUI前者更专一，话 说连个官网都不搞，所有答疑都在 gitHub Issues 解决了，这个框架极其简单，体积当然就不用说了，模块也就 7 个左右，不过体量虽然小做 的却不错，口碑看 star 就够了，框架从 16/1/23 发版至今 github star 超过 7K,不过也不排除用户没地方发泄所以都跑 到 git 上来，哈哈。

Github：https://github.com/weui/weui

DEMO：http://weui.github.io/weui/

Star：7,129

总结：看完微信设计团队设计的这套 DEMO，二话不说如果要做微信公众，这个二话不说必然是首选了。框架不好的地方简而言之就是框架本身应该就没考虑过让用户用到非微信的场景之下。

---
SUI
---

“SUI 是一套基于bootstrap开发的前端组件库，同时它她也是一套设计规范。通过SUI，可以非常方便的设计和实现精美的页面”。 果然 还是直接引用官方给的枯燥无味广告要节省自己的脑细胞( 囧… )，当然了就像广告说的，如果你之前用过 Bootstrap， 那么可以轻松转 向 SUI，这可能就是淘宝给前端屌丝们的福利了。。 

Github：https://github.com/sdc-alibaba/sui

官网：http://sui.taobao.org/sui/docs/index.html

Star：120

---
MUI
---

曾经一直使用 Android 系统的我，后来见到 IOS，果断移情别恋了，不知道为什么苹果每次调整系统我都特别喜欢，后来一段时间因为缺设计 我专门模仿 IOS 系统做 UI，但始终不能够做到很好，无意间就发现了 MUI 这个框架，这个框架给我的吸引之处就是它的 UI 是以 IOS 为 主体设计的，当然它也补充了android特有UI样式。并且MUI官方声称用来开发深入以后发现拿它做 APP 还能够提高用户使用流畅度，然后便试着 更深入的了解和使用一段时间。

官网：http://dev.dcloud.net.cn/mui/

Github：https://github.com/dcloudio/mui

Star：2,450

总结：就像之前说的这个框架是以两大系统为参照来封装UI组件，框架自身还有一个较为活跃的社区，不太好的地方这也是我特别关注的一点，关于开发应 用的流畅度，我当然知道这是 H5 目前的劣势，但是看到官网给的描述，还是抱着期待的心理试试看能否提升，然而它其实还是需要是借助 Webview来 提升，而不是框架本身。

---
Semantic UI
---

倒数第三个是 Semantic UI，接触这个框架还是因为 Bootstrap，Semantic UI 刚上线 github 就受到大量开发者的关注，以至于很多人拿它俩对比各种挑刺各种夸，是好是坏不能单凭别人三句四句就抬起手指开始赞，用了以后感觉 UI 上跟 Bootstrap 没太多的区别，不过代码命名规范上却相差甚大，本人认为 Semantic UI 是不是就想做的不一样，它的命名全是采用复合的方式，类名特别的离散，用的时候你得很小心自己扩展或者新增的 class 命名与它的类名冲突。

官网：http://www.semantic-ui.cn/

Github：https://github.com/semantic-org/semantic-ui/

---
Foundation
---

Foundation 算是框架界的元老啦，都说框架去的早，而这个框架一直到现在依然这么的热门，如果你比较介意 Bootstrap 开发撞脸的尴尬事情，那么你可以考虑使用 Foundation 。即使你使用预定义的 UI 元素, 也不会与其他网站太像，就像官方说的给开发者更灵活的框架体验。

官网：http://foundation.zurb.com/

Github：https://github.com/zurb/foundation-sites

Star：22,736

---
UiKit
---

UIkit是YOOtheme团队开发的，在许多WordPress主题中都有应用(也就是如果你是个 WordPress 爱好者，那么这个框架应该比较适合深究)，并且框架能够通过GUI编辑器和手动编辑，所以它提供了一个灵活、强大的自定义机制。框架借助LESS、 jQuery、normalize.css及FontAwesome开源项目的独有特点，整合成了这么一款轻量级、模块化的前端框架。

官网：http://www.getuikit.com/
Github：https://github.com/uikit/uikit
作者：YOOtheme Star：6,372

---
Pure
---

终于最后一个了，我和你一样好开森 (～￣▽￣)～)，这个框架是我在做管理系统时接触的，选择使用也是因为框架小巧，并且是纯 CSS，没有太多的牵扯，好用来与其他框架快速结合使用。

官网：http://purecss.io/

Github：https://github.com/yahoo/pure/

Star：13,592

