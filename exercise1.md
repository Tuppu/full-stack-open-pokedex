Experience of C#

CI follows the basic project phases in way of agile continous and iterative process. Automation of this process avoid most mistakes and errors, when process gets complicated by multiple programmers and multiple paralled tasks.

Linting helps keep the source code equally formatted. Formatting the source code later would make whole reposition to impossible merge with out solving style conflicts for the other programmers, so there should be a style guide beginning programming with codebase of multiple programmers to follow for. Small nyans like a line endling would be something that must be decided to have same with a different operating systems to avoid merge conflicts later. There are different recommendations for the correct line endling, but in the real world sometimes it must be adapted to follow colleques rule agains own style. (EditorConfig)

Testing for programmers is like a red muleta for bulls. Programmers like to test features that works, but it's not an effective way to do testing. The main goal of testing is to find bugs and ways improve the program. Progammers are blind for they own bugs, so it's very important if possible that the test person of the code is someone else that the person who wrote the code. If there is atleast two programmers, then they would test each other code. Munual test must be made after code is wrote, but autmatic tests can be wrote before the code. (dotnet test)

Building the program is something that programmers don't need to think about often, it's autonomous process made by IDE or some other tools. Programmers just write a command or click a button and everything works fine, the software works on the progammer's computer perfectly. Think changes when the program must be delivered. (yaml, Azure Pipeline / Azure devops)
(old school in Finnish:
https://tuppu.fi/wp-content/uploads/2024/12/oldSchoolCpp.jpg)

Azure Pipelines and Azure Devlopes are used for C# commonly. I don't think there is reasonable self-hosted servers for a most cases and organizations with Azure. Also other tools like Octodeply, GitHub actions and Nuke.build are used.