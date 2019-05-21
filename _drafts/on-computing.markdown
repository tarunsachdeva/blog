Computing works in layers. Layers are stacked on top of each other. Software is a layer that sits on top of hardware. Software has many layers in itself. The OS is a layer, and "apps" sit on top of the OS. 

Example: I write some Objective C code to create an app. The app runs on top of iOS. iOS sits on top of a a chip with CPU.

The code from one layer gets translated into a language the layer below it can understand. That process is called compiling.

This is a really important concept. Let that sink in.

In the same example: Objective C gets translated into a language that iOS can run (called Assembly). Assembly gets translated down into Machine language (1s and 0s), which provide an instruction set for transistors to do their thing in silicon.

Python, Objective C, Javascript, etc. are all HIGHER LEVEL languages that run on top of the OS. Assembly is a LOWER LEVEL language. There's an excellent article on this specific to iOS: https://www.raywenderlich.com/2705-ios-assembly-tutorial-understanding-arm. 

I paid $30,000 for a computer engineering degree and honestly if someone could have just told me this before that...I would be 30k richer today. 

So why is this important? How is it relevant to your question??

Whatever you learn, just remember it's being translated into very similar assembly language below it. When people say it doesn't matter what language you learn, it's really because of a few things.

Almost all higher level languages have the same fundamental capabilities. You can build almost anything no matter what language you choose.
Programming is programming. With a fundamental understanding of the basics of programming in whatever language, those skills are transferrable across languages (writing Ruby once you've written Python is easy).
The most popular languages have frameworks to help you build web apps, mobile apps, and pretty much anything in between, so just try to focus on what to build not on your language choice. 
Python is popular in math/stats (num.py) but can be used to build Webapps (using a framework called Django)
Ruby is popular on the web (Ruby on Rails) but can also be used to build mobile apps (using a framework called RubyMotion)
JS is a language used by web browsers to render web pages (HTML/JS/CSS) but can be used to build web servers (using Node.js)


The word language is really appropriate. A programming language is like Russian or Japanese - but instead of talking to people, you are using it to communicate with the layers below it. At the end of the day, it doesn’t matter which language you use, as long as you can get your message across. 

Some languages communicate some things better and faster than others. Ruby is pretty versatile but this can also lead to performance issues when used at scale. JS is performant, versatile, but holy shit is it hard to read and enjoy. Some languages were built for a certain use (i.e. JS in the browser), and then someone said hey can we use JS on the server? And Node.js was born. 

So to your original question -I don’t know what I can build with python? Almost anything, and hopefully that explanation helps you out. 

And if it didn’t well this is what Google told me :) 
https://www.python.org/about/apps/
https://intersog.com/blog/some-cool-things-you-can-do-with-python/

----

