---

layout: col-sidebar
title: OWASP Denver
site_side: true
tags: Denver
level: 3
region: North America
altfooter: true

---
OWASP Denver
-----------------
Welcome to the OWASP Denver chapter homepage!!

***EVERYONE*** is welcome to attend our regular meetings, whether CSO, Developer, QA Engineer, Project Manager, ....  whoever, welcome.  We are dedicated to vendor neutral presentations that raise the security awareness of all attendees.  Come join us!

Follow chapter news on [Meetup](https://www.meetup.com/Denver-OWASP/) 

Join us on our [Slack Channel](https://join.slack.com/t/denver-owasp/shared_invite/zt-d9ncxhfp-Px6DZBZhsRplWExVbJnm0w) 

The chapter board is 

* [Serge Borso (Chapter President)](mailto:serge.borso@owasp.org)
* [Aaron Cure (Board Member)](mailto:aaron.cure@owasp.org)
* [Brad Gable (Board Member)](mailto:brad.gable@owasp.org)
* [Steve Kosten (Board Member)](mailto:steve.kosten@owasp.org)
* [Matt Shufeldt (Board Member)](mailto:matt.shufeldt@owasp.org)
* [Frank Vianzon (Board Member)](mailto:frank.vianzon@owasp.org)


Next Meeting/Event(s)
---------------------
### Wednesday July 16th at 5:30 PM (Virtual Meeting)

**Location:** 
<a href="https://zoom.us/j/514365407?pwd=VUdmS1UxVXVMZU12aFFTVmNqaTB4Zz09" target="_blank">Zoom Meeting</a>


Meeting ID: RSVP on our <a href="https://www.meetup.com/OWASP-Denver" target="_blank">meetup page</a> to receive meetingID and password


**Time: 5:30 PM - 7:00 PM**

**Detect complex code patterns using semantic grep** <br>
>We’ll discuss a static analysis tool we’re developing called Semgrep and compare it to tools like gosec. Semgrep is a tool for writing security and correctness queries on source code (for Go, Python, Java, C, and JS) with a simple grep-like interface. The original author, Yoann Padioleau, worked on Semgrep’s predecessor, Coccinelle, for Linux kernel refactoring, and later developed Semgrep while at Facebook. He’s now full time at r2c.

>Semgrep is open-source and comes with a registry of OWASP Top 10 security checks. It’s ideal for security researchers, product security engineers, and developers who want to find complex code patterns without extensive knowledge of ASTs or advanced program analysis concepts.

>For example, with Semgrep you can:

>Simply match function calls.
The pattern exec.Command(...) matches exec.Command() called with any arguments or across multiple lines - but not the string "exec" in comments or hard-coded strings, because it's aware of the code structure.

>Find use of SSLv3
tls.Config{..., MinVersion: $TLS.VersionSSL30, ...}

>Find hardcoded JWT tokens
var $X = []byte("...")
...
$TOKEN := jwt.NewWithClaims(...)
...
$Y := $TOKEN.SignedString($X)

>[Source code](https://github.com/returntocorp/semgrep)
>[Test in your browser](https://semgrep.live/)

**Speaker: Clint Gibler ** 
<br>
>Clint Gibler (@clintgibler) is the Head of Security Research for r2c, a small startup working on giving security tools directly to developers. Previously, Clint was a Research Director at NCC Group, a global security consulting firm, where he helped companies implement security automation and DevSecOps best practices as well as performed penetration tests for companies ranging from large enterprises to new startups.Clint has previously spoken at conferences including BlackHat USA, AppSec USA/EU/Cali, BSidesSF, and DevSecCon Seattle/London/Tel Aviv/Singapore. Clint holds a Ph.D. in Computer Science from the University of California, Davis.Want to keep up with security research? Check out *tl;dr sec*, Clint’s newsletter that contains summaries of artisanally curated, top talks and useful security links and resources from around the web. <a href="https://tldrsec.com/" target="_blank">tldrsec.com</a>


Want to Present at OWASP Denver Chapter Events??
--------------------------------------------
Just email the proposed talk title, abstract and speaker bio to the Chapter Leaders via e-mail.  

REMEMBER, ALL PRESENTATIONS MUST BE VENDOR NEUTRAL ... NO SALES PITCHES!!!
