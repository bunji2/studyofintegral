# 【高校数学】今週の積分 #1 【難易度★★】

<!--
![今週のお題](https://latex.codecogs.com/gif.latex?I=\int\tan^3xdx)
-->
![](0.gif)

https://www.youtube.com/watch?v=vm7LcyupMs0

----
三角関数が出てくる積分の場合まず考えること。

発想：三角関数は二乗に強い。

----

まずは二乗を抜き出してみる。

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\tan^3xdx=\int\tan&space;x\cdot\tan^2xdx) 
-->
![](1.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\tan^2x)
-->
![](2.gif)
 を展開して変形させる。 

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\tan&space;x\left(\frac{1}{\cos^2x}-1\right)dx=\int\tan&space;x\cdot\frac{1}{\cos^2x}dx-\int\tan&space;xdx)
-->
![](3.gif)

-----

ここで

<!--
![](https://latex.codecogs.com/gif.latex?(\tan&space;x)'=\frac{1}{\cos^2x})
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\tan&space;x=\frac{\sin&space;x}{\cos&space;x}=-\frac{(\cos&space;x)'}{\cos&space;x}dx)
-->
![](5.gif)

であることに注目して変形すると

----

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\tan&space;x\cdot(\tan&space;x)'dx&plus;\int\frac{(\cos&space;x)'}{\cos&space;x}dx)
-->
![](6.gif)

----

そして以下がなりたつ。

<!--
![](https://latex.codecogs.com/gif.latex?\int&space;(f(x))^n\cdot(f(x))'dx=\frac{1}{n&plus;1}(f(x))^{n&plus;1}&plus;C)
-->
![](7.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\int\frac{(f(x))'}{f(x)}dx=\log|f(x)|&plus;C)
-->
![](8.gif)

----

従って積分結果は次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\tan&space;x\cdot(\tan&space;x)'dx&plus;\int\frac{(\cos&space;x)'}{\cos&space;x}dx=\frac{1}{2}\tan^2x&plus;\log|\cos&space;x|&plus;C)
-->
![](9.gif)

以上。
