# CyberSecurity RoadMap

```bash
Your Goal Is To Become A Penetration Tester. 
Do You Want To Get Paid For Going To Conferences, Taking Security Classes, Learning New Things,
And Working With Some Of The Finest Information Security Minds
In That Situation, Your Goal Should Be To Join The Redteam. 
This Article Will Cover The Qualifications And Practical Knowledge Needed To Work As A Penetration Tester.
```

<sup>
I'll Provide You A Goal-oriented Road Map That Ought To Help You Develop Into A Skilled Penetration Tester
Not Everyone Has What It Takes To Be A Professional, Do You Have What It Takes?
</sup>

```bash
1. NETWORKING
```
Understanding how computers communicate with one another is among the most important skills for a penetration tester to have. 
Discover the details of tcp/ip 3-way handshakes, protocols, and packet inspection. Get to the point where you can sit down in front of a white board, 
Sketch out a network communication using the osi module, and write out in detail how it all functions. Know every level of the osi module thoroughly,
And be familiar with every protocol related to each level. This is crucial since you will need to analyse every wrapper, every address, etc.
While analysing traffic through packet dumps. Once you have that level of understanding, 
You are ready to read and manipulate network traffic at the packet level like an expert.

```bash
How To Prepare:
```

* Study Network+ Ccna Security.

* Practice With Wireshark, Inspect Traffic, Understand How Packets Are Created And Transmitted.

* Study Http, Know It Inside And Out. "http The Definitive Guide" Is A Great Resource.

* Use Burpsuite (more On This Later) To Proxy And Inspect Web Traffic.

```bash
2. Understanding The Internet
```
I Mentioned HTTP and Burpsuite In The Networking Section, So Let's Talk About That Next. The majority of people mistakenly believe they comprehend the internet. Would You Be Able To Write Out A Complete HTTP Request And Response? Are You Aware of All HTTP Verbs? Do You Easily Recognise The Differences Between HTTP 1.0, HTTP 1.1, HTTP 2.0, AND HTTP 0.9? Do you have a good understanding of the majority of HTTP response codes, both general and specific ones? Know How a CDE Operates? Let's assume that most of those questions have a negative response because few people actually research how the internet functions. You'll need to understand how it works when performing web application testing, code reviews, and api reviews.
```
How To Prepare:
```
* Read "http The Definitive Guide"

* Read "the Tangled Web"

* Be Familiar With Rfc 2616 And Other Related Rfcs.

* Practice Inspecting Web-traffic With Both Wireshark And Burpsuite.

```bash
3. Operating Systems
```
All operating systems must be tested as a pentester. You Are Not Limited To Windows Environments That Run Windows 7 And Below. You will come across a variety of environments that use Windows, Macs, and Linux. You should feel at ease using all different kinds of operating systems, as well as knowing how to enumerate data, use the command line (cmd, PowerShell, Bash), and download, install, and run programmes. It Might Look Simple, But That Knowledge Is A Lot. Could You Change Roles, Add a New Admin, Push Updates, and Other Things If You Had Access To Windows Server 2012? Can You Find Insecure Files Or Permissions If You Log On To An Ubuntu Box As A Webuser? You Don't Need To Memorise, Of Course.

```bash
How To Prepare:
```
* Create A Vm Of At Least One Linux Distro And One Windows Server. 
* A Mac Vm Would Be Handy, But It Is Similar Enough To Unix That Knowing Linux Commands Will At Least Help. 
* Attain Admin Level Knowledge Of Their Functionality. 
* There Are Many Web Courses, Books, And Websites That Will Provide You With Great Knowledge.

---------
### I Have The Core Knowledge, Now What?


Congratulations, You Are No Longer A Noob If You Attained All The Core Knowledge Listed Above. That is a lot of technological knowledge, and you could probably find a respectable entry-level position with it. If you haven't already, it's time to find employment. The majority of pentesters have a variety of backgrounds, including network administration, IT help desk work, security analysis, web development, programming, and more. The Key Is To Find A Job In Technology, Security Related Is A Bonus But Not Required Right Away. At this point, you should also consider obtaining a few certifications; the Network+ and Ccna are excellent for landing networking jobs. It's easy to enter a system administrator role with Mcsa. If you have mastered the fundamentals, getting a few of the entry-level certifications shouldn't be a problem.

---------

> You might wonder why programming wasn't included in the list of core knowledge. There is a strong case for why it should be, however I believe programming belongs in the next phase. It will take you at least a year or two to master everything in the first section, depending on how quickly you can pick things up, your prior experience with technology, etc. Adding programming right away will take up even more time, and you risk forgetting a lot if you don't have a reason to learn coding just yet.

