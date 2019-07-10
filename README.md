# ???_Events README
>

## 项目结构
├── README.md  
├── css/  
├── img/  
├── js/  
├── data.js  
├── index.html  
└── test.html  

## 图片规范
1. 上传至[SM.MS](https://sm.ms)
2. 原图保存至 *img* / *events* / 下, 防止CDN链接失效, 补图用
3. 命名规范: yyyy-MM-dd_序号，eg. 19880324_01

## 数据格式 data.js 文件
``` json
{
  "update": "2018-11-03 09:46",
  "events": [
        {
          "id": "20181029",
          "title": "10.29 xx xx",
          "content": [
            {
              "txt": "x"
            },
            {
              "txt": "x"
            },
            {
              "txt": "x"
            },
            {
              "txt": "x"
            },
            {
              "txt": "x"
            }
          ],
          "imgs": [
            {
              "url": "xx06.jpg"
            }
          ],
          "link": [
            {
              "url": " ",
              "title": " "
            }
          ]
        }
	]
}
```
