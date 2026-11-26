# Objective: Understand how parameters affect output diversity.

    Use the same prompt with temperature = 0.2 and then with temperature = 0.9.

# Tell me about the president of nigeria

## Model output for 0.2
    Bola Ahmed Tinubu is the current President of Nigeria. 
    He assumed office on May 29, 2023, as the 16th president of the country.
    A member of the All Progressives Congress (APC), he previously served as the Governor of Lagos State from 1999 to 2007.
    His administration is currently focused on the 'Renewed Hope' agenda, which prioritizes economic structural reforms,
    national security, and infrastructure development. As of February 2026, 
    he continues to lead the nation from the Aso Rock Presidential Villa in Abuja

# Model output for 0.9

    Navigating the complex currents of the 'Giant of Africa,' President Bola Ahmed Tinubu stands as a veteran architect of Nigerian politics. Known as the 'Jagaban' to his supporters, his journey from the bustling streets of Lagos to the silent halls of Aso Rock is a saga of immense influence and strategic patience. Today, in 2026, his presidency is a high-stakes balancing act: wrestling with ambitious currency shifts, modernizing the ancient rhythms of Nigerian agriculture, and weaving a new diplomatic tapestry across West Africa. He is a figure of intense debate, representing a bold, 'it’s my turn' chapter in the nation's democratic history.

#  Record how the style, randomness, and focus of responses change.

# The output for the prompt at temp. 0.2 and 0.9 respectively
    The former is very factual and direct and it sticks to the most likely "safe" words, while the latter is more descriptive and colorful. It adds more creative phrases like "weaving a diplomatic tapestry" or "ancient rhythms.

# Repeat with different top-p values (e.g., 0.5 vs 1).

# Model output for top-p values 0.5

    President Bola Ahmed Tinubu is the current leader of Nigeria. He was inaugurated on May 29, 2023. Before becoming president, he served as the Governor of Lagos State. His current administration is focused on economic reforms and improving national security. He is a member of the All Progressives Congress party and is working to stabilize the Nigerian economy through his 'Renewed Hope' agenda.

# Model output for top-p values 1

Bola Ahmed Tinubu, often referred to as the 'Jagaban' of Borgu, currently steers the Nigerian state through a transformative and often turbulent era. Since his 2023 inauguration, his tenure has been marked by audacious fiscal pivots, such as the removal of the longstanding fuel subsidy. He remains a titan of West African geopolitics, balancing the aspirations of a youthful population with the grit required to overhaul institutional bottlenecks in Abuja.

# Record how the style, randomness, and focus of responses change.

# The output of the prompt for the top p-values 0.5 vs 1 respectively

    The former is Very standard and "safe" and more focused, while the latter is more nuanced and sophisticated.
