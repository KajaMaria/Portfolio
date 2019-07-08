## Week 2

By the end of the week I should be able to use these things or explain why not to use them:

- Use all of week 1's skills (don't underestimate the importance of this)
- Break one class into two classes that work together, while maintaining test coverage
- Unit test classes in isolation using mocking
- Explain some basic OO principles and tie them to high level concerns (e.g. ease of change) - why would you choose these principles :
    -SRP
    -SOLID
    -Encapsulation
- Review another person's code and give them meaningful feedback

OO Patters :
- Polymorphism
- Delegation
- Dependency injection
- Inheritance


Goals for my week:

- Modules
- Feedback (pairing)
- Dependency injection
- OO relationships

## Monday


### Code Review :

First thing to read is README

- It works? -> Fulfil user needs - For computers:
    - test :
        - What do they do?
        - Are they passing? / Coverage
        - Use IRB or feature test
-  It's readable - For Humans ( Can everyone read it? Is it simple to understand?)
- Good naming
- Dry :
    - Less code to read
    - Easier to change
- SRP -> Does one thing

### What I have learned from Code Review:

- Learned about README
- Common bugs/ gaps
- Feedback is important:
      - Gives evidence of progress
      - team player
      - weaknesses to opportunities (helps you improve )
- At work you will rely a lot on feedback to develop
- It is hard to give feedback if you don't know if it's right or wrong

###  There are many solutions to one problem:
    - Options to do things differently
    - Learn other styles to have more options to solve your problems
    - There are no best solutions

### How to choose best style?
    - Consider your team
    - What is typical style of the team
    - Consider the rest of the code
    - Be consistent
    - use your experience ( be careful around this one! You might have bad habits and stop yourself from developing )

### Fix the Weather :
Options for technique :
MOCKING :
  - Doubling
  - Spies
  - Stubbing

Allowig_subject - bad practice


Importance of feature tests -> Checks if the whole system works well together

Fixing randomness :
1. Allowing things
2. Seeding the weather number generator

# How did it go?
Great day with very positive and fast moving afternoon project.


Goal for today:
- Finish Oyster


## Tuesday

# Domain Model Diagraming

- Extracting objects to draw a diagram
- Relationships between objects

Form and shapes it can take:
- Physical representation of the code
- Blueprint / Map
- Hoe our code is going to fit together

How could it look like:
- Table
- Sequence Diagram
- Secret diary
- Physical representation
- Process modelling
- UML ? 30 different types

[Dependency Injection]

Dependency injection is a technique for helping your test classes in isolation. It allows us to use a class or a double.

1. constructor injection: the dependencies are provided through a class constructor.
2. setter injection: the client exposes a setter method that the injector uses to inject the dependency.
3. interface injection: the dependency provides an injector method that will inject the dependency into any client passed to it. Clients must implement an interface that exposes a setter method that accepts the dependency.
OO Relationships (Forwarding, Polymorphism)

https://github.com/makersacademy/skills-workshops/tree/master/week-2/oop_3 - typo Your job not You

# How was Tuesday?

As much as I understand that this is a learning process i was basically heart-broke when I have realised that I have to change the design of my Oyster card to implement new classes. I am almost done with this weekly task and I look forward to hopefully re-doing some bits again if my pair is behind. Changing already written code is much harder than writing one from the beginning.

##Thursday

# Dependency injection

- What is an object:
 It is responsible for some behaviour - of one of few things
 - Separating things in to objects
 - Managers of behaviours

```rb
class Airport
  def initialize(weather)
    @weather = weather
  end

  def land(plane)
    #named the same because they have the same responsibility
    #do some stuff
    plane.land
  end
end

weather = Weather.new
Aiport.new(weather)


class Plane
  def land
  @flying = false
  end
end
```

These are two different object working with each other

Private methods -> You can call on private class ONLY AND ONLY if it is a part of a public card

 Class/ Modules


# Friday

## Retrospective

- Reflecting and optimising our processes

# Feedback Workshop
- Giving feedback with the right approach

What is feedback:
- guidance used as a basis for improvement.

Why is it difficult?
- we feel like we are compromising relationship
- ego / too self aware

Feedback
Love & Acceptance vs Learning & Growth -> Self-protection

Practice feedback as a skill.

- How can we make feedback easier:
  1. Shift your perspective
  2. Empowered receiver
  3. Know yourself
  4. Understanding feedback
  5. Use a framework

Ad1. No positive or negative feedback - only feedback -> change your point of view.
- Shift your perspective, courage, simplicity, communication.
[Blog how to make a decision by Dana]https://blog.makersacademy.com/how-to-make-a-decision-588d0247ace0

Ad2. Empowered receiver :
  - You can use it only if you choose it
  - Gatekeeper
  - Improve work life
  - Helps us understand ourselves

Ad3. Know yourself
How do we reject feedback:
  - Truth triggers - seems wrong , off target
  - Relationship triggers - about our relationship with that person
  - Identity triggers - it is so an opposite of how we see ourselves
  - Wrong-spotting - we are looking for what is wrong with this information

  What is happiness set point?
  [Oxford Happiness questions]https://www.theguardian.com/lifeandstyle/2014/nov/03/take-the-oxford-happiness-questionnaire

#Create self-awareness to be able to build on feedback
- It is ok to have your own recovery period

Ad4. Understand feedback

Types of feedback :
Appreciation
Evaluation
Coaching

Ad.5 Use a framework
- Make it actionable
- Avoid vague Feedback
- Kind - don't try to hurt someone : Check your energy before, ground yourself.
What is my energy?
What do i want to leave that person with?
What is my effect on other people?

#Non - violent communication
- Instead of sorries, use facts :
Why are you always late versus You were after 10am on Tuesday and Wednesday etc
- Show them how their behaviour is affecting you
- I have a need
- would you be willing to work with me on this

If you are trigger, name it!!
Take your time
Know your boundaries
Thank the giver - Feedback is kind 
