## [XRU]XMW-ROXI-UI
XMW 社区 UI 重制计划
XMW 社区的 UI 已经 114514 年没换了。
既然看腻了，那就自己重写一个。😂
XMW-ROXI-UI（XRU） 是一个基于 JavaScript + CSS 的小码王社区用户脚本，旨在对社区页面进行视觉重制、深色化和交互优化。
本项目主要通过 Tampermonkey（油猴） 注入样式与功能，不修改小码王服务器端数据。

作者 投手 和 Deepseek

作者xmw社区账号主页 (点这个图片)
[![ts](https://github.com/user-attachments/assets/74d6b636-b4f6-4338-889b-8467f17e76ac)](https://world.xiaomawang.com/w/person/project/all/4168227)

主语言![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow)  ![CSS](https://img.shields.io/badge/style-CSS-1572B6?logo=css3&logoColor=white)

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



# <span style="color: #ff6500;">不给投手⭐STAR 的人是~~GAY~~</span>



