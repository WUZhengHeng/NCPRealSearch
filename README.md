### 新冠肺炎疫情实时查询

简单的H5模板，仅供交流学习使用。

可以更换页面内图片。

可以设置默认显示地区，在==init.js==文件中修改查询地区


```
29.   	url: 'https://jk.avuejs.com/news?name=浙江省' ,

56.     let number = list.findIndex(ele => ele.name === '河南');

73.     if (item.name === '杭州')

//修改地区中文名称即可更换查询地区
```

另外，在==intro_vp_v3.js==文件中，修改接口查询参数，即可调整首页默认查询地区


```
927.    $('#select-area').prepend("<option value='henan'>切换城市</option>"); 

931.    let urlarea = bbo.getUrlParam('pool') || 'henan';

//henan替换为想查询城市的字母缩写，如zj、hb
```

感谢各位朋友的指正
