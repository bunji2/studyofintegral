# 【高校数学】今週の積分#63【難易度★★】

<!--
![](https://latex.codecogs.com/gif.latex?I%3D%5Cint%5Cfrac%7B1%7D%7B3%5E%7B2-5x%7D%7Ddx)
-->
![](0.gif)

https://www.youtube.com/watch?v=p5wpEw7Powo

----

発想：複雑な指数はバラす。

----

とりあえず指数をバラすと…

<!--
![](https://latex.codecogs.com/gif.latex?I%3D%5Cint%5Cfrac%7B1%7D%7B3%5E%7B2-5x%7D%7Ddx%3D%5Cint3%5E%7B5x-2%7Ddx%3D%5Cint%283%5E5%29%5Ex%5Ccdot%203%5E%7B-2%7Ddx%3D3%5E%7B-2%7D%5Cint%7B3%5E5%7D%5Exdx)
-->
![](1.gif)


----

ここで対数微分法を使って 

<!--
![](https://latex.codecogs.com/gif.latex?y%3Da%5Ex)
-->
![](2.gif)

 の微分を考える。

両辺の対数をとる。

<!--
![](https://latex.codecogs.com/gif.latex?%5Clog%7By%7D%3D%5Clog%7Ba%5Ex%7D%3Dx%5Clog%7Ba%7D)
-->
![](3.gif)

両辺を微分すると

<!--
![](https://latex.codecogs.com/gif.latex?%5Cfrac%7By%27%7D%7By%7D%3D%5Clog%7Ba%7D)
-->
![](4.gif)

したがって

<!--
![](https://latex.codecogs.com/gif.latex?y%27%3Dy%5Clog%7Ba%7D%3Da%5Ex%5Clog%7Ba%7D)
-->
![](5.gif)

であることから、

<!--
![](https://latex.codecogs.com/gif.latex?%5Cint%7Ba%5Ex%7Ddx%3D%5Cfrac%7Ba%5Ex%7D%7B%5Clog%7Ba%7D%7D&plus;C)
-->
![](6.gif)

となる。

----

したがって、

<!--
![](https://latex.codecogs.com/gif.latex?I%3D3%5E%7B-2%7D%5Cint%7B3%5E5%7D%5Exdx%3D%5Cfrac%7B3%5E%7B-2%7D%283%5E5%29%5Ex%7D%7B%5Clog%7B3%5E5%7D%7D&plus;C%3D%5Cfrac%7B3%5E%7B5x-2%7D%7D%7B5%5Clog%7B3%7D%7D&plus;C)
-->
![](7.gif)

以上。
