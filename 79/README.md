# 【高校数学】今週の積分#79【難易度★★★】

![\begin{eqnarray}
I=\int\dfrac{1}{\cos{x}}dx\nonumber
\end{eqnarray}](texclip20200714234945.png)

https://www.youtube.com/watch?v=OsFDJgsaox0

----

![\begin{eqnarray}
I&=&\int\dfrac{1}{\cos{x}}dx\nonumber\\
 &=&\int\dfrac{\cos{x}}{\cos^2{x}}dx\nonumber\\
 &=&\int\dfrac{\cos{x}}{1-\sin^2{x}}dx\nonumber
\end{eqnarray}](texclip20200715000239.png)

置換積分をおこなう。

![\begin{eqnarray}
t&=&\sin{x}\nonumber\\
dt&=&\cos{x}dx\nonumber
\end{eqnarray}](texclip20200715000429.png)

![\begin{eqnarray}
I&=&\int\dfrac{\cos{x}}{1-\sin^2{x}}dx\nonumber\\
 &=&\int\dfrac{1}{1-t^2}dt\nonumber\\
 &=&\int\dfrac{1}{(1+t)(1-t)}dt\nonumber\\
 &=&\dfrac{1}{2}\int\left(\dfrac{1}{t+1}-\dfrac{1}{t-1}\right)dt\nonumber\\
 &=&\dfrac{1}{2}\left(\log{|t+1|}-\log{|t-1|}\right)\nonumber\\
 &=&\dfrac{1}{2}\left(\log{|\sin{x}+1|}-\log{|\sin{x}-1|}\right)\nonumber\\
 &=&\dfrac{1}{2}\left(\log{|\sin{x}+1|}-\log{|1-\sin{x}|}\right)\nonumber\\
 &=&\dfrac{1}{2}\log\left|\dfrac{1+\sin{x}}{1-\sin{x}}\right|
 \end{eqnarray}](texclip20200715002611.png)

----

別解。

![\setcounter{equation}{1}
\begin{eqnarray}
I&=&\int\dfrac{1}{\cos{x}}dx\nonumber\\
 &=&\int\dfrac{1}{\cos{x}}\cdot\dfrac{\frac{1}{\cos{x}}+\tan{x}}{\frac{1}{\cos{x}}+\tan{x}}dx\nonumber\\
 &=&\int\dfrac{\frac{1}{\cos^2{x}}+\tan{x}}{\frac{1}{\cos{x}}+\tan{x}}dx\nonumber\\
 &=&\int\dfrac{(\frac{1}{\cos{x}}+\tan{x})'}{\frac{1}{\cos{x}}+\tan{x}}dx\nonumber\\
 &=&\log\left|\dfrac{1}{\cos{x}}+\tan{x}\right|+C
\end{eqnarray}](texclip20200715001715.png)


----

(1) = (2) の確認。

![\begin{eqnarray}
(1)&=&\dfrac{1}{2}\log\left|\dfrac{1+\sin{x}}{1-\sin{x}}\right|\nonumber\\
   &=&\dfrac{1}{2}\log\left|\dfrac{1+\sin{x}}{1-\sin{x}}\cdot\dfrac{1+\sin{x}}{1+\sin{x}}\right|\nonumber\\
   &=&\dfrac{1}{2}\log\left|\dfrac{(1+\sin{x})^2}{\cos^2{x}}\right|\nonumber\\
   &=&\dfrac{1}{2}\log\left|\left(\dfrac{1+\sin{x}}{\cos{x}}\right)^2\right|\nonumber\\
   &=&\log\left|\dfrac{1+\sin{x}}{\cos{x}}\right|\nonumber\\
   &=&\log\left|\dfrac{1}{\cos{x}}+\tan{x}\right|\nonumber\\
   &=&(2)\nonumber
\end{eqnarray}](texclip20200715002453.png)