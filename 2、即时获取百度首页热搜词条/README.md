基于PHP5.4 即时获取百度首页热搜词条 DEMO
===============================================
小黄牛
-----------------------------------------------

### 1731223728@qq.com 


+ 命令行工具当前版本 - V1.0.0.1

+ 上传日期 - 2017-9-18 17:18:00

+ 作者 - 小黄牛

+ 邮箱 - 1731223728@qq.com                                                                                                                    


## 使用DEMO如下：


```
require 'vendor/Api.php';

// 使用DEMO
$obj = new Hotsearch();
$num = $obj->Obtain();
echo '<pre>';
var_dump( $num );
````


### $this->Obtain()的回调参数说明：


``` 
[
    'title' => 词条名
    'num'   => 指数
    'sort'  => 近期排名升降：1|2 升|降
]
```
