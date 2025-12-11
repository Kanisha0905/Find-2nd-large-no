# Find-2nd-large-no
a = []
n = int(input("Enter number of elements: "))

for i in range(n):
    b = int(input("Enter element: "))
    a.append(b)

a.sort()

if n < 2:
    print("Second largest element does not exist.")
else:
    print("Second largest element is:", a[-2])

OUTPUT
Enter number of elements: 5
Enter element: 1
Enter element: 2
Enter element: 3
Enter element: 5
Enter element: 6
Second largest element is: 5

