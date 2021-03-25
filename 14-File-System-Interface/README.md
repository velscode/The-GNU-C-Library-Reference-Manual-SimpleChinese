# 14 File System Interface 文件系统接口

> This chapter describes the GNU C Library’s functions for manipulating files. Unlike the input and output functions (see Chapter 12 [Input/Output on Streams], page 266; see Chapter 13 [Low-Level Input/Output], page 342), these functions are concerned with operating on the files themselves rather than on their contents.

本章介绍GNUC库用于操作文件的函数。不像输入输出函数（参见第12章[流的输入/输出]，第266页；参见第13章[低级输入/输出]，第342页）那样，这些函数与操作文件本身有关，而不是与文件的内容有关。

> Among the facilities described in this chapter are functions for examining or modifying directories, functions for renaming and deleting files, and functions for examining and setting file attributes such as access permissions and modification times.

本章所述的函数包括检查和修改目录的函数、重命名和删除文件的函数、还有检车和设置文件属性（比如访问权限、修改时间）的函数。