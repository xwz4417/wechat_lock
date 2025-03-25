![image](https://github.com/user-attachments/assets/ec771399-d8fc-4bef-b0bf-2721be38c8bf)**微信自动锁定工具**
- 为保护日常隐私，设定时间内不操作鼠标和键盘自动锁定微信
- 程序启动后，收纳到右下角托盘中，可右键退出程序
- 闲置时间可以在托盘菜单自行调整
- 源自吾爱破解论坛作者**Starrys**代码基础上修改而来,[原贴链接](https://www.52pojie.cn/thread-2000611-1-1.html)
- 放入Windows的开机自启文件夹即可，开机自动启动（以下目录二选一放入即可） 
    - **当前用户启动文件夹**：
    `%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup`
    - **所有用户启动文件夹**：
    `%ProgramData%\Microsoft\Windows\Start Menu\Programs\Startup`

**注意事项**:
- 打包出来的安装包不支持win7，原因是由于Python3.9已经不再支持Win7了，使用Python3.8.6编译能解决这个问题。
- 由于是使用微信自带的快捷键进行锁定,所以需确保锁定快捷键为Ctrl+L,如果想用其他快捷键请自行修改代码或微信快捷键
- ![image](https://i.miji.bid/2025/03/22/71db9fe224606f775ab6a9ce155b829b.png)
- ![image](https://github.com/user-attachments/assets/12461124-bdc2-4873-9939-3ca9004036e9)


