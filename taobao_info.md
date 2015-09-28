# taobao_info
xvshiting  
2015年9月28日  
##DATA ACCESS


```r
item<-read.table("dim_items.txt",header = FALSE)
match.taobao<-read.table("dim_fashion_matchsets.txt",header = FALSE)
```

##Data Analysis

商品类型一共有`283`种,编号最小为5，最大为646.每种所占数量如下图：

![](taobao_info_files/figure-html/unnamed-chunk-2-1.png) 
