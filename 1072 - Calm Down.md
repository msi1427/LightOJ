1072 - Calm Down

Problem link : http://www.lightoj.com/volume_showproblem.php?problem=1072

In the first figure, the circle contains 6 small circles . So the angle is (PI/6) . 
When the circle contains n small circles then the angle will be (PI/n) .

Now from the knowledge of trigonometric ratio , we know,

sin(theta) = opposite / hypotenuse

![calm](https://user-images.githubusercontent.com/35444388/42184769-7525e928-7e68-11e8-8371-ed8016430b3d.PNG)

sin(PI/n) = r/(R-r)

r = sin(PI/n)*(R-r)

r =( R*sin(PI/n)) – (r*sin(PI/n)

1 =(( R*sin(PI/n))/r) – sin(PI/n) [ dividing both sides by r ]

1 + sin(PI/n) = ( R*sin(PI/n))/r

r = ( R*sin(PI/n)) / (1 + sin(PI/n))

Hope it helps.....
