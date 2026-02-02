numbers = [3,8,1,7,2,9,5,4]

big = numbers[0]
position = 0
for i in range(len(numbers)):
if (numbers[i]&gt;big):
big = numbers[i]
position = i
print(&quot;The largest element is &quot;,big,&quot; which is found at position &quot;,position)
output
The largest element is 9 which is found at position 5
