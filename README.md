# IDEA&Android Studio快捷键

####  写在前面

```
PS：MacBookPro 国行版键盘上根本就没有印上那些鬼符号，只有一个Command菊花
ps续：18款的mbp上有，至少15寸的有，至少，15款的没有；

Mac独有按键说明，对比Windows：

Caps Lock ⇪  ---> Caps Lock 大写锁定键
Shift ⇧  --->   Shift键
Control (or Ctrl) ⌃  ---> Control键
Option (or Alt) ⌥   --->  Alt键
Command (or Cmd) ⌘  --->   Windows键

Mac键盘对比Windows键盘的主要差异在于：

 *Command和Option对应Windows中的Windows和Alt这两个键的物理位置是相反的；

```
> * [苹果官方keyboard shortcuts说明](https://support.apple.com/en-us/HT201236) 
> * Linux和Windows快捷键是一致的，**粗体**为常用能提高生产力快捷键，推荐记忆

#### 必须记住的快捷键[Remember these shotcuts]：

Function | 功能 | Windows | Mac
---|---|---|---
**Smart code completion**|**快速代码补全**|Ctrl + Shift + Space| Option + Shift + Space
**Search everywhere**|**全局搜索**|双击Shift|双击Shift
**Show intention actions and quick-fixes**|**显示建议并快速修复(类似Eclipse中的错误鼠标悬停点击修复)**|Alt + Enter| Command+Enter
**Generate code**|**自动生成代码(Get,Set,构造之类)**|Alt + Insert|Command+N或Option+Enter
**Parameter info**|**显示方法参数信息(光标需要放在参数区域)**|Ctrl + P|Command + P
**Extend selection**|**扩展选定的内容(以光标所在位置扩大选定的代码块，按一次扩大一次)**|Ctrl+W|Option + ↑
**Shrink selection**|**缩小选定的内容(同上)**|Ctrl+Shift+W|Option + ↓
**Recent files popup**|**弹出最近使用过的文件列表**|Ctrl + E|Command + E
**Rename**|**重命名**|Shift + F6| Shift + F6

#### 常规[General]

Function | 功能 | Windows | Mac
---|---|---|---
**Open corresponding tool window**|**打开对应的工具窗口(主界面的小窗口标注了响应带下划线的数字)**|Alt + [0~9]|Command + [0~9]
Save all|保存全部|Ctrl + S|Command + S
Synchronize|同步|Ctrl + Alt + Y|Command + Option + Y
**Toggle maximizing editor**|**将编辑器在最大化和正常之间切换**|Ctrl + Shift + F12|Command + Shift + F12
Inspect current file with current profile|使用当前配置文件检查当前文件|Alt + Shift + I| Option + Shift + I
Quick switch current scheme|快速切换当前方案(e.g.界面配色什么的..)|Ctrl + `(~那个键)|
**Open Settings dialog**|**打开IDEA设置窗口**|Ctrl + Alt + S|Command + ,
**Open Project Structure dialog**|**打开项目结构窗口**|Ctrl+Alt+Shift+S|Command + ;
**Find Action**|**查找IDEA操作和选项**|Ctrl + Shift + A|Command + Shift + A

#### 调试[Debugging]

Function | 功能 | Windows | Mac
---|---|---|---
**Step over / into**| **跨过/进入**|F8 / F7|F8 / F7
Smart step into/Step out|智能 步进/步出|Shift + F7 / Shift + F8|Shift + F7 / Shift + F8
Run to cursor|运行到光标处|Alt + F9| Option + F9
**Evaluate expression**|**计算表达式**|Alt + F8| Option + F8
Resume program|重新运行程序|F9|Command + Option + R
**Toggle breakpoint**|**切换断点**|Ctrl + F8|Command + F8
View breakpoints|查看断点|Ctrl + Shift + F8|Command + Shift + F8

#### 搜索/替换[Search / Replace]

Function | 功能 | Windows | Mac
---|---|---|---
**Search everywhere**|**全局搜索**|双击Shift|双击Shift
**Find**|**查找**|Ctrl + F| Command + F
Find next /previous|查找下一个/上一个| F3 / Shift + F3| Command + G / Command + Shift + G
Replace|替换|Ctrl + R| Command + R
Find in path|在所选路径中查找|Ctrl + Shift + F|Command + Shift + F
Replace in path|在所选路径中替换|Ctrl + Shift + R|Command + Shift + R
**Select next occurrence**|**选定下一个匹配项(每个匹配项后都会显示光标)**|Alt + J| Control + G
Select all occurrences|选定所有的匹配项(同上按一次选中所有块)|Ctrl + Alt + Shift + J| Control + Command + G
Unselect occurrence|取消所有选定的匹配项|Alt + Shift + J|Control + G

#### 编辑[Editing]

Function | 功能 | Windows | Mac
---|---|---|---
**Basic code completion**|**基本代码补全**|Ctrl + Space|Control + Space
**Smart code completion**|**智能代码补全**|Ctrl + Shift + Space| Control + Shift + Space
**Complete statement**|**完成(立即在当前行下插入空行并将光标移动至新行,类似Eclipse的Shift+Enter)**|Ctrl + Shift + Enter|Command + Shift + Enter
**Parameter info (within method call arguments)**|**参数信息(光标需要放在参数区域)**|Ctrl + P| Command + P
**Quick documentation lookup**|**快速查找文档(本地没有会联网找)**|Ctrl + Q|Control + J
**External Doc**|**查看外部文档(会打开浏览器显示本地or网站文档)**|Shift + F1|Shift + F1
**Brief Info**|**简要信息**|Ctrl+鼠标点进去|Control + 鼠标点进去
**Show descriptions of error at caret**|**在符号位置显示错误说明**|Ctrl + F1|Control + F1
**Generate code...**|**自动生成代码(Get,Set,构造之类)**|Alt + Insert|Command+N或Option+Enter
**Override methods**|**重写方法**|Ctrl + O| Control + O
**Implement methods**|**实现方法**|Ctrl + I| Control + I
**Surround with…**|**选定代码块添加包围(如if,try-catch块)**|Ctrl + Alt + T| Command + Option + T
**Comment / uncomment with line comment**|**使用/取消行注释**|Ctrl + /| Command + /
**Comment / uncomment with block comment**|**使用/取消块注释**|Ctrl + Shift + /|Command + Shift + /
**Extend selection**|**扩展选定的内容(以光标所在位置扩大选定的代码块，按一次扩大一次)**|Ctrl+W|Option + ↑
**Shrink selection**|**缩小选定的内容(同上)**|Ctrl+Shift+W|Option + ↓
**Context info**|**上下文信息(滚动条到下面时可以显示上面看不到的上下文信息)**|Alt + Q|Control + Shift + Q
**Show intention actions and quick-fixes**|**显示建议并快速修复(类似Eclipse中的错误鼠标悬停点击修复)**|Alt + Enter| Command + Enter
**Reformat code**|**重新格式化代码**|Ctrl + Alt + L|Command + Option + L
**Optimize imports**|**优化导入(去掉没使用到的导入类)**|Ctrl + Alt + O|Control + Option + O
**Auto-indent line(s)**|**自动缩进光标所在行**|Ctrl + Alt + I|Control + Option + I
Indent /unindent selected lines|缩进/取消缩进行|Tab / Shift + Tab|Tab / Shift + Tab
Cut current line to clipboard|将当前行剪切到剪贴板(无需全选)|Ctrl + X,Shift + Delete|Command + X
Copy current line to clipboard|将当前行复制到剪贴板(无需全选)|Ctrl + C,Ctrl + Insert|Command + C
Paste from clipboard|从剪贴板中粘贴内容|Ctrl + V,Shift + Insert|Command + V
Paste from recent buffers...|从最近缓存中粘贴内容(剪贴板历史,默认5条记录可以在设置中修改)|Ctrl + Shift + V|Command + Shift + V
**Duplicate current line**|**复制当前行到下一行(类似Eclipse中的Shift+Alt+↓)**|Ctrl + D|Command + D
Delete line at caret|删除插入符号(光标)所在的行|Ctrl + Y|Command + Backspace
Smart line join|智能追加行(把光标后续的行追加到当前行)|Ctrl + Shift + J|Ctrl + Shift + J
**Smart line split**|**智能划分行(跟回车一样只是光标还留在当前行)**|Ctrl + Enter|Command + Enter
**Start new line** |**开始新的一行**|Shift + Enter|Shift + Enter
Toggle case for word at caret or selected block|切换插入符(光标)所在单词或选中的代码块的大小写|Ctrl + Shift + U|Command + Shift + U
Select till code block end / start|选中直到代码块的开始/结束部分|Ctrl + Shift + ] / [|Command + Shift + ] / [
Delete to word end|删除此单词(光标所在位置)之后的内容|Ctrl + Delete| Option + 
Delete to word start|删除此单词(光标所在位置)之前的内容|Ctrl + Backspace|Option + Backspace
Expand/collapse code block|展开/折叠代码块|Ctrl + +/-(小键盘和数字区均可)|Command + +/-
Expand all|展开全部代码块|Ctrl + Shift + +| Command + Shift + +
Collapse all|折叠全部代码块|Ctrl + Shift + -| Command + Shift + -
**Close active editor tab**|**关闭当前活动的编辑标签页**|Ctrl + F4|Command + W

#### 重构[Refactoring]

Function | 功能 | Windows | Mac
---|---|---|---
**Copy**|**复制所选文件到新路径**|F5|F5
**Move**|**移动所选文件到新路径**|F6|F6
Safe Delete|安全删除(属性,方法,类,文件等)|Alt + Delete|Command + Delete
**Rename**|**重命名(属性,方法,类,文件等)**|Shift + F6|Shift + F6
Refactor this...|重构选中代码块|Ctrl + Shift + Alt + T|Shift + T
**Change Signature**|**修改签名**|Ctrl + F6|Command + F6
Inline|内联(找出有哪些类引用了此方法)|Ctrl + Alt + N|Command + Option + N
**Extract Method**|**提取所选内容到重构为新方法**|Ctrl + Alt + M|Command + Shift + M
**Extract Variable**|**提取变量**|Ctrl + Alt + V|Command + Shift + V
Extract Field|提取字段|Ctrl + Alt + F|Command + Shift + F
Extract Constant|提取常量|Ctrl + Alt + C|Command + Shift + C
Extract Parameter|提取参数|Ctrl + Alt + P|Command + Shift + P

#### 导航[Navigation]

Function | 功能 | Windows | Mac
---|---|---|---
**Go to class**|**前往某个类**|Ctrl + N|Command + O
**Go to file**|**前往某个文件**|Ctrl + Shift + N|Command + Shift + O
**Go to symbol**|**前往某个符号(打开文件后跳转到某个词的位置)**|Ctrl + Shift + Alt + N|Command + Option + O
Go to next /previous editor tab|前往下一个/上一个编辑标签页|Alt + ← / →|Option + ← / →
Go back to previous tool window|返回上一个工具窗口|F12|F12
**Go to editor (from tool window)**|**从工具窗口返回到编辑器**|ESC|ESC
Hide active or last active window|隐藏当前活动工具窗口或最后一个活动过的工具窗口|Shift + ESC|Shift + ESC
**Go to line**|**前往某行**|Ctrl + G|Command + L
**Recent files popup**|**弹出最近使用过的文件列表**|Ctrl + E|Command + E
Navigate back/ forward|导航到上一步/下一步|Ctrl + Alt + ← / →|Command + Option + ← / →
**Navigate to last edit location**|**导航到最后一个编辑的地方**|Ctrl + Shift + Backspace|Command + Shift + Backspace
**Select current file or symbol in any view**|**在选择的文件和内容处打开任何视图(显示在资源管理器中等)**|Alt + F1|Option + F1
**Go to declaration**|**跳转到声明(类似Eclipse的Ctrl+鼠标左击)**|Ctrl + B / Click|Command + B / Click
**Go to implementation(s)**|**跳转到执行处**|Ctrl + Alt + B|Command + Option + B
**Open quick definition lookup**|**打开快速定义查找(直接在当前页显示选中的文件的内容)**|Ctrl + Shift + I|Option + Space / Command + Y
Go to type declaration|跳转到类型声明|Ctrl + Shift + B|Option + Shift + B
Go to super-method/ super-class|跳转到父方法/父类|Ctrl + U| Command + U
Go to previous /next method|跳转到上一个/下一个方法|Alt + ↑ / ↓|Option + ↑ / ↓
Move to code block end/ start|移动(光标)到代码块的结束/开始位置|Ctrl + ] / [|Command + ] / [
**File structure popup**|**显示文件结构窗口**|Ctrl + F12| Command + F12
Type hierarchy|显示类型层次结构|Ctrl + H|Command + H
Method hierarchy|显示方法层次结构|Ctrl + Shift + H|Command + Shift + H
Call hierarchy|显示调用层次结构|Ctrl + Alt + H|Control + Option + H
Next /previous highlighted error|(移动光标到)下一个/上一个突出显示错误的位置|F2 / Shift + F2|F2 / Shift + F2
Edit source/View source|编辑源/显示源|F4 / Ctrl + Enter|F4 / Command + ↓
**Show navigation bar**|**显示导航条**|Alt + Home|Option + Home
Toggle bookmark|增删书签|F11| F3
Toggle bookmark with mnemonic|使用一个助记符增删书签|Ctrl + F11|Option + F3
Go to numbered bookmark|跳转到指定书签|Ctrl + [0~9]|Control + [0~9]
Show bookmarks|显示所有书签|Shift + F11|Command + F3


#### 编译和运行[Compile and Run]

Function | 功能 | Windows | Mac
---|---|---|---
**Make project**|**构建项目**|Ctrl + F9|Command + F9
Compile selected file, package or module|编译所选择的文件,包,或模块|Ctrl + Shift + F9/F10|Command + Shift + F9
Select configuration and run/debug|选择配置文件运行/调试|Alt + Shift + F9 / F10|Control + Option + R / D
**Run/Debug**|**运行 / 调试**|Shift + F9 / F10|Control + R / D
Run context configuration from editor|从编辑器运行上下文配置|Ctrl + Shift + F10|Control + Shift + R / D

#### 使用搜索[Usage Search]

Function | 功能 | Windows | Mac
---|---|---|---
**Find usages /Find usages in file**|**在文件中查找**|Alt + F7 / Ctrl + F7|Option + F7 / Command + F7
**Highlight usages in file**|**在文件中高亮显示所选内容**|Ctrl + Shift + F7|Command + Shift + F7
**Show usages**|**显示在哪里使用了这个方法**|Ctrl + Alt + F7|Command + Option + F7

#### 版本控制/本地历史[VCS / Local History]

Function | 功能 | Windows | Mac
---|---|---|---
**Commit project to VCS**|**向版本控制提交项目**|Ctrl + K|Command + K
**Update project from VCS**|**从版本控制更新项目**|Ctrl + T|Command + T
**Push commits**|**(往远程仓库)推送提交的代码**|Ctrl + Shift + K|Command + Shift + K
**‘VCS’ quick popup**|**版本控制快捷面板**|Alt + `|Control + V

#### Live模板[Live Templates]

Function | 功能 | Windows | Mac
---|---|---|---
Surround with Live Template|将所选的代码块外部包上Live模板代码|Ctrl + Alt + J|Command + Option + J
Insert Live Template|(在光标处)插入Live模板代码|Ctrl + J|Command + J