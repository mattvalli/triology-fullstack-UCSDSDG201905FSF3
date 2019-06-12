# Week 1 - Day 2
## Quick Review
### Computer Science History
#### Why are there totally different Command Lines?
It's actually quite simple and you already know all about it, even if you didn't know you did!

Ever since the birth of the Personal Computer, companies have been at war to dominate the market and lock users into their technologies.

IBM was really the first power house of Computing, but this was long before computers entered the households of everyday people. Back then, computers were giant...the size of whole rooms and even floors of big business. But this all changed in the late 1980s.

Advances in technology made it possible to pack all the required hardware into a 'small' device which was coined the Personal Computer or PC for short.

Many other companies saw an opertunity become society's next "can't live without" product.

You may know some of these companies because a few major ones are still around, such as Texas Instruments (but we know what happened to them, they lossed the war over PC development...instead, they are a rock-star calculator and electronic instrument player).

If we look around the classroom, we can see that we are surrounded by the last two Superpowers left standing...Microsoft and Apple.

They both emerged as victors, not because their hardware was any better than the rest. It was the development of their Operating Systems or OS for short.

At core of every OS is a set of fireware that manages the processing and flow of every single computation. This core is referred to as the Kernel.

The first software developed in any Operating System project is the Command Line. It functions as a means to interact with the kernel directly in a language humans can understand, otherwise computers would be useless to anyone who doesn't know how to speak binary fluently.

Long story, short. The reason that there are different Command Lines are because there are different Operating Systems.
```
Windows Command Lines: Command Prompt (DOS) -> evolution -> PowerShell (a more linux like set of commands)
Apple Command Line: Terminal (Macs are built on a variant of the Unix kernel, specifically a proprietary version of UnixBSD known as the MachKernel)
Linux Command Line: Command Line (They didn't brand their version of the Command Line like Microsoft or Apple did)
```

#### Why are we learning GitBash/Terminal?
GitBash is a Virtual Command Line so that Linux/Unix users don't have to learn an entirely different command line just because they're job provided them a Windows machine over an Apple or Linux machine.

What Virtual Command Line means is that you can use commands from an OS that is not the core OS of the machine you are working on. Basically, it translates Linux commands to Windows commands.

GitBash (Linux) and Mac's Terminal (UnixBSD) operate using an almost equal interface of commands. For example, changing directories is the same command in both of these Operating Systems:
```
C&#35; Commands are essentially the same between Unix/Linux (There are some minor differences to be explained)
C&#35; Change directory
cd /path/to/where/I/want/to/go

C&#35; List contents of directory
ls -lah

C&#35; Move file to project
mv my-website.html portfolio/my-website.html

C&#35; Move into my portfolio directory
cd portfolio

C&#35; Copy file
cp my-website.html website.html

C&#35; Relized I should follow HTML standards for the main page name, so I'll rename it
mv website.html index.html

C&#35; Delete the old file, becuase I don't really need two copies
rm my-website.html

C&#35; Checkout the website in my browser by openning it
open index.html
```

#### Why are Unix and Linux so similar?
Unix was built by Bell Laboratories, which later changed its name to Pacific Bell. At the time, Federal Laws prohibitted companies to have monopolies on certain industries. Since Bell Labs essentially owned the Telephone network coverage across the entirety of the United States, they could not package Unix as a product for profit...so they gave it away.

Since it was free, Universities adopted Unix as the primary Operating Systems for their internal computer systems. This influenced curriculum at these Universities and as the primary educators for Electrical and Software Engineers it had a major impact on the future of computing.

Pretty much anyone who went to College to learn the skills for a career in these fields learned Unix.

Eventually, Bell Labs sold off some of its telephone networks. This lifted the Federal Regulations preventing them from selling Unix...and since they like money, they started to charge for the software licensing.

Enter Linus Torvalds, a Finnish student studying Systems Engineering. He liked Unix, but didn't want to pay for it. He had the skills to build Operating System, so he thought why not re-build Unix but with different code under the hood.

It was one of the first Open-Sourced software projects that gained traction and was licensed for free. After a little time, thousands of Engineers accross the world were contributing to building up the OS so they too wouldn't have to pay for their Operating System...and that's how Linux was born.

#### Why use Linux/Unix though?
The INTERNET!

Microsoft machines were expensive during the development of the web and Window Licenses were also pricey for the ratpack of digital pioneers that were laying down the foundation for what the internet would eventually evolve to become...a place were no one is deprived of cat videos and amazon glutany!

