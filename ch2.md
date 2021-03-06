## [2.如何判断我的图像是否需要优化?](https://images.guide/#do-my-images-need-optimization)

通过[WebPageTest.org](https://www.webpagetest.org/)执行站点审核，它将有更明显的把优化图像(参见“压缩图像”)到更好的机会。

![](https://yylifen.github.io/images.guide/images/Modern-Image1-large.jpg)

> 网页测试报告中的“压缩图像”部分列出了可以更有效地压缩的图像以及这样做估计可以节省的文件大小。

![](https://yylifen.github.io/images.guide/images/Modern-Image2-medium.jpg)

[Lighthouse](https://developers.google.com/web/tools/lighthouse/)是审核性能的最佳实践工具。包括对图像优化的审核，并可以为可能被进一步压缩的图像提供建议，或者指出屏幕外可延迟加载的图像。

从Chrome 60开始，Lighthouse现在是Chrome DevTools里目前最权威的[审核面板](https://developers.google.com/web/updates/2017/05/devtools-release-notes#lighthouse)：

![](https://yylifen.github.io/images.guide/images/hbo-large.jpg)

> Lighthouse是可以审核Web性能的最佳实践和改进Web应用功能的工具。

你也可能熟悉其他性能审核工具，如[PageSpeed](https://developers.google.com/speed/pagespeed/insights/)、[Insight](https://developers.google.com/speed/pagespeed/insights/)或者通过Cloudinary的[Website Speed Test](https://webspeedtest.cloudinary.com/)，其中包括详细的图像分析审核。
