# Filecoin Node Operator Guide to Content Policy
## Purpose of this Guide
This guide is aimed at Filecoin node operators.

Its primary goal is educational: to draw attention to some key types of challenges we expect you might face in running a Filecoin node, and discuss and prepare for them. Specifically, we’re focusing  on risks related to the content of the files you host. 

Why? Because files have contents, like text, images, or video, that have meaning in the world. In many cases, you can host a file (such as someone’s personal photographs or their academic notes) and no one will have a problem with that. But in other cases, the contents of a file may bother a range of people or institutions. If you would like to avoid all these problems, you can store only files and data with which you are familiar and for which you can vouch. That is not always possible so you may need to consider how to avoid storing certain content or dropping content you accidentally stored. 

Like what? Well, for example, you might accidentally store Hollywood movies, or controversial political cartoons, or someone’s homemade pornography.

At this point you might be thinking, “Why is this my problem? I’m a storage provider. A client directs me to store files and I store them. I don’t care about their contents, I don’t even want to know what’s in them. Why should I be morally responsible or legally liable for their contents? If you have a problem, go talk to the client who is storing them.”  

Well, like it or not, once you are in the business of hosting files, you may be responsible in various ways -- legally and ethically are the main ones we have in mind -- for their contents, depending on a range of factors. 
Hosting files implicates a range of complicated issues depending on their contents. For example, a file’s contents may be illegal in some places. Or a file’s contents might be legal but still abusive or problematic in other ways, depending on what systems or norms or values you uphold. Hosting files raises several potential legal and ethical issues. This guide will cover only some of the most common ones, and the ones likely to cause the greatest harm.

It will also mention some common practices that can help you respond to common scenarios and reduce risk related to content that could affect you or your business. You may want to adopt these in whole or in part.

Even though this guide may help prepare you to deal with legal and ethical risks related to hosting files, the contents of this guide are not legal advice, and we are not your lawyers.  These materials are intended to help make you aware of common content policy issues and approaches to handling external complaints. Given the diversity of legal systems that could apply, and the global nature of networked content, it’s not possible to cover all potential legal issues involved with running a Filecoin node. It’s ultimately your responsibility to consult a lawyer in your jurisdiction for legal advice. But, we are here to help, and that includes doing our best to help you find a lawyer in your location who is experienced with content issues. Email us at info@murmuration.ai.

## Some Basic Information
### Responsibility and Risk as a Host
As a node operator, you’re allowing other internet users to store files on your computer or in a cloud server under your control, including both encrypted and unencrypted files. In short, you’re the host. 

Are hosts legally liable for the contents of files they host? The frustrating answer is -- “sometimes!” 

This type of liability is often called “intermediary liability” because you as a data service provider are sitting in between various users and parties. So, you are an intermediary, and you may have some legal liability as a result.

So, how do you know which files you are legally responsible for? Unfortunately, it depends on many factors and some of those factors are not very clear. To start with, different countries have different laws. For example, the US has strong protections for intermediaries. But, even in the US, sometimes an intermediary is liable. At the other extreme, China tends to hold intermediaries responsible in many more scenarios. And other places like Europe fall somewhere in between.   

These questions are complex and they are the reason that large technology companies often employ many lawyers, to figure out the answers to these questions and help steer the company away from the biggest risks. We are not going to use this document to try and spell out all of these legal requirements (many of which are in flux anyway).

But the point of this section is to make clear that acting as the host means you sometimes take on responsibilities such as legal liability for the contents of files you host. Sometimes, saying things like “I didn’t create these files so they are not my problem, I just store them” or “I don’t know what’s in these files, so I can’t be responsible for them” is not going to work. As a node operator, it is your responsibility to know and comply with relevant laws and regulations in your jurisdiction.

### Ethical Responsibility
Probably the main kind of responsibility you are concerned with is legal liability. Legal penalties are a very tangible form of consequences. However, there are other types of responsibility you will want to keep in mind and so we mention them here. For example, there is moral and ethical responsibility - if you are hosting files whose contents you believe are bad for the world, you may not want to host them. And in some jurisdictions, you may choose not to host files you believe are ethically or morally problematic for that region in particular.

Sometimes content is both illegal and immoral (that’s probably why it’s illegal in the first place). In other cases, content may be “lawful but awful” -- legal but something that most people would not want to be associated with. We will discuss this at greater length later, but for now, we encourage you to consider what your values are here. Are there certain types of content you would not want to host? Would you be ashamed if it were widely known that you hosted it? Would you be happy if a major newspaper or blog reported that you are a key host for this content? This is why it’s useful to figure out in advance what types of content might be against your values. Because later, you might be associated with that content by the public, and this could affect your reputation in ways you may not want.

