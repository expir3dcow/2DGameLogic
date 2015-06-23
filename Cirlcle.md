# CIRCLE:

## ---properties---
x : the x coordinate of the centre of the circle


y: the y coordinate of the centre of the cirlce


radius: the distance from the centre of the circle to the edge of the circle


diameter:  The suare root of the distance from an edge of the circle to the opposite edge of the circle (2 * radius) 



## ---formulas---
distance (to another circle) :

    difference of two circle's x's squared and added to the difference to the two circle's y's squared.
    Example:
    circle1 (x:10, y: 10, radius : 50) , circle2(x:30, y:10, radius: 70)
    distance_of_xs: abs(10-30) = 20
    distance_of_ys: abs(10-10) = 0
    distance: sqrt(20^2 + 0^2) = sqrt(400) = 20
  
collision (with another circle) :

    If the distance of the two circles are less than the sum of the two cirlce's radius's, than a collision is detected
    Example:
    circle1 (x:10, y: 10, radius : 50) , circle2(x:30, y:10, radius: 70)
    distance: 20
    20 < 50+70 = 20 < 120: true
    
