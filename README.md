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



<!-- xcLeigh
https://blog.csdn.net/weixin_43151418 -->
<!DOCTYPE html>
<html lang="zh">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>细语甜言与卿听</title>
    <link rel="stylesheet" type="text/css" href="./css/index.css"/>
	<script src="js/jquery-2.1.1.min.js" type="text/javascript"></script>
	<script type="text/javascript" src="js/index.js"></script>
  </head>
  <body oncontextmenu="return false;" onselectstart="return false;" unselectable="on" ondragstart="return false;">
  <div class="chat_window">
    <div class="top_menu">
        <div class="buttons">
            <div class="button close"></div>
            <div class="button minimize"></div>
            <div class="button maximize"></div>
        </div>
        <div class="title">细语甜言与卿听</div>
    </div>
    <ul class="messages"></ul>
    <div class="bottom_wrapper clearfix">
        <div class="send_message" onclick="location.href='yujian.html'" style="background-color:rgb(145,0,255,0.3); cursor:default;">
            <div class="icon"></div>
            <div class="text">遇见</div>
        </div>
        <div class="send_message" onclick="location.href='xiangshu.html'">
            <div class="icon"></div>
            <div class="text">相熟</div>
        </div>
        <div class="send_message" onclick="location.href='xiangzhi.html'">
            <div class="icon"></div>
            <div class="text">相知</div>
        </div>
        <div class="send_message" onclick="location.href='xiangnian.html'">
            <div class="icon"></div>
            <div class="text">相恋</div>
        </div>
    </div>
</div>
<div class="message_template">
    <li class="message">
        <div class="avatar">
		</div>
        <div class="text_wrapper">
            <div class="text"></div>
        </div>
    </li>
</div>
  </body>
</html>
