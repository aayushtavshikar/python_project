# problem statement #
print(" **********   Welcome to XYZ car dealership **********   ")
print(" The cars available in the store are : ")
print("SWIFT , CRETA , SELTOS , MG HECTOR")
enter_car = (input("Please enter your choice of CAR : "))
if enter_car == 'swift':
    price_swift = 500000
    price1 = str(price_swift)
    print("Price for swift is " + price1 + " lakh rupees.")
    print(" SCHEMES AVAILABLE FOR SWIFT ARE AS FOLLOWS : ")
    print(" All cash / emi  ? ")
    type_payment = input("please enter your choice of finance : ")
    if type_payment == "all cash":
        allcash_payment = input("All cash options are cheque/debit or credit card : ")
        if allcash_payment == 'cheque':
            print("XYZ")
        elif allcash_payment == 'debit/credit_card':
            print("abc")
    elif type_payment == "emi":
        print(" Welcome to EMI ")
        print(" ### SCHEMES AVAILABLE FOR EMI ### ")
        print(" 1 YEAR , 5 YEARS ")
        emi_period = input(" Enter the period for emi: ")
        if emi_period == "1 year":
            period = 1
            interest = (price_swift * period * 7)/100
            amount_1 = str(interest)
            print("The interest for 1 year will be " + amount_1 + " rupees")
            principle_amount1 = price_swift + interest
            total_amount = str(principle_amount1)
            print(" Hence total amount will be " + total_amount + " Rupees.")
        elif emi_period == "5 year":
            period = 5
            interest = (price_swift * period * 3) / 100
            amount_2 = str(interest)
            print("The interest for 1 year will be " + amount_2 + " rupees")
            principle_amount2 = price_swift + interest
            total_amount = str(principle_amount2)
            print(" Hence total amount will be " + total_amount + " Rupees.")
            exit()
elif enter_car == 'creta':
    price_creta = 2500000
    price2 = str(price_creta)
    print("Price for creta is " + price2 + " lakh rupees.")
    print(" SCHEMES AVAILABLE FOR CRETA ARE AS FOLLOWS : ")
    print(" All cash / emi  ? ")
    type_payment = input("please enter your choice of finance : ")
    if type_payment == "all cash":
        allcash_payment = input("All cash options are cheque/debit or credit card : ")
        if allcash_payment == 'cheque':
            print("XYZ")
        elif allcash_payment == 'debit/credit_card':
            print("abc")
    elif type_payment == "emi":
        print(" Welcome to EMI ")
        print(" ### SCHEMES AVAILABLE FOR EMI ### ")
        print(" 1 YEAR , 5 YEARS ")
        emi_period = input(" Enter the period for emi: ")
        if emi_period == "1 year":
            period = 1
            interest = (price_creta * period * 7)/100
            amount_2 = str(interest)
            print("The interest for 1 year will be " + amount_2 + " rupees")
            principle_amount2 = price_creta + interest
            total_amount = str(principle_amount2)
            print(" Hence total amount will be " + total_amount + " Rupees.")
        elif emi_period == "5 year":
            period = 5
            interest = (price_creta * period * 3)/100
            amount_2 = str(interest)
            print("The interest for 1 year will be " + amount_2 + " rupees")
            principle_amount2 = price_creta + interest
            total_amount = str(principle_amount2)
            print(" Hence total amount will be " + total_amount + " Rupees.")
