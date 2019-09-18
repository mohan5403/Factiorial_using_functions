# Factiorial_using_functions
'''Write a program which can compute the factorial of a given numbers. The results should be printed in a comma-separated sequence on a single line. Suppose the following input is supplied to the program: 8 Then, the output should be: 40320'''
def fact(n) :
    if n == 1 :
        print(n,end=' = ')
        return 1
    else :
        print(n,end='*')
        return n*fact(n-1)
s1 = int(input('Enter value'))
n1 = fact(s1)
print(n1)
