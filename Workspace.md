# 优化工作区

< [Back](README.md)

## Tips: 模拟器和 Xcode 全屏并列显示

先看效果，虽然损失些编辑空间，但是窗口管理省心了：

![模拟器和 Xcode 并列显示](image/workspace_simulator_full_screen_example.png)

默认模拟器是不可以全屏显示的，打开一个隐藏开关就能支持全屏了，在终端执行：

```shell
defaults write com.apple.iphonesimulator AllowFullscreenMode 1
```
