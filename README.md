
n = int(input("请输入一个整数:")); if n % 3 == 0 and n % 7 == 0:

a= input("请输入第一个整数")b= input("请输入第二个整数")if a>b:a,b=b,aprint(a,b)

ch.isdigit()ch.isalpha()

km<=3cost=10+(km-3)*1.2cost=10+7*1.2+(km-10)*1.5print('您需要支付{:.1f}元车费'.format(cost))




x = input('Please input x:') x = eval(x) if 0<=x<5: print(x) elif 5<=x<10: print(3*x-5) elif 10<=x<20: print(0.5*x-2) else: print(0)



money1=input("请输入欲兑换的数量(人民币以￥美元以$)结束:") money=eval(money1[0:-1]) if money1[-1]=="￥": money2=money/6 print("人民币{0:}元可以兑换{1:.2f}美元".format(money1,money2)) elif money1[-1]=="$": money2=money*6 print("{}美元可以兑换人民币{}元".format(money1,money2))




