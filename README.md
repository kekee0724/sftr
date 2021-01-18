# 2021年春运出行防疫政策查询

近期全国多地疫情出现反复态势，春运将至，各地疫情期间出行政策不一。这对很多用户出行造成困扰：能返乡吗？到当地会被隔离吗？需要做核酸检测吗？
本H5提供的“出行防疫政策查询”功能，便于用户实时查询各地出行政策，做好疫情防控准备，安全便利出行。

## 数据来源：使用聚合数据提供的在线API调用政策信息，并进行展示。
## 聚合API免费开通URL：`https://www.juhe.cn/docs/api/id/566?s=github`

开通API接口后，将会获得一个API的请求Key,只需要将文件`epidemic.js`第19行的key换成你申请到的key，就可以使用啦。
```js
// "http:"===window.location.protocol&&(window.location="https://"+window.location.host+window.location.pathname)

var fromCity = document.getElementById('fromCity')
    toCity = document.getElementById('toCity')
    fromVal = ''
    toVal = ''
    outFrom = document.getElementById('outFrom')
    inFrom = document.getElementById('inFrom')
    inTo = document.getElementById('inTo')
    outTo = document.getElementById('outTo')
    fromCode = document.getElementById('fromCode')
    ToCode = document.getElementById('ToCode')
    from_info = ''
    to_info = ''
    fromCodeDes = ''
    fromCodeImg = ''
    toCodeDes = ''
    toCodeImg = ''
    appKey = 'fa7914d4eec67d44499d2eca5eaea6e1'

```

H5效果图：
![image](https://github.com/JUHEAPI/covid-19/blob/master/huijia.jpg)
