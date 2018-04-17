<div class="wikidoc">

## Thor 仓库工具目录

本文档由 xinjie 于 2018.04.14 翻译

工具|描述|更新日期|视频
---|---|---|---
Comment highlighted text|改进的将注释高亮显示的方法；也可以创建带有日期的注释行|2011/06/09
Un-comment highlighted text|从高亮文本中的每行删除注释。 适用于原生 VFP 注释。|2011/10/22
Wrap text with IF / ELSE / ENDIF|用 IF / ELSE / ENDIF 包装高亮的文本|2011/10/22
Wrap text with Try / Catch|使用 Try / Catch 包装高亮的文本|2011/10/22
Wrap text with With / EndWith |用  With / EndWith 包装高亮的文本|2012/01/28
Change IF/ENDIF in highlighted text to DO CASE|将高亮文本中的 IF / ENDIF 更改为 Do Case / otherwise / EndCase|2011/10/22
Break highlighted text|将高亮文本分解成单独的一行|2011/10/22
Extract to Constant|将当前高亮代码块提取到一个新的常量（#Define）中，并且显示在代码的开头，对于方法，会将其包含到Include文件中。 另请参阅IDE工具中的“Extract to Method”。|2011/10/22
Extract to Variable|将当前高亮代码块提取到新变量中。 另请参阅IDE工具中的“Extract to Method”。|2011/10/22
代码 / 高亮文本|  
Highlight parameter|高亮显示方法或函数调用中的单个参数|2011/10/22
Highlight parentheses|高亮显示匹配括号之间的代码。 并在下一组括号重复使用高亮。|2011/10/22
代码 / 插入文本|
Insert blank lines around control structures|在控制结构前后添加空行（IF / ENDIF，DO CASE / ENDCASE等）|2011/10/22
Insert call to NewObject (from MRU classes)|弹出基于 MRU 类的菜单; 然后将 NewObject( ) 引用粘贴到所选类中|2011/10/22
Insert color|使用GetColor（）提示颜色，并插入RGB值|2011/07/29
Insert full name of object under mouse|将鼠标下的对象的完整路径名粘贴到代码窗口中。 更新代码并使类定义正确工作|2011/07/29
Insert reference to class|插入对象所属类的引用; 如 This.Parent.Parent 等|2011/07/29
代码 / “M.”操作符|
Add MDots to variable names|将“M.”添加到所有对参数，局部变量和其他变量赋值的引用。|2011/10/22
Remove MDots from variable names|从所有对参数，局部变量和其他变量的引用中“M.”。|2011/10/22
Code / Misc.|
Install enhanced ZLOC|安装ZLOC的增强版本，这会导致弹出列表还包括代码中分配的所有变量，无论它们是否在LOCAL列表中。 请注意，这只需要做一次，它更新FoxCode。|2011/10/22
Modify Class for PRG-based classes|提供一种将基于PRG的类（不带子对象）转换为临时VCX的机制，以便IDE Tools可以在其上工作; 然后再回到PRG中。 参看[修改基于 PRG 的类。](https://github.com/vfp9/Thor_CN/blob/master/Docs/VCD4PRG.md)|2011/10/22
Remove blank lines|删除当前代码窗口中的所有空白行|2012/01/28
Go To ...|
Go To ‘Find’ in PEM Editor|将焦点设置到PEM编辑器中的“查找”文本框; 如果它尚未打开，则打开PEM编辑器|2011/10/22
Go To File|打开一个带有过滤器框的对话框，从活动项目中快速选择一个文件（PRG，SCX，VCX等）|2011/10/22
Go To Include File|打开正在编辑的表单或类的头文件|2012/01/28
Go To Method|打开一个对话框来选择一种方法来查看或编辑。 允许通过部分方法名进行搜索。|2011/06/03
Go To Object|选择代码窗口所属的对象。|2011/07/29
杂项|
"View Definition" uses "Go To Definition"|修改代码窗口的右键关联菜单，以便在选择“View Definition”时调用“Go To Definition”。 必须在每个会话中运行一次。|2012/01/28
Display ClassLibs|在对话框中显示当前类库，每行一个。|2011/06/03
Display Path|在对话框的对话框中显示当前路径，每行一个。|2011/06/03
HackCX4 from MRU forms or classes|HackCX：弹出一个菜单，用于选择要使用HackCX4打开的表单或类（来自MRU列表）|2011/06/03
Toggle comment colors|在编辑窗口中为注释切换颜色（正常与柔和）|2011/06/03
项目|
MRU classes in this project|当前项目中MRU类的弹出式菜单|2011/06/04|<a href="Videos\MRU.wmv" target="_blank">(1:56)</a>
MRU files in this project|MRU的弹出式菜单列出当前项目中的文件|2011/06/04|<a href="Videos\MRU.wmv"  target="_blank">(1:56)</a>
Open project folder|打开显示活动项目文件夹的资源管理器文件夹|2011/07/29
Samples|
Modify the “Last Revision” comment|在编辑窗口中查找特定行并修改它的注释。|2011/07/29
Wrap text with IF / ENDIF|在编辑窗口中取出高亮文本，修改它并粘贴替换的示例。|2011/06/09
表|  
Create SQL from cursor|从一个打开的游标创建一个 CREATE CURSOR 的 SQL 语句并复制到剪贴板。|2011/06/03
Schema|打印/查看当前表格的模式|2011/06/08
Super Browse|在 Grid 中浏览当前表，显示表结构。 并且，您可以选择字段并构造各种SQL语句（选择，插入，创建表格等）|2012/01/28
WLC Column Listing Utility|高亮显示 LIST FIELDS |2011/06/03
窗口|
Cycle thru Designer windows|在表单设计器和类设计器窗口之间切换|2011/06/03|<a href="Videos\Windows.wmv" target="_blank">(3:33)</a>
Move Designer windows to top|将表单和类设计器窗口移动到屏幕顶部并水平对齐。|2011/06/03|<a href="Videos\Windows.wmv" target="_blank">(3:33)</a>
Resize Designer Window|调整当前表单/类设计器窗口的大小以显示正在编辑的整个表单或类。|2011/06/03|<a href="Videos\Windows.wmv" target="_blank">(3:33)</a>
向导|
"Insert Into" from cursor|弹出表单，允许从当前表中选择字段，并在剪贴板中创建“Insert Into”语句|2012/01/28
Messagebox Wizard|弹出表单创建对MessageBox的调用|2012/01/28
