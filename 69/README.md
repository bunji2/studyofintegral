# 【高校数学】今週の積分#69【難易度★★★★】

![I=\int_0^1\frac{2x+2}{x^2+x+1}dx](texclip20200504124140.png)

https://www.youtube.com/watch?v=PEDEjqrRHq4

----

【発想】

(一次式)/(二次式) の場合は、分子に分母の微分形を作る。

----

![I=\int_0^1\frac{2x+2}{x^2+x+1}dx](texclip20200504124140.png)

![texclip20200504124423.png](texclip20200504124423.png)

![=\int_0^1\frac{(x^2+x+1)'}{x^2+x+1}dx+\int_0^1\frac{1}{x^2+x+1}dx](texclip20200504124542.png)

![=[\log|x^2+x+1|]_0^1+\frac{4}{3}\int_0^1\frac{1}{(\frac{2x+1}{\sqrt{3}})^2+1}dx](texclip20200504132004.png)

ここで、

![\frac{2x+1}{\sqrt{3}}=\tan\theta](texclip20200504125231.png)

で置換すると

![dx=\frac{\sqrt{3}}{2}\frac{1}{\cos^2\theta}d\theta](texclip20200504125402.png)

![\frac{x: 0\rightarrow 1}{\theta: \frac{\pi}{6}\rightarrow\frac{\pi}{3}}](texclip20200504130756.png)

より、

![I=\log{3}+\frac{4}{3}\int_0^1\frac{1}{(\frac{2x+1}{\sqrt{3}})^2+1}dx](texclip20200504131737.png)

![=\log{3}+\frac{4}{3}\int_{\frac{\pi}{6}}^{\frac{\pi}{3}}\frac{1}{\tan^2\theta+1}\frac{\sqrt{3}}{2}\frac{1}{\cos^2\theta}d\theta](texclip20200504131843.png)

![=\log{3}+\frac{2\sqrt{3}}{3}\int_{\frac{\pi}{6}}^{\frac{\pi}{3}}1\cdot d\theta](texclip20200504130348.png)

![=\log{3}+\frac{2\sqrt{3}}{3}(\frac{\pi}{3}-\frac{\pi}{6})](texclip20200504130617.png)

![=\log{3}+\frac{\sqrt{3}}{9}\pi](texclip20200504130503.png)