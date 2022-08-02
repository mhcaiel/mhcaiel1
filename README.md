# mhcaiel1
python 基礎程式邏輯練習
#====練習題1  =====
#只能用 if…elif…else
"""
x=input("請輸入一個數字")
x=int(x)
if x==1:
    print("壹")
elif x==2:
    print("貳")
elif x==3:
    print("參")
elif x==4:
    print("肆")
elif x==5:
    print("伍")
elif x==6:
    print("陸")
elif x==7:
    print("柒")
elif x==8:
    print("捌")
elif x==9:
    print("玖")
else:
    print("以上皆非")

#===練習題2  =====
#只能用 if…elif…else
print("輸入英文水果名")
x=input("請輸入fruit：")
if x=="apple":
    print("蘋果")
elif x=="banana":
    print("香蕉")
elif x=="watermelon":
    print("西瓜")
else:
    print("以上皆非")

#===練習題3  =====
#只能用 if…elif…else
x=int(input("請輸入數學分數0~100:"))
if x>=90:
    if x<=100:
        print("A 級分")
elif x>=80:
    if x<=89:
        print("B級分")
elif x>=70:
    if x<=79:
        print("C級分")
elif x>=60:
    if x<=69:
        print("D級分")
elif x>=0:
    if x<=59:
        print("E級分")
else:
    print("以上皆非")

#===練習題4  =====
#只能用 if…elif…else    and
x=int(input("請輸入月分1~12:"))
if x>=2 and x<=4:
    print("春天")
elif x>=5 and x<=7:
    print("夏天")
elif x>=8 and  x<=10:
    print("秋天")
else:
    if x==11:
        print("冬天")
    elif x==12:
        print("冬天")
    elif x==1:
        print("冬天")
    else:
        print("以上皆非")
"""
#===練習題5  =====
#只能用 if…elif…else （不能用and）
x=input("請輸入顏色 red 或 green：")
y=input("請輸入水果 apple 或 banana 或 watermelon：")
if y=="apple":             #是蘋果就判斷顏色
    if x=="red":
        print("紅蘋果")
    elif x=="green":
        print("綠蘋果")
elif y=="banana":
    if x=="red":
        print("紅香蕉")
    elif x=="green":
        print("綠香蕉")
elif y=="watermelon":
    if x=="red":
        print("紅西瓜")
    elif x=="green":
        print("綠西瓜")
else:
    print("以上皆非")
