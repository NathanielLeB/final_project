# Title

## Repository
<https://github.com/NathanielLeB/final_project>

## Description
An split complementary color palette generator. You will choose the "primary" color, and the program will display that color, and the two colors next to its complement on the color wheel.
This would be very helpful for me, and artist who are wanting a challenge, or needing help coming up with a pallete for their peice.

## Features
- Feature 1: color picker
	- The program will ask what color you want as primary. you have to choose a value for the R, G, B channels, from a range of 0-255.

- Feature 2: visual display
	- this will be the display that will show all 3 of your colors, and what thier rgb hex code is. 
  - will be visually interesting, or at least organized in a way that isn't painful to understand.

- Feature N: Text and Mouse input
	- will allow for text and mouse input. This is how you will input your primary color, and how you will be able to copy the hex codes for each color on the palette.

## Challenges
- how to pull get the hex code from a color in python.
- how to pull specific random colors out from a range. For the case of split-complementary, how to get not just the opposite of a color from a range, but the two adjacent colors from that opposite.
- generally, i need to do a lot more research into random generators in python, and how to do it more effectivley.
- implementing system for mouse and text input (I did not learn how to do this for py.rain, I know its possible, just need to learn.)
- implementing clipboard system. (i intend to do this using pygame.scrap.)

## Outcomes
Ideal Outcome:
- The ideal outcome is that it is able to generate a split-complementary color palette, and be able to not only display that info effectivley, but allow interaction with that display, to allow for text input for the primary color, but also the have things be clickible, and react appropriatley, ie. being able to click on a box that says "copy" and have that string be copied.

Minimal Viable Outcome:
- be able to input a primary color, and have the program display the split-complemantary palette on a screen in pygame. Should still be able to type text and click links. if hexideceimal display is deemed too difficult, don't implement display for hexidecimal, or copy system.

## Milestones

- Week 1
  1. Work on Visual Display
  2. Create system for clickable links and text input

- Week 2
  1. color generator finalizations/ bug fixing
  2. completing visual display for colors 

- Week N (Final)
  1. finishing tasks i may not have been able to finish the last 2
  2. adding display for the specific hex values, 
  3. sprucing up visual display for color generator.