<img src="https://github.com/SlayksWood/SlayksWood/blob/main/assets/Bender_noback.png" width="155" align="right">

## :wave: Hi, My name is Kirill Slyshkov! 

My primary specialization at the moment is as a QA Engineer.

## :man_technologist: About Me
I've been passionate about video games since childhood, with some of my favorites being Warcraft, ECO, Divinity, and the Assassin’s Creed series. My love for gaming began when my brother and I got a first console, where I played Goal 3, Battle City, and Battletoads. As I grew older, I started visiting PC gaming clubs and became fascinated with Warcraft III and Counter-Strike, though Warcraft III made the biggest impression, especially with its custom maps and multiplayer. Later, I delved into MMORPGs, starting with Ragnarok and eventually becoming deeply involved in World of Warcraft.

In 2018, I shifted my career into game development. Initially, I began learning programming, but soon realized that testing and game design were my true interests. This led to my role at Strange Loop Games, where I worked on the development of ECO for 5.5 years. I spent the first three years as a QA Engineer, responsible for testing new game features, conducting regression tests, and identifying bugs. I later transitioned to the role of QA Lead, managing a team of four QA engineers.

I'm looking forward to continue my career in game development, working on exciting projects that challenge what games can be. I enjoy collaborating with talented people who care about creating fun and engaging gameplay, where I can share my ideas and skills to help make great experiences for players.

## :bug: Some examples of my various bug reports.
### My job at Strange Loop Games:

