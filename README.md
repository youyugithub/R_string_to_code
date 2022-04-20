# R_string_to_code

```
## 1
assign(paste('QR', method,'aggl.clust', sep="."), hclust(QR.daisy.mat, method = method))
## 2
a_code<-paste0('my_range<-range(data_all$',a_name,',na.rm=T)')
  eval(parse(text=a_code))
```
