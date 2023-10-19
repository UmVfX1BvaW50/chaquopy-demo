# chaquopy-demo

- 一个hello world的chaquopy使用案例
- 主要需要配置的文件是全局和app的build.gradle，在文件中有注释

- 具体配置方法可以参考
  - https://chaquo.com/chaquopy/doc/current/android.html
  - https://juejin.cn/post/7104465131723030564
 
# 一些问题
1. 官方比较支持python3.8
2. python路径直接写死即可，要打包可以利用pip install剥离
3. 如果AS不能识别python的函数，比如print，包导入等等。首先确保你的python.exe和pip已经导入，以及sourcedir指向正确。做完这些还有问题，直接忽略
