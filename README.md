# keju.jiker.com
极客学院tdd考试
Kata介绍
通过文本文件向应用程序提供输入数据testData.txt(src/main/resources/testData.txt)。
在AppRunner.java中集成你写的代码，并将结果赋值给receipt变量。
args[0]为resources下的测试数据文件名，例如传入的args[0]值为"testData.txt"。
你写的程序将把testDataFile作为参数加载此文件并读取文件内的测试数据，并对每条测试数据计算结果。
将所有计费结果拼接并使用\n分割，然后保存到receipt变量中。
不必为AppRunner.java写单元测试，AppRunner.java也不会统计测试覆盖率。
不得修改build.gradle与checkstyle.xml文件。
出租车计价：
不大于2公里时只收起步价6元。
超过2公里的部分每公里收取0.8元。
超过8公里的部分，每公里加收50%长途费。
停车等待时加收每分钟0.25元。
最后计价的时候司机会四舍五入只收到元。
测试数据：
1公里,等待0分钟\n
3公里,等待0分钟\n
10公里,等待0分钟\n
2公里,等待3分钟
期望输出：
收费6元\n
收费7元\n
收费13元\n
收费7元\n
开始考试
点击开始考试。
下载考题模板并解压，重命名为tdd-taxi。
cd tdd-taxi。
git init。
git remote add origin <github自有仓库>。
git add .。
git commit -m "Initial commit"。
git push -u origin master。
接着答题，使用gradle build或./gradlew build验证本地结果。
本地验证无误后，push到远程仓库，并将git地址提交到科举。
提交之后等待科举出考试结果。
考试通过的标准
通过checkstyle规则(配置文件见config/checkstyle/checkstyle.xml)：
单个Java文件不得超过50行。
单行代码长度不得超过150个字符。
单个方法长度不得超过10行。
单个方法的圈复杂度不得超过4。
单个方法参数个数不得超过3。
友好的方法命名。
在规定考试时间内完成答题，并完成所有需求。
测试覆盖率100%，没有严重的Sonar问题。
采用TDD开发模式。
