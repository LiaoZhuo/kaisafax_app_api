### APP后台配置相关接口

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
|updateInfo|当前版本|Y| |正整数|

updateInfo详细字段：
```json
    updateInfo:{


    }
```



