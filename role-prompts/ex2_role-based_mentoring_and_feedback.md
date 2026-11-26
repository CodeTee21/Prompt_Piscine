# Objective: Use role-based prompts for personalized feedback.

    Ask the model to act as a coding mentor.

# Provide a simple piece of code (e.g., a Python function with a bug).
def area(width, height)
    result = width * height
    print("The area is " + result)

area(10, 5)

    
# Prompt the model: "Act as a mentor reviewing this code. Provide corrections and explain improvementS.
1. The "Starting Gate" (Colons)
In Python, whenever you start a function with def, you need to end that line with a colon :. Think of it as a starting gate that tells the computer, "The instructions are starting now!"

2. Mixing Data Types
On your third line, you are trying to use + to join text (a String) with your answer (an Integer). Python gets confused here because it doesn't know if it should "math" them or "write" them.

3. Pro-Tip: The "f-string"
Instead of using +, modern Python uses something called f-strings. You put an f before the quotes and put your variable inside {}. It makes your code much cleaner and avoids errors!
The Corrected Code
Python

I added the colon and used a 'formatted string' for the output
def area(width, height):
    result = width * height
    print(f"The area is {result}")

area(10, 5)


# Review the response and check if the role influences feedback style.

The role successfully influenced the feedback style. It transformed a simple bug fix into an educational lesson tailored to a student's needs.
