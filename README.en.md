# Chinese Copywriting Guidelines
[![devDependency Status](https://david-dm.org/mzlogin/chinese-copywriting-guidelines/dev-status.svg)](https://david-dm.org/mzlogin/chinese-copywriting-guidelines#info=devDependencies)

Chinese copywriting guidelines for better written communication.

Other languages:

- [English](README.en.md)
- [Chinese Traditional](README.traditional.md)
- [Chinese Simplified](README.md)

-----

## Table of Contents

<!-- vim-markdown-toc GFM -->
* [Spacing](#spacing)
    * [Place one space before/after English words](#place-one-space-beforeafter-english-words)
    * [Place one space before/after numbers](#place-one-space-beforeafter-numbers)
    * [Place one space between numbers and units](#place-one-space-between-numbers-and-units)
    * [No additional spaces before/after punctuation in fullwidth form](#no-additional-spaces-beforeafter-punctuation-in-fullwidth-form)
    * [`-ms-text-autospace` to the rescue?](#-ms-text-autospace-to-the-rescue)
* [Punctuation](#punctuation)
    * [Avoid duplicate punctuation](#avoid-duplicate-punctuation)
* [Fullwidth and halfwidth](#fullwidth-and-halfwidth)
    * [Use punctuation in fullwidth form](#use-punctuation-in-fullwidth-form)
    * [Use numbers in halfwidth form](#use-numbers-in-halfwidth-form)
    * [Use punctuation in halfwidth form for English sentences](#use-punctuation-in-halfwidth-form-for-english-sentences)
* [Nouns](#nouns)
    * [Avoid jargons](#avoid-jargons)
* [Dispute](#dispute)
    * [Add extra spaces before/after links](#add-extra-spaces-beforeafter-links)
    * [Use corner brackets for Chinese Simplified](#use-corner-brackets-for-chinese-simplified)
* [Tools](#tools)
* [Examples of “Who is doing this?”](#examples-of-who-is-doing-this)
* [References](#references)

<!-- vim-markdown-toc -->

## Spacing

「有研究显示，打字的时候不喜欢在中文和英文之间加空格的人，感情路都走得很辛苦，有七成的比例会在 34 岁的时候跟自己不爱的人结婚，而其余三成的人最后只能把遗产留给自己的猫。毕竟爱情跟书写都需要适时地留白。

与大家共勉之。」——[vinta/paranoid-auto-spacing](https://github.com/vinta/pangu.js)

### Place one space before/after English words

Good:

> 在 LeanCloud 上，数据存储是围绕 `AVObject` 进行的。

Bad:

> 在LeanCloud上，数据存储是围绕`AVObject`进行的。

> 在 LeanCloud上，数据存储是围绕`AVObject` 进行的。

An example of complete and correct usage:

> 在 LeanCloud 上，数据存储是围绕 `AVObject` 进行的。每个 `AVObject` 都包含了与 JSON 兼容的 key-value 对应的数据。数据是 schema-free 的，你不需要在每个 `AVObject` 上提前指定存在哪些键，只要直接设定对应的 key-value 即可。

Exceptions: For product and brand names, please refer to the writing format of the official definition. For example, use “豆瓣FM” instead of “豆瓣 FM”.

### Place one space before/after numbers

Good:

> 今天出去买菜花了 5000 元。

Bad:

> 今天出去买菜花了 5000元。

> 今天出去买菜花了5000元。

### Place one space between numbers and units

Good:

> 我家的光纤入户宽带有 10 Gbps，SSD 一共有 20 TB。

Bad:

> 我家的光纤入户宽带有 10Gbps，SSD 一共有 10TB。

Exceptions: There should not be any spacing between numbers and degrees/percentages.

Good:

> 今天是 233° 的高温。

> 新 MacBook Pro 有 15% 的 CPU 性能提升。

Bad:

> 今天是 233 ° 的高温。

> 新 MacBook Pro 有 15 % 的 CPU 性能提升。

### No additional spaces before/after punctuation in fullwidth form

Good:

> 刚刚买了一部 iPhone，好开心！

Bad:

> 刚刚买了一部 iPhone ，好开心！

### `-ms-text-autospace` to the rescue?

Microsoft provides a CSS property [`-ms-text-autospace`](http://msdn.microsoft.com/en-us/library/ie/ms531164(v=vs.85).aspx) that can specify the autospacing and narrow space width adjustment of text. However it's not popular, and on other platforms such as OS X and iOS we can not use this feature. So it's better for you to keep up the habit.

## Punctuation

### Avoid duplicate punctuation

Good:

> 德国队竟然战胜了巴西队！

> 她竟然对你说「喵」？！

Bad:

> 德国队竟然战胜了巴西队！！

> 德国队竟然战胜了巴西队！！！！！！！！

> 她竟然对你说「喵」？？！！

> 她竟然对你说「喵」？！？！？？！！

## Fullwidth and halfwidth

If you’re not familiar with fullwidth and halfwidth forms please refer to [Halfwidth and fullwidth forms](https://en.wikipedia.org/wiki/Halfwidth_and_fullwidth_forms) on Wikipedia.

### Use punctuation in fullwidth form

Good:

> 嗨！你知道嘛？今天前台的小妹跟我说「喵」了哎！

> 核磁共振成像（NMRI）是什么原理都不知道？JFGI！

Bad:

> 嗨! 你知道嘛? 今天前台的小妹跟我说 "喵" 了哎!

> 嗨!你知道嘛?今天前台的小妹跟我说"喵"了哎!

> 核磁共振成像 (NMRI) 是什么原理都不知道? JFGI!

> 核磁共振成像(NMRI)是什么原理都不知道?JFGI!

### Use numbers in halfwidth form

Good:

> 这件蛋糕只卖 1000 元。

Bad:

> 这件蛋糕只卖 １０００ 元。

Exceptions: fullwidth numbers are acceptable for better visual alignment in graphic design.

### Use punctuation in halfwidth form for English sentences

Good:

> 乔布斯那句话是怎么说的？「Stay hungry, stay foolish.」

> 推荐你阅读《Hackers & Painters: Big Ideas from the Computer Age》，非常的有趣。

Bad:

> 乔布斯那句话是怎么说的？「Stay hungry，stay foolish。」

> 推荐你阅读《Hackers＆Painters：Big Ideas from the Computer Age》，非常的有趣。

## Nouns

### Avoid jargons

Good:

> 我们需要一位熟悉 JavaScript、HTML5，至少理解一种框架（如 Backbone.js、AngularJS、React 等）的前端开发者。

Bad:

> 我们需要一位熟悉 Js、h5，至少理解一种框架（如 backbone、angular、RJS 等）的 FED。

## Dispute

The following usages comprise of personal characteristics. As such, from the perspective of copywriting guidelines, they are still correct regardless of whether they comply with the following rules.

### Add extra spaces before/after links

Usage:

> 请 [提交一个 issue](#) 并分配给相关同事。

> 访问我们网站的最新动态，请 [点击这里](#) 进行订阅！

compared with:

> 请[提交一个 issue](#) 并分配给相关同事。

> 访问我们网站的最新动态，请[点击这里](#)进行订阅！

### Use corner brackets for Chinese Simplified

Usage:

> 「老师，『有条不紊』的『紊』是什么意思？」

compared with:

> “老师，‘有条不紊’的‘紊’是什么意思？”

## Tools

Repository| Language
--- | ---
[vinta/paranoid-auto-spacing](https://github.com/vinta/paranoid-auto-spacing) | JavaScript
[huei90/pangu.node](https://github.com/huei90/pangu.node) | Node.js
[huacnlee/auto-correct](https://github.com/huacnlee/auto-correct) | Ruby
[sparanoid/space-lover](https://github.com/sparanoid/space-lover) | PHP (WordPress)
[nauxliu/auto-correct](https://github.com/NauxLiu/auto-correct) | PHP
[hotoo/pangu.vim](https://github.com/hotoo/pangu.vim) | Vim
[sparanoid/grunt-auto-spacing](https://github.com/sparanoid/grunt-auto-spacing) | Node.js (Grunt)
[hjiang/scripts/add-space-between-latin-and-cjk](https://github.com/hjiang/scripts/blob/master/add-space-between-latin-and-cjk) | Python

## Examples of “Who is doing this?”

Website | Copywriting | UGC
--- | --- | ---
[Apple China](http://www.apple.com/cn/) | Yes | N/A
[Apple Hong Kong](http://www.apple.com/hk/) | Yes | N/A
[Apple Taiwan](http://www.apple.com/tw/) | Yes | N/A
[Microsoft China](http://www.microsoft.com/zh-cn/) | Yes | N/A
[Microsoft Hong Kong](http://www.microsoft.com/zh-hk/) | Yes | N/A
[Microsoft Taiwan](http://www.microsoft.com/zh-tw/) | Yes | N/A
[LeanCloud](https://leancloud.cn/) | Yes | N/A
[Zhihu](https://www.zhihu.com/) | Yes | Partial
[V2EX](https://www.v2ex.com/) | Yes | Yes
[SegmentFault](https://segmentfault.com/) | Yes | Partial
[Apple4us](http://apple4us.com/) | Yes | N/A
[Wandoujia](https://www.wandoujia.com/) | Yes | N/A
[Ruby China](https://ruby-china.org/) | Yes | Partial
[PHPHub](https://phphub.org/) | Yes | Partial

## References

- [Guidelines for Using Capital Letters](http://grammar.about.com/od/punctuationandmechanics/a/Guidelines-For-Using-Capital-Letters.htm)
- [Letter case - Wikipedia](http://en.wikipedia.org/wiki/Letter_case)
- [Punctuation - Oxford Dictionaries](http://www.oxforddictionaries.com/words/punctuation)
- [Punctuation - The Purdue OWL](https://owl.english.purdue.edu/owl/section/1/6/)
- [How to Use English Punctuation Corrently - wikiHow](http://www.wikihow.com/Use-English-Punctuation-Correctly)
- [格式 - openSUSE](https://zh.opensuse.org/index.php?title=Help:%E6%A0%BC%E5%BC%8F)
- [全角和半角 - 维基百科](http://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)
- [引号 - 维基百科](http://zh.wikipedia.org/wiki/%E5%BC%95%E8%99%9F)
- [疑问惊叹号 - 维基百科](http://zh.wikipedia.org/wiki/%E7%96%91%E5%95%8F%E9%A9%9A%E5%98%86%E8%99%9F)
