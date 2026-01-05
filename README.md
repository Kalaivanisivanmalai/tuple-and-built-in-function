# tuple-and-built-in-function
numbers = (10, 20, 30, 40, 50, 20)
print("Original Tuple:", numbers)
print("First element:", numbers[0])
print("Last element :", numbers[-1])
print("Tuple slice (index 1 to 4):", numbers[1:5])
print("Count of 20:", numbers.count(20))
print("Index of 40:", numbers.index(40))
print("Length of tuple:", len(numbers))
print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of tuple elements:", sum(numbers))
new_tuple = numbers + (60, 70, 80)
print("After concatenation:", new_tuple)
repeat_tuple = numbers * 2
print("Repeated Tuple:",

