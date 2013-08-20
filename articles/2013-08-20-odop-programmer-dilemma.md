
##Programmer's dilemma

From: <https://medium.com/i-m-h-o/231d7499a75>

Recently I interviewed tens of candidates for a kernel programmer's position. These candidates are from big, good companies, which are famous for chips or embedded OS/systems. Many of them claimed the have at least 10 years on-job experience on kernel. Their resumes look fairly shiny--all kinds of related projects, buzz words and awards...

But most of them cannot answer a really basic question: **When we call the standard malloc function, what happen in kernel?**

Don't be astonished. When I asked one of the candidate to write a simple LRU cache framework based on glib hash functions, he firstly claimed he had never used glib--that's what I expected--I showd the glib hash api page and explained the APIs to him in detail, then after almost an hour he wrote only a few lines of messy code.

I don't know if the situation is similar in other countries, but in China, or more specifically, in Beijing, this is reality. "Senior" programmers who worked for big, famous foreign companies for years cannot justify themselves in simple, fundamental problems.

###Why did this happen?

The more I think about it, the more I believe it is caused not only by themselves but also by the companies they worked for. These companies usually provide stable stack of code, which has no significant changes for years. The technologies around the code wraps up people's skills, so that they just need to follow the existing path, rather than to be creative. If you happened to work for such kind of code for a long period and did not reach to the outer world a lot, one day you will find yourself to be in a pathetic position--they called you "**EXPERT**" inside the team or company, yet you cannot find an equally good job in the market unfortunately.

This is so called "**Expert Trap**". From day to day, we programmers dreamed of being an expert inside the team/company; however, when that day really comes we trapped ourselves. The more we dig into existing code, the deeper we trapped into it. We gradually lose our ability to write complete projects from scratch, because the existing code is so stable (so big/so profitable). What's the worse, if our major work is just to maintain the existing code with little feature development, after a while, no matter how much code we've read and studies, we will find we cannot write code--even if the problem is as simple as a graduate school assignment. This is the programmer's dilemma: **We make our living by coding, but the big companies who fed us tend to destroy our ability to make a living.**

-----

###How to get away from this dilemma?

For personal --

First of all, **Do your own personal projects**. You need to "sharpen your saw" continuously. If the job itself cannot help you do so, pick up the problems you want to concur and conquer it in your personal time. By doing so, most likely you will learn new things. If you publish your personal projects, say in github, you may get chances to know people who may pull you away from your existing position.

**Do not stay in same team for more than two years.** Force yourself to move around, even if in the same organization, same company, you will face new challenges and new technologies. Try to do job interviews every 18 months. You don't need to change your job, but you can see what does the market require and how you fit into it.

For team/company--

**Give pressures and challenges to the employees.** Rotate the jobs, let the "experts" have chance to broaden their skills. Start new projects, feed the warriors with battles.

**Hold hackathon periodically.** This will help to build a culture that embrace innovation and creation. People will be motivated by their peers--"gee, that bustard can write such a beautiful framework for 24 hours, I gotta work hard".

-----
FURTHER READING 

[**The benefit of personal projects** -- Take the time to build something amazing](https://medium.com/what-i-learned-building/d875dea01f60)

[**How often is malloc still used? Is it still useful these days?**--Answer 1 of 1: We use it in our development all the time! We're not doing scientific computing but are doing software development on comp...](https://www.quora.com/Computational-Science-Scientific-Computing/How-often-is-malloc-still-used-Is-it-still-useful-these-days)

[**Peter Principle** -- The Peter Principle is a proposition that states that the members of an organization where promotion is based on achievement, success, and merit will eventually be promoted beyond their level of ability. The principle is commonly phrased, "Employees tend to rise to their level of incompetence."](http://en.wikipedia.org/wiki/Peter_Principle)

