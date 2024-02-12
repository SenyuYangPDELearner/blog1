<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>
# 张灯结彩：照亮球的表面需要多少盏灯

这篇博客的主题正如标题，下面用较严格的语言叙述它：

> 在欧氏空间$\mathbf{R}^3$中有一个单位球$B$(球心在原点，半径为$1$), 请问在$B$外至少需要多少个点光源才能照亮它的整个外表面(二维单位球面$S^2$)？

我们对点光源个数$n$分类讨论. 很快就会发现，一个点光源能照亮的面积严格小于$S^2$表面积的一半, 所以$n=1,2$肯定不行. 
