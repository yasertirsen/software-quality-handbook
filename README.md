# Software Quality Handbook

Intro

## Task estimation in Scrum

Content

## Coding standards

Good quality code requires consistent effort and a great focus from the developers’ team to meet the quality goal. Without conventions, it can be difficult for developers to understand the codebase and it can increase the development time as well as the complexity of the project structure.

Coding standards are a set of guidelines created by the development team. They are followed during development to achieve a uniform prgramming style, practices, and methods for each aspect of a prgram written in a specific programming language. This helps avoid unmaintainable codebase as it gets larger [<sup>1</sup>][1].

Without coding standards, certain negative impacts may occur which include:

- **Security Issues:** As each developer has their own style of coding, this will probably create inconsistencies within the code which results in vulnerabilities. These can be exploited and threaten the security of the program due to poor coding practices.

- **Increased Development Time:** Most codebases grow over time. Not having a set of coding standards can make the codebase structure complex and hard to follow resulting in higher development time and inefficient use of resources [<sup>2</sup>][2].

It is important to note that coding standards are usually created based on certain globally recognized formats of code. A developer that follows these practices will ensure the code is easier to maintain:

- Clearly define the varied data and its uses before writing the code.

- Code according to the coding conventions in place.

- Code ethically.

- Update the code according to latest updates and conventions at regular time intervals [<sup>4</sup>][4].

While it initially may take extra time to code according to the coding standards set by the development team, it will help the team maintain the code in the future. About 40-80% of the cost of a software goes to its maintenance [<sup>3</sup>][3]. Meaning that developers usually spend more time maintaining the software than build it.

Coding standards are essential to a development team, but they should not be written on stone. They should be flexible so that any unessential guideline can be marked as optional, and vice versa. Coding standards also save the team time and effort in the future, therefore, doing this activity is worthwhile. Below is a personal experience of developer who was involved in setting coding standards for their team.

“it makes sense to spend time discussing and arguing about them, since it is a valuable activity that will save you time and effort in the future. Code conventions should be reviewed frequently. Rules can be changed from "required" to "optional" and vice versa. If some of them do not work as expected, they should be revised or removed from the guidelines.” - [Roman Beskrovnyi][3]

## Code reviews

Code review is the process in which a developer's code is reviewed by a peer or peers. Code review prevents errors, helps maintain consistency across a project and allows for individuals to share knowledge and experience. Overall it leads to higher quality code and less bugs. Code review is an essential part of an Agile teams process.[<sup>6</sup>][6]

Failure to implement code review in the development process could result in:
- **Bugs -** - The author may not detect that their code will cause an error, even with integration testing only 45% of errors are detected compared to 55-60% effectiveness for  design and code inspections.  Working under time constraints can lead to even the most experienced developers making mistakes that can lead to bugs. The cost of bugs increases exponentially at the different stages of a product so it is important to catch them in the development stage while they are easily corrected.[<sup>7</sup>][7]

- **Code that is not understandable or maintainable -**  Code should be readable and coherent so that other developers can access it at any given time. New  developers or developers from other teams may need to access the code, it is important that when they do it is clean, understandable and documented. It should be straightforward for another person to pick up where one left off. Valuable time should not be wasted on trying to understand another's code, this is avoidable and can be checked very easily during a code review.  As Martin Fowler said “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.”

- **A missed opportunity for developers to improve -** A lack of review can result in developers not sharing knowledge and/or technologies that could be useful to each other. Learning can go both ways in code review. The reviewer is not necessarily superior so knowledge can be shared in both directions.  Continuous learning is key in Agile and there is always room to improve. [<sup>8</sup>][8]

 It is important to make the distinction that code review is intended to improve code and help developers, not to give harsh feedback or to second guess a developer. The author may dispute comments if they feel it is appropriate and have sufficient reasoning and evidence, however this should be a conversation and not an argument. The entire review process should be a positive experience for both involved and should be helpful and constructive. [<sup>9</sup>][9]


## References

1. [Coding Conventions][1]
2. [The Significance  of Coding Standards][2]
3. [10 Ways to Improve Your Code Proven Through Personal Experience][3]
4. [Coding Standards; Why Is It Important?][3]
5. [Importance of Code Quality and Coding Standards in Software Development][5]

6.[Why Code Review Matters][6]
7.[Code Reviews : Just Do It][7]
8.[Developer life: 5 reasons why the code review process is critical for developers][8]
9.[Developer code reviews: 4 mistakes to avoid][9]


[1]: https://en.wikipedia.org/wiki/Coding_conventions
[2]: https://webguruz.in/the-significance-of-coding-standards-2/
[3]: https://codegym.cc/groups/posts/387-10-ways-to-improve-your-code-proven-through-personal-experience
[4]: https://www.ommzi.com/coding-standards-why-is-it-important/
[5]: https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/

[6]: https://www.atlassian.com/agile/software-development/code-reviews
[7]:https://blog.codinghorror.com/code-reviews-just-do-it/
[8]:https://www.brightspot.com/products/developer-life-5-reasons-why-the-code-review-process-is-critical-for-developers
[9]:https://www.techrepublic.com/article/developer-code-reviews-4-mistakes-to-avoid/