# Objective: Practice designing prompts that mimic function calls.

## Create a prompt: “Simulate a weather API response for Paris today." 

```JSON
{
      "location": "Paris",
      "temperature_celsius": 18,
      "condition": "Cloudy"
}

```

# The prompt:

“Simulate a weather API response for paris today."

## Model output:
```JSON
{
  "location": "Paris",
  "temperature_celsius": 9,
  "condition": "Light rain"
}
```

# The prompt:

“Simulate a weather API response for kwara today."
```JSON
{
  "location": "Kwara",
  "temperature_celsius": 35,
  "condition": "Partly sunny"
}
```

# The prompt:

 “Simulate a weather API response for kogi today."

```JSON
{
  "location": "Kogi",
  "temperature_celsius": 37,
  "condition": "Mostly cloudy"
}
```

# Test the model with different cities and compare outputs.
The JSON outputs for both cities uses the exact same format, but the input values are different based on the specific location.
