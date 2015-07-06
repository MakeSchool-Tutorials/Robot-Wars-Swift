---
title: "Pair programming"
slug: pair-programming
---

For this exercise, we want you to try out "pair programming". There are two different roles in pair programming: the driver and the navigator.

The driver is the person currently programming. Before starting, the driver and navigator agree on a goal or problem to solve. This means you should draw out a state machine diagram for your AI before you get started coding! The driver then sits in front of the computer and types out code to solve the current goal. The goal should not be "implement the robot". It should be a small task like "implement scattering after gotHit is called".

The navigator does not dictate code. They are the drivers safety net and help them think through the problem. The navigator should be reading what the driver is writing as they write while looking for possible bugs and edge cases the driver may have not noticed.

Constant communication is key while pair programming! Read some more about best practices in [this excerpt](http://www.jamesshore.com/Agile-Book/pair_programming.html) from The Art of Agile Development.

Now it's time for you to find a partner!

#Getting ready!

To get started coding, create a new Robot by inheriting from the "Robot" class. Once you're ready to test your robot, place it's class name "Configuration.h" so it can fight against one of our default robots:

        static NSString \*robotClass1 = @"RobotOneClassName";
        static NSString \*robotClass2 = @"RobotTwoClassName";

Begin with trying to beat SimpleRobot. Once you can do that, move on and try to defeat the other robots!

Remember, the entire documentation is in `/docs` folder in the project you downloaded. You should read it over now with your partner.

Now its time to try out your own strategy. With your partner, plan out a robot. Start pair programming it together as described above. You will be working on a single computer for this assignment.

Good luck to you and your partner!