Because of this, the lion's share of servers hosting websites are Linux-based machines...since we all want a great opertunity for work after the completion of this program, UCSD and Triology have selected to teach you Linux. They would be putting you at a disadvantage to choose any other OS and Command Line for developing course curriculum for Fullstack Web Development.

### The Command Line

* [What is Git?](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics)
* [What does 'stage' mean in git?](https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git)
* [Git Cheatsheet](https://github.com/mattvalli/triology-fullstack-UCSDSDG201905FSF3/blob/master/week-01/day-01/Activities/01-ConsoleCommands/bash-terminal-commands-cheatshet.md)

#### What are our Command Line Options	
##### PC
* [Command Prompt (Windows original version of DOS)](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)
* [PowerShell (Windows effort to be more Unix/Linux like)](https://docs.microsoft.com/en-us/powershell/scripting/getting-started/getting-started-with-windows-powershell?view=powershell-6)
* [GitBash (Virtual Machine - Linux bash shell)](https://www.atlassian.com/git/tutorials/git-bash)

##### Mac
* [Terminal (bash shell)](https://support.apple.com/guide/terminal/welcome/mac)

##### Why Fullstack Developers need to feel comfortable in the Command Line
* Git
* Accessing Remote Machines over the Internet
* Accessing Virtual Machines running on your local environment
* Ethical Hacking
* Just to be a BOSS!

#### Instructor Bio
I'm going to demo how these tools relate to my work as a professional Fullstack Engineer (MERN Stack) working on a customer-facing product under AGILE processes.

### HTML
	* Language of Web Pages
	* [HTML5 Reference](https://www.w3schools.com/html/default.asp)
	* [HTML5 Elements](https://www.w3schools.com/html/html_elements.asp)
#### The 3 REQUIRED elements/tag to every page

##### HTML
```
<!DOCTYPE html>
<html>
  <head>
    <!-- metadata here -->
  </head>
  <body>
    <!-- visual content here -->
  </body>
</html>
```

##### HTML5
```
<html>
  <head>
    <!-- metadata here -->
  </head>
  <body>
    <!-- visual content here -->
  </body>
</html>
```

NOTE: You can also provide a language for your HTML page for better SEO
```
<html lang="en">
  <!-- You're a pro now...what goes here? -->
</html>
```

## Today's Objectives
### Introduce Git
* [What is Git?](https://www.atlassian.com/git/tutorials/what-is-git)
  * It's used for [Version Control](https://www.atlassian.com/git/tutorials/what-is-version-control)
* High-level Overview of how Git Works
* How is Git related to [GitHub](https://github.com/login)

### Explore Git by using it together
* [Git Cheatsheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
* Create a Repository on our [Github Account](https://github.com/login)
* Clone the Repository to our local machine
* Modify the Project
* Stage and Commit our changes
* Push our changes up to our GitHub Account
* Revel in our AWESOMENESS...and share it with the world

### Dive deeper into HTML
* HTML Version
  * HTML
  * HTML5
* Deconstruct HTML Elements
  * [Syntax](https://www.w3schools.com/html/html_elements.asp)
  * Nesting
  * [Attributes](https://www.w3schools.com/html/html_attributes.asp)
* [Element/Tag Types](https://www.w3schools.com/tags/default.asp)
  * pairs
  * self-closing
* [What HTML Elements/Tags are available to us?]()

### Applying your new HTML skills through an Activity
[HTML Activity - Student Bio](https://github.com/mattvalli/triology-fullstack-UCSDSDG201905FSF3/tree/master/week-01/day-02/Activities/04-HTML_Git)

### Introduce CSS
* [What is CSS?](https://www.w3schools.com/css/css_intro.asp)
* How do write CSS?
  * [Syntax](https://www.w3schools.com/css/css_syntax.asp)
  * [Selectors](https://www.w3schools.com/css/css_syntax.asp)
    * Elements/Tags
    * IDs
    * Classes
* [How do we apply CSS?](https://www.w3schools.com/css/css_howto.asp)
  * Inline
  * Script tag
  * External Stylesheets
* [What tools can we use to help debug CSS?](https://developers.google.com/web/tools/chrome-devtools/)
#### Example
[HTML/CSS Example](https://github.com/mattvalli/triology-fullstack-UCSDSDG201905FSF3/blob/master/week-01/day-02/Activities/05-BasicCSS/quick-example-internal-css.html)

### Applying CSS to our HTML through an Activity
[CSS Activity - CSS Layout](https://github.com/mattvalli/triology-fullstack-UCSDSDG201905FSF3/tree/master/week-01/day-02/Activities/06-HTML_CSS_Layout)
