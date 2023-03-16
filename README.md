- 👋 Hi, I’m @95544
- 👀 I’m interested in ...
- 🌱 I’m currently learning ..
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

s = "www.moe.gov.cn" print("第一个字符是:",s[0]) print("前三个字符是:",s[0:3]) print("后三个字符是:",s[11:]) print("字符串的总长度:",len(s)) id1 = s.index('o') print("o在字符串的",id1,"的位置") count = s.count('o') print("o在字符串出现的总次数是:",count) s1 = s.replace(".","-") print(s1) s2 = s.upper() print(s2) list1 = s.split('.') print(list1) print(s)



                                               myName = input("我的名字是：")firstChumName = input("我第一个室友的名字是：")secondChumName = input("我第二个室友的名字是：")thirdChumName = input("我第三个室友的名字是：")print("我们的组合是："+myName[-1]+firstChumName[-1]+secondChumName[-1]+thirdChumName[-1]) 
moths="JanFebMarAprMayJunJulAugSepOctNovDec"
n=input()
pos=(int(n)-1)*3
mothAbbrev=moths[pos:pos+3]
print(mothAbbrev)
                                                                                                                                                                                                                                                               

#3-2
s="www.moe.gov.cn"
print(s[0])
print(s[0:3])
print(s[-3:])
print(len(s))
print(s.index('o'))
print(s.count('o'))
print(s.replace('.','-'))
print(s.upper())
print(s.split('.'))
print(s)


#3-4

month="JanFebMarAprMayJunJulAugSepOctNovDec"
monthid=eval(input("请输入数字月份1~12："))
pos=(monthid-1)*3
print("{}月对应的英文缩写是:{}".format(monthid,month[pos:pos+3]))


#3-5
rmb=input("请输入要兑换的人民币，以￥结束：")
my=float(rmb[0:-1])*0.1456
print("{}人民币可以兑换{:.2f}美元".format(float(rmb[0:-1]),my))