Now that you have a job in information technology, it pays peanuts but looks good on a resume. From this point forward, every job you have will be a stepping stone. Expect to leave any job after two years since there is a ladder to the top and becoming complacent will keep you stuck on a lower rung. Of course, it's perfectly acceptable if you discover that you really enjoy working as a network administrator, system administrator, or security analyst and don't feel like pursuing penetration testing. Those jobs are excellent and will give you a bright future.

---------

<sub> 
  We Start To Go Deeply Into Security Now, Though, For Those Who Want To Keep Climbing The Ladder.
</sub>


 ## How Does A Hacker Get Started

```bash
1. Learn Defensive Security
```

How To Become A Hacker Is Most Likely One Of The Most Common Questions On Hf. Well, to start, if you mastered those foundational subjects, you are doing well. Now, Each Of Those Core Topics Can Apply Security. I believe it is best to become familiar with Blue Team (defensive security) prior to joining Red Team (offensive security). Since you will also learn about offensive security while studying defensive security first. And every pentester ought to be aware of the possible defences that may be put in place to prevent things like a reverse shell, code execution, logging, typical AV behaviour, and more. This path can also lead to a job as a security analyst, which is a great entry point into penetration testing. You can, of course, skip this step You can probably still enter penetration testing if you study the advanced subjects listed later. This is merely my advice.

