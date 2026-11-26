# Objective: Use structured prompting to encourage reasoning.

    Choose a math or coding problem (e.g., "Calculate the factorial of 5").
# Problem:
 Write a Python function that takes a list of numbers and returns only the even ones.


# Prompt the model: "Let's think step by step before answering."Prompting the AI: "Let's think step by step"

Step 1: Understand the Input
We are starting with a list of numbers, for example: [1, 2, 3, 4, 5, 6].

Step 2: Create a Storage Space
We need an empty list to hold the even numbers we find. Let's call it even_list.

Step 3: Look at Every Number
We need to loop through the list one by one.

Step 4: The Logic Test
For each number, we check if it is even. In coding, we use the "Modulo" operator (). If a number divided by 2 has a remainder of 0 (number%2==0), it is even.

Step 5: Store and Return
If it passes the test, we put it in even_list. Finally, we show the list.
The Final Result (The Code)
Python

def get_even_numbers(numbers):
    even_list = [] # Step 2
    for num in numbers: # Step 3
        if num % 2 == 0: # Step 4
            even_list.append(num) # Step 5
    return even_list

print(get_even_numbers([1, 2, 3, 4, 5, 6, 7, 8])) 
# Output: [2, 4, 6, 8]


# Compare outputs with and without the reasoning instruction.
# Without step by step
   It gives the code blocks.
   It's ease to write if you are an expert.

## With step by step
   It explain the code before before writing it.
   It is good for beginners to learn the logic

