# CIS567-integrated-lab-1
integer
first = int(input())
second = int(input())

if second < first:
    print("Second integer can't be less than the first.")
else:
    for num in range(first, second + 1, 5):
        print(num, end=' ')
    print()  # Ends the output with a newline
