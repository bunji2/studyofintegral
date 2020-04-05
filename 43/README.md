# 【高校数学】今週の積分#43【難易度★★★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^\pi\frac{x\sin&space;x}{8&plus;\sin^2x}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=lLhsvW8VqQ0


----

発想：

<!--
![](https://latex.codecogs.com/gif.latex?\int_0^\pi{x}f(\sin{x})dx=\frac{\pi}{2}\int_0^\pi{f(\sin{x})}dx)
-->
![](1.gif)

----


<!--
![](https://latex.codecogs.com/gif.latex?\int_0^\pi{x}f(\sin{x})dx)
-->
![](2.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_0^\pi(\pi-t)f(\sin(\pi-t))dt)
-->
![](3.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\pi\int_0^{\pi}f(\sin{t})dt-\int_0^{\pi}tf(\sin{t})dt)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\pi\int_0^{\pi}f(\sin{x})dx-\int_0^{\pi}xf(\sin{x})dx)
-->
![](5.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\therefore\int_0^{\pi}xf(\sin{x})dx=\frac{\pi}{2}\int_0^{\pi}f(\sin{x})dx)
-->
![](6.gif)

----
よって、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{\pi}{2}\int_0^\pi\frac{\sin{x}}{8&plus;\sin^2x}dx)
-->
![](7.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi}{2}\int_0^\pi\frac{\sin{x}}{9-\cos^2x}dx)
-->
![](8.gif)

----

ここで次の置換を行う。

<!--
![](https://latex.codecogs.com/gif.latex?t=\cos{x})
-->
![](9.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\frac{x:0\rightarrow\pi}{t:1\rightarrow{-1}})
-->
![](10.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dt=-\sin{x}dx)
-->
![](11.gif)

----

従って、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{\pi}{2}\int_{-1}^{1}\frac{1}{9-t^2}dt)
-->
![](12.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi}{2}\int_{-1}^{1}\frac{1}{(3-t)(3&plus;t)}dt)
-->
![](13.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi}{12}\int_{-1}^{1}\left(\frac{1}{3-t}&plus;\frac{1}{3&plus;t}\right)dt)
-->
![](14.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi}{12}\left[-\log|3-t|&plus;\log|3&plus;t|\right]_{-1}^{1})
-->
![](15.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi}{12}\left(-\log{2}&plus;2\log{2}&plus;2\log{2}-\log{2}\right))
-->
![](16.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\pi}{6}\log{2})
-->
![](17.gif)

以上。
