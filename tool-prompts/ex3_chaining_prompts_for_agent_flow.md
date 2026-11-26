# Objective: Combine multiple prompts to simulate a tool-using agent.

  Step 1 prompt: Ask for a user’s query (e.g., “What’s the temperature in Paris?”).
# Step1
# The prompt:
  What is the temperature in paris?
   
# Step 2 
# The prompt: 
## Simulate a call to the weather API.

```JSON
{
  "city": "Paris",
  "temperature": 22,
  "unit": "Celsius",
  "condition": "Partly Cloudy"
}

```

# Step 3 
# prompt: 
## Format the final answer back to the user.
   In Paris, it is currently **22°C** with **partly cloudy condition**.

# Document the chained process and outputs.
  Step 1: It receives the user’s question only.
  Step 2: It gives the answer in JSON format.
  Step 3: It changes the JSON into a clear sentence for the user.



