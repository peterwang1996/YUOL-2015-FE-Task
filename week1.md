# 第一周任务

在继续阅读之前，请保证你已经仔细阅读了[这里](https://github.com/peterwang1996/YUOL-2015-FE-Task)的所有内容，并且做完了要求的所有事情。

## 概述

为了给你们足够的时间熟悉 Git 和 Markdown ，本周的任务相对简单，是仿照[长江大学审计处](http://sjc.yangtzeu.edu.cn/)的主页写一个主页。

## 具体要求

- 关于工具的选择，我们目前需要的不是太多，只要有各种浏览器和一个趁手的代码编辑器就可以了，在这里我推荐使用 [Visual Studio Code](https://www.visualstudio.com/products/code-vs) ，[Emmet](http://emmet.io/) 和 [Git](https://git-scm.com/) 的集成、以及丰富的插件可以让我们的编码体验大幅提升，并且，它是免费且开源的。当然，你也可以使用任何你自己惯用的编码工具（如 Sublime Text 和 JetBrains WebStorm），但是**禁止使用诸如 Adobe Dreamweaver 之类的 Drag-and-drop 工具**。
- 在正式开始之前，请确保你已经掌握了 HTML 、 CSS 和 JavaScript 的一些基础内容。如果还没有，请移步下方的参考资料选择相应内容进行学习。
- 只需要做主页，无需做其他页面，所有链接均指向本页，例如 `<a href="#">测试</a>` 。当然，学有余力的同学也可以尝试完成列表页和内容页。
- 在真实的项目中，我们是在拿到 PS 组同学给我们提供的 PSD 格式的效果图来进行切图，然后来进行页面的构架。这里我们没有这个页面的视觉稿，所以我在这里提供一张整个主页的截图，存放在[这里](https://github.com/peterwang1996/YUOL-2015-FE-Task/blob/master/resourses/week1.png)，请用这张截图作为素材进行切图。如果发现素材上一些文字对切片被一些文字遮挡或者干扰，请自行用 Photoshop 进行处理。
- 项目目录最终应该是类似这样：
    ```
    week1
    ├─ images
    |   └─ （对应的图片素材）
    ├─ css
    |   └─ style.css
    ├─ js
    |   └─ main.js
    ├─ README.md
    └─ index.html
    ```
- 可以借鉴原网站和其他地方的代码，但至少你应该明确地了解这些代码每一行都是做什么的。
- 最终的网页应该保证在 IE8 以上，以及最新版的 FireFox 和 Chrome 浏览器中正常显示，学有余力的同学可以尝试兼容 IE7 。
- 请务必注意页面的细节，尽量做到和原网页一致，并且尽量不要使用在内容上没有意义的 DOM 元素。

## 参考资料

- [MDN Web 技术文档](https://developer.mozilla.org/zh-CN/docs/Web)（世界上第二权威的前端资料集散地，关于原生 Web 技术的讲解几乎应有尽有，只是在天朝访问速度较慢，且部分资料是英语）
- [W3School 在线教程](http://www.w3school.com.cn/)（对初学者极友好的前端手册/文字教程集散地，如果之前没有接受过编程方面的训练，推荐先在在这里查文档）
- [HTML+CSS基础课程](http://www.imooc.com/learn/9) & [JavaScript入门篇](http://www.imooc.com/view/36)（慕课网出品的前端基础教程，可以边看边做）
- [HTML5入门](http://study.163.com/course/introduction.htm?courseId=171001#/courseDetail) & [CSS3](http://study.163.com/course/introduction/190001.htm#/courseDetail) & [JavaScript](http://study.163.com/course/introduction/195001.htm#/courseDetail)（网易云课堂上翁恺老师的前端入门系列课程，如果你喜欢视频课程，而且有网易通行证的话，这会是个不错的选择）
- [利用 IE 的开发人员工具解决网站不兼容问题
](https://cnzhx.net/blog/ie-compatibility-developer-tools/)
- [前端开发必备！Emmet使用手册](http://www.w3cplus.com/tools/emmet-cheat-sheet.html)
- [前端工程师必备的PS技能—切图篇-慕课网](http://www.imooc.com/learn/506)
- [IE8+兼容经验小结](http://hustlzp.com/post/2014/01/ie8-compatibility)