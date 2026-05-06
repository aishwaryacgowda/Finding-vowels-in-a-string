# Finding-vowels-in-a-string
text=input("Enter a string:")
vowels="aeiouAEIOU"
count=0
for char in text:
    if char in vowels:
       count=count+1
print("The number of vowels:",count)
