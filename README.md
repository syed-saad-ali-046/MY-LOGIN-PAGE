# MY-LOGIN-PAGE
A SIMPLE BEGINNER LEVEL LOGIN PAGE PROGRAM OF PYTHON,THAT ALLOW USER TWO MADE ONLY 2 ATTEMPTS TWO SIGN IN AND IF USER FAIL TO SIGN IN THAT TIME,ALL ATTEMPTS FINSHED MESSAGE POP UP! ...
attempts_made=0
while attempts_made<2:
    username=input('PLEASE ENTER USER NAME:')
    password=input('PLEASE ENTER PASSSWORD:')
    if username=="SAAD ALI" and password=="TWIN TOWER":
        print('************ Home \npage*********\nMenu\n********* Setting')
        break
    else:
        attempts_made+=1
        print('invalid data!')
        if attempts_made==2:
            print('too many attempts') 
