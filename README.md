# test
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

sum = numbers[-1] # Initialize the sum with the last number in the list

for i in range(0, len(numbers)-1, 2):
    sum += numbers[i]
    
print(sum)
