numbers = [2, 5, 13, 7, 6, 4]
size = 6
total_sum = 0
i = 0

while i < size:
    total_sum = total_sum + numbers[i]
    i = i + 1

average = total_sum / size
print(average)
