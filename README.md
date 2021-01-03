## 简介

网易云音乐UWP重打包版，不会自动更新到Win32版。

本安装包将于2021年5月30日过期，届时将无法安装，需要手动更新证书。已安装的用户不受影响。

## 安装说明

1、下载 [压缩包](https://github.com/JasonWei512/NetEase-Cloud-Music-UWP-Repack/archive/master.zip)，并解压。

2、右键点击 x86 或 x64 安装包，点击属性，切换到"数字签名"选项卡。双击签名列表中的"esaeten"。在弹出的"数字签名详细信息"窗口中点击"查看证书"，再点击"安装证书"。

3、在"证书导入向导"中：

- "存储位置"选"本地计算机"，下一步。（需要同意UAC权限请求）

- 选择"将所有的证书都放入下列存储"，点击"浏览"，选择"受信任人"，确定，下一步，继续完成证书导入。

4、双击 x86 或 x64 安装包安装。


## UWP 版本无法登录的解决方案

点击发现音乐-》最新音乐把我喜欢的音乐调出来

从创建的歌单-》我喜欢的音乐那里点击登录

PS:应该只支持网易账号和手机号


## 本地回环代理设置

管理员运行 

`checknetisolation loopbackexempt -a -n="1f8b0f94.122165ae053f_kq4t7q4nstjby"`

