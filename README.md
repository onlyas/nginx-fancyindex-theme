# nginx-fancyindex-theme
nginx fancyindex theme

## 1.安装ngx-fancyindex
https://github.com/aperezdc/ngx-fancyindex

## 2.vim nginx.conf

```
fancyindex on;
fancyindex_localtime    on; 
fancyindex_exact_size off;
fancyindex_name_length  255;
fancyindex_header       "/fancyindex-theme/header.html"; 
fancyindex_footer    "/fancyindex-theme/footer.html";
fancyindex_ignore    "fancyindex-theme";
fancyindex_time_format  "%Y-%m-%d %H:%M";
charset utf-8,gbk;
```
