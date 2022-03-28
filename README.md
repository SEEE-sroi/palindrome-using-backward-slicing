# palindrome-using-backward-slicing
n = len(str1)
c = []
for i in  range (n-1, -1, -1):
    c.append(str1[i])
rev = "".join(c)
if str1 == rev:
    
