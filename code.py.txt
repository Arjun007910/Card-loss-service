print("Which service would you like?")
print(" 0 ---> Report a problem")
print(" 1 ---> Month wise transaction")
print(" 2 ---> Total cash withdrawn in a month")
N = int(input())
if( N == 1):
    print("Enter the kind of problem")
    print(" 1 ---> Card loss")
    print(" 2 ---> Block the card")
    N2 = int(input())
    if (N2 == 1):
        print("The services that we provide for card loss are as follows :-")
        print("1. Block the card")
        print("2. View transactions after the card was lost")
        N3 = int(input())
        if (N3 == 1):
            Cnum = int(input("Enter your card number --->  "))
            blockcard(Cnum);
            
