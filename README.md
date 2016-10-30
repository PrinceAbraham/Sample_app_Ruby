# README

We will begin developing the professional-grade sample application that will serve as our example throughout the rest of this tutorial

https://www.railstutorial.org/book/static_pages


We’ll also plan to make actions for a Home page, a Help page, and an About page, designated by the lower-case action names home, help, and about. The generate script takes an optional list of actions, so we’ll include actions for the Home and Help pages directly on the command line, while intentionally leaving off the action for the About page so that we can see how to add it
*rails generate controller StaticPages home help

Error 1
Don't forget to add a root

Error 2
Something went wrong. Make sure the def hello render html: "hello" syntax is correct. The colo has to be next to the render html not string