# hello-world
#python 模拟登陆过程
# 模拟登陆过程
# python 程序   练习

account = 'xuelei'   #定义用户账号
password = '123456'     #定义密码

print('输入账号')

r = 0
while r != 1:     #循环
    user_account = input()   #获取键盘输入
    if user_account == account:   
        r = 1
        p = 0
        while p != 1:
            print('输入密码')
            user_password = input()     #获取键盘输入
            if user_password == password:
                print('succeed')
                p = 1
            else : print('密码错误，重新输入')
    else: print('账号不存在，请重新输入')
        

# 程序结束  运行成功

