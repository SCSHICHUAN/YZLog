# YZLog

# Xcode输出中文日志

# 直接将文件拷贝到项目里如图：

![Alt text](http://118.24.89.63:8080/5.png)


# 配置工程      

TARGETS->Build Settings->Other Linker Flags 添加一个  -force_load

接着再添加一个 $(SRCROOT)/YZLog/libYZLog.a（具体路径看文件位置）