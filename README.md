## Git та GitHub

After completing first 2 weeks of the course **Introduction to Git and GitHub**, `I've wrapped my head around all these new concepts`.

Learning at **LearnGitBranching** was like playing a game where you have to pass levels. I liked the visualization of what happens behind the scenes of the command line.
I am going to apply the acquired skills to store my code's history in Git and collaborate with others in GitHub.
![Screens](0.git/2022-08-07_10-47-42.png "Basics")
![Screens](0.git/2022-08-07_10-51-06.png "Remote repositories")


## Linux CLI, and HTTP
Linux Survival course provides all the fundamentals of Linux. I am familiar with basic Linux commands. 
New ones were: `man`, `ps` (with its option `aux`), `grep` and `|` symbol, which sends output to another program.
`kill` command, which tells a process to die gracefully, and its option `-9`, which tells a process to die immediately, suprised me.
The course helped me to understand important aspects of working with Linux, which I will use in the future.
![Screens](1.task_linux_cli/01.png "Quiz Number 1")
![Screens](1.task_linux_cli/02.png "Quiz Number 2")
![Screens](1.task_linux_cli/03.png "Quiz Number 3")
![Screens](1.task_linux_cli/04.png "Quiz Number 4")

**HTTP articles** [(1)](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177?ec_unit=translation-info-language "HTTP: The Protocol Every Web Developer Must Know  - Part 1") and [(2)](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155?ec_unit=translation-info-language "HTTP: The Protocol Every Web Developer Must Know - Part 2") expanded my knowledge of the HTTP protocol.
 

## Git Collaboration
  * 3 and 4 modules of **Introduction to Git and GitHub** explain me how to work with remotes, tackle conflicts by utilizing the pull-merge-push workflow. Also, how the typical workflow of a pull request looks like on GitHub and what the code review workflow looks like. All this collaboration tools will definitely help improve the quality of my code and keep my code better trackable in the future.

[week 3](2.task_git_collaboration/git_colllab(3).png)

[week 4](2.task_git_collaboration/git_colllab(4).png)

  * **main** and **remote** levels at **LearnGitBranching** help me to be more comfortable with fetching and merging, pulling and pushing. I've learned all about git fetch, pull and push arguments and colon refspecs `(<source>:<destination>)`.

[main](2.task_git_collaboration/2022-08-16_10-59-06.png)
 
[remote](2.task_git_collaboration/2022-08-16_10-53-45.png)


## Intro to HTML and CSS
  * After listening modules 1 and 2 of the course **HTML, CSS, and Javascript for Web Developers** on Coursera I've apdated knowledge of HTML5 basics, like valid document structure, which elements can be included inside other elements and which can not, the meaning and usefulness of HTML5 semantic tags(semantic html element - is an element that implies some meaning to the content). 3 characters that should always be escaped in html: `<, >, & `, use instead: `&lt; &gt; &amp;`. `&nbsp; (non-breaking space)` - a space character that prevents an automatic line break at its position. And also, some advanced CSS3 concepts like floating and CSS rule conflict resolution, relative and absolute elements, the 'box model', background property. 
  
[week 1](task_html_css_intro/html-1.png)
 
[week 2](task_html_css_intro/html-2.png)

  * [**Codecademy courses.**](https://www.codecademy.com/learn) Some new and important things for me, i'll just put them here:
    - Remember to always add two spaces of indentation when you nest elements inside of `<div>`s for better readability.
    - The attribute selector can be used to target HTML elements that already contain attributes. The most basic syntax is an attribute surrounded by square brackets.
`[href]{color: magenta;}`. `type[attribute*=value]` this code selects an element where the attribute contains any 
instance of the specified value. For example: `<img src='/images/seasons/cold/winter.jpg'> => img[src*='winter'] { height: 50px;}`
    - IDs are the most specific selector in CSS, followed by classes, and finally, type.
    - The **!important** flag will override any style, however it should almost never be used, as it is extremely difficult to override.
    - Vertical margins collapse, so the space between vertically adjacent elements is equal to the larger margin.
    - There are four ways to represent color in CSS: 
      - Named colors—there are more than 140 named colors, which you can review here. 
      - Hexadecimal or hex colors. Hexadecimal is a number system that has sixteen digits, 0 to 9 followed by “A” to “F”. Hex values always begin with # and specify values of red, blue, and green using hexadecimal numbers such as #23F41A. Six-digit hex values with duplicate values for each RGB value can be shorted to three digits.
      - RGB colors use the rgb() syntax with one value for red, one value for blue and one value for green. RGB values range from 0 to 255 and look like this: rgb(7, 210, 50). 
      - HSL. HSL stands for hue (the color itself), saturation (the intensity of the color), and lightness (how light or dark a color is). Hue ranges from 0 to 360 and saturation and lightness are both represented as percentages like this: hsl(200, 20%, 50%). You can add opacity to color in RGB and HSL by adding a fourth value, a, which is represented as a percentage.

[Screen](task_html_css_intro/LearnHTML-CSS.png)
















