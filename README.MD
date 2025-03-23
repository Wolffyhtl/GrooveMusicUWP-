# Groove音乐UWP 去更新版
自己改过的安装包，可以共存，不用担心更新
## 已知问题：
- 软件界面几乎全是英文，只有三处中文
    *2.6.672.0版本纯英文
- 扫描不到本地音乐，必须右键音乐文件，选择Groove Music打开才能播放
    *2.6.672.0版本可以扫描本地音乐
    *10.18052.11111.0版本有几率闪退，日用建议使用2.6.672.0版本或10.20112.10111.0版本
## 打包方法：
1. 下载Groove音乐的安装包，打开[这个链接](http://tlu.dl.delivery.mp.microsoft.com/filestreamingservice/files/c92cf6fc-faca-4aff-94b9-a032ddb4541b?P1=1742473249&P2=404&P3=2&P4=BHClUtq8TGnhWWVtA2JfrNk60Bbv%2bwwYDLqyp6QpQ4nEWgiucHd5UYDogO8P71YfRNl%2fnn6y2B8wNwULRupO3A%3d%3d)，会直接开始下载Groove音乐10.20112.10111.0版本.
想要其他版本的话，去[这个网站](https://store.rg-adguard.net/)里找
解包与去更新参考[从网易云UWP说起：修改AppManifest阻止UWP自动更新/多版本共存](https://zhuanlan.zhihu.com/p/146393154)
2. 下载[WSAppBak](https://github.com/Wapitiii/WSAppBak)与[7zip](https://sourceforge.net/projects/sevenzip/files/latest/download),解压安装包.然后，我们可以看到许多appx文件.
我们选择Music_Desktop_Production_x64.appx，用7zip解压.
接下来的步骤请参考[从网易云UWP说起：修改AppManifest阻止UWP自动更新/多版本共存](https://zhuanlan.zhihu.com/p/146393154)
这里我们介绍第一种方式.（即直接安装appx文件）
3. 打开WSAppBak，在input path中选择解压appx出来的文件夹,按回车键.
output path选择一个文件夹，再按回车键.
等会会出现一个窗口，点击None，继续.
### 安装过程
4. 完成后，打开你设置的output path文件夹，找到.pfx文件，双击打开，存储位置选本地计算机，然后一直下一页，将证书存储位置选为受信任的根证书颁发机构，继续下一页，完成.
5. 打开你设置的output path文件夹，找到Appx文件，双击打开并安装.
6. 打开你的开始菜单，找到应用，找到Groove音乐，点击即可.


