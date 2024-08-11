# python-program
#running total program
TOTAL = 0
t1 = 0
t2 = 0
r1 = 1
r2 = 5

while(r1 <= r2):
    print("Enter Sales of Month-",r1," : ", end='')
    sales = int(input())
    TOTAL += sales
    if(r1 <= 2):
        t1 += sales
    else:
        t2 += sales
    
    r1 += 1

avg = TOTAL/r2
print("Total Sales for 5 Months : ", TOTAL)
print("Average Sales for 5 Months : ", avg)
avg1 = t1 / 2
avg2 = t2 / 3
print("\nTotal Sales for First 2 Months : ", t1)
print("Average Sales for First 2 Months : ", avg1)

print("\nTotal Sales for Last 3 Months : ", t2)
print("Average Sales for last 3 Months : ", avg2)
