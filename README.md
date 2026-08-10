# XMW-ROXI-UI
XMW社区的ui已经114514年没换了，现在看腻了，于是重写

作者 投手 和 Deepseek

XMW社区主页https://world.xiaomawang.com/w/person/project/all/4168227

![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow)

作品名称XMW-ROXI-UI [XRU]


目前版本1.0

 功能
 
| 🌈 **文字统一变色** | 

用户名、评论昵称在随机颜色序列中同步平滑切换

| 🆔 **显示用户ID** | 

在个人主页用户名旁显示 `#用户ID`，颜色同步渐变 

| 🖼️ **必应每日背景** | 

个人主页背景自动替换为必应每日高清壁纸

| 🌌 **社区主页渐变背景** | 

社区主页深色系持续流动渐变背景
| 🌙 **强力深色模式** | 

强制将白色背景改为深色，黑色文字改为白色

| ✨ **液态玻璃效果** | 

作品卡片、用户卡片毛玻璃质感,~~一点也不卡~~

| ⬜ **标题颜色优化** | 

作品卡片标题纯黑、板块标题纯白

| 🗑️ **移除干扰元素** | 

移除背景按钮、测评按钮等 

| 🔄 **Logo旋转动画** | 

主页Logo持续左右摆动

| 📢 **自定义公告** | 在公告栏插入自定义公告，点击跳转惊喜页面 

## ⚙️ 功能配置

脚本内置了功能开关，你可以在代码开头的 `CONFIG` 对象中自由开启或关闭任意功能：

    enableColorFlow: true,        // 文字统一变色
    
    enableUserIdDisplay: true,    // 显示用户ID
    
    enablePersonalBg: true,       // 个人主页必应每日背景
    
    enableHomepageDarkBg: true,   // 社区主页暗色渐变背景
    
    enableDarkMode: true,         // 强力深色模式
    
    enableGlassEffect: true,      // 液态玻璃效果(觉得卡可以关掉)
    
    enableTitleOptimize: true,    // 标题颜色优化
    
    enableRemoveElements: true,   // 移除干扰元素
    
    enableLogoSpin: true,         // Logo旋转
    
    enableCustomAnnounce: true,   // 自定义公告

*使用方法*

安装Tampermonkey(油猴插件)

打开 Tampermonkey 仪表盘，点击 **"添加新脚本"**

将我们的js文件拖进去并启用

刷新小码王社区页面即可生效

📃更新日志

1.0 （2026/08/10）

初始版本发布


