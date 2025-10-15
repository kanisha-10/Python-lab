pos_sum = 0
pos_count = 0
neg_sum = 0
neg_count = 0

print("Enter numbers (enter -1 to stop):")

while True:
    num = int(input())
    if num == -1:
        break
    if num > 0:
        pos_sum += num
        pos_count += 1
    elif num < 0:
        neg_sum += num
        neg_count += 1

avg_pos = pos_sum // pos_count if pos_count else 0
avg_neg = neg_sum // neg_count if neg_count else 0

print("avg negative number is", avg_neg, ", avg positive number is", avg_pos)