Unfortunately, since we moved to another bug reporting system, I can't link newly created bug reports. However, I'd like to add links to some of my old bug reports and suggestions that I created when I worked as a QA Engineer. You can also see all my bug reports [created on GitHub](https://github.com/StrangeLoopGames/EcoIssues/issues/created_by/SlayksWood).

- [Chunk loading problem](https://github.com/StrangeLoopGames/EcoIssues/issues/22390), [Crash with "objects in the world" tooltip](https://github.com/StrangeLoopGames/EcoIssues/issues/22233) - Bugs were created with conditions that allow for easy reproduction by the developer.
- [Camera glitches if you press ESC in the beginning of Meteor Tutorial](https://github.com/StrangeLoopGames/EcoIssues/issues/21865), [Hint overlaps when hold selecting form type more then 1 sec](https://github.com/StrangeLoopGames/EcoIssues/issues/21860) - Adding screenshots, GIF or videos to the issues.
- [NullReferenceException with reconnect to server](https://github.com/StrangeLoopGames/EcoIssues/issues/22228), [Caught exception on Player while in NetObject ReceiveInitialState. BSON](https://github.com/StrangeLoopGames/EcoIssues/issues/22227), [A few NRE during disconect from server on avatar](https://github.com/StrangeLoopGames/EcoIssues/issues/21967) - Constant monitoring of errors in the log to ensure that the log file remains clean and is not spammed with errors that hinder tracking other errors in the log file.
- [Can break hammer controller](https://github.com/StrangeLoopGames/EcoIssues/issues/22255), [Stuck in Tab mode after editing a list and cancel selection](https://github.com/StrangeLoopGames/EcoIssues/issues/20566), [Receive Permission contract crash](https://github.com/StrangeLoopGames/EcoIssues/issues/19977) - Adding errors from log files so that the developer does not waste time investigating logs.
- [Eco server take a lot of CPU](https://github.com/StrangeLoopGames/EcoIssues/issues/22314)- Monitor performance degradation. Also for that goal I created a special world to compare the different game versions with the same condition.
- [Minimap navigation QOL](https://github.com/StrangeLoopGames/EcoIssues/issues/20507), [Improvement for Displaying markers on the minimap ](https://github.com/StrangeLoopGames/EcoIssues/issues/20058), [Extending the functionality of creating currencies](https://github.com/StrangeLoopGames/EcoSuggestions/issues/874) - Constant feedback to improve UI/UX, add some quality-of-life enhancements for users, and suggest feature improvements.

![Kirill's GitHub stats](https://github-readme-stats.vercel.app/api?username=SlayksWood&theme=dark&show_icons=true)

## :notebook_with_decorative_cover: Test Plans, suites, cases.
### My job at Strange Loop Games:

I can't show you many of my test cases and checklists because they are in private repositories. However, I can provide
1. [A small part of our Economics Test Plan as an example, which I used for experimentation](https://docs.google.com/spreadsheets/d/1sRE2hZ3cfN8LnyIdNWyqO7HQ-uH18adAcLPKiSak0Y0/edit?usp=sharing). 

When I joined the team, there wasn't a proper test plan. We only had a small checklist of about 60-80 rows in a Google Sheet. It was a small checklist for such a large game. My colleague, who started working with me at the same time, and I divided the game into different parts and began improving our test plan by adding more cases, including negative test cases, since the original checklist mostly covered only positive ones. After some time, our test plan became so large that working with the Google Sheet caused it to freeze. The document I provided above is my first attempt to split that large Google Sheet into six documents based on the game's features. This document is for testing the Economic part (which is actually a small portion of the final economy document). As you can see, we have a detailed test plan for Contracts, Work Parties, and Store, while Economy Viewer, Exchange, and Mint are not as detailed yet since they haven't been redone. Also, because this is a copy, the links to the game versions are broken. In the official document, everything was properly set up.

2. [A couple of screenshots of our Test Plans, suites, and cases after we migrated them to TestLodge](https://mixolydian-skipjack-992.notion.site/A-couple-of-Test-Lodge-examples-119f83a3786e80d791cde14da75fe8b1).

When I was appointed as QA Lead at the company, things were going quite well. The team was expanding, and including myself, there were 6 QA members. However, one of them worked separately with their own team, focusing on the game’s website and wasn’t directly reporting to me. Two of the testers were newcomers, and I realized that our checklists in Google Sheets were not detailed enough for them. Some of the more detailed ones were good, but still not detailed enough for training purposes. After discussing this with our Producer, CTO and CEO, I received approval to implement a Test Case Management Tool. I conducted research to find the most suitable one for us. I looked into all the popular tools: TestRail, Qase, and TestIt. But the final decision came down to TestLodge and Sleekplan, as our budget was limited. Ultimately, we chose TestLodge because it could be integrated with ClickUp.

It was quite an interesting time, where I gained a lot of experience, including learning from my mistakes. At the same time, the migration from Google Sheets to TestLodge was made easier by my prior educational background as a Metalworking Process Engineer, which helped me create detailed test cases.

## :hammer_and_wrench: Tools Experience
### Project Tracking Software:
<div>
    <a href="https://clickup.com/teams/software" >
        <img src="https://app-cdn.clickup.com/clickup-symbol_color.6c3fc778987344003164b4b4c9826eb8.svg" title="ClickUp" alt="ClickUp" height="40"/>&nbsp
    </a>
    <a href="https://www.zenhub.com/extension">
    <img src="https://app.zenhub.com/dist/images/zenhub-logo-icon.533659dc14e092e17bd2.svg" title="Zenhub" alt="Zenhub" height="40"/>
    </a>
</div>

### Test Documentation:
<div>
    <a href="https://www.testlodge.com/">
        <img src="https://www.svgrepo.com/show/354448/testlodge.svg" title="TestLodge" alt="TestLodge" height="40"/>
    </a>
    <a href="https://www.figma.com/">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" title="Figma" alt="Figma" height="40"/>
    </a>
</div>

### Web Application Testing: 
<div>
    <a href="https://www.postman.com/">
        <img src="https://seeklogo.com/images/P/postman-logo-0087CA0D15-seeklogo.com.png" title="Postman" alt="Postman" height="40"/>&nbsp
    </a>
    <a href="https://developer.chrome.com/docs/devtools">
    <img src="https://d33wubrfki0l68.cloudfront.net/38b5c953a4667366685d55db55d057c86db1fc54/a0fdc/static/acae6b24d940347661ca901ea07f47c1/chrome-dev-logo-icon.png" title="Chrome DevTools" alt="Chrome DevTools" height="40"/>
    </a>
</div>

### Working with Code:
<div>
    <a href="https://git-scm.com/">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title="Git" alt="Git" height="40"/>&nbsp
    </a>
    <a href="https://www.jenkins.io/">
    <img src="https://contributors.jenkins.io/jenkins.png" title="Jenkins" alt="Jenkins" height="40"/>&nbsp
    </a>
    <a href="https://code.visualstudio.com/">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" title="VScode" alt="VScode" height="40"/>&nbsp
    </a>
    <a href="https://visualstudio.microsoft.com/vs/">
    <img src="https://visualstudio.microsoft.com/wp-content/uploads/2022/11/vs-icon.svg" title="Visual Studio" alt="Visual Studio" height="40"/>&nbsp
    </a>
    <a href="https://www.jetbrains.com/rider/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/JetBrains_Rider_Icon.svg/512px-JetBrains_Rider_Icon.svg.png" title="Rider" alt="Rider" height="40"/>
    </a>
</div>

### Game Development:
<div>
    <a href="https://unity.com/">
        <img src="https://www.svgrepo.com/show/342325/unity.svg" title="Unity" alt="Unity" height="40"/>
    </a>
</div>

## :globe_with_meridians: Connect with me:
<a href="https://t.me/SlayksWood" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Telegram-Slaykswood-purple?logo=telegram&logoColor=25a3e2&color=25a3e2&style=flat-square" /></a>
<a href="mailto:kirill.slyshkov@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Gmail-kirill.slyshkov@gmail.com-purple?logo=Gmail&logoColor=red&color=red&style=flat-square" /></a>
<a href="https://www.linkedin.com/in/kirill-slyshkov/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-Kirill%20Slyshkov-purple?logo=linkedin&logoColor=blue&color=blue&style=flat-square" /></a>

<a href="https://steamcommunity.com/id/slayks/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Steam-Slayks-purple?logo=steam&logoColor=black&color=black&style=flat-square" /></a>
<a href="https://discordapp.com/users/233925988763959296/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Discrod-Slaykswood-gray?labelColor=7087e4&logo=discord&logoColor=white&&style=flat-square" /></a>
<a href="https://twitch.tv/slayks" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Twitch-Slayks-purple?labelColor=6441a5&logo=twitch&logoColor=white&&style=flat-square" /></a>
