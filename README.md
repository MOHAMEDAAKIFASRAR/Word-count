# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program

### Step 2: 
Get the text from the user.
 
### Step 3:
Write the function to count the words.

### Step 4: 
Type the program to get the output.

### Step 5:
Print the number of words.

### Step 6: 
End the program.

## PROGRAM:
~~~
## Developed By:AAKIF ASRAR S
## Reference Number:23003613
def count_words(text):
    words = text.split()
    return len(words)

if__name__ == "__main__":
    user_input = input("Enter a text: ")
    word_count = count_words(user_input)
    print(f"Word count: {word_count}")
~~~

### OUTPUT:
![prem](https://github.com/MOHAMEDAAKIFASRAR/Word-count/assets/148514683/31015f36-6bcd-4b18-b4c1-f217b82c890c)




## RESULT:
Thus the program is written to find the word count from a text.
