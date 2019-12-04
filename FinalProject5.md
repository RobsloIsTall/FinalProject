# A Coding Project

#### Other Pages
[Home](README.md) &nbsp; &nbsp;
[Water Polo](finalProject2.md) &nbsp; &nbsp;
[College Essay](finalProject3.md) &nbsp; &nbsp;
[Videogames](FinalProject4.md) &nbsp; &nbsp;
[Code](FinalProject5.md)

### ObjectPositionCalc

    xPosition = float(input("Where do you want to start? "))
    yPosition = float(input("How high do you want to start? "))
    acceleration = float(input("how fast do you want to go? "))
    time = float(input("How long do you want to go? "))
    # xf = x0 + v0t + ½at2
    finalPosition = xPosition + yPosition * time + (.5 * acceleration * time ** 2)
    print("You made it to")
    print(finalPosition)
