# seafile客户端交叉编译到windows运行，fedora28

 参考网站，很感谢该网站的作者！!   
http://www.ilovecpp.com/2018/06/25/seafile-compile/  
其实按照作者的去做，正常来说是可以成功编译的。再修改运行copy_dependent_dll.sh脚本，不出意外就可以在windows下运行了。  
  
为了避免作者网站登不进去，这里作为作者博客的备份，和补充。  
auto-install-qt-tools.sh 安装依赖库   
copy_dependent_dll.sh 拷贝软件依赖的库到exe目录下   
download-source-code.sh 下载相关源码，本脚本主要是从官方路径下下载   
Makefile.mak make构建文件   
CMakeLists.txt 修改后的seafile-client-{版本}的cmake构建文件   
toolchain-i686-w64-mingw32.cmake 交叉编译用到的文件，作为补充  
cross-compile-guide.docx 交叉编译的指南  
