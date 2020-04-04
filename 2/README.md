# 【高校数学】今週の積分 #2 【難易度★★】

<!--
![今週のお題](https://latex.codecogs.com/gif.latex?I=\int_0^{2\pi}\sqrt{1&plus;\cos&space;x}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=cORrgWIjr9g

----
根号があると積分しにくい。

発想：根号は外す

----

半角の公式によると

<!--
![](https://latex.codecogs.com/gif.latex?\cos^2\theta=\frac{1}{2}(1&plus;\cos{2\theta}))
-->
![](1.gif)

なのでこれで根号がはずせそう。

----

<!--
![](https://latex.codecogs.com/gif.latex?\sqrt{1+\cos{x}}=\sqrt{2\cos^2\frac{x}{2}}=\sqrt{2}\left|\cos\frac{x}{2}\right|) 
-->
![](2.gif)

ゆえに

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^{2\pi}\sqrt{2}\left|\cos\frac{x}{2}\right|dx) 
-->
![](3.gif)


----
ここで 

<!--
![](https://latex.codecogs.com/gif.latex?\cos\frac{x}{2})
-->
![](4.gif)

 の符号は、区間 
 
<!--
![](https://latex.codecogs.com/gif.latex?[0,\pi])
-->
![](5.gif)
 
  でプラス、区間 
  
<!--
![](https://latex.codecogs.com/gif.latex?[\pi,2\pi])
-->
![](6.gif)
  
   でマイナスとなることから、次のようになる。


<!--
![](https://latex.codecogs.com/gif.latex?I=\sqrt{2}\int_0^{2\pi}\left|\cos\frac{x}{2}\right|dx=\sqrt{2}\int_0^{\pi}\cos\frac{x}{2}dx-\sqrt{2}\int_\pi^{2\pi}\cos\frac{x}{2}dx) 
-->
![](7.gif)

-----

従って、積分結果は次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?I=2\sqrt{2}\left[\sin\frac{x}{2}\right]_0^{\pi}-2\sqrt{2}\left[\sin\frac{x}{2}\right]_\pi^{2\pi}=2\sqrt{2}-(-2\sqrt{2})=4\sqrt{2})
-->
![](8.gif)


以上。
