# DYS_Events README
> 前端师傅死的早, 属于随手弄的, 有看不下去的请直接修改 pull request, 目前数据由我整理定义格式方便模版抽象使用, 有疑问直接改, 没啥问题我就会合进来发布的。

[德云色·大事记·ChaosTong](https://deyunse.wang)

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

## 数据格式
``` json
{
  "update": "2018-11-03 09:46",
  "events": [
        {
          "id": "20181029",
          "title": "10.29 DYS 第一届 '奇葩说'辩论赛",
          "content": [
            {
              "txt": "辩题：如果Kid没有退役 顶替掉Duke，那么今年S8 iG 还能打进决赛吗？"
            },
            {
              "txt": "孙哥主持，太强了不参赛，以免比赛索然无味"
            },
            {
              "txt": "这个辩题是在 Kid 再次请假，然而其他直播员正常上班的周一零点举办的，所以这告诉我们一个道理，不要在别人正常上班的时候请假。"
            },
            {
              "txt": "正反方疯狂 Diss 我孩神"
            },
            {
              "txt": "最后反方 '便手'(癞疙宝、三代目、元气) 以微弱票数获得胜利"
            }
          ],
          "imgs": [
            {
              "url": "https://i.loli.net/2018/10/30/5bd844c5c2506.jpg"
            }
          ],
          "link": [
            {
              "url": "https://www.bilibili.com/video/av34941325",
              "title": "B站录播 德云色便论带会"
            }
          ]
        }
	]
}
```