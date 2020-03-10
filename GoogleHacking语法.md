## 常用的GooleHacking语法

1. intext: （仅针对Goodle有效）

   把网页中的正文内容中的某个字符作为搜索条件

2. intitle: 

   把网页标题中的某个字符作为搜索条件

3. cache

   搜索搜索引擎里关于某些内容的缓存，可能会在过去内容中发现有价值的信息

4. filetype:

   指定一个格式类型的文件作废搜索对象

5. inurl:

      搜索包含指定字符的url
      
6. site:

      在指定的站点搜索相关内容

## 其他GoogleHacking语法

1. 引号 “”

   把关键字打上引号后，把引号里的内容作为整体来搜索

2. or

   同时搜索两个或者更多的关键字

3. link:

   搜索某个网站的链接

## 典型用法

1. 找管理后台地址

   site:xxx.com intext:管理|后台|登录|登陆|用户名|密码|系统|账号

   site:xxx.com inurl:login/admin/mange/manger/admin_login/system

   site:xxx.com intitle:管理|后台|登录|登陆

2. 找上传漏洞类地址

   site:xxx.com inurl:file

   site:xxx.cin inurl:upload

3. 找注入页面

   site:xxx.com inurl:php?id=

4. 找编辑页面

   site:xxx.com inurl:ewebeditor


   