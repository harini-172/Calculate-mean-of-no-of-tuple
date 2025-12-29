# Calculate-mean-of-no-of-tuple
tpl=eval(input("Enter Tuple :"))
length =len(tpl)
mean=sum=0
for i in range(0,length):
    sum+=tpl[i]
mean =sum/length
print("Given tuple is :",tpl)
print("the mean of the given tuple is :",mean)

output

Enter Tuple :(1,2,56,6)
Given tuple is : (1, 2, 56, 6)
the mean of the given tuple is : 16.25
