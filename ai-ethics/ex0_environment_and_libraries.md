# Write down your honest answers:

    How have you used AI for coding so far?
    I used AI to break questions down and confirm where my mistakes is in my answer.

    Do you ask AI for solutions before trying yourself?
    No, i tried doing it myself before asking.

    Can you explain code you've submitted without AI's help?
    Yes

    What would happen if AI was suddenly unavailable during an exam or interview?
    I will try my best to answer it.
# Identify your current pattern: Which learner are you now? Learner A: "AI is my answer generator"

    Asks: "Write a function that does X"

    Copies code without reading carefully

    Moves on once it works

    Cannot explain how the code works

# Learner B: "AI is my learning amplifier"

    Attempts the problem first

    Asks: "Why does this approach work? What are the trade-offs?"

    Tests understanding by explaining concepts

    Uses AI to explore deeper, not to avoid thinking

    Learner B

    Write a brief paragraph: Where are you now, and where do you want to be?
    I'm better than yesterday, and i want to become a learner that can write code very well and understand what i'm doingPart B: The Wrong Way vs. The Right Way

# Challenge: Implement a simple function to check if a string is a palindrome.

Track A — The Wrong Way (observe but DO NOT do this):

    Immediately ask AI for the function

    Copy the code

    Test it, submit it, move on

Why this fails: You learn nothing, can't handle variations, can't explain your code, and train yourself to be dependent.
# Track B — The Right Way (DO THIS): Step 1: Attempt independently

    Write pseudocode for a palindrome check
   I will define the word
   I will reverse the word
   if they are the same, it's a palindrome
   if they are not the same, it's not a palindrome 
    Implement your solution in Python

      def is_palindrome(word):
       reverse_word = word[::-1]
      if word == reverse_word:
        return True
      else:
         return False   

 Test with examples: racecar, hello, A man a plan a canal Panama

    Debug any issues yourself
   I forgot to add a colon (:) after the if statement, i have now corrected it.
    Add comments explaining your logic
    First, i defined the function, Then I reversed the word using slicing. After that, i reversed word. if it's true it should return True and if it's false it should returns False. Finally, I tested the function with an example word.

Step 3: Reflection

    What did you learn by struggling first?
    I learnt that i'm improving after struggling first

    How is your understanding different than if you'd just asked for the solution?
    If i only asked for solution i won't know any mistake the code is having and i willn't understand the code

    Can you now implement similar functions (reverse a string, find duplicates) without AI?
    Yes, i can reverse a string and find duplicate

    What mental model did you build?
    I built a new model of how strings can be reversed using slices and for a function to print True or False

# Part C: Testing Your Understanding

Without using AI, complete these variations:

    Ignore spaces and punctuation

    Make it case-insensitive

    Return the position where the string stops being a palindrome (if not a palindrome)

def is_palindrome(word):
    word = ''.join(char.lower() for char in word if char.isalnum())
    return word == word[::-1]

word = "bayo"
if is_palindrome(word):
    print(f"'{word}' is a palindrome")
else:
    print(f"'{word}' is not a palindrome")


Then use AI strategically:

"I modified my palindrome function to handle these cases: [show your modifications] Did I miss any edge cases? How could I make this more efficient?"
I learned to check palindromes by cleaning the word, ignoring case and punctuation, and finding the first mismatch without relying on AI.
# Part D: The Fairness Contract

Create ex00_ai_ethics_coder.md with a personal code of ethics for AI use in learning:

    I will use AI when:

    After I've attempted a problem for at least 20 minutes

    To understand why my solution works/doesn't

    To explore alternatives after I have a working solution

    [To under a question if it's hard in understanding]

    I will NOT use AI when:

    I haven't tried the problem myself

    I'm taking an assessment or test

    I need to build fundamentals

    [When i need to digest it very well]

    I know I'm using AI fairly when:

    I can explain my code without looking at AI's response

    I could solve similar problems without AI

    I feel more confident in my abilities

    [I'm able to answer really well]

# Sign and date this contract.
Ajibaye fathiat [02,12,2026]
Part E: Real-World Scenario Analysis

    Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer?
    I prefer to understand the question cashing system design and answer it base on my understanding, if i always reply on AI I willn't be able to attempt a question on my own.


    Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?
    Yes, i can


    New tech with little documentation: If you never learned to read docs and experiment, what happens?
    I will make use of my head to think and document it down, so it will be useful for me another time and i can also make use of google or articles that speaks about the subject matter.

Write a paragraph: How does using AI fairly now prepare you for these scenarios?
Firstly, i have to try attempting questions after that i can now prompt AI if the code isn't running or i want AI to break the question to me and guideliness on how to solve it. This fair use of AI prepares me mentally and helps me to think deeply about a problem even when AI is not available.

Part F: Building Irreplaceable Skills

Rate yourself 1–5 and write an improvement plan for your lowest area:

    Problem decomposition
    2/5	Always attempt

    Systems thinking
    3/5  15 munites self thinking

    Critical evaluation
    2/5  Been able to know when a code is true

    Debugging mindset
    2/5 Know what’s wrong and how to fix it

    Conceptual understanding (the "why")
    2/5 I will understand the code line by line

# Action plan: 3 specific actions this week to improve it without outsourcing thinking to AI.
I want to improve in solving code my self
Knowing another ways of solving code
Been able to know what's wrong with my code

 





 
