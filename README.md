# python-atm-system
Python-based ATM automation system for deposits, withdrawals, balance checks, and user authentication
# Bank account----
pin_number = "1239"
account_balance = 1000
pin_num = input("Enter your four digits pin number:")
if pin_num == pin_number:
    print("1\tCheck Balance")
    print("2\tDeposit Money")
    print("3\tWithdraw Money")
    print("4\tExit")
elif pin_num != pin_number:
    pin_num = input("Enter your four digits pin number:")
    if pin_num == pin_number:
      print("1\tCheck Balance")
      print("2\tDeposit Money")
      print("3\tWithdraw Money")
      print("4\tExit")
      if pin_num != pin_number:
       pin_num = input("Enter your four digits pin number:")
      elif pin_num == pin_number:
       print("1\tCheck Balance")
       print("2\tDeposit Money")
       print("3\tWithdraw Money")
       print("4\tExit")

else:
    print("Contact with customer service representative\n you have exceed your pin number limits")
