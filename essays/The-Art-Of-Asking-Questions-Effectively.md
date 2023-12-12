---
layout: essay
type: essay
title: "The Art of Asking Questions Effectively"
# All dates must be YYYY-MM-DD format!
date: 2023-09-05
published: false
labels:
  - Stack Overflow
  - Technical Questions
---

## What Not To Do:
The question titled <a href="https://stackoverflow.com/questions/77050165/find-distance-between-2-turtles-in-python-but-from-only-one-side">"Find distance between 2 turtles in python, but from only one side [closed]"</a> with the 
accompanying code snippet and description presents several issues that categorize it as a less-than-ideal 
question according to Raymond's guidelines. Firstly, the question lacks clarity in its objective. While it
mentions finding the distance between two turtles from only one side, it does not explain the 
specific problem. Furthermore, the code provided does not have details about the "player" and 
"car_manager" variables, as pointed by one of the answers. It is challenging for the responders to answer
the question without these informations. Additionally, the question's title and description do not follow the 
conventions of a well-structured technical inquiry. It is essential to provide concise and detailed information, 
context, and clear objectives when seeking help, as the vagueness and ambiguity in this question hinder potential 
responders from offering targeted solutions.

```
game_on = True
while game_on:
    time.sleep(.1)
    screen.update()
    car_manager.create_car()
    car_manager.move()
    if player.reset_position():
        car_manager.increase_speed()
        scoreboard.increase_level()
    for car in car_manager.all_cars:
        if player.distance(car) < 25:
            scoreboard.game_over()
            game_on = False
```

## What To Do:
The question titled <a href="https://stackoverflow.com/questions/336859/var-functionname-function-vs-function-functionname">"var functionName = function() {} vs function functionName() {}"</a> aligns well with Eric Raymond's principles for asking technical questions effectively. It demonstrates a proactive approach, echoing Raymond's call for showing effort and diligence in understanding the issue at hand before seeking help. In the description, the author questions why the programmer they are maintaining uses two ways to declare a function in Java. He asks if there are differences in the two ways they initialized a function. This shows that they refrained from making assumptions or premature judgments, following Raymond's guidance of not "pre-supposing the use of a method that may not be appropriate." Instead, they seeked informed insights from the community. In line with Raymond's belief in fostering collective learning, this question also offers valuable insights not just to the author but also to anyone facing similar challenges. In essence, it exemplifies how following Raymond's guidelines results in asking technical questions that are not only well-structured but also beneficial to the community.

## What I Think:
As a computer science major, mastering the art of asking technical questions effectively is an invaluable skill that extends far beyond the boundaries of the field itself. While it undoubtedly plays a pivotal role in problem-solving, debugging, and collaborating with peers, its significance transcends these confines. Asking questions effectively nurtures logical thinking, the ability to communicate complex concepts in a clear and concise manner, and the drive to seek information. These skills are applicable in various aspects of life. In the professional world, the capability to articulate questions effectively facilitates teamwork, innovation, and decision-making. In essence, the skill of asking technical questions equips computer science majors with a versatile toolset that enhances their problem-solving skills and enriches their professional interactions, making it an invaluable skill for the future.

