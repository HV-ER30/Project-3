# Project-3
def most_frequent(string):
    d = dict()
    for key in string:
        if key not in d:
            d[key] = 1
        else:
            d[key] += 1
    return d

str=input("Enter the string: ")
print(most_frequent(str))
