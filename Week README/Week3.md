## Week 3

# Monday

Resolving Twilio default text:
class = TWilio::REST:Client.new(account, token)
Extract Client.new and change it to double


# Web

Primary Goal:
- Can you build a web app?

By the end of this week:
- Build a simple web app
  - Complete weekend challenge - or at least know how to complete it
- Follow an effective debugging process for web app:
  - using pry! understand it well
- Explain the basics of how the web works(request/response, HTTP etc):
  - Ex. Can i do a diagram t explain the process?
- Explain the MVC patter

http request
-----------     ------>    ------------
|             |           |             |
|   Client    |           |    Server   |
|             |           |             |
-----------     <------     ------------
http response

Underneath :

MVC -> Model-View-Controller:
Extracting logic into different files with different responsibilities

Controller:
define a list of requests that we can respond to
if it is not supported 404 error

If i can handle it:

Model
Go to the class you need to return a value
Pass it back to controller

View
Make that information to some sort of document that can be changed into html.
View is responsible for creating a document pass is back to the model in a form of http and goes back tot he user.

# Process Modelling
Notes from Sam's workshop on HTTP/ Request Response Cycle:

A process model is just a way of describing a process (describing process modelling.)

Chrome Dev Tools (F12) -> network tab -> Hit record and it's possible to then view all POST and GET requests sent.

Response tab shows what the server has responded with.

Response codes:

200's - Ok Response
300's - Cached response
400's - Bad response
500's - Got in touch with the server, however the expected response wasn't received.


<img source='cat.jpg' > -> this triggers the second get request
Request can deal with one document at the time
If there are multiple pictures request keeps going back to model.
When internet is slow or website is bad you can see pictures loading one by one and this is the reason why

Request:
HTML - string of characters

ERB -> It piles down to html file.

In Sinatra by default -> it will look in the public folder

# Sinatra

get -> http request
name = params[:name]... -> route inside a string
end - last line is sent to the browser

named parameters can be accessed by using params.


get -> to show a result
post -> when we want to create something
put / patch -> when you want to update something
delete -> remove result

Inline views -> erb :hello etc -> instance variable available in views


# Empathy with Dana

Empathy builds trust.
3 types of empathy:
- Affective empathy - > heart breaking but won't rise any action
- Cognitive empathy -> doctors
- Empathic concern ->  You understand the other person and you are trying to help

Why empathy might be missing:
- anger
- protection
- identifying
- fear of intimacy


 Training Empathy:
 1. Just like me ->  We tend to be more empathetic when people are more similar to us.
  If you expect person to be in a certain you will only see that. Try to make them look more like you. Go with curiosity and no expectations.

 2. Metta Bhavana -> Wishing somebody well."May that person be happy". Imagine people being happy. It will warm up your heart. Researched material
 Hack for interviews: People can feel when you are needy. Take a moment, ground yourself. Wish the interviewers to be happy and change energy. Be interested no interesting.

 3. Empathetic Listening:
  - Where people are really listening to you. Deep listening is a big part of empathy. 80% full attention and just listen. 20% looping and thinking how is this affecting me.
  Listen to them as you are going to be tested on what they are saying.

  Your judgment is your key to growth.Give people empathy first before your judge them or yourself.

# Debugging 2

- Tighten the loop; Get visibility

debugging for command line:
- Stack trace
- p
- tests
- pry/irb

identifying capybara because we have "scenario" in our test

capybara -> save_and_open_page -> it is freezing at that point showing what is happening on that point


# Reflections

What i have liked about this  week?
- Learning we apps <3
- Sinatra was super fun
- Having birthday in Makers! Best cohort ever!
- Sam is a great coach!

What was lacking?
- CSS and html
- Better understanding of feature test


What have I learned?
- capybara
- using Ruby as a model
- MVC pattern

Easy wins:
- Ruby in Sinatra
- Rspec
