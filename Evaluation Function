#Evaluation Function :

def Temperature_modeling(a,b,c,time):
  temp  = a*time**2+b*time+c
  return temp
# Version 1: Hardcoding the variables:

a=1
b=2
c=3
time = 4
temp = Temperature_modeling(a,b,c,time)
print(f"the Temperature at time {time} is {temp}")
# Version 2 : Keyboard Input:
temp = Temperature_modeling(float(input('Enter a:')),float(input('Enter b:')),float(input('Enter c:')),int(input('Enter Time:')))
print(f"the Temperature at time {time} is {temp}")
# Version 3: Single Input from the text file:
with open('whether_single.txt','r') as files:
  file = files.readline();
  a,b,c,time = file.split()
  a = float(a)
  b= float(b)
  c = float(c)
  time = int(time)
  temp = Temperature_modeling(a,b,c,time)
  print(f'The Temperature at time {time} is {temp}')
  # Version 4: Multiple Input from the text file
with open('whether_multiple.txt','r') as files:
  for file in files:
    a,b,c,time = file.strip().split()
    a = float(a)
    b=float(b)
    c = float(c)
    time = int(time)

    temp = Temperature_modeling(a,b,c,time)
    print(f'The Temperature at time {time} is {temp}')
