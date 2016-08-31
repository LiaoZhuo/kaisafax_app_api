### APP后台配置相关接口，此部分接口需要后台做对应的配置功能（以下报文全部说明的是报文体body的参数，且均为正常流程，具体数据结构暂时尚未给出）

#### 系统版本升级：
* 应用场景：系统版本升级
* cmdId： **CheckUpdate**
* request：

|参数名|参数描述|必要|参数校验|备注|
|-|-|-|-|-|
|version|当前版本|Y| |正整数|

* response（如果有版本更新）：

|参数名|参数描述|必要|参数校验|备注|
|-|-|-|-|-|
|newestVersion|最新版本信息|Y| |最新版本信息|

updateInfo详细字段：
```json
    newestVersion:{


    }
```

#### 首页banner、公告、动态运营区信息获取：

* 应用场景：首页banner、公告、动态运营区信息获取
* cmdId： **GetIndexInfo**
* request：无

* response：

|参数名|参数描述|必要|参数校验|备注|
|-|-|-|-|-|
|bannerList|banner信息列表|Y| | banner信息列表|
|noticeList|通知信息列表|Y| | 通知信息列表|
|dynamicInfoList|动态运营信息列表|Y| | 动态运行信息列表|

bannerList、noticeList、dynamicInfoList详细字段：
```json
    bannerList:{

    
    }
    
    noticeList:{

    
    }
    
    dynamicInfoList:{



    } 
```



