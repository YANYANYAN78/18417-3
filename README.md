# 18417-3
成绩分级



利用条件运算符的嵌套来完成此题：学习成绩>=90分的同学用A表示，60-89分之间的用B表示，60分以下的用C表示。


x=int(input('the score is'))
if x>=90:
    g='A'
elif x>=60:
    g='B'
elif x<60:
    g='C'
    
    
print('%d is %s'%(x,g))



x=int(input())
print('A'if x>89 else 'B'if x>59 else 'C')



