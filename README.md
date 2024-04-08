# Pitch Control in NFL Defense
This project aims to use monotonic neural networks (Sill, 1997) to visualize pitch control (Fernandez & Bornn, 2018) in NFL defense.

Here, I introduce a novel method to quantify and visualize NFL defense by adapting the concept of pitch control from soccer to American football. 
In soccer, pitch control measures each player's potential zone of ball possession. We extend this concept to NFL defense to create tackle zone control. 
Tackle zone control quantifies each defender's zone where a tackle is most likely. This is calculated using a monotonic neural network that considers features such as relative velocity, acceleration, and position of the defender, runner. 
This approach offers a new way to analyze and visualize NFL defensive strategies and player effectiveness. <br>



## Future Work Remaining
- Train more! (more data, more epochs, smaller cross-entropy loss)
- Player-specific neural networks to personalize tackle zones
- Defender Rankings:
    - Who outperforms the MNN-predicted tackle success probabilities across a season?
    - Who is always in a good position to tackle on average?
- Team Rankings:
    - Which defending teams cover the most possible receivers?
    - Which defending teams have the largest cumulative tackle control of the receiver on average?
- “Catch Zone Control” to extend concept to catches, swats, and interceptions.
