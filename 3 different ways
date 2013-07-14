## Recursion, most elegant but most expensive ##

def is_palindrome(s):
    if s == "":
        return True
    elif s[0] != s[-1]:
        return False
    else:
        return is_palindrome(s[1:-1])

## Iter tools ##

def iter_palindrome(s):
    for i in range(0,len(s)/2):
        if s[i] != s[-(i+1)]:
            return False
    return True

## Pythonic ##

def is_palindrome(s):
    if s[::1] == s[::-1]:
        return True
    else:
        return False
