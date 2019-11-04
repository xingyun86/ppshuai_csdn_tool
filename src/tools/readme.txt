
--------------------------------------------------使用说明--------------------------------------------------

1.下载firefox x64
https://www.firefox.com.cn/
2.安装openjdk x64
https://github.com/AdoptOpenJDK/openjdk8-binaries/releases/download/jdk8u232-b09/OpenJDK8U-jdk_x64_windows_hotspot_8u232b09.msi
3.csdn_main-input.csv	-- 要采集的关键词列表
4.BrowserSession.exe	-- Cookie采集主程序
5.CsdnTool.exe		-- 批量发布文章主程序
6.其它重要文件geckodriver.exe、ssserver.jar（无需理会，但是必须存在）

-------------------------------------------------------------------------------------------------------------
运行方法：
1.设置csdn_main-input.csv（有内容一次就好）
2.双击执行BrowserSession.exe，扫码登陆后关闭弹框即可（注意，所在目录尽量不要使用中文路径）
3.运行CsdnTool.exe批量发布文章
备注事项：
jdk设置环境变量