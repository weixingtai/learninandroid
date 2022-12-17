启动优化

冷启动
$ adb shell am start -W -n com.meizu.safe/.SecurityMainActivity

冷启动停止APP
$ adb shell am force-stop com.android.browser

热启动
$ adb shell am start -W -n com.android.browser/.BrowserActivity

热启动停止APP
$ adb shell input keyevent 3


卡顿检测
$ adb shell dumpsys gfxinfo com.mu.safe

内存占用
$ adb shell dumpsys meminfo com.mu.safe

获取perfetto日志
$ adb pull /data/local/traces /home/mu/桌面



