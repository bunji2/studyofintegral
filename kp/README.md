# King Property

<!--
![](https://latex.codecogs.com/gif.latex?\int_a^b{f(x)}dx=\int_a^b{f(a&plus;b-x)dx})
-->
![](0.gif)

https://www.youtube.com/watch?v=xIvYvac4Ok8

----

<!--
![](https://latex.codecogs.com/gif.latex?\int_a^b{f(x)}dx=\int_a^b{f(a&plus;b-x)dx})
-->
![](1.gif)

あるいは

<!--
![](https://latex.codecogs.com/gif.latex?\int_0^b{f(x)}dx=\int_0^b{f(b-x)dx})
-->
![](2.gif)

----

(証明)

<!--
![](https://latex.codecogs.com/gif.latex?u=a&plus;b-x)
-->
![](3.gif)

とおくと、

<!--
![](https://latex.codecogs.com/gif.latex?du=-dx)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x:a\rightarrow{b})
-->
![](5.gif)

<!--
![](https://latex.codecogs.com/gif.latex?u:b\rightarrow{a})
-->
![](6.gif)

したがって、

<!--
![](https://latex.codecogs.com/gif.latex?\int_a^b{f(a&plus;b-x)dx})
-->
![](7.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_b^a{f(u)}\cdot(-1)du)
-->
![](8.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_a^b{f(u)}du)
-->
![](9.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_a^b{f(x)}dx)
-->
![](10.gif)

----

King Property で何ができる？

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_a^b{f(x)}dx=\int_a^b{f(a&plus;b-x)}dx)
-->
![](11.gif)

少し変形すると、

<!--
![](https://latex.codecogs.com/gif.latex?2I=\int_a^b{f(x)+f(a&plus;b-x)}dx)
-->
![](12.gif)

となる。

<!--
![](https://latex.codecogs.com/gif.latex?f(x)&plus;f(a&plus;b-x))
-->
![](13.gif)

の部分が簡単な形をしていれば、そこから I の値を求めることができる。

----

例1

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_2^3\frac{x^2}{x^2&plus;(5-x)^2}dx)
-->
![](14.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x\rightarrow5-x)
-->
![](15.gif)

<!--
![](https://latex.codecogs.com/gif.latex?2I=\int_2^3\left\{\frac{x^2}{x^2&plus;(5-x)^2}&plus;\frac{(5-x)^2}{(5-x)^2&plus;x^2}\right\}dx)
-->
![](16.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_2^3dx)
-->
![](17.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=1)
-->
![](18.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\therefore&space;I=\frac{1}{2})
-->
![](19.gif)

----

例2

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^{\pi}\frac{x\sin&space;x}{1&plus;\cos^2&space;x}dx)
-->
![](20.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x\rightarrow\pi-x)
-->
![](21.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\sin(\pi-x)=\sin{x},&space;\cos(\pi-x)=-\cos{x})
-->
![](22.gif)

<!--
![](https://latex.codecogs.com/gif.latex?2I=\int_0^{\pi}\left\{\frac{x\sin&space;x}{1&plus;\cos^2&space;x}&plus;&space;\frac{(\pi-x)\sin(\pi-x)}{1&plus;\cos^2(\pi-x)}&space;\right\}dx)
-->
![](23.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_0^{\pi}\left\{\frac{x\sin&space;x}{1&plus;\cos^2&space;x}&plus;\frac{(\pi-x)\sin&space;x}{1&plus;\cos^2&space;x}\right\}dx)
-->
![](24.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\pi\int_0^{\pi}\frac{\sin&space;x}{1&plus;\cos^2&space;x}dx)
-->
![](25.gif)

ここで置換する。

<!--
![](https://latex.codecogs.com/gif.latex?t=\cos{x},&space;dt=-\sin{x}dx)
-->
![](26.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x:0\rightarrow\pi)
-->
![](27.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t:1\rightarrow{-1})
-->
![](28.gif)

より、

<!--
![](https://latex.codecogs.com/gif.latex?2I=\pi\int_{-1}^1\frac{1}{1&plus;t^2}dt)
-->
![](29.gif)

となるのでまたも置換する。

<!--
![](https://latex.codecogs.com/gif.latex?t=\tan\theta,&space;dt=\frac{1}{\cos^2\theta}d\theta)
-->
![](30.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t:-1\rightarrow{1})
-->
![](31.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\theta:-\frac{\pi}{4}\rightarrow\frac{\pi}{4})
-->
![](32.gif)

より、

<!--
![](https://latex.codecogs.com/gif.latex?2I=\int_{\frac{\pi}{4}}^{\frac{\pi}{4}}d\theta)
-->
![](33.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi^2}{2})
-->
![](34.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\therefore&space;I=\frac{\pi^2}{4})
-->
![](35.gif)
