# BASIC-PYTHON <BR> [PALINDROME.PY](https://github.com/user-attachments/files/21890922/PALINDROME.PY)
# wap to input a three digit number and check number is palindrome or not.
num=int(input("Enter three digit number:"))
num1=num
rev=0
while num>0:
         u=num%10
         rev=rev*10+u
         num//=10
if num1==rev:
         print("palindrome number")
else:
         print("not palindrome")



     
