# program4
numbers=(10,20,30,40,50,20)
print("original tuple:",numbers)
print("first element:",numbers[0])
print("last element:",numbers[-1])
print("Tuple slice (index 1 to 4):", numbers[1:5])
print("count of 20:",numbers.count(20))
print("Index of 40:", numbers.index(40))
print("Length of tuple:", len(numbers))
print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of tuple elements:", sum(numbers))
new_tuple = numbers + (60, 70, 80)
print("After concatenation:", new_tuple)
repeat_tuple = numbers * 2
print("Repeated Tuple:",new_tuple)

Output:
original tuple: (10, 20, 30, 40, 50, 20)
first element: 10
last element: 20
Tuple slice (index 1 to 4): (20, 30, 40, 50)
count of 20: 2
Index of 40: 3
Length of tuple: 6
Maximum value: 50
Minimum value: 10
Sum of tuple elements: 170
After concatenation: (10, 20, 30, 40, 50, 20, 60, 70, 80)
Repeated Tuple: (10, 20, 30, 40, 50, 20, 60, 70, 80)




