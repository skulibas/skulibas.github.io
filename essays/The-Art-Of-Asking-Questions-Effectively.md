---
layout: essay
type: essay
title: "The Art of Asking Questions Effectively"
# All dates must be YYYY-MM-DD format!
date: 2023-09-05
published: true
labels:
  - Stack Overflow
  - Technical Questions
---

## What Not To Do:
The question titled <a href="https://stackoverflow.com/questions/77050165/find-distance-between-2-turtles-in-python-but-from-only-one-side">"Find distance between 2 turtles in python, but from only one side [closed]"</a> with the 
accompanying code snippet and description presents several issues that categorize it as a less-than-ideal 
question according to Raymond's guidelines. Firstly, the question lacks clarity in its objective. While it
mentions finding the distance between two turtles from only one side, it does not sufficiently explain the 
specific problem. Furthermore, the code provided does not have critical details about the "player" and 
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

## Passion
My interests in software engineering stem from a strong desire to express myself creatively. I've always enjoyed expressing my ideas through art forms such as video editing and artistic design. What interests me in software engineering is the possibility to combine my artistic abilities with technical abilities. I consider software engineering as a blank canvas on which to paint with code, creating solutions to challenging problems while adding a bit of creativity. Whether it's creating user interfaces that are not only functional but also visually appealing, or developing new applications that push the boundaries of user experience, I'm excited to use my creative abilities to elevate software engineering to the level of an art form. 

## Growth
In the future, I aspire to bridge the gap between my creative instincts and software engineering expertise. I'm determined to master advanced design principles and UX concepts while delving deeper into front-end development. I see myself collaborating with diverse teams to apply my creative insights to a variety of projects. Ultimately, I aim to be a software engineer who merges technical prowess with artistic sensibilities, making a lasting impact in this ever-evolving landscape.

