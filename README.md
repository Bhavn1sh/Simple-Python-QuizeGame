# Simple-Python-QuizeGame

print('Welcome to the Quiz Game')
print('Each question is 2 marks')
print('Try to get as many questions correct as possible')

total_question = 5
score = 0

ans = input('1. What are the benefits of using Python language as a tool in the present scenario? ')
if ans.lower() == 'object-oriented language' or ans.lower() == 'high-level language':
    print('Correct')
    score += 2
else:
    print('Incorrect')

ans = input('2. Is Python a compiled language or an interpreted language? ')
if ans.lower() == 'interpreted language' or ans.lower() == 'both':
    print('Correct')
    score +=2
else:
    print('Incorrect')

ans = input('3. What is the primary purpose of Python’s built-in data structures? ')
if ans.lower() == 'to store and organize data' or ans.lower() == 'organizing data':
    print('Correct')
    score +=2
else:
    print('Incorrect')

ans = input('4. What is the function of the “self” keyword in Python classes? ')
if ans.lower() == 'refers to the instance of the object' or ans.lower() == 'instance reference':
    print('Correct')
    score +=2
else:
    print('Incorrect')

ans = input('5. How do you create a virtual environment in Python? ')
if ans.lower() == 'python -m venv venv' or ans.lower() == 'python -m venv <env-name>':
    print('Correct')
    score +=2
else:
    print('Incorrect')

print('You got ' + str(score) + ' out of ' + str(total_question*2))
print('Thank you for playing the Quiz Game')   
