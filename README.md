# Python_Coding
# Every day excercise
# Date: 26-08-2023 Saturday
year = int(input("which year do you want to check?\n"))

if year % 4 == 0:
  if year % 100 == 0:
    if year % 400 == 0:
      print("Leap year")
    else:
      print("Not a Leap year")
  else:
    print("Leap year")
else:
  print("Not a leap year ")
