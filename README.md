自定义协议 注册表 脚本
custom protocl webower
=======


Windows Registry Editor Version 5.00
 
[HKEY_CLASSES_ROOT\xxxx]
@="URL:xxxx Protocol"
"URL Protocol"="C:\\WINDOWS\\system32\\calc.exe"
 
[HKEY_CLASSES_ROOT\xxxx\DefaultIcon]
@="C:\\WINDOWS\\system32\\calc.exe"
 
[HKEY_CLASSES_ROOT\xxxx\shell]
@="open"
 
[HKEY_CLASSES_ROOT\xxxx\shell\open]
@="open"
 
[HKEY_CLASSES_ROOT\xxxx\shell\open\command]
@="\"C:\\WINDOWS\\system32\\calc.exe\" \"%1\""

#### Webowser input  xxxx://    go calc!####


