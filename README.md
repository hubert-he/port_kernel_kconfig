# port_kernel_kconfig
the portable linux kernel Kconfig
=========================================
编译方式
=========================================
1. make all
2. make clean

主要内容
=========================================
1. oskConf    处理程序，移植自Linux kernel 3.12.5
2. TestConfig 测试示例，简要的概括了 宏之间的依赖关系的书写方式
3. Kconfig    根据config.func 简单整理而得到的配置文件

TestCase运行方式
=========================================
1. 运行命令： 
    ./oskConf Kconfig 
2. 可视化配置
  如下图
3. 生成config.func文件
  保存

![image](https://github.com/hubert-he/port_kernel_kconfig/blob/master/TestCase/img1.jpg)

