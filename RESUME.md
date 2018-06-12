# Alec Sanger

> Passionate developer/architect/leader, hell-bent on doing great work and bringing out the best in the people around me. 

## Table of Contents
- [Contact](#contact)
- [Work Experience](#work-experience)
  - [GalaxE.Solutions](#galaxesolutions-detroit-mi)
  - [LevelSet Solutions](#levelset-solutions-royal-oak-mi)
  - [Ancor Information](#ancor-information-troy-mi)
- [Education](#education)
- [Programming Languages/Frameworks](#programming-languagesframeworks)
- [Favorite Projects](#favorite-projects)

## Contact

5195 Tahoe Ct  
Clarkston, MI 48348  
sanger.alec@gmail.com  
248.941.3813  


## Work Experience

### GalaxE.Solutions (Detroit, MI)

**Director of Technology** (July 2017 - PRESENT)

Primarily responsible for driving the technical elements of client projects both in-house and on-site.

- Migrated a number of on-prem systems to the cloud using AWS.
- Implemented coding standards, commit guidelines, and agile methodologies for in-house software projects.
- Mentored individuals and teams around best practices, especially when it comes to cloud-ready applications.
- Ran a weekly Machine Learning roundtable discussion to help teach people about machine learning. Meeting topics included things like the core concepts and mathematics of machine learning, the ethics of the industry, and actual design/implementation of small ML applications.
- Formed and lead a “SWAT” team of highly skilled developers to tackle the most interesting problems in sometimes unconventional ways using primarily linux-based stacks.

--- 

### LevelSet Solutions (Royal Oak, MI)

**Director of Technology** (March 2015 - July 2017)  
**Technical Development Lead** (October 2013 - March 2015)  
**Full Stack Developer** (December 2010 - October 2013)  

- First developer to join the company
- Initially focused on .NET (C#) rewrite of a large enterprise web application
- Solely responsible for all aspects of development until additional developer was hired
- **Promoted to Technical Development Lead in October 2013**
- Continued development with modern technology, primarily in ruby, php, javascript (angular), and objective-c. 
- Hired people for their values and desire to learn, more so than their current technical skills. This resulted in a team of highly motivated, highly collaborative developers who were constantly looking to improve themselves and their peers.
- Emphasized the importance of a collaborative development experience. By moving all of our code to Github, we were able to introduce standards for referential commit messages and a streamlined code review processes that kept the experience tidy for both developers and business analysts. I introduced Slack and an open-source internal wiki that we used for documentation, and cultivated a culture of openness and and curiosity.
- Went all-in on Amazon Web Services and Infrastructure As Code, which allowed us to rapidly deploy environments that were fully redundant and version-controlled.
- Shifted our focus away from .NET and onto technology that was linux-friendly (PHP, Ruby, Node, etc). Through the use of open source tools and frameworks, we were able to script large portions of our workflows that greatly reduced the amount of manual effort in development and deployment.
- Dedicated a large portion of my time to mentoring both junior and senior developers, not only in best development practices, but also in being a good colleague.
- Established a weekly technology meeting with a rotating presentation schedule between each developer to encourage open discussions and collaboration.
- Emphasized the importance of doing things the right way. Code smells were made to be an important part of our development process, and when something didn’t smell right, we always discussed why and what could be done to make it better.
- **Promoted to Director of Technology in March 2015**
- Continued development with modern technology, primarily in ruby, php, and javascript (angular). 
- Fully responsible for re-architecture and migration of multiple enterprise applications to the cloud. In total, hosting infrastructure consisted of 45+ servers between 6 virtual private networks, all implemented with load balancing, automatic failovers, and distributed services.
- Implemented coding and architecture standards that revolved around stateless services. At the infrastructure level, services were broken up by domain and decoupled for reusability between systems. At the code level, stateless single-purpose service objects were the primary drivers of functionality. This resulted in a significantly cleaner codebase with highly reusable components.
- Researched and tested several Infrastructure as Code technologies to replace our home-grown solution built several years prior. Converted all of our hosted applications to use Chef and AWS Opsworks for provisioning/deployment.
- Significantly increased automated test coverage (both front and back-end) which allowed us to safely implement continuous integration and continuous deployment.
- Completed EOS training, which provides a framework for maximizing the effectiveness of time and decisions in a leadership capacity.  
- Increased emphasis on career development for my team, defining personal goals with each individual and creating paths within the company for them to grow.

--- 

### Ancor Information (Troy, MI)

**.NET Developer** (February 2007 - December 2010)

Develop and maintain automated .NET systems for file processing and print output

- Automatically process CSV data to be printed on various mediums such as medical mailers and insurance cards.
- Responsible for all “non-continuity” jobs which were often one-time jobs that could not be easily automated.
- Formed a communication committee to improve the communication between the technical team and the operations team, which resulted in a greater understanding of each other and a significant reduction in future errors (that were previously caused by a lack of communication).
- Performed minor enhancements to large batch processes.
- Converted legacy applications to the .NET framework.
- Formed a Communication Committee to help different teams address and work through communication issues


## Education

**Certificate, Technical and Professional Communication**; Lawrence Technological University (Southfield, MI)  
2010-2011

**BSc, Computer Science**; Lawrence Technological University (Southfield, MI)  
2005-2010


## Programming Languages/Frameworks

- **Ruby:** My pride and joy. I have a deep passion for the expressiveness that ruby provides and the community that surrounds it. Most of my large-scale web applications are built Rails, though I have also built apps with Sinatra and Hanami (previously known as Lotus). If I need to script something in a pinch, you can bet it'll be a few lines of ruby!
- **PHP:** Prior to discovering ruby, PHP was my language of choice. I made little use of popular frameworks and instead spent a great deal of time trying to roll my own custom code. While I'm not a huge fan of the language itself, I do still appreciate it and recognize it as a valuable language, especially with PHP7. It will always hold a special place in my heart.
- **Javascript** The effort required to stay up-to-date with the latest and greatest in the Javascript world has prevented me from making it a primary language of mine, but I have used both Angular and React a fair amount. I prefer to focus on functional components that consume APIs rather the user interface. Node/Express are great, but I've often opted for rails for my APIs.
- **C#:** Honrable mention - I think .NET is extremely powerful and comprehensive, I just don't like developing on Windows. .NET Core is a step in the right direction, though!
- Basic knowledge of **Objective-C**, **Python**, **Elixer**, **Java**


## Favorite Projects

### Real-time "Competition" App

**Description:** This was an iOS application that worked just like the bar trivia games that you see at Buffalo Wild Wings. Each user would get an iPad with the application on it which allowed them to either host a game or join a game. The host user could watch as players joined their game (like a "waiting room") and could start the game whenever they were ready. The game itself consisted of X number of questions, each with Y seconds to answer. The quicker the question was answered, the more points the player was awarded. At the end of the game, the winning player was displayed on all of the iPads.
people join their game and then start the game at any time.

**Why I liked it:** There were a number of reasons why this was such a cool app...  
1. The ability to connect any number of devices was a super interesting challenge. Internet connectivity was not guaranteed, so we couldn't rely on a server to manage the connections and states. We ended up implementing bluetooth connectivity which for the most part worked great as there were no external dependencies other than proximity - we just needed one of the iPads to act as a temporary server/host. Of course this came with an immediate connection loss when the iPad went to sleep, which was another problem entirely... 
2. I got a chance to construct and deconstruct packets manually, which was a nice change since that's almost always handled automatically these days.
3. I got to implement a proper state machine (I am a big fan of state machines!)
4. The organization of the code turned out really well. It was extremely clear where all of the functionality lived, classes were abstracted and subclassed appropriately, comments were meaningful, it just felt really good. 

### Driving School
**Description:**   

**Why I liked it:** 

### Medical Payment Plan
**Description:** This was an enterprise web application that processed payment plans for medical bills. Hospitals would partner with this company to offer the service to patients, who would then make monthly payments through the application. Behind the scenes, the system would reimburse the hospitals and keep a small percent of the financed amount. This was a highly ambitious project, as there was significant logic around generating loan installments, interest calculations, and custom rules that each hospital could specify that had a ripple effect on many other aspects of the system.

**Why I liked it:** The project itself sounds like the epitome of boring - there is nothing exciting about generating payment plans. What made this exciting was *how* we built it. [Rails "engines"](http://tech.taskrabbit.com/blog/2014/02/11/rails-4-engines/) allow you to build a large application out of multiple smaller applications. This greatly simplifies the process of testing and forces a separation of concerns at the engine-level. The engines that we created, which encapsulated *all* functionality for this system, were Account Management, Accounting, API, Events, and Payments. This was a fun experiment that worked out extremely well.

### On-Demand Scheduling 
**Description:**   

**Why I liked it:** 