```bash
How To Prepare:
```
* Study: Security+ And Cissp (don't Have To Get Cert But At Least Study).

* Understand Common Defense Techniques Such As How Anti-virus Works, How Firewalls/ids/ips Work And Where They Are Installed In Networks.

* Create Your Own Lab Setup, Play With Setting Up Splunk And Other Free Security Tools.

* Study Compliance Such As Hippa, Pci Dss, And Fedramp. Study Standards Such As Iso 9000 And Nist.

--------

<sup>
You ought to be able to design, at the very least on paper, a completely secure network by this point, and you should also be familiar with every kind of security device you use to implement the layered security. Additionally, depending on the compliance or security standard that a company may choose to use, you should be able to write a security policy and comprehend various security controls.
</sup>

```bash
> Start applying if you are not currently a security analyst or part of an IT security team. 
> Now that you are knowledgeable, you can at least apply for Level 1 Security positions.
```
```
2. Can I Start Coding Yet
```
It is indeed time to start learning how to write programmes. You Can Be A Penetration Tester Without Being A Programmer, Which Is Something To Keep In Mind. In fact, studying to become a programmer would be a waste of time unless you are already one. You should, however, be familiar with the fundamentals of computer science and be able to write at least simple scripts and programmes for security testing. We don't need to be in dev operations to learn how to test applications, find insecure code, and exploit it. Of course, the more programming knowledge you have, the better you will be at testing it, but there are many other things a pentester needs to be aware of.If Programming Is Your Thing Then You Should Start That Much Earlier In The Training, Add It To Your Core Knowledge Set, Go To School For It, And Make That Your Job. You can eventually transition to penetration testing if you so choose, but in my opinion there are better jobs out there, like malware analyst (reverse engineer) or security researcher (discover and create zero-day exploits). Both of which require a high level of programming expertise and are fantastic jobs.

--------

Though We Want To Keep It Simple For Penetration Testers. A fantastic language to learn and master is Python. Python allows you to create unique security tools and learn computer science. Python is natively supported on Linux, Mac, and soon, Microsoft's Windows operating system as well. I advise learning Python 2.x first, but also becoming proficient in Python 3.x programming. Although There Are Many Excellent Free Resources For Learning Python, I Found "Learning Python the Hard Way" To Be The Most Useful For Beginning. You can then move on to books like "black Hat Python" and "violent Python."

<sup>
  Even while I advise sticking with one language until you have mastered it completely, there are other languages that are worthwhile to learn, at least up to the point where you can read and comprehend source code.
</sup>
 
 ```bash
> C For Exploit Development.
> Php For Server Side.
> Html For Web Development.
> Javascript For Client Side.
```
This is by no means an exhaustive list of languages to learn, but it's a great place to start. Once you have a basic understanding of programming, learning various syntaxes is really all that's left. Of course, there are many differences between Python and C (not to mention Asm), but you ought to be able to jump right into C and use your prior knowledge there. Reviewing source code from sites like Github and other places is one of the best ways to learn to code once you have the fundamentals down.

--------

```bash
3. Learn Offensive Security
```
You ought to be level 2 or 3 in the security job you selected at this point. You are a programmer, capable of creating security policies, capable of performing risk analysis, etc. You Can Use Any Operating System With Confidence and Above Average Efficiency. A minimum of two to four certifications are also recommended. So let's dive into the specifics of popping shells.
You'll realise why you have to learn so much other information first once you really get into security testing. Try to reverse shell from a friend's computer to your local host, but nothing happens. You're not understanding, the software worked in your home lab, what could possibly be wrong? That's where networking expertise comes into play.
There are several possibilities, and if you lacked the knowledge mentioned above you would be stuck, probably writing a post on Hf asking for assistance. It's possible that the programme doesn't have the proper permissions or that an antivirus programme is blocking it. But you can easily troubleshoot the issue because you closely followed this tutorial and diligently studied for the past few years. It's time to start learning about hacking now.

--------
```bash
How To Prepare (in No Particular Order):
```

* Highly Recommend Reading "web Application Hackers Handbook". Know It Inside And Out.

* Pick Up A Book On The Basics Of Hacking. The Material Will Be Very Out Dated But It Will Provide You Solid Knoweldge.

* Use Youtube And Other Sources To Learn About: Getting Shells Such As Php Shells, Reverse Shells, Bind Shells, Etc.

* Learn About Enumerating A Host, Port Scanning, Manual And Automated Methods Of Searching For Security Vulnerabilities.

* Learn How To Exploit Well Known Vulnerabilities, Such As Ms08-067 And Ms17-010.

* Learn Basics Of Privilege Escalation Methods, Both Manual And Automated.

* Learn How To Enumerate Hosts In A Network, Capturing Packets In Wireshark, Doing Broadcast Scans With Nmap, Using Netbios And Smb To Enumerate Hosts Etc.

* Learn How To Research For Vulnerabilities.

* Be Able To Modify Scripts To Fit Your Needs. And Be Able To Troubleshoot Older Exploits To Work With More Modern Libraries.

--------

There is a lot I didn't mention, to be honest. This section focuses more on natural learning than strict discipline. You'll Switch Between Topics. You will discover something you don't understand as you learn more about one subject, and you will study that as well. I Would Recommend Taking Some Online Courses For A More Controlled Learning Environment. Although they are costly, they will offer a more thorough and structured form of learning. The Pwk is suitable for those who are already proficient in the fundamentals of hacking. Elearnsecurity Is Excellent For Those Who Need A Little More Guidance To Learn The Same (and More) Skills Taught By The Pwk.Your Goal is to obtain the Oscp, but you can start by obtaining something like the Pptp to help you become ready for the Pwk.

```bash
4. Practice Practice Practice
```
Now is the time to put all of that knowledge into practise. Now Is The Time To Hone Your Skills. There are a few ways to practise lawfully.

1. Build Your Own Lab.

2. Use An Online Lab.

  There is no excuse not to use online labs in this day and age, unless you want to learn how to set up a virtual lab. The websites 
  [`HackTheBox.com`](https://www.hackthebox.com/) and 
 [`TryHackMe`](https://tryhackme.com/) are only a couple of the many free labs available online. Then there are Pay-For-Service Labs like
 [`Pentesterlab`](https://pentesterlab.com/)pentesterlabs.com that are really helpful. You can also search Vulnhub.com for ready-made insecure virtual machine images to use as practise. The key message is that the best way to learn is to actively do security testing in lab settings.
 
 -------
If you are actively working a full-time job, Steps 3 and 4 will take you at least a year to complete. Once you have a few advanced certifications, such as the OSCP, it is time to continue.
```
Time To Become A Penetration Tester
```
Going From A Complete Noob (knowing nothing about Security, Networking, Etc.) To Penetration Tester Would Take About 5 to 7 Years If You Followed The Steps I Provided. If you already work in the information technology industry, have a degree in computer science or a closely related field, etc., this time will obviously be shorter. So, if you start when you're 16 years old, you can probably land a job as a penetration tester by the time you're 23 or so. It took me about 6 years from the time I first enrolled in college until I was hired as a penetration tester because I started much later in life.You should be well-versed in infosec and related technologies by this point. Multiple certifications and jobs on your resume will clearly demonstrate your growth in experience and desire to better yourself. You will be better qualified than the majority of applicants for jobs as penetration testers. A job will be yours if you apply to enough places.

--------

Applying to places that are entry-level friendly is something I advise. Because that isn't practical experience, even with the jobs you've had and your lab expertise. For at least the first year, you will begin as a Level 1 (or whatever they call it). But after a year of practical experience, you are set. You Should Look For A New Job Because You Are Deserving If After Two Years You Are Not Making $100k.
```
Conclusion
```
I had no idea the post would end up being so lengthy; it was just a task summarising the steps to becoming a penetration tester. My hat is off to all of you who persisted and read the entire post; I think you have what it takes to succeed. Your research will be laborious and time-consuming, and you'll read dry material that will make any break from it welcome. But being a professional and not just a hobbyist means exactly that.

--------


#### Author / Creator : [`KABIR`](https://github.com/kabir0104k)

