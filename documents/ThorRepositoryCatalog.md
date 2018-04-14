<div class="wikidoc">

## Thor 仓库工具目录

本文档由 xinjie 于 2018.04.14 翻译

工具|描述|更新日期|视频
---|---|---|---
Comment highlighted text|改进注释高亮文本的方法；也可以创建带有日期的注释行|2011/06/09
Un-comment highlighted text|从高亮文本中的每行删除注释。 适用于原生 VFP 注释。|2011/10/22
Wrap text with IF / ELSE / ENDIF|用 IF / ELSE / ENDIF 包装高亮显示的文本|2011/10/22
Wrap text with Try / Catch|使用 Try / Catch 包装突出显示的文本|2011/10/22
Wrap text with With / EndWith |用  With / EndWith 包装突出显示的文本|2012/01/28
Change IF/ENDIF in highlighted text to DO CASE|将突出显示的文本中的 IF / ENDIF 更改为 Do Case / otherwise / EndCase|2011/10/22
Break highlighted text|将高亮文本分解成单独的一行|2011/10/22
Extract to Constant|将当前高亮代码块提取到一个新的常量（#Define）中，并且显示在代码的开头，对于方法，会将其包含到Include文件中。 另请参阅IDE工具中的“Extract to Method”。|2011/10/22
Extract to Variable|将当前高亮代码块提取到新变量中。 另请参阅IDE工具中的“Extract to Method”。|2011/10/22
Code / Highlighting text|  
Highlight parameter|高亮显示方法或函数调用中的单个参数|2011/10/22
Highlight parentheses|高亮显示匹配括号之间的代码。 并在下一组括号重复使用高亮。|2011/10/22
Code / Inserting text|
Insert blank lines around control structures|在控制结构前后添加空行（IF / ENDIF，DO CASE / ENDCASE等）|2011/10/22
Insert call to NewObject (from MRU classes)|弹出基于 MRU 类的菜单; 然后将 NewObject( ) 引用粘贴到所选类中|2011/10/22
Insert color|使用GetColor（）提示颜色，并插入RGB值|2011/07/29
Insert full name of object under mouse|将鼠标下的对象的完整路径名粘贴到代码窗口中。 更新代码并使类定义正确工作|2011/07/29
Insert reference to class|插入对象所属类的引用; 如 This.Parent.Parent 等|2011/07/29
Code / MDots|
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
Miscellaneous|
"View Definition" uses "Go To Definition"|Modifies the right-click context menu for a code window so that selecting ‘View Definition’ causes ‘Go To Definition’ to run. Must be run once per session.|2012/01/28
Display ClassLibs|Display current class libraries in a dialog box, one per line.|2011/06/03
Display Path|Display current path in a dialog box in a dialog box, one per line.|2011/06/03
HackCX4 from MRU forms or classes|HackCX: Pop-up menu to select a form or class (from MRU lists) to be opened with HackCX4|2011/06/03
Toggle comment colors|Toggle colors for comments in edit windows (normal vs. subdued)|2011/06/03
Projects|
MRU classes in this project|Popup menu of MRU classes in the current project|2011/06/04|<a href="Videos\MRU.wmv" target="_blank">(1:56)</a>
MRU files in this project|Popup menu of MRU lists for files in the current project|2011/06/04|<a href="Videos\MRU.wmv"  target="_blank">(1:56)</a>
Open project folder|Open an Explorer folder showing the folder of the active project|2011/07/29
Samples|
Modify the “Last Revision” comment|Sample of finding a specific line in a edit window and modifying it.|2011/07/29
Wrap text with IF / ENDIF|Sample of taking the highlighted text in an edit window, modifying it, and pasting back the replacement.2011/06/09
Tables|  
Create SQL from cursor|Puts a CREATE CURSOR SQL statement on the clipboard from an open cursor.|2011/06/03
Schema|Print/View the current table's schema|2011/06/08
Super Browse|Browse current table in a grid, showing table structure.  You can then select fields and construct various SQL statements (Select, Insert, Create Table, etc.)|2012/01/28
WLC Column Listing Utility|LIST FIELDS replacement by White Light Computing.|2011/06/03
Windows|
Cycle thru Designer windows|Cycle thru Form Designer and Class Designer windows|2011/06/03|<a href="Videos\Windows.wmv" target="_blank">(3:33)</a>
Move Designer windows to top|Move Form and Class Designers to top of screen and align them horizontally.|2011/06/03|<a href="Videos\Windows.wmv" target="_blank">(3:33)</a>
Resize Designer Window|Resize current Form / Class Designer window to show the entire form or class being edited.|2011/06/03|<a href="Videos\Windows.wmv" target="_blank">(3:33)</a>
Wizards|
"Insert Into" from cursor|Pops up form which allows selection of fields from current table and creates an ‘Insert Into’ statement in the clipboard|2012/01/28
Messagebox Wizard|Pops up form for creating calls to MessageBox|2012/01/28
