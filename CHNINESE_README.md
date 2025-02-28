### 1、此编译脚本需要在Linux环境下进行编译，如果当前电脑是windows系统，可以通过vmware安装虚拟机（比如Ubuntu系统）来进行编译
### 2、在Linux环境下将此项目下载在本地后，修改config.conf里面配置文件，主要是ndk、openssl的版本，根据自己的需要进行修改，此外还有编译pjsip的版本，
特别注意：如果下载的pjsip版本大于等于2.15，那么Android编译的版本就必须大于等于29，也就是Android10+设备才能使用
### 3、执行prepare-build-system这个脚本文件后，如果直接执行build可能会失败，这时就需要根据[pjsip](https://docs.pjsip.org/en/latest/get-started/android/requirements.html)文档步骤手动编译
