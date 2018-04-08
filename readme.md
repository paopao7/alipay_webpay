说明
=====
该demo为支付宝电脑网站支付官方demo的PHP版本

>具体更改如下：

1. 修改文件名"alipay.trade.page.pay-PHP-UTF-8" 为 "webpay" 
2. 删除readme.txt、idnex.php、notify_url.php、return_url.php
3. 新增dataHandle.php文件，该文件为自定义文件用于调用支付宝下单及回调验签功能


>其他说明：

1. 下载后需先配置数据库连接信息
2. 支付宝公私钥、appid等参数采用数据形式存储，具体调用时需先读取数据库
3. 对应配置表已生成.sql文件，测试前需导入对应sql文件

>联系方式：(添加请注明技术咨询)

本人QQ：980569038
TP集成支付宝群：594955172