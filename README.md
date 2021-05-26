# zhihubackup
下载文章对应的 html 和 .zip 文件，解压 .zip 后，打开 html 文件即可。

逼乎的文章保存到本地后，直接打开可能会反复刷新，需要用 text editor 打开 html 文件，删除其中这段代码：
```
<script id="js-clientConfig" type="text/json">
{"host":"zhihu.com","protocol":"https:",
"wwwHost":"www.zhihu.com",
"fetchRoot":{"www":"https:\u002F\u002Fwww.zhihu.com","api":"https:\u002F\u002Fapi.zhihu.com",
"lens":"https:\u002F\u002Flens.zhihu.com","zhuanlan":"https:\u002F\u002Fzhuanlan.zhihu.com",
"walletpay":"https:\u002F\u002Fwalletpay.zhihu.com","captcha":"https:\u002F\u002Fcaptcha.zhihu.com"}}
</script>
————————————————
版权声明：本文为CSDN博主「weixin_51184047」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/weixin_51184047/article/details/112562118
```