## Some Practical Thoughts
In a sense, we are talking about something pretty straightforward and basic. Sooner or later, people are almost certainly going to complain about the contents of files you host. As the Filecoin Network matures, we will learn more about the types of complaints and how to handle them. And we (Murmuration Labs) are helping to develop software tools for you to deal with files you have stored that you later find are problematic. But for now, we want to give you some ideas on how to get ready to receive those complaints and deal with them as they arrive.

### Terms of Service
By storing client files, you are entering into a relationship with clients -- one with promises and expectations in both directions. This is the type of situation where it makes sense to spell out the terms of that relationship in a contract, like Terms of Service, so the risk of surprises later is less. You may want to publish and adhere to terms of service that structure and articulate the basic contractual relationship between you and clients. This would also be a good place to publish your abuse contact, any public procedures related to handling inbound complaints, and your policies as a node operator. We’ve provided a suggested template Terms of Service you can start with here. As always with a legal contract, you should discuss this and any other  potential compliance issues with your lawyer.

### Publish an Email Contact Address for Complaints
Let’s assume that someone -- a copyright owner, an individual, a company -- will inevitably take issue with content you host for one reason or another. They’ve investigated the network and decided that you are one of the hosts of the CID at issue. They are going to want to find you and talk to you.

Now, one of your instincts in response to this development may be, well, I don’t want to be found. If it’s hard to find me and tell me they are unhappy, then maybe I won’t have any problems.

But, we don’t recommend hiding. If someone is motivated and wants to find you, they eventually will.  And if it’s hard to find you, it will be hard to communicate with you in order to tell you what their issue is and seek resolution. And then by the time they find you, things may have escalated more than they otherwise would.

So, for a range of reasons, we recommend you make it easy to send complaints to you. Creating a dedicated email alias just for complaints, such as “abuse@yourdomain.com” and listing it on your website or some other easily findable place will help you separate complaints from other email traffic, and set up a funnel for sorting them once they have arrived.

It’s pretty simple, but lots of people forget to do it -- give people an easy way to find you and send you complaints. Once you start getting lots of complaints, then it might be time to get some software to help you keep them organized, and start automating part of your response system. We will add more contents to this repo about that process later as it becomes relevant.

### Handling Inbound Complaints
If you do choose to publish an abuse contact (and even if you don’t) you will then have to choose how to handle inbound complaints. This is not a fun or directly profitable part of running a node. But it’s a necessary part of the file hosting business.

### Legal Demands
Some of the complaints you receive will be legal threats -- letters from lawyers asking or demanding you to do or stop doing something. If you don’t respond to these, it’s possible they might give up and stop writing to you. But, it is more likely that they will escalate and may eventually seek ways to coerce you to do what they want (for example, by asking a court to force you). 

