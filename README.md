# Python variables
## time: 45mins

### task
- What is a variable
- Dynamically typed language
- user interaction

### Testing the pycharm env
```
print("hello world")
```
- If, the outcome is Hello world that means everything is working fine.
- To add comments to python code use 
 ``` # ```
  
### Use .gitignore to ignore files/ folders that we don't want to send to github.
Create a file called:
```
.gitignore
```
 
### What is a variable?
- Variables work as a placeholder
- Variable types: string, float, integer(int), boolean(True or False).
```
name = "Bob"  # string
age = 16  # integer
hourly_wage = 8.5  # float

print(name)
print(age)
print(hourly_wage)
```
- To get user data we use input()
```
first_name = input("Please enter your name ")
age = input("Pleas enter your age")
print("Hello, ")
print(first_name)
```
- To check the type of data use type()
```
print(type(age)) # This will return <class int>
```
- Overwriting a variable

You assign the same variable to a different item using the below method.
```
first_name = "belle"
print(first_name)
```