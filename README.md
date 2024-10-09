my_list = [42, 69, 322, 13, 0, 99, -5, 9, 8, 7, -6, 5]
a = 0
for a in my_list:
    if a > 0:
        print(a)
    else:
        if a < 0: break
        a += 1
