MkLink
======

本程序主要功能为创建符号链接，通过 mklink 命令实现，支持 Windows 7 及更新版本  

各功能说明：  

1. 选项  
	- 符号链接（d）：用于目录，允许相对路径
	- 软链接（j）：用于目录
	- 硬链接（h）：用于文件，删除源文件，不影响链接文件

2. 模式
	- 链接：在链接路径建立源文件或目录的链接
	- 映射：先把文件或目录从源路径迁移到链接路径，再在源路径建立链接

3. 批量链接
	- 命令格式：{链接路径}|{源路径}[|{链接类型}][|{链接模式}]

4. 日志：使用批量链接会生成日志，日志路径在程序的Log目录下
