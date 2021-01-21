---

title: PastEvents
displaytext: Past Events
layout: null
tab: true
order: 2
tags: Denver
altfooter: true

---

## Past Events
<hr>
===================================================================================
**2021 January: [Download presentation](zz_presentations_2021_01.pdf)**

**Archetypal Secure Application Design Pattern: The Next Evolution** <br>
>This is the next evolution of the App Sec Effort to move security left
through repeatable secure software design patterns. Security
responsibilities and controls are distributed across various levels of
(IDE-consumable!) UML diagrams; they become Patterns as Code, Architecture
as Code, Config as Code. Now the diagrams are actually useful to the
builders and designers, so no effort is wasted, producing true agility
through treating software archetypes as repeatable, solvable problems with
appropriate security baked in, just in time, rather than bolted on as an
afterthought. Bigger, better, and with real examples. Help us improve
patterns to improve software security.

>**Speaker: Joe Gerber**
Joe Gerber is a Secure Software Architect and Secure Software Design
practice lead with 10+ years of secure software design experience. He is
also a recovering senior web developer and former embedded systems
programmer. He deeply desires to use patterns to truly make secure software development a repeatable phenomenon.

>He has previously presented at:
- RMISC 2018
- SnowFroc 2018
- Three OWASP Chapter meetings
- Local community IT professional groups
- Lead App Sec presenter at quarterly classes held by my employer

>He was a volunteer at Defcon’s inaugural App Sec Village


===================================================================================
**2020 October: [Download presentation](zz_presentations_2020_10.pdf)**

**Exploring Impostor Syndrome and Pluralistic Ignorance in Pentesting** <br>
>“What if they find out I’m not as smart as they think I am?”
“If I can do it, anyone can do it.”
“I can’t pull this off? Who am I kidding?”
“Lucky me, I was in the right place at the right time.”

>Have you ever asked yourself these types of questions? Studies suggest that more than 70% of people experience the impostor syndrome phenomenon at some point in their career, no matter what field they are in. Impostor syndrome combined with pluralistic ignorance can be catastrophic. Pluralistic ignorance can be described as “no one believes, but everyone thinks that everyone else believes”. Together it can make you feel like you are constantly privately rejecting the norm, but publicly go along with it. You have mistakenly assumed everyone else accepts it because they are smarter/faster/better than you are.

>This talk will help you identify those thought patterns that undermine your ability to feel as capable as others know you are and take ownership of your well deserved success. Being proactive, asking the right questions, and once you know there is a problem, start working on the solution.

===================================================================================
**2020 September: [Download presentation](zz_presentations_2020_09.pdf)**

**Account Takeover: Data Findings, Popular Tools, and Prevalent Actors** <br>
>In our latest account takeover (ATO) findings, we have observed a significant increase in credentials listed on the deep and dark web (15 billion and counting), tools that enable account takeover, and account takeover service advertisements on criminal marketplaces. This presentation highlights the sheer volume of account takeover, how ATO can impact your organization, and mitigation recommendations to keep your credentials safe.

>By attending this session, you will take away:
• The size of the ATO problem
• Tools that attackers use for conducting ATO
• Current and evolved approaches to brute-forcing
• Best practices for preventing ATO

===================================================================================
**2020 July:**

**Detect complex code patterns using semantic grep** <br>
>We’ll discuss a static analysis tool we’re developing called Semgrep and compare it to tools like gosec. Semgrep is a tool for writing security and correctness queries on source code (for Go, Python, Java, C, and JS) with a simple grep-like interface. The original author, Yoann Padioleau, worked on Semgrep’s predecessor, Coccinelle, for Linux kernel refactoring, and later developed Semgrep while at Facebook. He’s now full time at r2c.

>Semgrep is open-source and comes with a registry of OWASP Top 10 security checks. It’s ideal for security researchers, product security engineers, and developers who want to find complex code patterns without extensive knowledge of ASTs or advanced program analysis concepts.

>For example, with Semgrep you can:

>Simply match function calls. The pattern exec.Command(…) matches exec.Command() called with any arguments or across multiple lines - but not the string “exec” in comments or hard-coded strings, because it’s aware of the code structure.

>Find use of SSLv3 tls.Config{…, MinVersion: $TLS.VersionSSL30, …}

>Find hardcoded JWT tokens var $X = []byte(“…”) … $TOKEN := jwt.NewWithClaims(…) … $Y := $TOKEN.SignedString($X)

===================================================================================
**2020 June:  [Download presentation](zz_presentations_2020_06.pdf)**

**How to Build Awesome Security Instrumentation to Automate AppSec Testing and Protection** <br>
>Modern software demands velocity, and traditional “outside in” scanning and firewalling are creating bottlenecks and slowing things down. In this talk, Jeff will approach application security from the “inside out”. We will show you how to create simple agents that get inside a running application (like a profiler or debugger) and give you access to everything you might want to know. We’ll demonstrate real agents that identify vulnerabilities without changing any code, scanning, or extra steps. We’ll identify vulnerabilities, analyze access control, and even prevent RCE attacks. Unlike scanning and firewalling, this approach establishes a safe and powerful way for development, security, and operations teams to collaborate. We’ll discuss how software security instrumentation works, how it’s being used in many organizations, and the implications for the practice of application security.

**Speaker:  Jeff Williams** 
<br>
>Jeff brings more than 20 years of security leadership experience as co-founder and Chief Technology Officer of Contrast Security. He recently authored the DZone DevSecOps, IAST, and RASP refcards and speaks frequently at conferences including JavaOne (Java Rockstar), BlackHat, QCon, RSA, OWASP, Velocity, and PivotalOne. Jeff is also a founder and major contributor to OWASP, where he served as Global Chairman for 9 years, and created the OWASP Top 10, OWASP Enterprise Security API, OWASP Application Security Verification Standard, XSS Prevention Cheat Sheet, and many more popular open source projects. Jeff has a BA from Virginia, an MA from George Mason, and a JD from Georgetown. <a href="https://www.linkedin.com/in/planetlevel/" target="_blank">Jeff's LinkedIn page</a>

===================================================================================
**2020 April:  [Download presentation](zz_presentations_2020_04.pdf) **

**You got Honey in my Web App** <br>
Let's face it, attackers seem to be holding all the advantages... but it doesn't have to be that way... With a little bit of creativity and understanding of how attackers actually do what they do, you can mount an effective defense that will leave your attackers openly weeping wondering where it all went wrong. Turns out... it was when they mistakenly started gunning for your web apps. Attendees of this talk will learn about how each layer of a web app stack can be made into the attackers' worst nightmare.

**Speaker:  Michael Douglas** <br>
Even when his job title has indicated otherwise, Mick Douglas has been doing information security work for over 10 years. He received a bachelor's degree in communications from Ohio State University. He is the managing partner for InfoSec Innovations. He is a SANS Instructor and a member of the IANS faculty.
