# 一键更新 Thor
 
 本文档由 xinjie 于 2018.04.14 翻译

通过 Thor 菜单上的单个菜单项（FoxPro系统菜单中），可以对 IDE 工具和其他工具以及 VFPX 中的所有项目如 Thor，Thor 仓库，PEM 编辑器 7等进行更新。 '检查更新'会检查是否有更新可用于任何这些应用程序; 如果有任何的更新，你都可以进行选择以便它们自动下载并安装。

![](images/CheckForUpdates.png)

“检查更新”从确定是否有更新版本的 Thor 本身开始。 如果找到，它会显示如下消息：

![](images/UpdateThor.png)

然后继续检查所有其他可用应用程序和工具的更新，如下所示。 请注意，PEM 编辑器和 Thor 仓库是 Thor 的重要组成部分; 您应该立即下载它们，并随时在“检查更新”窗体上显示更新它们。 表格中绿色的项目是最近更新的项目

![](images/UpdateList.png)

检查更新中列出的项目分为五组并按字母顺序列出：

1.  您已下载的项目有更新的版本。 （见＃4）

2.  您尚未下载的项目在过去三个月内有更新

3.  您尚未下载的所有其他项目

4.  您已经下载并且是最新的项目

5.  所有标记为“从不更新”的项目。 这优先于任何其他类别。

## 这些更新安装在哪里？

如果您已经安装了 Thor，PEM 编辑器或 GoFish ，则此更新过程将用新版本替换已安装的版本。 您将不会失去已经在这些已安装工具的文件夹中完成的任何工作。

If you did <u>not</u> have prior versions installed, then the update process will install them in a subfolder of the Thor folder (Thor\Tools\Apps).

## Important Note

The applications that are automatically downloaded as part of ‘Checking for Updates’ are not only downloaded, but they are also installed and ready to run.  There is nothing else you need to do in order to start using them.

## Recommendations

Thor is started by running RunThor.PRG, a file that is created as part of the installation process. This file can be copied into any other folder you wish (such as in your path), since it contains an explicit reference to the folder where you installed Thor.

1.  Since this process works best if run right after launching FoxPro, before you begin working and BEFORE opening PEM Editor, and with no other FoxPro sessions running, we recommend that you call RunThor as part of your IDE setup

2.  As Thor continues to evolved there are updates from time to time. We recommend calling RunThor with a parameter of 7 so that “Check For Updates” is run automatically every week.
