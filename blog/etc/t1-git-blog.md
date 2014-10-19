Let's talk about VCS,Git and Github

My first tech blog challenge

Oct 11, 2014

Questions:
1.What are the benefits of version control?
2.How does git help you keep track of changes?
3.Why use GitHub to store your code?

My answers for non-tech people

1. Imagine you are drawing something on paper, you  always feel you need to fix or erase some part of your drawing. If you are a graphic designer, you definetely want to keep the original files and layouts of all versions.So you can go back to the beginning, track the process, and recover any mistakes. VCS( version control system) is like this.
There are 3 kinds of VCS; 1.local version control system 2.Centralized version control 3.Distributed version control system. To begin with, local version control system is simply,you just store all the data into your laptop computer. It is simple,convienient,and generally being used by most of people.But it is risky when your local computer is broken and caused a lot of errors and mistakes. You can overwrite new files to old ones by chance.
Another problem is people,or developers want to work together.Local version control system can not help out this cooperation, Centralized Version Control was made. Also simply I can explain that this CVC is two computers with one server. This provides a lot of benefits to develpers,because server master can control the projects and developers are able to check and compare the project each others. However, if the server or hard drive containing a lot of data is broken, it still cause a lot of problems again.
Therefore, distributed version control system (DVCS) is finally invented. Here, user do not have to download recent snapshot. They simply copy the repositories into there local repository. Therefore, when the server is down, still users can work together and even recover the server. you can back-up all the data when checkout.Githup support this DVS to its users.

2. git has three stages. 1) working dir 2) index 3)head. When you track your changes, it is very useful you put tags by typing  "$ git tag". Then you can see the version 1.0.0.  If you have to go back to previous,use "$ git checkout -- <filename>"

3. Before Github made, many or most of companies create their codes and knowledge in private under the name of copyright. When you access Github, you are free to download any code sources and develop entire industry with permission when repos made.Now it becomes the largest online storage space collaborative working space on earth. Of course, it contains a lot of knowledge and information for everyone.FREE!
