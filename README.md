# GitKraken 简体中文翻译

[GitKraken](https://www.gitkraken.com/) 简体中文翻译补丁

##### 来源说明：

翻译来自 github 上大佬的台湾翻译，我只是将 “繁体中文” 换行成了 “简体中文”。

大佬 github 地址： https://github.com/rogeraabbccdd/GitKraken-zh-tw

![image-20211108180142739](https://github.com/Pupper0601/GitKraken-zh-cn/blob/main/home.png)

## 使用方法

-   目前支援版本: 8.1.0
-   将 原文件 `strings.json` 改名为 `strings.en.json`
-   至 [Release](https://github.com/Pupper0601/GitKraken-zh-cn/releases/tag/%E4%B8%AD%E6%96%87%E8%A1%A5%E4%B8%81) 下载 `strings.json`
-   文件存放位置
    -   Windows: `%LOCALAPPDATA%\gitkraken\app-8.1.0\resources\app.asar.unpacked\src`
    -   Mac: `/Applications/GitKraken.app/Contents/Resources/app.asar.unpacked/src/strings.json`
    -   Linux: `/usr/share/gitkraken/resources/app.asar.unpacked/src`
-   开启 GitKraken ，至 Preference -> UI Customization -> Language 切换语言

![image-20211108180820412](https://github.com/Pupper0601/GitKraken-zh-cn/blob/main/set.png)

## 关于取消更新
GitKraken 安装后默认的快捷方式为 `updata.exe`,我们删除这个快捷方式，然后将 `****\gitkraken\app-8.1.0` 中的 `gitkrken.exe` 设置为快捷方式，这样软件就不会更新了。
![image-20211108180820412](https://github.com/Pupper0601/GitKraken-zh-cn/blob/main/取消更新.png)
