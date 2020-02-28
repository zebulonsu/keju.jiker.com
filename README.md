Kata介绍
通过文本文件向应用程序提供输入数据testData.txt(src/main/resources/testData.txt)。

在AppRunner.java中集成你写的代码，并将结果赋值给receipt变量。

args[0]为resources下的测试数据文件名，例如传入的args[0]值为"testData.txt"。

你写的程序将把testDataFile作为参数加载此文件并读取文件内的测试数据，并对每条测试数据计算结果。

将所有计费结果拼接并使用\n分割，然后保存到receipt变量中。

不必为AppRunner.java写单元测试，AppRunner.java也不会统计测试覆盖率。

不得修改build.gradle与checkstyle.xml文件。
