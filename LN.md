## IDEA 安装

在C:\Windows\System32\drivers\etc找到host.ics文件

把host.ics文件复制到桌面

使用前请将```“0.0.0.0 account.jetbrains.com”```添加到hosts文件中

修改完成后粘贴覆盖回C:\Windows\System32\drivers\etc

打开IDEA，下一步，don't send



![](C:\Users\Hpr\IDEA\pictures\1.png)

选Activation code，复制http://idea.lanyus.com/中的注册码



---





## IDEA配置



![](C:\Users\Hpr\IDEA\pictures\2.png)

![](C:\Users\Hpr\IDEA\pictures\3.png)

![](C:\Users\Hpr\IDEA\pictures\4.png)

![](C:\Users\Hpr\IDEA\pictures\5.png)

![](C:\Users\Hpr\IDEA\pictures\6.png)

![](C:\Users\Hpr\IDEA\pictures\7.png)

---



## New Project

![](C:\Users\Hpr\IDEA\pictures\8.png)

![](C:\Users\Hpr\IDEA\pictures\9.png)

## 解决输入法跟随问题

把Java安装路径下的jre文件拷贝到IDEA的安装目录下并重命名为jre64；

![](C:\Users\Hpr\IDEA\pictures\10.png)

![](C:\Users\Hpr\IDEA\pictures\12.png)



把对应版本的jdk/lib下的tools.jar拷贝到jre64/lib中



![13](C:\Users\Hpr\IDEA\pictures\13.png)

![14](C:\Users\Hpr\IDEA\pictures\14.png)

补充由于jdk1.8.0_91使用后，IDEA打开项目后卡死，用所以重新安装回jdk1.8.0_171

安装完后还有个问题就是微软自带的输入法有跟随，但是搜狗输入法还是没有跟随。