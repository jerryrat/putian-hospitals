# putian-hospitals
莆田系医院数据及其经纬度坐标，包括geojson和shp文件。

## 数据来源

-[凤凰网的数据](http://news.ifeng.com/mainland/special/ptxyy/)

- 解密其`main2.min.js`文件，得到了hospitals的数组，使用python转成json数据。

## 坐标获取

- 使用node调用高德的geocode api解析。

