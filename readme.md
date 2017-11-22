# 腾讯文智分析接口的。。。的。。。的api调用方法
---
###没抛出各种异常。。就，应该，不会有太多异常吧，不过以后有时间会补的

###怎么用呢？
```
  action_param = {
        ''' 里面的内容替换成每个api对应的必须项,下面是TextClassify的示例 '''
        'title': u'Dior新款，秋冬新款娃娃款甜美圆领配毛领毛呢大衣外套、码数：SM、P330',
        'content': u'Dior新款，秋冬新款娃娃款甜美圆领配毛领毛呢大衣外套、码数：SM、P330',
    }
    param = {
        'Region': 'sz',  #还有广州啊(gz)、上海(sh)啊、北京之类的
        'SecretId': '你的那个。。', 
        'SecretKey': '你的这个。。',
        'Action': 'TextClassify', #看文档加
        'action-param': action_param
    }
```
* [分词&命名实体识别API](https://www.qcloud.com/document/api/271/2071)
* [情感分析API](https://www.qcloud.com/document/api/271/2072)
* [关键词提取API](https://www.qcloud.com/document/api/271/2074)
* [句法分析API](https://www.qcloud.com/document/api/271/2075)
* [同义词API](https://www.qcloud.com/document/api/271/2076)
* [转码API](https://www.qcloud.com/document/api/271/2079)
* ...其他的自己看吧

* [云API密匙地址](https://console.qcloud.com/capi)