As a node operator, it’s a good idea to have a lawyer ready for such scenarios. While we cannot serve as your lawyer, here is a list of attorneys by region with relevant expertise in content and blockchain issues. Once you have a lawyer, they can help you determine the best course of action in a given scenario.
- [Jerry Fang](http://www.zhonglun.com/Content/2016/12-02/1413520202.html)
- [Rick Zhu](https://www.spencerstuart.com/our-consultants/richard-zhu) 

### Other Requests and Demands
Some other complaints will not come from lawyers. They might come from ordinary people or small businesses. Some of them might make legal threats (“do this or else”). But others will ask you to do something because it is the right thing to do or because if you don’t, the complainant will draw attention to you on social media or find some other way to create risk for you and your business. For example, “this file contains private pictures of me and it was posted without my permission, so please disable access to it `because it is violating my privacy and traumatizing me.” Requests like this could be legal in nature (depending on where you are located). But sometimes, they are simply asking you to do what the complainant believes is right.

This is why it is helpful to think about your values in advance as much as possible, and to post clear policies about what types of content you are okay with hosting, or not okay with hosting. What kinds of contents do you want to store? And, are there any types of content you do not want to store?

### Responding to Complaints
As a node operator, you will likely receive a variety of complaints from third-parties. Some types of complaints, and complainants, will no doubt be more common, and we will learn more about this as the Filecoin Network operates and matures. For now, here is some information about types of complaints we expect you might receive more frequently, based on patterns of complaints received by conventional web, storage, and social media companies. We also identify certain types of complaints that are the highest priorities because of the intensity of possible harm and likelihood of attention from law enforcement or other government actors.

### Copyright claims
We believe that some of the first and most common complaints you will get are takedown requests based on copyright law. In other words, you might be hosting a file that is a film or a song, and you will get a complaint from the copyright owner (such as a movie studio or record company) or their agent (a company hired by the copyright owner just to send out copyright takedown complaints).

The Digital Millennium Copyright Act (sometimes called the “DMCA”) is a US law, but for many reasons (such as the historical prevalence of US-based web companies and platforms), it is common to receive takedown requests based on the DMCA from all over the world. 

For someone hosting files stored at the direction of a client, the DMCA works like this.  Let’s say you are hosting files that contain copyrighted content -- such as a song recording, or film, or a complete novel. A client directs you to store the file. Does the client have all of the necessary rights to do this? Generally, you have no way of knowing. Maybe the client purchased the song under a license agreement. Or maybe the client’s file is a parody making fair use of the copyrighted material (an exception to copyright law). 

If a copyright owner believes you are hosting infringing content they will send you a complaint. It might contain all of the information that a well-formed DMCA notice is supposed to have. Or it might just demand that you take down a particular file. A DMCA takedown notice sent under Section 512(c) of that law (17 U.S.C. 512(c)) is the copyright owner telling you, I believe the client does not have the right to store this file with copyrighted material. Are you as the node operator liable for storing this file? If you disable access to the file, then no. The DMCA gives you “safe harbor” if you respond to the notice “expeditiously.”

Once you disable the file, one of several things may happen. One scenario is -- nothing. You don’t hear anything more from either the client or the complainant, and you leave the file disabled. Another scenario (which is rare) is counternotice -- the client writes to you and says, “I believe it was ok for me to store this file.” In that case, you may restore access to the file.

Now, if you receive a DMCA takedown notice are you required to disable access to a file? The answer is no. But, disabling access to the file gives you “safe harbor” from damages under US Copyright law. In other words, you don’t have to take it down. But, if you do take it down, you are “safe” from a US lawsuit from the copyright owner.

There are other nations that have similar laws protecting you from copyright liability for files you are hosting at the direction of a client. For example, in Europe, [the e-commerce directive](https://en.wikipedia.org/wiki/Electronic_Commerce_Directive_2000) sets up a similar notice and takedown structure. If you receive a takedown complaint from someone based on the law of an EU member state, you have a chance to disable access to the file, and if you do so, you are safe from a copyright lawsuit.

How can you encourage complainants to send you well-formed DMCA notices that contain all of the necessary information? Here’s a for a public-facing form you may want to post, that gives instructions on how to correctly file a DMCA notice.

### Child Sexual Abuse Materials (CSAM)
Child Sexual Abuse Material (often abbreviated by people who deal with it professionally as “CSAM,” pronounced “See-Sam”) is often regarded as the “worst of the worst” -- among the most immoral, dangerous, and broadly illegal type of content.

For a global network like Filecoin (and the Internet),content like CSAM raises difficult questions. In most cases, hosting CSAM is illegal. Most countries (118 countries according to a [2018 report by the International Centre for Missing and Exploited Children](https://www.icmec.org/csam-model-legislation/)) have laws against CSAM. Definitions differ from country to country as to what counts as CSAM. Even if CSAM were legal in your country, or even if you knew no one would find out, do you as a node operator want to accept compensation for storing such traumatizing and despised content? Is declining to host or to retrieve CSAM “censorship?”

If you become aware that you are hosting CSAM, we suggest you take fast action to report it. In the US, this can be done through the hotline run by the [National Center for Missing and Exploited Children](https://en.wikipedia.org/wiki/National_Center_for_Missing_%26_Exploited_Children) (sometimes called “NCMEC,” pronounced “Nick-Meck”). That tipline is available here -- [https://report.cybertip.org/](https://report.cybertip.org/)

In the US, CSAM must be reported. So, for example, if you receive a DMCA complaint about hosting a copyright film, you can choose whether or not to act, and the risk is whether you get sued by the copyright owner. With CSAM, there is clear law that you must report.

We are working to help with this significant challenge -- our goal is to provide node operators with software that has the detection ability to match hosted files against hashed databases of CSAM in order to identify this material, and then the ability to block retrieval of such files, in order to prevent distribution.

### Terrorist or Violent Extremist Content (TVEC)
A similar category of content is “Terrorist or Violent Extremist Content,” sometimes called “TVEC” in the content moderation industry. A classic example of TVEC would be video showing a beheading or a real life shooting spree. TVEC is a second area where many people have strong emotional and taboo responses, and will demand fast and decisive action from you. The laws around removing TVEC are not yet entirely clear or uniform. They are currently in flux, but appear to be moving in the direction of requiring hosts to remove it. For example, after the Christchurch, New Zealand shooting in 2018, governments have begun to move in the directions of greater restrictions on removing TVEC. If you receive a notice that you are hosting TVEC, you should take it seriously, respond quickly, and you may want to consult an attorney or act to disable retrieval of a file you have determined to be TVEC. A relatively new organization, the Global Internet Forum to Counter Terrorism (GIFCT), is working to provide resources to address online TVEC, and we hope to adapt their resources for use by node operators as they become available.

### Dangerous or Malicious Software, Code or Functionality
You may also receive complaints regarding dangerous or malicious software, code or functionality hosted by a client. For example, it is possible that a client has uploaded files that control a botnet, are used for unauthorized computer or network intrusions, or constitute malware, computer viruses, Trojan horses, worms, time bombs, cancelbots, or other similar software, code or functionality that may damage, disable, overburden or impair the operation of another’s computer or network or property of another. For example, organized crime groups or even military or intelligence agencies often use distributed infrastructure to carry out cyberattacks or engage in theft of funds or personal information from victims. If you receive a notice that you are hosting dangerous or malicious software, code or functionality, you should take it seriously, respond quickly, and you may want to consult an attorney or act to disable content you have a reasonable basis to believe falls within these categories of dangerous or malicious content. 

In assessing whether the software, code or functionality is malicious, there are two primary considerations. First, consider whether the reporting party is a reputable member of the global security community (for example, cybersecurity companies, large technology companies, security researchers, security non-profits or public interest organizations, or law enforcement agencies, all frequently report cybercrime and attempt to help victims avoid attacks). It should be relatively easy to identify a reporting party as a legitimate and reputable member of the security community.  Second, consider whether the reporting party can provide some evidence to establish that the content is in fact malicious or dangerous software or code and it is reasonable to ask how that party knows the content is dangerous or malicious.  Common responses may be to provide security research reports reverse engineering malware, evidence that a particular IP address and/or code is used in connection with a phishing email or domain, or to control malware or a botnet command and control server, or other technical telemetry. Between these two considerations, you can make good decisions. 

It will not be useful for you as a node operator to facilitate serious criminal groups, so it is important to take this seriously. You may want to consider establishing relationships with one or more trusted members of the global security community to help you make decisions. For example, there are non-profits such as [Global Cyber Alliance](https://www.globalcyberalliance.org/) or [Cyber Threat Alliance](https://www.cyberthreatalliance.org/) that can provide support, or you may want to get to know a cybersecurity company or organization in your country. 

## Choosing to Host or not to Host Certain Content
### No central controller
Filecoin is a decentralized network, which is run by its nodes and according to the functionality of the system. There is no central controller which determines what happens on the network outside of Filecoin’s governance system, and the nodes themselves and their transactions with one another. One implication of Filecoin’s core value of decentralization is that no one at Protocol Labs or the Filecoin Foundation is telling you, or forcing you, to host or not host any particular file or type of file. You are free to host or not host the types of files you want. And similarly, it means that if you receive complaints for the contents of a file you host, you will not be able to defend yourself by saying, “I hosted this file because Protocol Labs made me.” 

### Redundancy and node operator choice
A content-addressable storage system offers certain advantages over one based on location-based addressing.  One of these is resilience -- having multiple, redundant copies of files makes it more difficult to completely “delete” a particular file from the entire network. At the same time, viewed from a level down, from your perspective as a node operator, there is always a choice as to whether you wish to host a particular file, or type of file. If you as a node operator decide that there is certain content you don’t want to host, then you don’t have to host it. And, we can expect that as node operators each make different choices, then the Network may have a range of policy options for clients to choose from, as various node operators follow different content policies.

This creates new challenges, such as, how do you figure out which CIDs you do not want to host before you store them. Or, if you have already stored a file with a particular CID and then learn it has contents you don’t want to host, how can you decline to have this file retrieved?

These are areas where we (Murmuration Labs) are at work on software that can help you as a node operator customize which files you will and will not store or allow to be retrieved, based on CID. We expect to ship this functionality soon, available through the node operator software, followed by updates and expansions.
