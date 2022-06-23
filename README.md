# w_183
一键在线IOS免签封包app分发平台源码
<br/></br>
[下载地址](https://www.uuid2.com/183.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>分享APP在线IOS免签封包仿fir二开分发平台 一键IOS免签 支持在线封装APP分发源码

安装说明:
安装环境：php7.0 ，mysql5.6，nginx
php7.0设置里，设置最大上传1024m，超时时间1000s，禁用exec函数。
域名开启ssl。
上传源码到根目录
域名/install.php在线安装，按提示输入数据库信息即可完成安装。
码支付修改地址/codepay/codepay_config.php<p>
<p>nginx伪静态规则：
if (!-d $request_filename){
set $rule_0 1$rule_0;
}
if (!-f $request_filename){
set $rule_0 2$rule_0;
}
if ($rule_0 = "21"){
rewrite ^/([a-z0-9A-Z]+)$ /app.php/$1 last;
}

后台地址：域名/admin.php<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/d0d6912388.jpg" alt="一键在线IOS免签封包app分发平台源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202105/1136959235.jpg" alt="一键在线IOS免签封包app分发平台源码">
