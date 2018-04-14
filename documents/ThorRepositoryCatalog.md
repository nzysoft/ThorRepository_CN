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
Add MDots to variable names|Adds MDots to all references to parameters, locals, and other variables assigned values.|2011/10/22
Remove MDots from variable names|Removes MDots from all references to parameters, locals, and other variables.|2011/10/22
Code / Misc.|
Install enhanced ZLOC|Installs an enhanced version of ZLOC, which will cause the pop-up list to also include all variables assigned in code, whether they are in the LOCALs list or not.  Note that this only need be done once, is it updates FoxCode.|2011/10/22
Modify Class for PRG-based classes|Provides a mechanism to convert a PRG based class (with no child objects) into a temporary VCX so that IDE Tools can work on it; and then post back again into the PRG. See [Modify class for PRG-based classes.](https://github.com/VFPX/Thor/blob/master/Docs/VCD4PRG.md)|2011/10/22
Remove blank lines|Removes all blank lines from the current code window|2012/01/28
Go To ...|
Go To ‘Find’ in PEM Editor|Sets focus to the ‘Find’ textbox in PEM Editor; opens PEM Editor if it is not already open|2011/10/22
Go To File|Opens a dialog with a filter box to quickly select a file (PRG, SCX, VCX, etc.) from the Active Project|2011/10/22
Go To Include File|Opens the include file for the form or class being editres|2012/01/28
Go To Method|Opens a dialog form to choose a method to view or edit. Allows searching by part of a method name.|2011/06/03
Go To Object|Select the object which the code window belongs to.|2011/07/29
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
