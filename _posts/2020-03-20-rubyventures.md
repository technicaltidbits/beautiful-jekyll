---
layout: post
title: Adventures in Ruby
subtitle: By the way, dynamically typed languages are great
tags: [programming languages], [ruby]
comments: true
---
Lately, I've become interested in learning more about [docs as code](https://www.writethedocs.org/guide/docs-as-code/). This philosophy refers to using the same tools to write documentation as you would with code. As an example, teams might write their documentation in a markup language like Markdown, store those files in a version control system like Git, and publish with a static site generator (SSG) like [Hugo](https://gohugo.io/).

I was reading Anne Gentle's [Docs Like Code](http://www.lulu.com/spotlight/justwriteclick), which has a nice tutorial that walks you through the steps of using git and GitHub pages to create a website using [Jekyll](https://jekyllrb.com/), another SSG. I did some digging and discovered that Jekyll is written with [Ruby](https://www.ruby-lang.org/en/), a _dynamic_, open-source language. 

{: .box-note}
**Dynamically typed languages**: Dynamically typed languages check the types of your variables during runtime. They differ from **statically typed languages**, which check the types of your variables during compile time (in other words, before the program runs). If you want to read more, see this helpful blog post from [Hexlet](https://en.hexlet.io/courses/intro_to_programming/lessons/types/theory_unit).

I'm interested in learning dynamically typed languages after spending a few months wrangling with C#, which is a statically typed language. Here's an example of the difference between the two:

### Ruby
```ruby
my_name = "Deanna"
puts my_name #prints 'Deanna' to the screen
```

### C#
```csharp
string my_name = "Deanna";
Console.WriteLine(my_name); //prints 'Deanna' to the screen
```

The difference here is that C# requires that you declare the data type of `my_name` before it's used.  In contrast, Ruby does not. This makes Ruby much more flexible than C#. However, it can cause issues at runtime, which is an entirely different discussion.

If you're interested in learning how to code, or want to learn a new language, I think that Ruby is a good place to start. It seems like a readable language and after a quick Google search, is very forgiving. You can view the documentation using the link I included in this post. I plan to use Codecademy to get started before I start building programs in VS Code.

Happy coding, friends.