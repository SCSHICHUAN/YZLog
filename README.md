# YZLog

# Xcode输出中文日志

# 直接将文件拷贝到项目里

# 配置工程      

TARGETS->Build Settings->Other Linker Flags 添加一个  -force_load

接着再添加一个 $(SRCROOT)/YZLog/libYZLog.a（具体路径看文件位置）
