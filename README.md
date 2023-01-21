# online-book-shop
#here is my code , am a beginner  to python and learning . i write this code to make a book shop by some simple syntax, sorry if there ios mistake . please support me .
# a simple online book shop
 #made by tinku with basic code, im just a beginner to python ;
 #hope ypu will enjoy it
 #no help from online; logic also from me


while (True) :
    welcomeMsg = '''\n ====== Welcome to tinku's book shop ======
            Please choose an option:
            1. List all the books
            2. buy a book
            3. read demo of book online
            4. Exit the shop
            ''' 
    print ("\n \n hi sir " )

    print (welcomeMsg)
    sel = int (input("select an option from above table :::::"))

    if sel == 1 :
        print ("""\n\n the books are avilable on my shops ======\n
    1 : NIRIBILI
    2 : JEC
    3 : MURU ETA XOPUN ASE
    4 : MOROMOR DEUTA
    5 : PHYSICS 
    and all books are avilable
    ''''
if you want to buy or read your favourite books then, select another option
    """)

    elif sel == 2 :
        print (""" the books are.........
        
        1 : NIRIBILI
        2 : JEC
        3 : MURU ETA XOPUN ASE
        4 : MOROMOR DEUTA
        5 : PHYSICS
        and all books avilable...
        """)
        book = input("\nNAME OF the book to buy ::::")
        n= input ("""\nYOUR NAME :::""")
        input ("\nyour address ::")
        input ("\nyour mobile number::\n\n")
        msg = ("*****\n !!BOOKS CAN ENABLE YOU TO FLY,THANK YOU FOR  BUY THIS BOOK ")
        print ("hii!! " + n )
        print (  msg + book ,"**your book will be delivered on your address in 2 days")

    elif sel == 3 :
        online = input("which book you want to read a demo ???")
        input(" \n *enter your email address to send the file :::")
        print ("\n ~~~THANKS FOR REQUESTING THe DEMO OF THE BOOK .file will be sent to your email AD. HOPE YOU WILL LIKE THE BOOK~~~ \n")

    elif sel == 4 :
        print("!!THANK YOU FOR VISITING US. SEE YOU AGAIN **!!")
        exit()
    else :
        print (" **please choose a valid option**")

        # thnx
        #follow me on insta @tinku.785
