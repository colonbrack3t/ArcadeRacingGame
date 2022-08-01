# ArcadeRacingGame
4 hour coding challenge


- To run, simply download the project and open the html file into any browser


- To play, up arrow to accelerate, left and right arrows to turn

![image](https://user-images.githubusercontent.com/26506402/182030978-6dc07982-50f4-4f73-9c04-e8e94c12331c.png)

This arcade-like car game is actually just tricks of geometry. Interestingly, the track is just an array of distance and curvature pairs, describing sections of the track. The game feels like it is moving through a track using visual cues like the grass and clips "moving", whilst actually theyre just oscilating from a sin function. Curvature in the track is expressed by moving the centre of the track. This naturally makes the player drift to the side of the track by creating descrepancy between track and player curvature, forcing them to turn.
