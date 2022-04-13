# daily_practise_4.13
 for the prepare for the last test of the postgraduate examination,the practise has been paused for a week.
 and  the practise will go on from today, I'd like to exert my best to do it well.the codes and the content has been becoming more and more difficult so that i
 can not able to put it aside for a while.
 today practise:
 #函数的递归
def fact(n):
    if n == 0:
        return 1
    else:
        return n * fact(n-1)
num = eval(input('a nuber:'))
print(fact(int(abs(num))))

#字符串反转
a = 'abcdefg'
print(a[::-1])
b=''.join(reversed(a))
print(b)

#understanding
import turtle as tl
def koch(size,n):
    if n == 0:
        tl.fd(size)
    else:
        for angle in [0, 60, -120, 60]:
            tl.left(angle)
            koch(size/ 3,n-1)
def main():
    tl.setup(800,500,200,200)
    tl.penup()
    tl.goto(-300,-50)
    tl.pendown()
    tl.pensize(2)
    tl.pencolor('red')
    koch(600,3)
    tl.hideturtle()
main()

![image](https://user-images.githubusercontent.com/102724466/163147495-1636d881-9a55-4fb9-8318-04f983cee278.png)
  a='987616521'
print(sorted(a)) sorted 返回的是一个list 会将输入的内容转化为list 之后进行运算，在返回list？
#画田字格
![image](https://user-images.githubusercontent.com/102724466/163164391-fb51a4d1-f5fc-4bcb-86da-9f8f3e82d692.png)
