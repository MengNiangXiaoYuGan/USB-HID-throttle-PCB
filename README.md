# USB-HID-throttle-PCB

该仓库作为USB-HID-throttle项目的电路板仓库,仓库内文件夹结构如下


|

|\  ternel_box  //节流阀主体的电路板，用于进行信号转换和USB通信

|

|\  ternel_handel   //节流阀手柄的电路板，用于tdc，雷达俯仰轴和两个五向开关的连接

|

|-  .gitignore      //用于排除包含电路设计过程中的备份文件

|   

|-  firmware.bin    //编译好的固件

|

|-  LICENSE     //许可证文件



如果不打算使用源文件的话，可以直接下载releases中的压缩包，里面包含了两块电路板的gerber文件和动态bom单，以及关于为了下载程序需要对电路板进行应急处理

另外，为了制造具有完整功能的USB-HID节流阀，还需要制造外壳模型以及下载程序。
模型可以从以下仓库获得
https://github.com/MengNiangXiaoYuGan/USB-HID-throttle-model.git

程序源码可以在以下仓库获得，或者在电路板仓库中直接使用已经编译好的bin文件
https://github.com/MengNiangXiaoYuGan/USB-HID-throttle-program.git

祝，使用愉快，有问题请反馈，有闲心会看一下
