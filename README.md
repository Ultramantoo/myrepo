# myrepo
bookmark
如何使用：
【总结】一下：
要填写三项：
1.你GitHub的名字，不是账户名

2.token [Settings>Developer settings>Personal access tokens>Generate new token] 生成 【重点】：只勾选 repo 权限，生成的 token，的权限是不够的。
【会报错：not found】  先试全勾选  

3.创建一个仓库：如名：myrepo;在这库存下创建一个.json文件，如：bookmark.json 。那么Path 填 ：myrepo/bookmark.json

坑1:  token的权限 只勾选 repo，会报错 ：not found [说第二遍了]  权限先给全部，后面可以改【重点】
坑2:  其实在仓库下不用创建一个.json文件也是可以的。只要给了全部权限，可以自动生成，不用提前建json。



【书签同步】官方说明：
概述

与您的设备兼容
上传/下载书签信息到Github
使用指南：

- 登录Github，在 Settings->Personal access tokens->Generate new token 生成一个访问token

- 生成的 token 需要勾选 repo 权限，保存生成的 token  【这个可能的误】

- 点击插件icon，依次输入用户名、凭据、仓库名、文件存放路径

- 如果需要记住用户数据，需要打开 Remember Me 开关

- 填写完用户数据后，便可以进行“上传”或“下载”操作
https://chrome.google.com/webstore/detail/%E4%B9%A6%E7%AD%BE%E5%90%8C%E6%AD%A5/fbcbemgibdnpboehnfcnkegefaomnlbk
