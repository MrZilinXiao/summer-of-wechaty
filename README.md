# 开源软件供应链点亮计划-暑期2020

- [Wechaty 暑期2020 - 开源软件供应链点亮计划官网](https://isrc.iscas.ac.cn/summer2020/#/organisations/wechaty)
- [Wechaty Summer of Code Tasks Slides](https://docs.google.com/presentation/d/1ZLH37rQyRgChGqFCUDjA5rbVgBuRkVM4Tys-_ls0gs0/edit?usp=sharing)

## 开源软件供应链点亮计划-暑期2020”是什么？
“开源软件供应链点亮计划-暑期2020”（以下简称 暑期2020）是由中科院软件所与 openEuler 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

该计划将联合各大开源社区，针对重要开源软件的开发与维护提供 mini 项目，并向全国高校学生开放报名。学生可自主选择感兴趣的项目进行申请，并在中选后获得该软件资深维护者（社区导师）亲自指导的机会。根据项目的难易程度和完成情况，参与者还可获取“开源软件供应链点亮计划-暑期2020”活动奖金和奖杯。

“暑期2020”项目在今年（2020）首次举办，与Google Summer of Code类似，不同点是“暑期2020”只允许中国学生参加，可以看做中国版的GSoC。

官网：https://isrc.iscas.ac.cn/summer2020
官方新闻：http://www.iscas.ac.cn/xshd2016/xshy2016/202004/t20200426_5563484.html

## 活动的主要参与方有哪些？
活动组织方：中国科学院软件研究所、openEuler 社区主办，中国科学院软件研究所中国科学院软件研究所南京软件技术研究院，华为技术有限公司、中科软科技股份有限公司、深圳华锐金融技术股份有限公司等公司协办，此外，活动组组委会还联合国内公司、科研院所和各大高校共同推广此次活动。

活动参与方主要角色为学生、社区和导师。

学生：学生自由选择项目，与导师沟通实现方案并撰写项目计划书。被选中的学生将在导师指导下，按计划完成开发工作，并将成果贡献给社区。社区评估学生的完成度，主办方根据评估结果发放资助金额给学生。
社区：社区提供项目列表和描述，并安排项目对应的导师，导师与申请者沟通方案、并从申请者中选中一位承接项目。在为期三个月的开发周期中，导师指导学生进行对应项目的开发工作。
导师：社区针对每一个项目指定一个导师，与学生一起制定合适的开发计划和方案，指导学生按计划完成开发。
项目的奖金额度是多少？
项目难度分为高、中、低三档，对应税前奖金分别为高（12000 元）、中（9000 元）、低（6000 元）。

# Wechaty Code in Summer 2020

[Wechaty 社区暑期2020点亮计划](https://github.com/wechaty/summer-of-code)

## Wechaty 是什么

Wechaty 是一个开源聊天机器人框架SDK，具有高度封装、高可用的特性，支持NodeJs,  Python,  Go 和Java 等多语言版本。在过去的4年中，服务了数万名开发者，收获了 Github 的 8000 Star。同时配置了完整的 DevOps 体系并持续按照 Apache 的方式管理技术社区。

[![Wechaty](https://wechaty.github.io/wechaty/images/wechaty-logo-green-en.png)](https://github.com/wechaty/wechaty)

[![Downloads](https://img.shields.io/npm/dm/wechaty.svg?style=flat-square)](https://www.npmjs.com/package/wechaty)
[![GitHub stars](https://img.shields.io/github/stars/wechaty/wechaty.svg?label=github%20stars)](https://github.com/wechaty/wechaty)
[![Docker Pulls](https://img.shields.io/docker/pulls/zixia/wechaty.svg?maxAge=2592000)](https://hub.docker.com/r/zixia/wechaty/)
[![TypeScript](https://img.shields.io/badge/%3C%2F%3E-TypeScript-blue.svg)](https://www.typescriptlang.org/)
[![Gitter](https://badges.gitter.im/Chatie/wechaty.svg)](https://gitter.im/Chatie/wechaty?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

## Connecting Chatbots

Wechaty is a Conversational AI RPA Chatbot SDK for Wechat **Individual** Account which can help you create a bot in 6 lines of [JavaScript](https://GitHub.com/Wechaty/wechaty), [Python](https://GitHub.com/Wechaty/python-wechaty/), [Go](https://GitHub.com/Wechaty/go-wechaty/), and [Java](https://GitHub.com/Wechaty/java-wechaty/), with cross-platform support including [Linux, Windows, MacOS](https://github.com/wechaty/wechaty/actions?query=workflow%3ANPM), and [Docker](https://github.com/wechaty/wechaty/actions?query=workflow%3ADocker).

:octocat: <https://github.com/Wechaty/wechaty>  
:beetle: <https://github.com/Wechaty/wechaty/issues>  
:book: <https://github.com/Wechaty/wechaty/wiki>  
:whale: <https://hub.docker.com/r/zixia/wechaty>  

## Voice of Developers

> "Wechaty is a great solution, I believe there would be much more users recognize it." [link](https://github.com/Wechaty/wechaty/pull/310#issuecomment-285574472)  
> &mdash; <cite>@Gcaufy, Tencent Engineer, Author of [WePY](https://github.com/Tencent/wepy)</cite>
>
> "太好用，好用的想哭"  
> &mdash; <cite>@xinbenlv, Google Engineer, Founder of HaoShiYou.org</cite>
>
> "最好的微信开发库" [link](http://weibo.com/3296245513/Ec4iNp9Ld?type=comment)  
> &mdash; <cite>@Jarvis, Baidu Engineer</cite>
>
> "Wechaty让运营人员更多的时间思考如何进行活动策划、留存用户，商业变现" [link](http://mp.weixin.qq.com/s/dWHAj8XtiKG-1fIS5Og79g)  
> &mdash; <cite>@lijiarui, Founder & CEO of Juzi.BOT.</cite>
>
> "If you know js ... try Wechaty, it's easy to use."  
> &mdash; <cite>@Urinx Uri Lee, Author of [WeixinBot(Python)](https://github.com/Urinx/WeixinBot)</cite>
>
> "Wechaty is a good project, I hope it can continue! Therefore, I became a contributors in open collective."  
> &mdash; <cite>[@Simple](https://github.com/mrwhh)</cite>

## Wechaty 希望实现的新进展及可选项目列表

Wechaty 希望实现多平台、多语言、多功能三个层次，成为易用度最高、可迁移性最强的聊天机器人框架。    
多平台是指，在现有的基于微信个人号的聊天机器人框架基础上，逐渐覆盖包括企业微信、钉钉、飞书的多个IM，并通过封装同一套应用层代码的形式，仅更改一个变量就将同一套聊天机器人代码迁移到多个平台中。
多语言是指，针对同一套功能，能使用多种编程语言调用不同功能、不同平台的微信机器人，并通过打通多语言之间的通路，实现针对每门语言开发的功能都能同步到其余所有语言中。 
多功能是指，在 Wechaty 已经上线的插件系统的基础上，将特定功能按一定形式封装成接口，让其他开发者可以以仅添加短至一行代码的方式，使用原有数百行代码才能完成的功能。    


### 多平台（Muti-Plat）
- （难度：高）基于开放 API 封装 Wechaty 接口下的企业微信聊天机器人（https://github.com/wechaty/summer-of-code/issues/2）
- （难度：高）基于开放 API 封装 Wechaty 接口下的钉钉聊天机器人（https://github.com/wechaty/summer-of-code/issues/11）
- （难度：高）基于开放 API 封装 Wechaty 接口下的飞书聊天机器人（https://github.com/wechaty/summer-of-code/issues/12）
- （难度：高）基于 RPA 封装 Wechaty 接口下的抖音聊天机器人（https://github.com/wechaty/summer-of-code/issues/13）
- （难度：高）基于 RPA 封装 Wechaty 接口下的快手聊天机器人（https://github.com/wechaty/summer-of-code/issues/14）
### 多语言（Muti-Lang）
- （难度：中）为 go-wechaty 设计实现 插件体系（https://github.com/wechaty/summer-of-code/issues/9）
- （难度：中）Go-wechaty Github Action optimization（https://github.com/wechaty/summer-of-code/issues/8）
- （难度：低）Wechaty Java 移植组件开发（https://github.com/wechaty/summer-of-code/issues/4）
### 多功能（Plugin）
- （难度：中）基于python-wechaty的群聊助手机器人（https://github.com/wechaty/summer-of-code/issues/6）
- （难度：中）基于Python-wechaty建立一个斗图机器人（https://github.com/wechaty/summer-of-code/issues/7）
- （难度：低）编写一个“每日一句”插件（https://github.com/wechaty/summer-of-code/issues/10）


# 投递要求
申请学生需要同时完成以下“联系社区”和“官网投递”两个环节：

1. 联系社区（2020年5月15日至6月20日）
扫描二维码添加 Wechaty 社区官方机器人 Friday BOT
![Friday BOT](https://camo.githubusercontent.com/48e830f95ba1e018c365013991e685951b8cf5f4/68747470733a2f2f776563686174792e6769746875622e696f2f776563686174792f696d616765732f626f742d71722d636f64652e706e67)  
确定认领项目后，由社区官方机器人拉群，开始任务推进。
2. 官网投递（2020年6月1日至6月20日）
详见：https://isrc.iscas.ac.cn/summer2020/help/student.html#学生如何报名
