Exercise 4: AI as Learning Amplifier

Goal: Practice the "right way" to use AI for learning on a technical topic (wireless routing protocols) — attempt first, then use AI to probe and deepen.
Phase 1: Build Foundation (you first)

Active reading, self-explanation (close the doc), simple scenario design (5–10 devices) with your justification.
There are[6 mobile phone] moving around i picked a protocol [AODV] because it creates routes only when needed and it's efficient for small mobile network.
Phase 2: Strategic AI Use

Test your understanding, explore edge prompt-basicscases with targeted questions, then validate.

After selecting AODV, I used AI to test situations like node movement, heavy traffic, and larger networks. I learned AODV works well for a small mobile group because routes are created only when needed, but frequent movement and high traffic cause delays and extra control messages. For bigger networks, a protocol like OLSR would be better.   
Phase 3: Real Application

Design a small smart-city network (1,000 IoT sensors, 50 traffic lights, 10 emergency vehicles). Decide protocols, justify choices, list failure points, then refine with AI feedback.
 For 1,000 IoT I'm using [OLSR] because it's meant for a large dense network , 50 traffic lights, i'm using [DSDV] because it has stable network and 10 emergency vehicle i'm using [AOVC] because it's reactive and adapt quickly to mobility.
 
 List failure points
 Congestion too many devices updating routes
 Delays AODV routes discovery may slow emergency response
 Overhead OLSR  uses handwidth to keep routes fresh

Reflection:

    % human judgment vs. AI contribution
    65% vs 35%

    Could you defend decisions without AI?
    Yes.

    What will you still remember in 6 months?
    I will remember that OLSR and DSDV are proactive and AODV is reactive and AODV has small mobile network, OLSR has a large network and DSDV has a stable network.

    Did AI make you sharper, or think for you?
    AI makes me sharper and didn't think for me.

