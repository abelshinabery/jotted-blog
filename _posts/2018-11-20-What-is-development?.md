---
layout: post
title: What is development?
---

Development is traditionally a process that takes place over time and is closely linked to the growth of skills, fluidity and difficulty level of a certain task, such as an athlete being trained or sharpening one’s critical thinking. However, these are optional and are not by any means requirements of the process, they are just the most popular ideas that spring up when talking about development in general.

Development in the work force usually means the ongoing attention that is being paid to a project. More specifically, in the computer science world, development is often boiled down to coding or the act of coding. Once you’ve spent some time playing around with a computer language it is pretty easy to see why this became a popular synonym and also why the most logical step was to start calling those who code developers.

## Beginning Your Journey

So where do you, as a new developer, begin? The easiest way to answer that is by showing you what the start of development might look like. If you are completely new to HTML, this will seem a little foreign, but just bare with me and I will explain the bigger concepts as we go along.

<ol>
  <li> Pick a basic text editor on your machine, the most popular is notepad for windows users.</li>

  <li>Write the following text inside your word document:  
  {% highlight html %}
  <!DOCTYPE html>
  {% endhighlight %}  
  This first line is a statement that lets browsers know what version of HTML is being run and is mainly there by convention. For our purposes you shouldn’t need to change the doctype too often, if at all. The statement is surrounded by brackets because it is the syntax of HTML, or the rules of the language, and is called a tag. Tags can either be self closing, like the doctype, or require a specific closing tag like the statements below.
  </li>

  <li>
   Now write this set of tags underneath:
   {% highlight html %}
   <!DOCTYPE html>
   <html>
   </html>
   {% endhighlight %}
   The html tags enclose all other html tags besides the doctype declaration. This lets the browser know how to render the html in a webpage format.
  </li>

  <li>
  Next, we'll add the head and body tags:
  {% highlight html %}
  <!DOCTYPE html>
  <html>  
      <head>
      </head>

      <body>
      </body>
  </html>
  {% endhighlight %}
  These tags hold specific types of information inside of them. Head contains the metadata for the html document, things like the title of the page or files that are linked to the page. The body contains things like headings, text and images for the webpage.
  </li>

  <li>
  Now, add a title and a heading to display on the page:
  {% highlight html %}
  <!DOCTYPE html>
  <html>
      <head>
          <title>My page!</title>
      </head>

      <body>
          <h1>Hello there!</h1>
      </body>
  </html>
  {% endhighlight %}
  The title tag encloses the text that will be used at the title and also for search engines like google to help find your page faster. The h1 tag stands for “header 1” and tells the page that the text inside of it is a heading and is at the top of the priority. This is usually reserved for the main heading of the entire page. There are also h2, h3, h4, h5, and h6 tags depending on their specific priority!   
  </li>

  <li>
  Now press save and select “all files” as the file type, and rename your file to index.html (any name before .html will work, but traditionally your homepage will be called the index).
  </li>

  <li>
  Next, fire up your favorite browser and press CRTL + O. Find and select your index.html and double click. You should see a blank page on the browser with the title “My page!” on the tab and also “Hello there!” in big black letters on the page itself.
  </li>

  <li>
  Pat yourself on the back for creating your first web page!
  </li>
</ol>

Each step by itself doesn’t really amount to much, but put them all together and it becomes a process, with steps and decisions along the way. This is the essence of development.

## What it Means to Be a Developer

I’m a firm believer that most things in life are subjective, so for the most part my answer to questions like this is that it changes depending on who you are and who you want to be as a developer. As in most things in life it is important to know why you are getting into something and most importantly, why you enjoy it. There are plenty of developers who learned to code because they love it and also plenty that do it because it is a good job with security as long as you know what you’re doing. What fuels the fire doesn’t matter quite as much as how bright the fire burns, but for the sake of your well-being and those who care about you, I hope you like it, or dare I suggest, have fun while doing it.

To avoid being too broad, I’ll list a few points below that I believe is in the heart of every developer that ever touched their fingers to the keyboard. Again, these may be different for everybody, but from my own personal experience, here is what one should expect when exploring the art of code.  

### Time and Effort

It’s pretty hard to pass up one of the most important aspects of learning any new skill. It takes time and practice to learn how to develop and create code. As a professor once told my sister while in undergraduate school, “If you could learn by looking, the dog would be the butcher.”

Okay, so it was cooler when he said it. But I think you catch my drift when I say that you have to put finger to keyboard in order for things to really sink in and allow your thought process to really start getting used to the computer science mindset. Never underestimate the amount of time a program might take, and respect the effort you put into something like there’s no tomorrow.

### Problem Solving

For me, the thrill of solving the problem is the reason why I keep coming back again and again. That and I have homework due. But on my free time I just don’t quite feel right when I don’t have a problem to solve. Sometimes it is hard to put down and can end with me staying up entirely too late.

You do not have to LOVE solving problems, your mind will get used to the process and you can find plenty of motivation from other sources. Maybe you enjoy created new things and can’t wait to crank out the next big idea from your mind, or maybe you want to be the next Zuckerberg. However, the core of development is definitely solving problems, and you should be aware that this will take up the majority of your time when developing.

### Languages, Languages, Languages

By this I mean computer programming languages. There are thousands of them, but only around 10 are still used widely as far as I know. While you definitely do not need to know every computer language, it is important to stick to one, maybe two languages that you enjoy using and are useful in the field you would like to go into to become proficient in.  

I recommend C++  and Python for initially learning programming. C++ is the grandfather of most modern languages and is still in wide use to this day. Because of its seniority there are plenty of tutorials online and getting used to the syntax will help you tremendously when switching over to languages like Java and JavaScript.

Python is arguably the easiest modern language to learn that is in high use. There are no fancy curly brackets to be found and it is very powerful as well as versatile. It is important to note that while it may be easier to learn on initially, there will be some concepts when switching to other languages that might be hard to get used to, like having to explicitly state what type of variable you are creating and being very careful with syntax errors.

Other languages to consider are Java and JavaScript. Java is widely used and extremely powerful, but a little harder to pick up than C++, simply because it is an entirely object oriented language and can require a lot of concepts that can seem overcomplicated and scary to new programmers. Don’t let me scare you away though! It is highly recommended to learn at some point in your career, so why not now?

JavaScript, like Python, is a scripting language that people have taken to the next level. If you plan on becoming a web developer then this may be the only computer language you will ever have to write in, although not very likely in the long run as you will probably have to deal with backend languages such as SQL and PHP at some point.  

Whichever language you decide, just make sure you are understanding the fundamentals of programming and you will find transferring from one to another relatively easy.  

### With Great Code Comes Great Responsibility

It takes time and effort to create an application, even if it is a simple command line menu interface, and often requires multiple skills to be completed. It is true that anybody can become a developer, but it is important to remember that this title comes with a responsibility to complete the projects you start, even when the procrastination bug is knocking on your window. This isn’t meant to shame people who give up on projects, or just decide it isn’t worth your time, but more as inspiration for people to look deeper into your projects before letting go of them. As developers we are given the chance to create and along with that must also come responsibility for that creation, so remember to think twice before letting that unfinished code sit on your hard drive forever.

## Code On

If you managed to get anything from this article, I hope it helps you along your journey and maybe even spark some inspiration for you to continue learning and adapting to new problems and technologies. Remember, being a developer doesn’t end once you finish a project. There is always another one waiting beyond the horizon.
