一直以为Airbnb 电面以面经为主，花了整整一个礼拜看以前的面经，结果出了一个新题。。光搞清楚题就花了好久。。。小哥冷冷的，一点提示都没有，最后代码都没写完。
不说废话，直接上题。

Given an array of numbers A = [x1, x2, ..., xn] and T = Round(x1+x2+... +xn). 
We want to find a way to round each element in A such that after rounding we get a new array B = [y1, y2, ...., yn] such that y1+y2+...+yn = T where  yi = Floor(xi) or Ceil(xi), ceiling or floor of xi.
We also want to minimize sum |x_i-y_i|


我一开始给了一个brute force, 就是穷据，复杂度2^n. 但是小哥说有更快的解法。。试了好几个都没做出来。看看大家能不能想出来。
