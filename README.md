# Software Quality Handbook

Intro

## Task estimation in Scrum

Task Estimation in Scrum projects is done by the entire team. It is setup during the Spring Planning meeting. The goal of Estimation is to consider the User Stories for the Sprint by Priority and by the Ability of the team to deliver during the Time Box of the Sprint. Estimations are done to get people liable for their work, predict when they will complete it and to understand the magnitude of the project itself.

“Estimating isn’t about estimating at all. Estimating is about creating a shared understanding of the requirements, and a shared understanding of the solution. When teams have problems estimating, it’s almost never an estimating problem, it’s a shared understanding problem” [<sup>10</sup>][10].

There are plenty of ways to estimate your work. The key thing is to find the right way of doing it and the most suitable for the team. Types of Estimation includes Story Points with its most popular being Planning Poker. Story Points are intended to make team estimating easier. Instead of looking at a product backlog item and estimating it in hours, teams consider only how much effort a product backlog item will require, relative to other product backlog items [<sup>11</sup>][11].

**Benefits of Story Points over using Hours as a measure of Estimation [<sup>12</sup>][12]:**

1. **Points make it compulsory to use team’s performance data (velocity) for release planning.** - Planning can only be performed by knowing or predicting the team’s  velocity.  Thus, using points forces all planning to happen through the lens of the team’s velocity.
2. **Prevents the need for frequent re-estimation:** - Planning can only be performed by knowing or predicting the team’s velocity.  Thus, using points forces all planning to happen through the lens of the team’s velocity. Helps to prevent the need for non-frequent re-estimation.
3. **Story Points allays fear of commitment:** -When people are under less stress they think more rationally and hence better estimates.
4. **Focuses client conversation on the right questions if client is Agile or at-least understands Agile:** - Communicating with the client tends to be easier and more honest when using “points” rather than “days”.  This is because points allow us to separate the two concepts of how much work is to be done vs. how long it takes to do that work.
5. **Story Points invites collaboration as team behaviour becomes prominent over individuals:** - Using planning poker to estimate story points brings team together. Brings the team to share, constructively criticizes, debate and have fun with playing cards.
6. **Story Points help drive cross functional behaviour:** - Makes members of the team from different roles cooperate and learn to work cross-functionally.
7. **Story-points estimation is typically faster:** - Teams who estimate in days tend to take discussion few levels deep causing the fear of commitment to play a role because you are estimating in days.

**Disadvantages of Story Points [<sup>13</sup>][13]:**

- **Not understanding Agile methodology:** Developers are used to calculating and giving hourly estimates, so when the agile methodology is introduced in a team, in the initial phase the team may not feel comfortable with story point estimation.

- **Inflated Story Points:**
    Under pressure to improve performance, and to prove that more is getting accomplished, teams may inflate story points. This just creates an illusion of higher velocity, though the same/ less amount of work is being done.

- **Quality can be Sacrificed:**
    If the sole focus of the team (probably due to external pressures) is to maintain constant/ increasing velocity, then Quality is sacrificed. Efficient and optimized design, code optimization, code re-factoring are the first things to be dropped when the team is trying to complete all the work within a time-box.

The important things to remember about Task Estimation and planning in Scrum are as follows:

- Knowledge and progress are gained allowing reduce uncertainty around the delivery of the project.

- Team will work better if there are all thinking the same. Estimating should be carried as a whole team and not in teams of their roles.

- With the team coming together, Estimation can help members understand the magnitude of the project whether it is harder than they thought or easier compared to the other team members.

- Low Story Point sections help keep momentum helping to remove a slow start and rushed end, resulting in a consistent flow of work.

Task Estimation in Scrum can be beneficial if done right. Picking the right technique can help of team develop a project in the right time frame with the right amount of time spent on certain aspects.

## Coding standards

Good quality code requires consistent effort and a great focus from the developers’ team to meet the quality goal. Without conventions, it can be difficult for developers to understand the codebase and it can increase the development time as well as the complexity of the project structure.

Coding standards are a set of guidelines created by the development team. They are followed during development to achieve a uniform prgramming style, practices, and methods for each aspect of a prgram written in a specific programming language. This helps avoid unmaintainable codebase as it gets larger.[<sup>1</sup>][1]

Without coding standards, certain negative impacts may occur which include:

- **Security Issues:** As each developer has their own style of coding, this will probably create inconsistencies within the code which results in vulnerabilities. These can be exploited and threaten the security of the program due to poor coding practices.

- **Increased Development Time:** Most codebases grow over time. Not having a set of coding standards can make the codebase structure complex and hard to follow resulting in higher development time and inefficient use of resources.[<sup>2</sup>][2]

It is important to note that coding standards are usually created based on certain globally recognized formats of code. A developer that follows these practices will ensure the code is easier to maintain:

- Clearly define the varied data and its uses before writing the code.

- Code according to the coding conventions in place.

- Code ethically.

- Update the code according to latest updates and conventions at regular time intervals.[<sup>4</sup>][4]

Implementing a set of coding standards is quite beneficial to the development team, below are some of the most notable advantages:

- **Increased Efficiency:** As mentioned above, the majority of development time goes to maintenance. However, some maintenance issues could have been prevented. Implementing coding standards would help the team to detect the problems early or even prevent them completely. This will increase efficiency throughout the software process.

