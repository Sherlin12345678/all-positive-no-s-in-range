# all-positive-no-s-in-range
python program to print all positive no's in range
start = int(input("Enter the start of range: "))
end = int(input("Enter the end of range: "))
 
# iterating each number in list
for num in range(start, end + 1):
     
    # checking condition
    if num >= 0:
        print(num, end = " ")
