## 问题描述
在 `Ventura 13.6.5` 安装 `Bob`、`PopClip`，安装 [bob-popclip](https://github.com/ripperhe/bob-popclip) 插件，划词时选择 `Bob` 图标后无反应，隐私与安全性 - 自动化里无 `PopClip` 调用 `Bob` 的允许项，控制台报：

```log
Since sending application *** is not permitted to send this AppleEvent to this process, returning an errAEEventNotPermitted reply.
```
![](https://github.com/WhyMeta/fix-ventura-bob-popclip/blob/main/public/exception.gif?raw=true)
![](https://github.com/WhyMeta/fix-ventura-bob-popclip/blob/main/public/1-1.png?raw=true)
![](https://github.com/WhyMeta/fix-ventura-bob-popclip/blob/main/public/1-2.png?raw=true)

## 修复步骤
1. 安装 [Bob Shell.popclipextz](https://github.com/WhyMeta/fix-ventura-bob-popclip/raw/main/Bob%20Shell.popclipextz)
2. 划词选择 `Bob`，弹窗后允许
3. 重新安装 [bob-popclip](https://github.com/ripperhe/bob-popclip) 插件
4. Done.
![](https://github.com/WhyMeta/fix-ventura-bob-popclip/blob/main/public/fixed.gif?raw=true)
![](https://github.com/WhyMeta/fix-ventura-bob-popclip/blob/main/public/2-1.png?raw=true)
![](https://github.com/WhyMeta/fix-ventura-bob-popclip/blob/main/public/2-2.png?raw=true)
