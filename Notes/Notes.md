# Meeting Notes
Click here to access our [miro board](https://miro.com/app/board/uXjVLq3f7QE=/)

Vote on the future topics: [Poll](https://novascotia-my.sharepoint.com/:fl:/r/personal/andrew_smith_novascotia_ca/Documents/Microsoft%20Teams%20Chat%20Files/Lunch%20and%20Learn%20Loop%20paragraph.loop?d=wa98bdf5b377a456e87a8a2e4905e69e0&csf=1&web=1&e=l3MLk6&nav=cz0lMkZwZXJzb25hbCUyRmFuZHJld19zbWl0aF9ub3Zhc2NvdGlhX2NhJmQ9YiUyMU83OFJBRTBsQUVheV9tNzV5d3RjQmFIRDJiMlNNWlpJa05sal9PZmEwdDliNlQ3SEkwMDFUNGlQb181c2llTmomZj0wMUxMSFRXUUszMzZGMlM2UlhOWkNZUEtGQzRTSUY0MlBBJmM9JTJGJmE9TG9vcEFwcA%3D%3D)

## 2025-07-15
- We talked about our practices working with GitLab and OpenShift
- We talked about benefits and challenges with making our applications open-source
- One of the concerns we discussed was about finding a bug in an open-source government application before we learn about it and fix it. We talked how bug bounty could help with this.
- We also discussed the CVE and CWE databases, which catalog cybersecurity vulnerabilities.
  
## 2025-06-10
- We solved Halifax's traffic issue :)
- Discussed Event-Driven Architecture, Microservices, and the challenges of data consistency.
- Reviewed the [Saga Pattern](https://learn.microsoft.com/en-us/azure/architecture/patterns/saga) as a solution, comparing the Choreography and Orchestration approaches.
- Planned for next week to continue the discussion on Event-Driven Architecture, with a deeper dive into the Saga Pattern.
  
## 2025-04-15
- We talked about challenges with merging branches and some possible solutions to help with solving the conflicts.
- We talked about bug fixes and how to test them and merge them into the main branch and keep uat and dev branches up-to-date
- We watched this short video on [gitflow](https://www.youtube.com/watch?v=1SXpE08hvGs)
## 2025-04-01
- We went through the subjects in the poll and chose MVC for today's learning topic.
- We reviewed this post from [GeeksforGeeks](https://www.geeksforgeeks.org/mvc-design-pattern/).
- We also watched a part of Uncle Bob's talk about [MVC](https://www.youtube.com/watch?v=WpkDN78P884)

## 2025-04-01
We selected the following patterns to explore further:
- Abstract Factory/Factory Method
- Command pattern
- Template Method
- Builder

We only had time to cover the first one, Abstract Factory. We watched a video explining some applications of this pattern and discussed it while reviewing additional example codes.

## 2025-03-25
Finished the Behavioural Design Patterns series with 
- Strategy
- Template Method
- Visitor

Create Design Patterns - All Stars Poll
- Vote on Favourites 
- Use those to delve deeper into the use and application of that pattern

## 2025-03-18
Meeting Cancelled

## 2025-03-11
Continued the Behavioural Design Patterns series with 
- Mediator
- Memento 
- Observer
- State

## 2025-03-04
We reviewed the Behavioural Design Patterns 
- Chain of Responsibility 
- Command 
- Iterator 

## 2025-02-25
- We watched [10 Design Patterns Explained in 10 Minutes](https://www.youtube.com/watch?v=tv-_1er1mWI)
- We chose Proxy pattern to dig into further and watched a video from [Design Patterns in the Real World, an Analysis-Based Approach](https://learning.oreilly.com/course/design-patterns-in/9781491935828/) course about this pattern. We think it was helpful and would like to watch more design pattern videos from this course.

Next session:
- Behavioural Design Patterns presentation
- If we will have time, learn more about the use of Proxy pattern in Entity Framework

## 2025-02-18
Andrew covered the rest of structural patterns by presenting the following patterns:
- Proxy
- Bridge
- Composite
- Facade
- Flyweight

You can find the slides under Slides folder (Slides/BytesAndBites - Design Patterns - Structural.pptx).

## 2025-02-11
Andrew covered the following design patterns in his presentation:
- Prototype
- Decorator
- Adapter
     
We agreed to continue with design patterns next week.

## 2025-02-04
Andrew covered the following design patterns in his presentation:
- Singleton
- Factory (Abstract Factory, Factory Method)
- Builder

__Links:__
- [Refactoring Guru](https://refactoring.guru/design-patterns)
- [Design Patterns in C# Path | Pluralsight](https://app.pluralsight.com/paths/skill/design-patterns-in-c)
- Free Course: https://youtu.be/NU_1StN5Tkk?si=u_Nf6IPyHiXHhfB1

We agreed to continue with design patterns next week.

## 2025-01-28
We watched [Clean Code talk by Robert Martin](https://youtu.be/7EmboKQH8lM) about the first rule of a function, function arguments, and switch statement.
Some take aways from the talk:
- Large functions are difficult to read and understand
- A function gets large because it tries to do more than one thing.
- Large functions can be broken down to classes and methods
- Booleans shouldn't be passed to functions - Consider breaking things down to additional functions (one for true, another for false)
- Switch Statements can be problematic
  - Managing Dependency Requirements > Create classes
  - Consider leveraging Polymorphism

We also watched a short video about [Strategy Pattern](https://youtu.be/E9-4uaoncVY?si=WPijzbqeQ2V1Q3xV)

Potential talks 
  - Exception Handling
  - Logging 
  - Code Review Process 

Next session: Design Patterns

## 2025-01-21
Today we talked about Clean Code. We started with choosing the questions or subjects to discuss. We talked about how to make functions smaller, how to name variables, and what design patterns to use.

We talked about the possibility of using one of the existing style guide like from Google, or Microsoft as the guideline for our implementations. Mark also mwntioned the possibility of checking the style during git commit automatically.

Next session we will continue with Clean Code and dig into what design patterns result clean codes.

- [Observer Pattern](https://en.wikipedia.org/wiki/Observer_pattern)
- [Strategy Pattern](https://en.wikipedia.org/wiki/Strategy_pattern)

## 2025-01-14

Today we talked about the topics and structure of the meetings. Here is the list of topics we came up with and chose "Clean Code" as the first one to go with.
We also talked about the possible outcome of these sessions, which for Clean Code it could be a coding style guideline for the team, similar to [Google's Style Guide for C#](https://google.github.io/styleguide/csharp-style.html).

| Topic | Comment |
|:---------- | :---------- |
| __Mastering Git:__ Best Practices and Common Pitfalls |
| __Clean Code:__ Principles and Practices for Writing Maintainable Code | Perhaps reviewing one of the popular guidelines |
| __Object-Oriented Programming:__ Best Practices and Design Principles |
| __Design Patterns Demystified:__ Practical Solutions to Common Software Problems |
| __Effective Design Principles:__ DRY, SOLID, YAGNI, and Beyond |
| __Collaborative Coding:__ Pair Programming with AI Assistance |
| __Unit Testing Like a Pro:__ Best Practices and Strategies |
| __Test-Driven Development (TDD):__ Building Quality Software Through Testing First |
| __Refactoring Code:__ Techniques for Improving Existing Codebases |
| __Software Architecture Styles:__ Choosing the Right Fit for Your Application |
| __Optimizing File Storage Systems:__ Designing for Performance and Scalability |
| __Effective Logging Strategies:__ Best Practices for Monitoring and Debugging |
| __Performance Management in Software:__ Tools, Techniques, and Strategies |
| __Database Design and Optimization:__ Building Efficient and Scalable Systems |
| __Securing New Applications & Addressing Vulnerabilities in Legacy Systems__ | NIST & OWASP |
| __Leveraging DevOps:__ Tools and Practices for Agile Software Delivery |Guest speaker series |
| __Cloud Migration:__ Assessing When and How to Make the Move | Guest speaker series |

## 2025-01-07

- Audience 
 - Open to: 
  - Government Employees
  - Health Employees
 - Future inclusion of Public citizens by invite/approval

- Goals
 - Create a network of software enthusiasts who are looking to build on or improve their skills 
 - To create a common knowledge of best practices and possibly use them to 

- For Next Session
 - Think about topics for next session 
   - Decide on topics before next session
 - Invite people to group

