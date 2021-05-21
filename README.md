# launchOrder
1\直接搜索 Other C Flags 来到 Apple Clang - Custom Compiler Flags 中 , 添加

-fsanitize-coverage=func,trace-pc-guard 

swift混编也添加Other Swift Flags
-sanitize-coverage=func
-sanitize=undefined

将生成order file拖到工程，甚至order file 路径
$(SRCROOT)/ktv/lb.order


Write Link Map File 可以查看结果
