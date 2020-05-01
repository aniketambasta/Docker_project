import os
print("hello and welcome to my world")
print("enter your name:")
name = input()         
print("""welcome  {}   choose an option below""" .format(name))       
while True:
    print("""press 1 for see the live date and time
    press 2 to see the desired year of calendar
    press 3 to add anew user in your os
    press 4 to add any two no.
    press 5 to subtract any two no.
    press 6 to multiply any two no.
    press 7 to divide any two no.
    press 8 to check whether the no. is armstrong no. or not
    press 9 to exit""")
    inp = input()
    if int(inp) ==1:
        print ("hey")
        x=os.system('date')
        print (x)

    elif int(inp) == 2:
        print ("enter the month and year to see the calendar")
        month = input("month")
        year = input("year")
        cal = "cal {0}  {1}".format(month,year)
        os.system(cal)

    elif int(inp) == 3:
        print ("enter the name you want to create a new user")
        user_name = input("user name")
        new_user = "useradd {}".format(user_name)
        os.system(new_user)

    elif int(inp) == 4:
        print("enter the two numbers to be added")
        no_1 = input("enter the no. 1-:")
        no_2 = input("enter the no. 2-:")
        sum = float(no_1) + float(no_2)
        print("addition of{0} & {1} is {2}".format(no_1,no_2,sum))

    elif int(inp) ==5:
        print("enter the numbers to subtract-:")
        s1 = input("enter no.1-:")
        s2 = input("enter no.2-:")
        subtract = float(s1) - float(s2)
        print("subtraction of {0} & {1} is {2}-:".format(s1,s2,subtract))

    elif int(inp) == 6:
        print("enter the numbers to multiply-:")
        m1 = input("enter the no.1-:")
        m2 = input("enter the no.2-:")
        product = float(m1) * float(m2)
        print("product of {0} & {1} is {2}-:".format(m1,m2,product))

    elif int(inp) == 7:
        print("enter the numbers to divide-:")
        d1 = input("enter the no.1-:")
        d2 = input("enter the no.2-:")
        divide = float(d1) / float(d2)
        print("{0} / {1} is {2}-:".format(d1,d2,divide))

    elif int(inp) == 8:
        print("enter the no. to check")
        num = int(input("no.="))
        su = 0
        temp = num
        while temp > 0:
            digit = temp % 10
            su +=  digit ** 3
            temp //= 10

        if num==su:
            print(num,"is an Armstrong number")
        else:
            print(num,"is not an Armstrong number")



    else :
        break
