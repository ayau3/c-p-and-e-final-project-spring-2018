# Starry Night Interactive Painting
We propose making an interactive version of Van Gogh's Starry Night, which invites the user to blow on the painting, triggering LEDs behind the painting to blink in different patterns, resembling the movement of stars and wind. The bottom right of the painting includes a town with houses that will also have LEDs that turn on and off to mimic people moving about the town. 

## Team

By Andy Jin, Sasha Manghise, Jennifer Xiao, and Annabel Yau

## Summary

The main goal of the project is to incorporate interactive elements into Van Gogh’s Starry Night through the use of LEDs and sound sensors positioned behind a semi-transparent representation of the painting. The audience will first blow into a small microphone on the left side of the painting, positioned behind the gust of wind. This will trigger a succession of LEDs to light up across the painting throughout the gusts of wind, then fade away. Then by pressing the capacitive touch sensor at the center of each star, the lights surrounding the centers will light up and fade, mimicking a glowing effect.

Following the project we found that the most challenging part was soldering and configuring the neopixels, which hindered our progress and prevented all of the stars from working.

## Component Parts

An artistic representation of Starry Night was painted on a large sheet of paper that allowed the light of the LEDs to diffuse through.

Components:
Cardboard frame with wooden supports and a large sheet of semi-transparent paper to display painting
Microphone to detect user’s breath (INPUT)
Individual neopixels soldered together and a neopixel strip, to resemble stars and wind (OUTPUT)

### Block Diagram
![alt text](https://raw.githubusercontent.com/ayau3/Final-Project/master/Screen%20Shot%202018-04-03%20at%204.40.49%20PM.png)
![alt text](https://raw.githubusercontent.com/ayau3/Final-Project/master/Screen%20Shot%202018-04-03%20at%204.41.29%20PM.png)

## Challenges

The most challenging part of our project was mainly the tedium of soldering together the neopixel stars. In order to create neopixel rings, we soldered together individual neopixels. However, the wires kept breaking or the connections weren't strong enough, so we had to resolder them countless times. We eventually hot-glued each of the connections to reinforce them, but in the end, not all of the stars lit up. This also made it difficult to connect them to the capacitive touch sensors. In the future, we would likely buy rather than solder neopixels because it would be less time-consuming. 

## Timeline

- Week 1: Write proposal 
- Week 2: Purchase microphone and neopixels and create a mockup of where we wanted all of the LEDs to be 
- Week 3: Program sensors and finalize layout of LEDs
- Week 4: Finish painting Starry Night, create frame
- Week 5: Assemble all components, debug neopixels, present

## Completed Work

![alt text](https://github.com/ayau3/c-p-and-e-final-project-spring-2018/blob/master/imagejpeg_0.jpg)
![alt text](https://github.com/ayau3/c-p-and-e-final-project-spring-2018/blob/master/IMG_7864.JPG)
![alt text](https://github.com/ayau3/c-p-and-e-final-project-spring-2018/blob/master/IMG_7869.JPG)
[Click link to view video of project](https://www.youtube.com/watch?v=bfCJk_1FTVQ&feature=youtu.be)


## References and links

**Final Showcase One Page Description**:
https://github.com/ayau3/c-p-and-e-final-project-spring-2018/blob/master/starry%20night%20poster.pdf

1. A similar interactive painting that allows a user to blow on dandelion lights that are painted using a traditional Chinese brush painting style: https://vimeo.com/40904471 
2. Research on the meaning and inspiration behind the original starry night:
3. https://www.moma.org/learn/moma_learning/vincent-van-gogh-the-starry-night-1889 
  - “This morning I saw the countryside from my window a long time before sunrise, with nothing but the morning star, which looked very big,” wrote van Gogh to his brother Theo, describing his inspiration for one of his best-known paintings, The Starry Night (1889). 
4. http://mentalfloss.com/article/62621/11-things-you-didnt-know-about-starry-night
  - This connection gives a special significance to this van Gogh quote, "Looking at the stars always makes me dream. Why, I ask myself, shouldn't the shining dots of the sky be as accessible as the black dots on the map of France? Just as we take the train to get to Tarascon or Rouen, we take death to reach a star."
5. TED Ed: The Unexpected Math behind The Starry Night: https://www.youtube.com/watch?v=PMerSm2ToFY
