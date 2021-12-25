---
layout: post
title:  "新人入门级教程"
date:   2021-11-11 12:00:00 +0800
categories: game
---

``` shell
  
# 0x1 下载文件
$ wget file
```

在 [模组使用指南](https://1.618.sh/mods) 页面下载所需文件:

||| :--- |
||| 0001.TMI测试工具 |
||| 110128.兔人框架 |
||| ShipWrecked.APK(1.28.1) |
||| ShipWrecked.OBB(1.28.1) |

一般浏览器(Edge、Chrome)下载目录为 `/sdcard/download` 文件夹，找不到文件可以使用*MT管理器*的搜索功能[(tu00.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial00.png)。  

``` shell
  
# 0x2 安装框架
$ install frame
```

1、兔人模组(0001)，此文件只有数据包补丁(ADD\_TO\_OBB)这一部分的文件[(tu01.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial01.png)。  

2、兔人框架(110128)，此文件有安装包补丁(ADD\_TO\_APK)和数据包补丁(ADD\_TO\_OBB)这两部分的文件[(tu02.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial02.png)。  

3、游戏安装包[(tu03.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial03.png)与数据包[(tu04.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial04.png)文件皆为 [ZIP格式](https://baike.baidu.com/item/zip/16684862) 的压缩文件。  

4、将兔人框架中安装包补丁(ADD\_TO\_APK)里的文件***全选***并添加到安装包[(tu05.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial05.png)，数据包补丁(ADD\_TO\_OBB)里的文件***全选***并添加到数据包[(tu06.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial06.png)。  

5、安装包需要***签名***后才能安装[(tu07.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial07.png)；数据包需要重命名将 \*\*\*.***com***.klei\*\*\* 改为 \*\*\*.***hei***.klei\*\*\* ，然后移动到 /sdcard/Android/obb/***hei***.klei\*\*\*/ 文件夹[(tu08.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial08.png)。  



``` shell
  
# 0x3 安装补丁
$ install mod
```

安装包补丁只会使用一次，所以一般说的补丁是数据包补丁，模组则是扩展游戏玩法的数据包补丁。在安装框架的第4步，你已经操作过了。请找到数据包补丁(ADD\_TO\_OBB)，将里面的文件***全选***并添加到数据包[(tu09.png)]({{ site.baseurl }}/assets/image/bunnyman_tutorial09.png)。