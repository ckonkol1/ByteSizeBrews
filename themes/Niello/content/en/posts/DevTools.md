---
title: "My Daily Dev Stack: Tools I Wouldn't Want to Code Without"
categories: ["Technical Deep Dive", "Showcase"]
featuredImage: "image/posts/devtools/devtools.png"

date: 2025-09-15T09:15:00+08:00
draft: false
---

<div align="center">
  <img src="/image/posts/devtools/devtools.png" alt="Yeti Developer" width="55%" />
</div>

<br/>

As a software engineer, there are countless tools available to boost productivity and make development life easier. As an experienced developer, I wanted to share the tools I use daily and explain why they've earned a permanent spot in my workflow. Keep in mind that tool choice is highly personal. What works for my coding style and needs might differ from yours.

*Note: No affiliate links or sponsorships here—just sharing tools that actually make my coding life better. All links go straight to the official product sites.*

## 📓 Code Editor (IDE)

---
<br/>

<img src="/image/posts/devtools/visualstudio.jpg" alt="Visual Studio" style="float:right;margin-left:10px; margin-top:20px; margin-bottom:5px;" width="35%"/>

My programming language of choice is C# and I primarily use .NET as my platform. Because of that, my IDE of choice is [Visual Studio 2022](https://visualstudio.microsoft.com/vs/). Like any IDE, it has some issues (looking at you, performance), but since this is what most companies I work for use, I stick with it in my personal projects too for consistency. For those who can't stand Visual Studio, definitely give [JetBrains Rider](https://www.jetbrains.com/rider/) or [Visual Studio Code](https://code.visualstudio.com/) a try. I also use VS Code for any non-C# development work. All of these have free options—either community editions or free licenses for personal projects.

## 🤖 AI Coding Assistants
---
<br/>

<img src="/image/posts/devtools/github-copilot.jpg" alt="Github Copilot" style="float:right;margin-left:10px; margin-top:20px; margin-bottom:5px;" width="35%"/>

There are many AI coding assistants available, including Claude Code, Cursor, and [GitHub Copilot](https://github.com/features/copilot/), each with their own pros and cons. My assistant of choice is GitHub Copilot. I chose it primarily because it has excellent plugins for both Visual Studio and Visual Studio Code, and the integration feels seamless in both IDEs. I also expect strong future support since Microsoft owns both GitHub and these IDEs. My favorite feature is the GitHub pull request integration. Being able to add Copilot as a reviewer to get automated code review feedback is incredibly useful. While there's a free plan offering 50 chat conversations per month, I upgraded to the Pro plan at $10/month for unlimited conversations. I found myself burning through those 50 chats pretty quickly! Check out [GitHub Copilot's current pricing plans](https://github.com/features/copilot/plans) for more options.

<br/>

## 🐊 Code Analysis and Refactoring

---
<br/>
<img src="/image/posts/devtools/resharper.png" alt="ReSharper" style="float:right;margin-left:10px; margin-top:20px; margin-bottom:5px;" width="15%"/>

I use [ReSharper from JetBrains](https://www.jetbrains.com/resharper/) for my C# development. ReSharper is a static analysis and refactoring tool that focuses on code quality and developer productivity by enforcing coding standards and helping maintain clean architecture. I rely on it to ensure my code follows consistent standards, maintain proper formatting, eliminate code smells, catch potential bugs I might have missed, and assist with complex refactoring tasks.

<br/>

## 🔥 Git GUI Client 
---
<br/>
<img src="/image/posts/devtools/gitkraken.png" alt="GitKraken" style="float:right;margin-left:10px; margin-top:20px; margin-bottom:5px;" width="25%"/>

 Hot take for a second... I really don't care for memorizing git commands or having a deep understanding of every git intricacy. I don't find value in remembering all the complexities of the tool. I prefer to rely on my IDE and understand just the basics like merge, rebase, etc. Early in my career, I created a few issues with ClearCase that affected entire departments, and I've never gotten over it. I'll never forget the look of fear on people's faces every time I walked into that team room because of the impending disaster I might have created.
 <br/>
 <br/>
 Happily, times have changed and there are great tools to help prevent and mitigate disasters when they happen. Because of that, I have a great love for GitKraken. GitKraken provides a beautiful visual interface that makes git operations intuitive and safe. I love the interactive rebase feature that lets me clean up commit history without fear, the visual merge conflict resolution that makes resolving conflicts actually manageable, and the commit graph that shows exactly what's happening with branches and merges. The undo button has saved me more times than I care to admit—it can reverse almost any git operation if you mess something up. Plus, it integrates seamlessly with GitHub, GitLab, and other git hosting services, making pull requests and issues easy to manage right from the interface.

## 🚒 Search Engine

---
<br/>
<img src="/image/posts/devtools/kagi.png" alt="Kagi" style="float:right;margin-left:10px; margin-top:15px; margin-bottom:5px;" width="25%"/>

I understand search engines are free, but what you're actually paying for is advertising. Scrolling through ads and sponsored sites to find real results is irritating so I made the switch to [Kagi](https://kagi.com/). Why use should you use Kagi and [make the switch](https://help.kagi.com/kagi/why-kagi/why-pay-for-search.html) from a free search engine? Kagi focuses on user-centric search rather than ad-centric search, anonymizes user data, and has zero search telemetry. The search results are clean, relevant, and actually prioritize the best content instead of whoever paid the most for ad placement. I pay for the Starter package at $5/month and 300 searches, but other [pricing plans](https://help.kagi.com/kagi/plans/plan-types.html) are available.

## 💻 Console Emulator

---
<br/>
<img src="/image/posts/devtools/cmder.png" alt="Cmder" style="float:right;margin-left:10px; margin-top:18px; margin-bottom:5px;" width="20%"/>

I have spent a ton of time typing commands in a command line and I have found nothing that compares to [Cmder](https://cmder.app/). What makes Cmder incredible is its tabbed interface. I can have multiple command sessions open simultaneously without cluttering my desktop with terminal windows. The copy-paste functionality actually works properly (unlike the default Windows command prompt), and the text selection is intuitive. Cmder comes with Git for Windows pre-installed, so I get a proper Unix-like environment on Windows with commands like ls, grep, and ssh working out of the box. The customizable aliases save me tons of time. I can create shortcuts for complex commands I use frequently and the search functionality lets me quickly find previous commands in my history. Once you use Cmder's smooth, modern terminal experience, going back to cmd.exe feels like using a typewriter.

## ⭐ Summary
---
<br/>

Your development environment is deeply personal—what works for me might not work for you, and that's perfectly fine. The tools I've shared here aren't necessarily the "best" tools available, but they're the ones that have consistently made my coding life better, more productive, and frankly, more enjoyable.
<br/>

The key is finding tools that complement your workflow rather than fighting against it. Don't be afraid to experiment with alternatives, especially when you find yourself frustrated with your current setup. That frustration is usually a sign that there's a better way to do things.
<br/>

Remember, these tools are investments in your productivity and sanity as a developer. While some have costs associated with them, the time they save and headaches they prevent make them worthwhile investments in your career.

Happy coding, and may your tools serve you well!