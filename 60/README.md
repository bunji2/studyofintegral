# 【高校数学】今週の積分 #60 【難易度★★★】

<!--
![今週のお題](https://latex.codecogs.com/gif.latex?I=\int_{\sqrt{2}}^2\left(\frac{1}{x\sqrt{x^2-1}}\right)dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=ICdosy8T744

----

根号があると、積分はやりにくい。というわけで、

発想：根号は基本的に外す。

----

<!--
![](https://latex.codecogs.com/gif.latex?t=\sqrt{x^2-1})
-->
![](1.gif)

 とおくと 
 
<!--
![](https://latex.codecogs.com/gif.latex?x^2=t^2&plus;1)
-->
![](2.gif)
 
 となるので、

----

<!--
![](https://latex.codecogs.com/gif.latex?dt=\frac{x}{\sqrt{x^2-1}}dx)
-->
![](3.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x:\sqrt{2}\rightarrow2)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t:1\rightarrow\sqrt{3})
-->
![](5.gif)

----

ゆえに置換積分すると次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?\int_{\sqrt{2}}^2\left(\frac{1}{x\sqrt{x^2-1}}\right)dx=\int_1^{\sqrt{3}}\frac{1}{x^2}dt=\int_1^{\sqrt{3}}\frac{1}{t^2&plus;1}dt)
-->
![](6.gif)

ここで、

<!--
![](https://latex.codecogs.com/gif.latex?t=\tan\theta)
-->
![](7.gif)

 とおけば、

----

<!--
![](https://latex.codecogs.com/gif.latex?dt=\frac{1}{\cos^2\theta}d\theta)
-->
![](8.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t:1\rightarrow\sqrt{3})
-->
![](9.gif)

<!--
![](https://latex.codecogs.com/gif.latex?%5Ctheta%3A%5Cfrac%7B%5Cpi%7D%7B4%7D%5Crightarrow%5Cfrac%7B%5Cpi%7D%7B3%7D)
-->
![](10.gif)

----

ゆえに再び置換積分すると次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?%5Cint_1%5E%7B%5Csqrt%7B3%7D%7D%5Cfrac%7B1%7D%7Bt%5E2&plus;1%7Ddt%3D%5Cint_%5Cfrac%7B%5Cpi%7D%7B4%7D%5E%5Cfrac%7B%5Cpi%7D%7B3%7D%5Cfrac%7B1%7D%7B%5Ctan%5E2%5Ctheta&plus;1%7D%5Ccdot%5Cfrac%7B1%7D%7B%5Ccos%5E2%5Ctheta%7Dd%5Ctheta%3D%5Cint_%5Cfrac%7B%5Cpi%7D%7B4%7D%5E%5Cfrac%7B%5Cpi%7D%7B3%7Dd%5Ctheta%3D%5Cfrac%7B%5Cpi%7D%7B3%7D-%5Cfrac%7B%5Cpi%7D%7B4%7D%3D%5Cfrac%7B%5Cpi%7D%7B12%7D)
-->
![](11.gif)

以上。

----
# Maxima でも確認してみた。

Windows 版の Maxima を使用。

```
C:\work>C:\maxima-5.43.2\bin\maxima --version
Maxima 5.43.2
```

作成した Maxima コード (60.txt)

```
integrate(1/(x*sqrt(x^2-1)),x,sqrt(2),2)$
quit()$
```

とりあえずコマンドラインから Maxima で積分させてみよう：

```
C:\work>C:\maxima-5.43.2\bin\maxima --very-quiet -b 60.txt
batch("60.txt")

read and interpret C:/work/60.txt
integrate(1/(x*sqrt(x^2-1)),x,sqrt(2),2)
                                      %pi
                                      ---
                                      12
quit()

```

速い。一瞬で積分結果が出力される。ASCII ART で分数って目新しい。

調べてみたら、Maxima は LaTeX で出力させることも可能とのことなので、
LaTeX で積分結果を出力させるコードを作成 (60tex.txt)

```
load("mactex-utilities.lisp")$
tex(integrate(1/(x*sqrt(x^2-1)),x,sqrt(2),2))$
quit()$
```

Maxima で積分結果を LaTeX で出力したところ。

```
C:\work>C:\maxima-5.43.2\bin\maxima --very-quiet -b 60tex.txt
batch("60tex.txt")

read and interpret C:/work/60tex.txt
load("mactex-utilities.lisp")
tex(integrate(1/(x*sqrt(x^2-1)),x,sqrt(2),2))
$$\frac{\pi}{12}$$
quit()
```

積分結果が $$\frac{\pi}{12}$$ と LaTeX の構文で出力された。

以上。
