### Parameters/Legend 圖例說明


##### title: 圖例中顯示點線混合符號 (date: 2017.8.5) - ref:  [ 圖例中顯示點線混合符號 legend](http://rwepa.blogspot.tw/2017/08/legend.html)

x1 <- c(1,2,5,4,3)
x2 <- c(4, 1.5, 1.9, 3, 7)
x3 <- c(5, 6, 9, 3, 1)
ymax <- max(c(x1,x2,x3)) + 1.5
plot(x1, type = "b", pch = 19, lty = 1, col = 1, 
 ylim = c(0, ymax), 
 main="圖例中顯示點線混合符號")
points(x2, pch = 17, col = 2)
lines(x3, lty = 2, col = 4)
legend("topleft", legend = c("x1", "x2", "x3"),
 pch = c(19, 17, NA), lty = c(1, NA, 2),
 col = c(1, 2, 4), text.col = c(1,2,4))

![](/assets/legends_case01.jpeg)

from [圖例中顯示點線混合符號 legend](http://rwepa.blogspot.tw/2017/08/legend.html)


----

#### Reference: 
- []()