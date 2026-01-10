---
date: '2026-01-08T21:37:49+13:00'
draft: false 
title: 'CWES Review: How Pokemon Cards Helped Me Pass the CWES?'
---
## Introduction

### What is CWES
The Certified Web Exploitation Specialist (CWES) is a hands-on web penetration testing certification from HackTheBox.
It consists of two parts:
* The Course Content: Complete HTB's "Web Penetration Tester" Job Role Path first (20 modules, 279 sections, 22 days).
* The Exam: Then take a 7-day hands-on exam where you attack a simulated environment and submit a commercial-grade report.

### Why I took it
Three reasons drove me:
* Practical Skills Over Theory: I wanted a cert that tested real exploitation, not multiple-choice memorisation.
* HTB Labs Prep: My goal was to learn how to tackle web footholds in the more advanced platform HTB Labs, and the CWES path seemed like good preparation.
* 5-year goal?: I set a 5-year goal back in 2021 to focus on cybersecurity after finishing my computer science degree. The CWES was part of that vision.

![goal](/images/2021_goal.png)

## What You Need to Know Before Starting
### Pricing
The exam attempt costs $210 USD, which includes one retake in the same environment.

To unlock the course content which is separated into modules, you need cubes (HackTheBox Academy platform currency). 
My access recommendations:
* For students: Use the student subscription (best value).
* Otherwise: Get cubes via a monthly subscription.
* If pursuing both CJCA and CWES: Consider the annual subscription, which includes both exams and module solutions, which can be very helpful when you get stuck.


### Who Should Take This Exam? (Spoiler: Not Beginners)
In reality, it is a beginner web penetration testing certification, not a beginner IT certification. You are expected to have core IT fundamentals already in place.

Before you can schedule the exam, you must complete HTB’s Penetration Tester Job Role Path. This curriculum includes 480 sections across 28 modules. HTB estimates it takes 43 days, or over 430 hours, of dedicated work.

That large prerequisite explains why only about 2,000 people have passed it in the first four years. So, while HTB describes CWES as easier compared to more advanced certs like CWEE and CPTS, do not mistake that for "entry level."

If you already have:
* Basic Linux fundamentals (command line/shell, file system, permissions)
* Core networking knowledge (IP, TCP/UDP, HTTP, DNS)

…and you are ready for a serious, hands-on challenge, the CWES could be your next step.

If those topics are still new to you, build your basics first. Consider starting with these:

1. **HTB CJCA** (a true entry-level certification)
2. **Run Linux as your daily OS** (I personally suggest Ubuntu for its support)
3. **Complete HTB’s Information Security Foundations path**
4. **Unix Shell basics** https://swcarpentry.github.io/shell-novice/ (Tutorial from Software Carpentry)

This is not the certification to start with if you have limited IT knowledge. I know this firsthand. I tried to get into HackTheBox and the CWES path after high school but before my computer science degree, and it was overwhelming. The hardest part was struggling with the command line and networking concepts while trying to learn cybersecurity concepts. I waited, built my core skills during university, and tackled CWES after graduation.

## My Background & Preparation
Before tackling the CWES, I gained experience across three main areas:

**Hands-on Practice:**
- 59 apprentice-level PortSwigger labs
- CBBH/CWES modules (old and new versions) (3-4 months to complete)
- All module skills assessments (completed 2-3 times each)
- 27 HTB machines (15 non-Starting Point boxes)
- 80% of CPTS path (everything except privilege escalation, documentation/reporting and attacking enterprise networks)
- Created my own step-by-step testing methodologies for each module

**Education & Work:**
- Computer Science bachelor’s degree
- Current junior web developer

In hindsight, this was slightly more preparation than necessary. The CPTS content in particular went beyond what CWES required. The most valuable practice actually came from:
- **Repeating the skills assessments**
- **PortSwigger labs**
- **Practising web footholds on HTB machines**

The CWES course content itself is comprehensive enough if you fully understand it.

## My Exam Timeline: A 4-Day Sprint 
Here’s how my 7-day exam window actually played out:

**Day 1 - Enumeration & Simple Exploitation**  
A 16-hour session got me to 50/100 points. By this point, I had done all the enumeration required, just need to try different vulnerabilities

**Day 2 – Finishing up the exploitation**  
Another 16 hours brought me to 80/100 points. Mental fatigue was setting in; the report clearly demanded clarity, which I didn't have, not just more screen time.

**Day 3 - The Reset**  
I broke from the usual exam advice to use every minute given, although I'd already passed. I completely stepped away, drove around, cleared my head, and indulged in some Pokémon card therapy. Ripping open pack after pack, I got some illustration rares and promos that actually felt more rewarding than any flag. This mental reset was essential; I couldn't bear another minute staring at that screen.

| [![Piplup IR](/images/piplup_ir.jpg)](/images/piplup_ir.jpg) | [![Bulbasaur IR](/images/bulbasaur_ir.jpg)](/images/bulbasaur_ir.jpg) | [![Charizard Promo](/images/charizard_promo.jpg)](/images/charizard_promo.jpg) |
|:---:|:---:|:---:|
| **Piplup IR** | **Bulbasaur IR** | **Charizard Promo** |


**Day 4 - Report**  
With a clear mind, I focused entirely on crafting the 34 page professional report, a process that took about 8-10 hours. I revisited and repeated findings as needed to improve the steps in my proof of concept, and carefully documented the impact and remediation steps. The real challenge wasn’t finding more vulnerabilities; it was clearly communicating what I’d already discovered.


I submitted on **December 27, 2025** and received my passing grade on **January 7, 2026**, a fast, 11-day turnaround from HTB considering the number of public holidays.


## Key Tips & Tricks

- **SysReptor:** Use it to build the report. Leverage the findings template heavily.
- **Attack Host:** Test from your own lab (I use Kali in a VirtualBox VM).
- **Skills Assessments First:** Your top priority. Redo them without help until they're fluent. Go back to module sections if needed—this is the most direct exam prep.
- **PortSwigger Labs Second:** For reinforcing concepts. Complete the apprentice-level labs for practice. Note: Some advanced labs are out of scope.
- **HTB Machines (Optional/Last):** If you have extra time, boxes like GoodGames, Editorial, BountyHunter, Meta, Forge, TwoMillion, and Usage are good for practising initial web footholds.
- **What vulnerabilities?** Ask yourself which vulnerabilities could lead to an in-app flag or reading a txt file. This focuses your exploitation.
- **Avoid Rabbit Holes:** If stuck on a target for 60-90 minutes, switch. Circle back later with fresh eyes.
- **Methodology is King:** Stick to a repeatable process from the course. No need for obscure attacks.
- **Pace Yourself:** Build in short, scheduled breaks (5-10 minutes every hour or two) to maintain mental clarity. Stepping away is often when you think the best.

## Final Verdict
The CWES is an awesome certification. Its hands-on curriculum builds practical skills and then puts them to a real-world test. For anyone ready to learn web penetration testing, it's a highly difficult but rewarding step forward. Just don't forget the power of a strategic break; taking a break for some "Pokémon card therapy" is highly recommended.

![cwes cert](/images/cwes_cert.png)