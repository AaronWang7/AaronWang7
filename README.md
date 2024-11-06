while True:
 list = ["Tom","Aaron","Aron","Peter","Someone 1","Someone2","Someone3","Someone4",no]
 hi = input("What's your name?:")
 
 if hi == “Tom” :
	  Print (“You are admin”)
Elif hi in list:
        print(f"hello {hi} you are in the lists")
 else:
    hiii = input("You are not on the list would you like to be on the list?(Y/N):")
    if hiii == ("Y"):
            no = input("Whats your name?:")
            list.insert(no)
            print(f"{no} You are now on the list")
    else:
        print("Ok, have a nice day!")
