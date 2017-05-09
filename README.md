修复volley中只能取到一个cookie的bug,只修改HurlStack文件，多cookies之间用;分割。
参考：http://blog.csdn.net/qiang_xi/article/details/50608653

打jar流程：(最简单)
1.确保安装了gradle
2.确保添加了android sdk环境变量
3.cd到项目文件夹下 执行gradle build
4.在生成的aar文件中提取jar或者到/build/intermediates/bundles/中拿取
