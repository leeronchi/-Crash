# -Crash
快速找出无主要log输出的Crash

有时我们遇到程序Crash 很难通过控制台log查找具体崩溃位置

这时你可以通过：

Debug——>Breakpoints——>Create Exception Breakpoints ，Exception 选 Objective-C 

再次崩溃前，断点会停在崩溃位置、或附近，有助于快速定位我们的崩溃。
