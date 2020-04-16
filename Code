import pandas as pd
d=pd.read_csv("Employee.csv")
print(d.iloc[0:10,:]) # To display the 1st 10 records
print(d.iloc[6:13,3:9]) # To display the columns 4 to 0 for rows 7 to 13
deq=list(d.iloc[:,15])
for x in range(0,100):
  if deq[x]=="Q1" or deq[x]=="Q4":
    print(d.iloc[x,:]) # To display the info of employees in Q1 and Q4
dow=list(d.iloc[:,22])
reg=list(d.iloc[:,34])
y=[x for x in range(0,100) if reg[x]=="South" and dow[x]=="Monday"]
print("The number of people who joined from the southern region on Monday are",len(y)) #No of people from the Southern region who joined on a Monday
exp=list(d.iloc[:,24])
for x in range(0,100):
  if exp[x]>13:
    print(d.iloc[x,:]) # Info of employees who have >13 years of work experience
z=[x for x in range(0,100) if d.iloc[x,5]=="F" and int(d.iloc[x,26].rstrip("%"))>20]
print("The number of female employees who got a hike more than 20% are:",len(z)) #No of female employees with a >20% hike 
