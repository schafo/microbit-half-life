# micro:bit Half-life
Using a micro:bit to demonstrate the concept of radioactive decay

Intended to act as a visualization and experimention tool for understanding how radioactive elements undergo decay.


## How to use
Press **A** to decrease the number of LEDs to start with (min 1x1)
Press **B** to increase the number of LEDs to start with (max 5x5)
Press **A+B** to start decay

Single 988Hz tone = decay
Single 196Hz tone = no decay

Double 659Hz tone = half of LEDs have decayed, simulation stopped. Press **B** to resume

Once all the LEDs have decayed, **shake** the micro:bit to reset the simulation


## Learning use-cases / lesson ideas
1. Get a stopwatch and measure the time of each half-life period, starting with the default 5x5 LED setup. Write down how long each one takes.
2. Repeat step one (multiple times), recording the timing of each half-life period.
3. Vary the size of the starting grid.

### Questions:
- How do the half-life periods compare when there's 25 LEDs to when there's only 6 LEDs left?
- What do you observe as you repeat the experiment multiple times?
- Does varying the size of the starting grid have any effect on the half-life? If so, what?


## Notes
- I'm sure there are improvements, both in terms of improving scientific and code efficiency. If you want to make a contribution, feel free to raise a PR.
- As 25 isn't happily devisable by 2 (and neither is 3), the simulation in these cases is stopped when remaining LEDs is *less* than half 
