# compiler_project
编译原理课程大作业：实现了C语言的词法分析器和语法分析器，生成了语法分析表 <br>
（1）	针对测试程序输出其语法分析结果； <br>
源程序： <br>
// This is a note. <br>
int main(int a, int b){ <br>
int res; <br>
res = a + b; <br>
int d = a; <br>
if (a < 0){ <br>
res = -a; <br>
} <br>
else{ <br>
while (b > 0){ <br>
b = b-1; <br>
} <br>
res = 0; <br>
} <br>
} <br>
# 界面：
![界面](https://github.com/user-attachments/assets/61538ebd-e93c-4f38-9fd7-16e07a43a458)
# 词法分析结果：
![词法分析结果](https://github.com/user-attachments/assets/9d5b3c4d-3bb4-438d-8f7c-b8066dcaac1e)
# FIRST集：
![FIRST集](https://github.com/user-attachments/assets/6a9697fe-fbb0-47bc-bed0-bc9d76decf19)
# FOLLOW集：
![FOLLOW集](https://github.com/user-attachments/assets/42901c9b-2882-42c0-bb02-1fdd2c5902c1)
# LR(0)项目集规范族：
![LR(0)项目集规范族](https://github.com/user-attachments/assets/5b711459-3309-4f30-8c43-4663cd9f1a28)
# ACTION表：
![ACTION表](https://github.com/user-attachments/assets/8db36eaf-5b8f-4d39-bcf7-24b730139542)
# GOTO表：
![GOTO表](https://github.com/user-attachments/assets/40d15766-de72-4be4-b7a5-427234510134)
# 语法分析记录：
![语法分析记录](https://github.com/user-attachments/assets/c149737e-4ac9-40e6-872e-cf7d7dd8dbc6)
![语法分析记录1](https://github.com/user-attachments/assets/5ca4a9f2-36e2-478c-baa4-44132a4f3b02)

