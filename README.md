# Waypoint Icon Small Black Green Circle
A waypoint icon replacement with a small circle with a black border and white inner fill color. (The white will be automatically turned to green by T2.) It is 10x9 pixels. There are no patterns. 

### Summary
This script simply contains a waypoint icon replacement. It can be described a small circle with a black border and white inner fill color. (The white will be automatically turned to green by T2.) It is 10x9 pixels. There are no patterns. 

Why use this icon? There are three primary reasons:

1. When there are a lot friendly players in the same area, it can be incredibly difficult to quickly determine who your flag carrier actually is. This is truly a pain when in LT - especially LT with higher numbers. The reason is that all the icons are colored green. The flag icon is green, the friendly IFF is green, and, if you are using buddy points, then your player waypoints are green. It's just a green mess with not enough differentiation. 

2. T2 is incredibly limited with how you can color friendly and enemy icons. The game forces you to use .png files, and it programmatically changes that .png files so that it either is green in color (friendly) or red in color (enemy). There is nothing you can do to prevent this. Within these constraints, the only thing you can control is the darkness of the green. A transparent .png will color as neon green. If you start with a darker color (ex: red, purple), then you'll end up as a darker green. There is *one* exception. If you color your .png solid black, then the game is unable to change the color - it will actually display black.

3. The default T2 waypoint icon (small_cross.png) is 16x16 pixels. This icon scales to a size that is *too* large when you're a certain distance from the player you have waypointed. The icon basically consumes the whole player. By using a very small icon, the scaling isn't so drastic, and it doesn't consume the player model.

Given the above, I tried to find a waypoint icon that was very visible. I found that combining black with green turned out to be very effective. The black stands
out from the green used with the flag icon and player IFFs, creating a sharp contrast. The green inner fill color is still absolutely necessary, so that you can find
your player waypoints from a far distance, as black tends to get lost in the terrain.

Even better, when the flag carrier has the flag, the black part of the waypoint icon can be seen in the middle flag icon, so the flag carrier stands out even more.

*Bonus Recommendation*: I highly recommend combining this with the flag icon script, FlagIconRoundedSquare.vl2. The two combined very much help differentiate teammates
more easily.
