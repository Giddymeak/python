#programm to login
username=str(input("enter username: "))#user enter username
pwd=int(input("enter password:"))#user enter password
logins=["BSCIT-05-0134/2020",4971]
if username in logins and pwd in logins:
  print ("login succesesfull")
else:
  print("incorect username or password")
