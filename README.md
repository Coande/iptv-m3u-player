**原 README：**

>## Live TV
>
>#### 简介
>---
>项目:[iptv-m3u-maker](https://github.com/EvilCult/iptv-m3u-maker)的衍生项目
>
>基于Electron + React 开发的**轻量级**桌面端播放器.
>
>频道数据会定期更新.
>
>目前仅打包了 Mac OS 的 App.
>
>以上
>
>视频演示: [YouTube](https://youtu.be/BhuYB4l3NUY)
>


**在原来基础上修改了：**

- 宽高改为自适应
- 打开时自动播放
- 弹出菜单时保持播放
- 节目源更改（改为深圳移动测试的节目源）
- 还有其它一些小改动


**下载：**

[LiveTV-win32-ia32.zip](https://github.com/Coande/iptv-m3u-player/releases/download/v1.0.2/LiveTV-win32-ia32.zip)

[LiveTV-win32-x64.zip](https://github.com/Coande/iptv-m3u-player/releases/download/v1.0.2/LiveTV-win32-x64.zip)

[LiveTV-darwin-x64.zip](https://github.com/Coande/iptv-m3u-player/releases/download/v1.0.2/LiveTV-darwin-x64.zip)


**参加开发（摸索的）：**

启动前端：
```
npm run start
```
启动 Chrome 时添加参数，关闭跨域等安全策略：
```
--disable-web-security --user-data-dir
```
然后就可以在 Chrome 调试该项目了

打包：
```
npm run package
```
打包后文件位于 dist 目录下
