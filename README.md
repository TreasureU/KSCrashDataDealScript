# KSCrashDataDealScript
使用Python脚本编写的定制化KSCrash崩溃文件的处理程序，配合 KSCrashDataManager使用更佳，可以使用GUI，不考虑脚本复杂的参数。

预先配置操作：
1.arm64:下面放 arm64 架构的系统库的符号表文件，命名形式为【库名_iosVersion】
2.armv7:下面放 armv7 架构的系统库的符号表文件，命名形式为【库名_iosVersion】
3.armv7s:下面放 armv7s 架构的系统库的符号表文件，命名形式为【库名_iosVersion】
4.self: 将自己的程序符号表文件，放在这里。

系统bug匹配：
可以通过修改 parserScript 下的json 文件实现匹配，具体匹配规则下次详述。

