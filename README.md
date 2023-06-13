name = input('type your name')
age = int(input("enter the age"))
income=float(input('enter the income'))
percent_R = float(input('enter the raise'))

Subtotal = income * percent_R
NewIncome = income + Subtotal

print("confirmation: " + name + "\nage " +str(age) + 
      "\nincome is " + str(income))

print ("Your raise is " + str(percent_R) + "%")
print("your actual raise based on the present income is $" +str(Subtotal))
print("your new salary is $" +str(NewIncome))

print("your new salary is ${:,.2f}".format(income))









