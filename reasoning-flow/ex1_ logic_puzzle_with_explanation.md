## Objective:
 Guide the model to solve a problem with explicit reasoning.

    Write a logic puzzle (e.g., "Alice is older than Bob, Bob is older than Carol. Who is the youngest?").
## Prompt:
    Alice is older than Bob, Bob is older than Carol. Who is the youngest?
## model Output:
    Alice is older than Bob

    Bob is older than Carol

    So the age order is:

    Alice → Bob → Carol

    Therefore, Carol is the youngest.



## prompt:
Prompt the model: "Explain your reasoning before giving the final answer."

## Model Output:

    We compare ages step by step:

    * Alice is older than Bob →   Bob is younger than Alice
    
    *  Bob is older than Carol →   Carol is younger than Bob

    So Carol is younger than both Bob and Alice.

    Final answer: Carol is the youngest.

## Prompt:
Verify that the model provides step-by-step reasoning followed by the correct answer.

## Model Output:
Yes, it explain it step by step before giving the correct answer.
