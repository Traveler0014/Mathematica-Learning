# Mathematica-Learning
Slot 
#

表示提供给纯函数的第一个参数.

#n

表示第 n 个参数.

#name

表示在第一个参数中的一个相关性中与键值 "name" 相关联的数值.

#0 

表示整个纯函数

范例：
f[#1,#2]&[x,y]                    f[x,y]

f[#,#,#]&[x,y,z]                  f[x,x,x]

f[#a,#b]&[<|"a"=x,"b"=y|>]        f[x,y]
