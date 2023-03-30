from functools import reduce
print(reduce(lambda x,y:x*y,range(1,101)))


#range函数，sum求和
print(sum(range(1,100,2)))
#for 嵌套 if
sum=0
for i in range(100):
    if i%2==0:
        continue
    sum+=i
print('1到100之间奇数和为:{}',format(sum))
#while语句
count=0
number=1
while number<100:
    count+=number
    number+=2
print(count)


#100以内能被3整除不能被5整除
#while
i=1
while i <=100:
    if i%3==0 and i%5!=0:   
        print(i, end="\t")
    i += 1
#for
num = 0
for i in range(1,101):
    if i % 3 ==0:   
        if i % 5 != 0:
            print({i},end="\t")


#1000-2000年之间的闰年，每行五个
#while语句
i = 1000
count = 0
while i <= 2000:
    if (i % 400 ==0) or (i % 4 ==0 and i % 100 !=0):
        print(i,end="\t")
        count +=1
        if count % 5 == 0:
            print()
    i += 1
#for语句
k = 0
for 
