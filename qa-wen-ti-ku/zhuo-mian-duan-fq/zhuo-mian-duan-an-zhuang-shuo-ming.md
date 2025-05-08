# 桌面端安装说明



## Windows 安装说明 <a href="#windows-ban-ben-an-zhuang-shuo-ming" id="windows-ban-ben-an-zhuang-shuo-ming"></a>

情况：Windows已保护你的电脑

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

解决方法：

1. 点击【更多信息】
2. 点击【仍要运行】
3. 之后即可正常安装

***

## MacOS 安装说明

**安装问题：**&#x56E0;安全设置问题，macOS系统默认无法打开未验证开发者的应用。

**解决方案：**&#x4FEE;改macOS系统安全设置，允许打开任何来源的应用。

* 在macOS系统的命令行下关闭安全模式。

复制

```
sudo spctl -- master -- disable
```

* 在MacOS系统桌面，选择启动台 > 系统偏好设置 > 安全性与隐私 > 通用。
* 单击左下角锁图标，输入管理员账号密码后单击解锁。
* 在允许从以下位置下载的应用区域，选择任何来源。

配置完成后，macOS系统可以正常打开SCRM Champion客户端。

**完成上述步骤，重新打开之前报错软件，如果仍报错，继续以下操作**

* 终端中输入以下命令(注意: 后面有个空格)

```
sudo xattr -d com.apple.quarantine /Applications/SCRMChampion.app
```

* 然后重新打开应用即可，执行到此问题就解决了。
