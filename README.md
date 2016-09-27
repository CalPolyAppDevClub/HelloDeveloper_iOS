Project: Hello Developer
Created by Joe Durand 9/26/16

INTRODUCTION********************************************************************
Welcome to Hello Developer, a simple app to help get you aquainted to the
AWESOME world of iOS Development! While we won't do any crazy - at
least not yet - it's a great way to get started fast, and we can build on this
easily.

I'm always open to suggestions, questions, and comments concerning this app and
iOS development. One can contact me via email:  joe.durand3 AT gmail.com.


SAYING HELLO********************************************************************
Traditionally, the first program any programmer writes is the Hello World
program. The goal is to simply print out "Hello, World!" We'll make it a bit
more interesting by having the user type in their name, have them hit a button,
and we'll deliver a nice customized hello world message.
Check out Main.storyboard in the file pane on the left, which will show you what
the app will look like when we run it.


MODEL VIEW CONTROLLER***********************************************************
While we won't get too involved in this topic yet, it's important to remember
that 9 out of 10 iOS apps are built using the model view controller (MVC)
structure. Each of these parts plays an important role in delivering information
to the user. This can be a tricky concept to grasp, but is easily understood
once you get going!

MODEL - the model manage data used in the app. It's the real brain of the
operation; without it, the app is just a pile of fancy buttons and sliders.

VIEW - the view serves as our interface with the user. Views contain buttons,
sliders, text boxes, pictures, navigation tools, and a lot more. The view by
itself is dumb; it can't do anything besides take input and show output.

CONTROLLER - the controller, more specifically the view controller, is the
interface between the model and the view mentioned above. It connects a name
field, for example, to a name property in the model. It tells the view what to
do, and sometimes the view tells the controller what to do.

Since this is a simple app, we will combine the model and the controller because
our model only consists of the user's name. (HelloViewController)


QUICK TOUR**********************************************************************
A quick overview of the files contained in this project. I encourage you to
Google these topics and look at Apple documentation to further your
understanding:

Hello Developer (blue icon) - the project file dictates all kinds of settings
for building the app, organized into tabs. Take a quick look and see if you can
understand some of the important basic settings in the General tab.

App Delegate - the 'messenger' between the app and the operating system.

HelloViewController - this is a controller in the Model View Controller system.
It takes information from the view, does some 'things,' and udpates the view
accordingly. More specifically, it reads the user's name, adds "Hello, " to the
front of it, and puts that on the label.

Main.storyboard - While there are several ways to build a user interface in
Xcode, the easiest way is by using storyboards. Storyboards in iOS Development
are similar to storyboards in comics; it's a series of panes that tell a story.
They lay out views and visual elements that make up the user interface. An app
might have, for example, a storyboard for that goes through the registration
process, or a storyboard that takes a user through the checkout process in a
shopping app. We have one main storyboard, since the user stays on the same
screen the entire time.

LaunchScreen.storyboard - As the app starts up, the launch screen is displayed
to let the user know something is going on. This is a good place to stick a
logo or company name.

Assets.xcassets - Asset directories store images, videos, audio files, and more
to be used in the app.

Info.plist - Working with the project file mentioned first, this stores
important details and settings about the app. A developer can set an app to only
work on an iPad or only work in portrait mode, for example.
