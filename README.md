# function_upper_lower_count
def count_upper_lower(string):
    upper_count = 0
    lower_count = 0
    for char in string:
        if char.isupper():
            upper_count += 1
        elif char.islower():
            lower_count += 1
    return (upper_count, lower_count)
my_string = "The quick Brow Fox"
result = count_upper_lower(my_string)
print("No of Uppercase characters:", result[0])
print("No of lowercase characters:", result[1]          # output : No of Uppercase characters : 3
                                                                    No of Lowercase characters : 12
