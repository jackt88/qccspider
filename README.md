#企查查每日新增企业数据抓取

* 尚未完成的工作：
    * 需要自行抓包获取设备id，appid，sign等等
    * sign和时间戳保持一致即可
    * 把所有的数据库、redis配置
    * 无法自动登录，账号需要独立
    * redis数据转存mysql
    * 企查查限制，每分钟请求大概不能超过30次，所有功能未加并发，请不要使用代理并发，会封账户的
    * 有些工作尚未完成，需要自己进行继续开发，可以找我要app的脱壳源代码，继续分析。
* 已经完成工作
    * 每天定时抓取
    * 自动刷新token
    * 省份、市的所有代码
    * token自动刷新
    * 根据地址自动将省份、市、区县进行分割
    * 所有数据存到redis里面
    
