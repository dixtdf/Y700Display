# Y700Display
开机自动设置外部显示器分辨率刷新率<br/>
全局允许直接打开息屏运行<br/>
全局允许直接打开旁路供电<br/>
软件免费分享！请不要售卖！发现售卖的请点点举报！<br/>

# 分辨率刷新率使用方式
1.安装magisk模块y700-display-auto-change.zip<br/>
2.安装app-release-unsigned.apk<br/>
3.授权Y700Display root权限<br/>
4.打开Y700Display选择需要的分辨率刷新率<br/>
5.点击设置<br/>
6.重启<br/>
注1：如果APP出现闪退请检查root有没有授权<br/>
注2：开机后此程序会持续检测显示器是否连接，连接后修改分辨率刷新率后程序退出。如果没连显示器会一直检测，会浪费电，不使用显示器时建议卸载/禁用模块，APP不用卸载<br/>

# 息屏运行/旁路供电使用方式
root授权后打开APP点击按钮<br/>
root授权后在控制栏添加磁贴并点击<br/>

# 已知问题
按电源键时无法恢复亮屏，只能通过点击app按钮进行亮屏，不过对于投屏使用者够用了，未来我会想办法，今天太累了。<br/>
偶尔可能无法黑屏或者开屏，多点两下<br/>
切记不要暴力点击，没做防暴力点击<br/>

# 建议条件
Y700四代 其他Y700请自测出现问题概不负责<br/>

# 警告
该软件是给外接屏幕或者使用投屏的用户使用<br/>
请确保你的手机连接过电脑adb,否则黑屏后你可能无法恢复亮屏,可能需要重启才能恢复。<br/>
如果黑屏后你无法操作画面，请使用adb打开本app，重新打开app会自动亮屏<br/>
adb打开app命令<br/>
```shell
adb shell am start -n io.dixtdf.y700display/.MainActivity -S
```
# 免责声明
请在合法范围为使用本软件，请不要用于非法用途，使用本软件造成的任何后果，本软件概不负责。<br/>

# 测试通过
Y700四代
<img width="3840" height="2160" alt="Screenshot-TB322FC(WIFI)-20251225201209" src="https://github.com/user-attachments/assets/482fb7a6-855d-44b5-bae4-9f5bb10e76d2" />
<img width="3840" height="2160" alt="Screenshot-TB322FC(WIFI)-20251222210259" src="https://github.com/user-attachments/assets/c1689841-a456-4611-b6f2-f50eb8b2c925" />
