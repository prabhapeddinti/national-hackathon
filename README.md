# national-hackathon

# Research Data Analysis Model

data = [10, 20, 30, 40, 50]

total = 0

for value in data:
    total = total + value

average = total / len(data)

highest = data[0]
lowest = data[0]

for value in data:
    if value > highest:
        highest = value
    if value < lowest:
        lowest = value

print("Research Data:", data)
print("Total:", total)
print("Average:", average)
print("Highest Value:", highest)
print("Lowest Value:", lowest)
