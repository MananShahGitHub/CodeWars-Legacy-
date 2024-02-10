def count_smileys(arr):
    total = 0
    eyes = ':;'
    nose = '-~'
    mouth = ')D'
    for char in arr:

        if len(char) == 3:
            if char[0] in eyes and char[1] in nose and char[2] in mouth:
                total += 1

        elif len(char) == 2:
            if char[0] in eyes and char[1] in mouth:
                total += 1
    return total
