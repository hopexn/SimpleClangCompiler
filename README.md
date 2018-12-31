# SimpleClangCompiler
编译原理大作业，简单的C编译器
主要做的工作包括：词法、语法、语义和目标代码生成

编译最终生成汇编指令，可在DOSBOX模拟器中运行

使用方法： 
1. "./test.sh <文件名> "
    ./test.sh 会自动编译lex yacc等文件，然后使用./testcase/<文件名>进行测试
2. "./push.sh <注释> " 
    自动添加文件到git仓库并push

a = 1 + 2

