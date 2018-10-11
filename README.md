# beginner-project-solutions

# 99 Bottles of Beer Solution
for i in range(99, -1, -1):
    if i < 3 and i > 1:
        print("%s bottles of beer on the wall, %s bottles of beer. Take one down and pass it around, %s bottle of beer on the wall. " % (i, i, (i - 1)))
    elif i  < 2 and i > 0:
      print("%s bottle of beer on the wall, %s bottle of beer. Take one down and pass it around, %s bottles of beer on the wall. " %(i, i, (i-1)))
      break
    else:
        print("%s bottles of beer on the wall, %s bottles of beer. Take one down and pass it around, %s bottles of beer on the wall. " % (i, i, (i - 1)))
