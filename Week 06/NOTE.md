学习笔记

https://tc39.es/ecma262/#sec-intro


# 非形式语言 
  英文  中文

# 形式语言 
  计算机语言

  乔姆斯基谱系：是计算机科学中刻画形式文法表达能力的一个分类谱系，是由诺姆·乔姆斯基于 1956 年提出的。它包括四个层次：
  
  0- 型文法（无限制文法或短语结构文法）包括所有的文法。
  
  1- 型文法（上下文相关文法）生成上下文相关语言。
  
  2- 型文法（上下文无关文法）生成上下文无关语言。
  
  3- 型文法（正规文法）生成正则语言。
  
  编程语言的描述一般可以分为语法及语义。
  
  语法是说明编程语言中，哪些符号或文字的组合方式是正确的，语义则是对于编程的解释

    形式语言——用途 

    数据描述语言：JSON HTML XAML SQL CSS
    
    编程语言：Java C C++ VB PHP C# Python JavaScript Ruby
    
    形式语言——表达方式

    声明式语言:JSON HTML XAML SQL CSS
    
    命令型语言:C C++ Java C# Python Ruby JavaScript PHP

# 产生式

## 四则运算
1 + 2 *（3-1）
终结符：

Number
+-*/()

非终结符符：

MultiplicativeExpression

AddtiveExpression

PrimaryExpression

BNF

MulltiplicativeExpression::=BraketExpression|

    MulltiplicativeExpression"*"Number|
    
    MulltiplicativeExpression"/"Number|
    
AddtiveExpression::=MulltiplicativeExpression|

    AddtiveExpression"+"MulltiplicativeExpression|
    
    AddtiveExpression"-"MulltiplicativeExpression|
    
BraketExpression::=Number|"("AddtiveExpression")"

