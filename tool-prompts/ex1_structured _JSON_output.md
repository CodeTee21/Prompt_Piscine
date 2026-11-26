# Objective: Create prompts that produce structured machine-readable output.

## Write a prompt that asks for unstructured information (e.g., “List three cities with their populations.”).

# The prompt:
   List three cities with their populations.

# Model Output:

   1. Tokyo – about 37 million people (metropolitan area)

   2. Lagos – about 15 million people

   3. New York City – about 8.5 million people
    

# Rewrite the prompt to enforce structured JSON output:

## Example: “Return the following in JSON format: [{city: string, population: number}].”
```JSON
     [
      {"city": "Tokyo", "population": 37000000},
      {"city": "Lagos", "population": 15000000},
      {"city": "New York City", "population": 8500000}
     ]
```    

# Test with multiple inputs and verify the JSON stays valid.
# Output
```JSON
[
  {"city": "London", "population": 9000000},
  {"city": "Paris", "population": 11000000},
  {"city": "Istanbul", "population": 16000000},
  {"city": "Jakarta", "population": 33000000},
  {"city": "Seoul", "population": 25000000},
  {"city": "Bangkok", "population": 11000000},
  {"city": "Los Angeles", "population": 13000000},
  {"city": "Manila", "population": 14000000},
  {"city": "Buenos Aires", "population": 15000000},
  {"city": "Dhaka", "population": 23000000},
  {"city": "Karachi", "population": 17000000},
  {"city": "Tehran", "population": 9000000},
  {"city": "Madrid", "population": 7000000},
  {"city": "Toronto", "population": 6000000},
  {"city": "Nairobi", "population": 5000000}
] 
```

# Observation
  Yes, the JSON is valid because the strings are in quotes and the numbers are written correctly without quotes.
