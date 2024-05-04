# Tip-calculator-using-python

bill_by_the_customer = float(input("Enter the bill amount $"))
tip_percentage = float(input("Enter the percentage of tip you want to give from the bill "))
tip_amount = (tip_percentage/100)*bill_by_the_customer
tip_amount_rounded = round(tip_amount,2)
print(f"Your tip amount will be $ {tip_amount_rounded}")
