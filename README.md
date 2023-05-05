# pjsip
现代交换原理与技术
自定义config_site.h
PJSIP是一个开放源代码的SIP协议栈，支持多种SIP的扩展功能。PJSIP的官网地址为https://www.pjsip.org/。下载最新版本pjproject-2.10.zip。
现如今PJSIP的开源代码已经移动到了github平台。可以在github上找到项目的下载链接https://github.com/pjsip/pjproject.git
在pjsip的官网上可以找到pjsip的文档支持（https://trac.pjsip.org/repos/wiki/Getting-Started/Windows），我们可以参照文档来实现此开源项目的使用。

对于 Visual Studio 16 （VS 2019）：打开解决方案文件。pjproject-vs14.sln

设置为“活动”或“启动项目”。pjsua

设置为平台。Win32

根据需要选择或构建。DebugRelease

生成项目。这将构建应用程序和所有库 需要 。pjsuapjsua

构建成功后，pjsua 应用程序将被放置在目录中，库将放置在每个项目下的 lib 目录中。pjsip-apps/bin
经过本人测试，只有2.12-1和2.13在vs2022中可以正常运行。