- **Bug Rectification:** It becomes really easy to locate and correct bugs in the software if the source code is written in a consistent manner. It also helps in reducing bugs in general which might require a hotfix which would not be ideal during development.

- **Cost-Efficient:** A clear code gives the developers an opportunity to reuse the code whenever required. This can radically reduce the cost along with the efforts put in the development.

- **Minimal Complexity:** If a code is complex, there are higher chances of it being vulnerable to errors. Coding standards help in the development of software programs that are less complex and thereby reduce the errors.

While it initially may take extra time to code according to the coding standards set by the development team, it will help the team maintain the code in the future. About 40-80% of the cost of a software goes to its maintenance [<sup>3</sup>][3]. Meaning that developers usually spend more time maintaining the software than build it.

Coding standards are essential to a development team, but they should not be written on stone. They should be flexible so that any unessential guideline can be marked as optional, and vice versa. Coding standards also save the team time and effort in the future, therefore, doing this activity is worthwhile. Below is a personal experience of developer who was involved in setting coding standards for their team.

“it makes sense to spend time discussing and arguing about them, since it is a valuable activity that will save you time and effort in the future. Code conventions should be reviewed frequently. Rules can be changed from "required" to "optional" and vice versa. If some of them do not work as expected, they should be revised or removed from the guidelines.” - [Roman Beskrovnyi][3]

## Code reviews

Code review is the process in which a developer's code is reviewed by a peer or peers. Code review prevents errors, helps maintain consistency across a project and allows for individuals to share knowledge and experience. Overall it leads to higher quality code and less bugs. Code review is an essential part of an Agile teams process.[<sup>6</sup>][6]

Failure to implement code review in the development process could result in:

- **Bugs:** The author may not detect that their code will cause an error, even with integration testing only 45% of errors are detected compared to 55-60% effectiveness for  design and code inspections.  Working under time constraints can lead to even the most experienced developers making mistakes that can lead to bugs. The cost of bugs increases exponentially at the different stages of a product so it is important to catch them in the development stage while they are easily corrected.[<sup>7</sup>][7]

- **Code that is not understandable or maintainable:**  Code should be readable and coherent so that other developers can access it at any given time. New  developers or developers from other teams may need to access the code, it is important that when they do it is clean, understandable and documented. It should be straightforward for another person to pick up where one left off. Valuable time should not be wasted on trying to understand another's code, this is avoidable and can be checked very easily during a code review.  As Martin Fowler said “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.”

- **A missed opportunity for developers to improve:** A lack of review can result in developers not sharing knowledge and/or technologies that could be useful to each other. Learning can go both ways in code review. The reviewer is not necessarily superior so knowledge can be shared in both directions.  Continuous learning is key in Agile and there is always room to improve. [<sup>8</sup>][8]

It is important to make the distinction that code review is intended to improve code and help developers, not to give harsh feedback or to second guess a developer. The author may dispute comments if they feel it is appropriate and have sufficient reasoning and evidence, however this should be a conversation and not an argument. The entire review process should be a positive experience for both involved and should be helpful and constructive. [<sup>9</sup>][9]

It is worth noting that while code review is very useful, it can be done inefficiently.  Reviews can take time, so where suitable it can be very beneficial to use analyzer tools to lighten the load. It is also important to assign appropriate reviewers who have a good knowledge of the broader scope of the project and its requirements. For example it would be counterproductive for a junior developer to review another junior developer's work, they might not have the experience to spot a potential bug and they may also not be fully aware of the business requirements of the project.

“I think it is very important to have a feedback loop, where you’re constantly thinking about what you’ve done and how you could be doing how you could be doing it better.” - Elon Musk

## References

1. [Coding Conventions][1]
2. [The Significance  of Coding Standards][2]
3. [10 Ways to Improve Your Code Proven Through Personal Experience][3]
4. [Coding Standards; Why Is It Important?][3]
5. [Importance of Code Quality and Coding Standards in Software Development][5]
6. [Why Code Review Matters][6]
7. [Code Reviews : Just Do It][7]
8. [Developer life: 5 reasons why the code review process is critical for developers][8]
9. [Developer code reviews: 4 mistakes to avoid][9]

[1]: https://en.wikipedia.org/wiki/Coding_conventions
[2]: https://webguruz.in/the-significance-of-coding-standards-2/
[3]: https://codegym.cc/groups/posts/387-10-ways-to-improve-your-code-proven-through-personal-experience
[4]: https://www.ommzi.com/coding-standards-why-is-it-important/
[5]: https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/
[6]: https://www.atlassian.com/agile/software-development/code-reviews
[7]: https://blog.codinghorror.com/code-reviews-just-do-it/
[8]: https://www.brightspot.com/products/developer-life-5-reasons-why-the-code-review-process-is-critical-for-developers
[9]: https://www.techrepublic.com/article/developer-code-reviews-4-mistakes-to-avoid/
[10]: https://www.knowledgehut.com/blog/agile/top-5-scrum-estimation-techniques-find-your-best-fit
[11]: https://www.scrum.org/resources/blog/why-do-we-use-story-points-estimating#:~:text=Story%20Points%20are%20intended%20to,to%20other%20product%20backlog%20items
[12]: http://www.agilebuddha.com/agile/agile-estimation-9-reasons-why-you-should-use-story-points/
[13]: https://www.linkedin.com/pulse/advantages-disadvantages-using-story-points-anshika-misra/
