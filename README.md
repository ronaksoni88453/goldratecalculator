
Name=str(input("enter your name:"))
M_no=int(input("enter your number:"))
Address=str(input("enter your address:"))

X=int(input("Enter today's 24 carat gold price:Rs."))
n=input("1 for 22 carat gold price, 2 for 18 carat gold price,3 for 14 carat gold price, 4 for exit :")







if(n=="1"):
        print((X*23)//24)
elif(n=="2"):
        print((X*19)//24)
elif(n=="3"):
        print((X*15)//24)
elif(n=="4"):
        print("exit and thank you so much !!")
